## create configmap from file
kubectl create configmap green-web-cm --from-file=./index.html

## expose the port
kubectl expose deployment green-web --type=NodePort