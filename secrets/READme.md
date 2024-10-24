- #####  Copy Paste the content of certificate and private key content into file and give the path of those file in the below command to create secrets in K8S and also pass the secrets into ingress file

```bash
kubectl create secret tls <secret-name> --cert=path/to/certificate.crt --key=path/to/private.key --namespace=default
```

---
- #####  To View Secrets

```bash
kubectl get secrets 
kubectl describe secrets <secret-name>
```

---


