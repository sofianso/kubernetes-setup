Having one master deployment file, it is ideally is better to have the `service.yaml` first. You can also separate a serice or deployment by using `---` after each yaml file.

## To apply master deployment file

`kubectl apply -f=master-deployment.yaml`

## Expose the service again

`minikube service backend`
