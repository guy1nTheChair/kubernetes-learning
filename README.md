Install Kubectl or MicroK8s

1. sudo snap install microk8s --classic
2. sudo snap install docker
3. sudo groupadd docker
4. sudo usermod -aG docker $(whoami)
5. sudo snap install kubectl
6. sudo microk8s start
7. sudo microk8s enable dashboard dns
8. sudo microk8s stop
