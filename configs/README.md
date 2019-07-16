# configs

This folder contains configuration files for services

```bash
# discovery-service
kubectl create configmap discovery-service-config --from-file discovery.json

# client-service
kubectl create configmap client-service-config --from-env-file client-service-config.env

# scope-service
kubectl create configmap scope-service-config --from-env-file scope-service-config.env

# auth-code-service
kubectl create configmap auth-code-service-config --from-env-file auth-code-service-config.env

# access-token-service
kubectl create configmap access-token-service-config --from-env-file access-token-service-config.env

# refresh-token-service
kubectl create configmap refresh-token-service-config --from-env-file refresh-token-service-config.env

# id-token-service
kubectl create configmap id-token-service-config --from-env-file id-token-service-config.env

# login-consent-session-service
kubectl create configmap login-consent-session-service-config --from-env-file login-consent-session-service-config.env

# token-endpoint-gateway-service
kubectl create configmap token-endpoint-gateway-service-config --from-env-file token-endpoint-gateway-service-config.env

# authorize-endpoint-gateway-service
kubectl create configmap authorize-endpoint-gateway-service-config --from-env-file authorize-endpoint-gateway-service-config.env
```
