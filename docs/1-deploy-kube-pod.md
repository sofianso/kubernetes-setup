## Build
`docker build -t kube-first-app .`

## Tag Your Docker Repo
`docker tag kube-first-app <sofianso/name_of_app>`

## Docker Push To Docker Repo
`docker push <sofianso/name_of_app>`

## Create A Kube Pod
`kubectl create deployment node-app --image=<sofianso/name_of_app>`

## List All Pods
`kube get pods`

## Delete A Pod
`kube deployment delete <name_of_pod>`

