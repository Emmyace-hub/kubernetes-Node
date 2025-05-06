# kubernetes-Node
Diving into nodes on kubernetes

* Start Minikube cluster using thge command:
   
    minikube start
![1](./img/1a.png)

* Stop Minikube cluster :

    minikube stop
![1](./img/1b.png)

* DeleteMinikube Cluster:
    
    minikube delete

![1](./img/1c.png)
* View Node :
   
    kubectl get nodes
![1](./img/1d.png)

* Inspect Node :

    kubectl describe node <minikube>


![1](./img/1e.png)

 In summary minikube is often used for local development and testing, scaling nodes may not be as critical in production environment. However by efectively managing nodes in minikube kubernetes cluster, we can create, test, and deploy applications locally, simulating a kubernetes cluster without the need for a full-scale production setup which is useful for debugging, experimenting and developing applications in a controlled environment.