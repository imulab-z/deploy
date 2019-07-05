# Deploy
Collection of deploy scripts

## Redis

```
# make sure redis-secret is created
helm install --name dev ./redis --set existingSecret=redis-secret
```
