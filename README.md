# hellokubernetes-deployment
hello kubernetes technical test source

command to run yaml file:
kubectl apply -f technicaltest.yaml --dry-run=client

Expected output:
deployment.apps/paulbouwer-deployment created (dry run)
service/hellokubernetes-service created (dry run)
ingress.networking.k8s.io/hello-ingress created (dry run)

Assumptions:
Inordder to launch the service with proper DNS name we need to replace hostname with registred DNS name.  
