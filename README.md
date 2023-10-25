# Scalable-p2 Orchestrator

> Note: Don't forget to define the following environment variables
```sh
kubectl create secret docker-registry ghcr-login-secret \
    --docker-server='...' \
    --docker-username='...' \
    --docker-password='...'

kubectl create secret generic aws-credentials \
    --from-literal='AWS_ACCESS_KEY_ID=...' \
    --from-literal='AWS_SECRET_ACCESS_KEY=...'

kubectl create secret generic db-secret \
    --from-literal='DB_NAME=...' \
    --from-literal='DB_USER=...' \
    --from-literal='DB_PASS=...' \
    --from-literal='DB_PORT=...' \
    --from-literal='DB_IP=...' \
    --from-literal='DB_ROOT_PASS=...'
```
