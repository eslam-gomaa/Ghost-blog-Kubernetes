# Ghost-blog-Kubernetes
Kubernetes YAML to deploy Ghost blogging system on Kubernetes

---

```bash
kubectl create ns ghost

kubectl apply -f mysql.yml
kubectl apply -f ghost.yml
```

