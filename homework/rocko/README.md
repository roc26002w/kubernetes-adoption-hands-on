# learn-kubernetes

## Install

* kubectl create configmap nginx-default-conf --from-file=config/nginx/default.conf
* kubectl create configmap fluent-default-conf --from-file=config/fluent/fluent.conf
* kubectl apply -f .
