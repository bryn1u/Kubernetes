

kubectl apply -f ingress-passage.yml -f ingress-passage-v2.yml -f ingress-web-api.yml
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.1.2/deploy/static/provider/cloud/deploy.yaml
kubectl apply -f ingress-resource.yml


ingress-example-dns.yml  ingress-passage-v2.yml  ingress-passage.yml  ingress-resource.yml  ingress-web-api.yml

