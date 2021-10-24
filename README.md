Overview
ingress-nginx is an Ingress controller for Kubernetes using NGINX as a reverse proxy and load balancer.

Get started

create 2 service cowboysysop and whoami via "kubectl apply -f..."

run the ingress addin by "minikube addons enable ingress"

kubectl apply -f Ingress.yaml for deply it on k8s

kubectl describe ingress "host-ingress"

the following Ingress routes traffic requested for cowboysysop to service1, whoami to service2
