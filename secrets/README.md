# secrets

This folder contains **non-production** secrets (therefore in plain text).

```bash
# create redis secret
kubectl create secret generic redis-secret --from-literal redis-password=12345678

# create jwks secret
kubectl create secret generic jwks --from-file jwks.json

# create stock clients secret
kubectl create secret generic stock-clients-secret --from-file clients.json
```
