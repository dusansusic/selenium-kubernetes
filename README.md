# Documentation

## Selenium Hub Service

Creating Selenium hub service can be done with command `kubectl create -f selenium-hub-service.yaml`.
Service is defined as LoadBalancer so you can access Selenium Console directly over the port 4444.
Change your IPs with actual IP addresses.

## Ingress

Create ingress rules `kubectl create -f selenium-hub-ingress.yaml`. Change your host domain!

## Selenium Hub Deployment

Deploy Selenium Hub with executing `kubectl create -f selenium-hub-deployment.yaml`.

## Selenium Node Chrome Deployment

Deploy Selenium Node Chrome with executing `kubectl create -f selenium-node-chrome-deployment.yaml`.
Change number of replicas.

## Selenium Node Firefox Deployment

Deploy Selenium Node Chrome with executing `kubectl create -f selenium-node-firefox-deployment.yaml`.
Change number of replicas.

## Selenium console
![Alt text](images/selenium-hub-nodes.png?raw=true "Selenium console")
