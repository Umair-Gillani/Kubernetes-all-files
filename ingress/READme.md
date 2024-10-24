
- ##### To View Logs of Ingress Controller 

```bash
kubectl logs -f <pod/nginx-ingress-controller> -n kube-system
```

---

```bash
kubectl -n kube-system rollout restart deployment <nginx-ingress-controller-controller>
```

---

