
- ##### To View Logs of Ingress Controller 

```bash
kubectl logs -f <pod/nginx-ingress-controller> -n kube-system
```

---

- ##### Roll back and restart deployment

```bash
kubectl -n kube-system rollout restart deployment <nginx-ingress-controller-controller>
```

---

