# K3D cluster lightning fast

## Create/start Cluster
k3d cluster create --config k3d.yaml 

### check it's running
docker ps
kubectl config use-context k3d-my-cluster
kubectl cluster-info

## Delete Cluster
k3d cluster delete my-cluster
