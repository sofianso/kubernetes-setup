## Exposing a Deployment with a Service
`kube ctl expose deployment node-app --type=LoadBalancer --port=8080`

## List all available services
The command will also display the URL where your app is running on web.
`kubectl get services`