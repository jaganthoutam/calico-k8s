# calico-k8s

NOTE: This line initializes the cluster.

    kubeadm init --pod-network-cidr=10.244.0.0/16
    
    
    kubectl apply -f https://raw.githubusercontent.com/jaganthoutam/calico-k8s/master/calico.yaml
    
    kubectl apply -f https://raw.githubusercontent.com/jaganthoutam/calico-k8s/master/rbac-kdd.yaml
