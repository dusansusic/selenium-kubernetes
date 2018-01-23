# Documentation

## Selenium Hub Service

Creating Selenium hub service can be done with command:

`kubectl create -f selenium-hub-service.yaml`.
go to Ingresses and see the endpoint for Selenium console.

## Ingress

Create ingress rule:

`kubectl create -f selenium-hub-ingress.yaml`.

## Selenium Hub Deployment

Deploy Selenium Hub with executing:

`kubectl create -f selenium-hub-deployment.yaml`.

## Selenium Node Chrome Deployment

Deploy Selenium Node Chrome with executing:

`kubectl create -f selenium-node-chrome-deployment.yaml`.

Change number of replicas if you need more nodes.

## Selenium Node Firefox Deployment

Deploy Selenium Node Chrome with executing:

`kubectl create -f selenium-node-firefox-deployment.yaml`.

Change number of replicas if you need more nodes.

## Selenium console
![Alt text](images/selenium-hub-nodes.png?raw=true "Selenium console")
