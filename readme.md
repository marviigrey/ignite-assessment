Setup a kubernetes cluster using kind

    Write a simple bash script that deploys a kind cluster locally

    Answer: script can be found in this directory in a file called kind.sh

    Download the kubeconfig for the cluster and store in a safe place, we will use it much later in the next steps

Deploy a sample Node.js app using terraform

    When kind is up and running, dockerize a simple hello world express and deploy to dockerhub.
    Tested the app running as a docker container on my local-machine.
    
    create a kubernetes deployment manifest to deploy the Node.js to the kind cluster but don't apply it yet

    using the kubectl terraform provider, write a terraform code to deploy the kubectl manifest to the kind cluster
