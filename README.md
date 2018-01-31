# Documentation

## Selenium Namespace
First, create namespace for Selenium:
```
kubectl create -f selenium-namespace.yaml
```

## Selenium Hub Service
Creating Selenium hub service can be done with command:

```
kubectl create -f selenium-hub-service.yaml
```

## Ingress

Create ingress rule:

```
kubectl create -f selenium-hub-ingress.yaml
```

## Selenium Hub Deployment

Deploy Selenium Hub with executing:

```
kubectl create -f selenium-hub-deployment.yaml
```

## Selenium Node Chrome Deployment

Deploy Selenium Node Chrome with executing:

```
kubectl create -f selenium-node-chrome-deployment.yaml
```

Change number of replicas if you need more nodes.

## Selenium Node Firefox Deployment

Deploy Selenium Node Chrome with executing:

```
kubectl create -f selenium-node-firefox-deployment.yaml
```

Change number of replicas if you need more nodes.

## Selenium console
![Alt text](images/selenium-hub-nodes.png?raw=true "Selenium console")
