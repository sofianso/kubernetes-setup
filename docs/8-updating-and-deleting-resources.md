## To Update Resources

For example: If you want to add another pod, you can go to the deployment.yaml file and change the replicas to 3. You just then have to apply that new changes by running the following command:

`kubectl apply -f=deployment.yaml`

## To Delete Resources

By running the command below, it will simply delete the services running on the pods NOT the yaml files.
`second-app-deployment` comes from name of the metadata.

`kubectl delete deployment second-app-deployment` or `kubectl delete -f=deployment.yaml, -f=service.yaml`
