# Foodkit API CI Docker

Dockerfile for the image used to run Foodkit API tests in Circle CI.

## Build

```
docker build -f api .
```

## Push

```
# Tag the image created in the `build` step
docker tag <hash> foodkit/php-ci:7.4

# Push to Docker Hub
docker image push foodkit/php-ci:7.4
```
