## Check Status of Kube Pod 
`kubectl rollout status deployment/node-app`

## Rollback The Last Deployment
`kubectl rollout undo deployment/node-app`

## Check Rollback History
`kubectl rollout history deployment/node-app --revision=3`

## Go Back To Specific Version 
For example: Go back to the first revision

`kubectl rollout undo deployment/node-app --to-revision=1`
