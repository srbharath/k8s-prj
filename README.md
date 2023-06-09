# Multicontainer application

Codeching - video 9 - Multi container deployment kubernetes | React| Node.js | Postgres | Ingress Nginx | step by step


It contains React client, Node.js backend, PostgreSQL and Nginx

nginx github link 
https://docs.nginx.com/nginx-ingress-controller/installation/installation-with-manifests/#1-configure-rbac

You should install Ingress Nginx with command:
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.8.0/deploy/static/provider/cloud/deploy.yaml

After that you can use the following command to start in main folder:

kubectl apply -f k8s
