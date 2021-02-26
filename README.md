# kubernetes-example
 Simple example for Kubernetes
 
   minikube start
 
   kubectl apply -f mongo-secret.yaml
   kubectl apply -f mongo.yaml
   kubectl apply -f mongo-configmap.yaml
   kubectl apply -f mongo-express.yaml
   
   minikube service mongo-express-service
   
   
