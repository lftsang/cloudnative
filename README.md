# cloudnative
# Tested on ubuntu 18.04.1
# chmod +x k8smaster.sh
# chmod +x k8sworker.sh
# k8smaster.sh is to install latest kubernetes master node
# k8worker.sh is to install latest kubernetes worker node
# after installed worker node , type command "kubeadm token create --print-join-command" on master node to get the join command, 
# and run it in workder node 
# verify command
# on master node, kubectl get nodes


