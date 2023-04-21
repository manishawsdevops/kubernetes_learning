# kubernetes_learning


Node
Cluster
Master 

Components of Kubernetes:
	API Server
	Scheduler
	Controller
	Container runtime
	Kubelet
	Etcd
Kubectl - Command line tool for creating and managing clusters on Kubernetes.

Kubectl commands
Kubectl run hello-minikube	
Kubectl cluster-info	
Kubectl get nodes
kubectl get pods -o wide	


# Kubernetes POD Creating commands
kubectl apply -f pod-definition.yaml  # Creates the Kub POD.

# Replication Controller / Replication Set

kubectl create -f replicaset-definition.yaml # Creates replicaset
kubectl get replicaset
kubectl delete replicaset myapp-replicaset
kubectl replace -f replicaset-definition.yaml
kubectl scale --replicas=6 -f replicaset-definition.yaml



