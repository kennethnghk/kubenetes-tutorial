## create configmap from file
kubectl create configmap greep-web-cm --from-file=./index.html

## expose the port
kubectl expose deployment green-web --type=NodePort