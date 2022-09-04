kubectl create –f deploy.yaml //create deployment

kubectl apply –f deploy.yaml // apply changes to deploy

kubectl get deploy // get the deplyment status

 kubectl get pods // gets the pods

 kubectl get pods --selector="app: pluscode" //get the pods by selector

 kubectl logs pluscode-bf9f9fb49-svc5h //pod logs

kubectl exec -it $POD_NAME sh // access pod interacively

kubectl create –f service.yaml //create service 

kubectl get service //get service 


watch -d kubectl get deploy //watch deployment

kubectl delete –f deploy.yaml service.yaml // delete deployment