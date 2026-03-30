# How to open **minikube dashboard** in GitHub Codespaces
1. Run this command -> minikube dashboard --url
2. Then run this command in other terminal -> kubectl port-forward -n kubernetes-dashboard service/kubernetes-dashboard 8080:80