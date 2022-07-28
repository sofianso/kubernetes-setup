# Purpose
Learn how to Kubernetes works.

## 1. [Install kubectl] (https://kubernetes.io/docs/tasks/tools/)
**NOTE: Install this first.**
A tool to communicate to your Kubernetes. 

## 2. [Install Virtual Box] (https://www.virtualbox.org/manual/ch02.html)

## 3, [Install Minikube](https://minikube.sigs.k8s.io/docs/start/)
=Minikube allows you to test and run single-node Kubernetes clusted in a VM on the host machine. 

## 4. Start Minikube
The following command will install worker nodes and master nodes inside the virtual box.
`minikube start --driver=virtualbox`

## To Check The Status
`minikube status`

## To Open Kubernetes Dashboard
`minikube dashboard`
