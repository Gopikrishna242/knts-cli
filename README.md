# knts-cli


# Install klusternetes cli 
 curl -sL https://get-klusternetes-dev.web.app | TAG=v0.0.4 bash
 
 # Authenticate with provided token
 knts auth --token="knts.bf2afe1877ef7425b29c369b76fe517b" 

 # Create cluster 
 knts create cluster mycluster --size SMALL

 # Get cluster info
 knts get clusters
 knts get cluster mycluster


 # get kubeconfig for your cluster
 knts get kc mycluster

 # check your cluster access
 kubectl get nodes

 # exporting KUBECONFIG (If you have any existing KUBECONFIG)
 export KUBECONFIG=~/.kube/config 
