# Documentation to deploy worker node

### Deploy with `kubectl`:
```bash
kubectl apply -f https://raw.githubusercontent.com/embedez/webscraper-config/main/kubectl-deploy.yml
```

### Deploy with Docker:
```bash
docker run --name webscrapper-node -d ghcr.io/embedez/webscrapper-node:latest
```
