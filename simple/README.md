# kubernetes-service-example

Simple example deployment in Kubernetes.

Creates a `Deployment` running 2 instances of a demo website along with a `Service` of type `NodePort` to expose the website outside the cluster on port `30001`.

`kubectl apply -f deployment.yml`
