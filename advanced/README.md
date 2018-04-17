# kubernetes-service-example
Example deployments in Kubernetes

https://labs.play-with-k8s.com/

## Advanced example
Multi layered application with web front end, API and back end DB:

`kubectl create -f db-svc.yml`

`kubectl create -f api-svc.yml`

`kubectl create -f web-svc.yml`

`kubectl create -f db-deployment.yml`

`kubectl create -f api-deployment.yml`

`kubectl create -f web-deployment.yml`

