## Update Depployments
**NOTE: You need to update the tag of the image of your Docker container in order for Kube to differentiate what version it is pulling.
**
`kubectl set image deployment/node-app kube-first-app=sofianso/<name_of_app_in_docker>:<version_no>`

`docker push <sofianso/kube-first-app>:<version_no>`

