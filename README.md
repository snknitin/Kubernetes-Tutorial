# Kubernetes-Tutorial
Deploy a complicated application with a database and APIs.


# Installing Requirements

## Kubectl

    $ curl -LO https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/darwin/amd64/kubectl
    $ chmod +x ./kubectl
    $ sudo mv ./kubectl /usr/local/bin/kubectl

## minikube

    $ curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
    $ chmod +x minikube
    $ sudo mv -v minikube /usr/local/bin
