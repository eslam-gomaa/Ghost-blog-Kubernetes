# Ghost-blog-Kubernetes
Kubernetes YAML to deploy Ghost blogging system on Kubernetes

---

```bash
kubectl create ns ghost

kubectl apply -f mysql.yml -n ghost
kubectl apply -f ghost.yml -n ghost
```

