Kubernetes Installation Steps :

1. Download Docker Desktop
2. Install KubeCTL : curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/darwin/arm64/kubectl"
3. chmod +x ./kubectl
4. sudo mv ./kubectl /usr/local/bin/kubectl
5. Install Minikube : curl -LO https://github.com/kubernetes/minikube/releases/latest/download/minikube-darwin-arm64
6. Minikube start
 
Minikube will run in Docker Desktop as it requires  a Virtualbox to run