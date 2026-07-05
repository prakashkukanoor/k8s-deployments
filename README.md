# k8s-deployments

## Exec into the pod
kubectl exec -it frontend-client-6456b9d84-5vp2m  -n frontend -c frontend-client -- /bin/sh

## Get the response
wget -O- http://backend-server.backend/get

## Status Code
wget -O- http://backend-server.backend/status/:code