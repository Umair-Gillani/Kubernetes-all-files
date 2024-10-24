## Copy Paste the content of certificate and private key content to directory and give the path in the below command to create secrets in K8S

```bash
kubectl create secret tls seulah-tls --cert=path/to/certificate.crt --key=path/to/private.key --namespace=default
```


