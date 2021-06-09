# kubenetes-extra

## deploy nginx-ingress-controller

```bash
$ kubectl create ns ingress-nginx
$ kubectl apply -f ./deploy/nginx-ingress-controller/
```

## deploy metrics-server

```bash
$ kubectl apply -f https://raw.githubusercontent.com/crazytaxii/kubernetes-extra/master/deploy/metrics-server/all.yaml
```

## deploy prometheus-operator

```bash
$ kubectl apply -f ./deploy/prometheus-operator/
```

## deploy monitoring

```bash
$ kubectl create ns monitoring
$ kubectl apply -f ./deploy/monitoring/
```

## deploy flask-demo (ClusterIP)

```bash
$ kubectl create -f https://raw.githubusercontent.com/crazytaxii/kubernetes-extra/master/deploy/flask-demo/all.yaml
```

## deploy local static provisioner

```bash
$ kubectl create -f https://raw.githubusercontent.com/crazytaxii/kubernetes-extra/master/deploy/local-static-provisioner/all.yaml
```
