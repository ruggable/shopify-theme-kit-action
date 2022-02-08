# shopify-theme-kit-action

Plain binary of Shopify Theme Kit for Github Actions

## Building the Docker Image

```
export CR_PAT=YOUR_TOKEN
echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin
docker build . --tag ghcr.io/ruggable/shopify-theme-kit-action:latest
docker push ghcr.io/ruggable/shopify-theme-kit-action:latest
```
