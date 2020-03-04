# kubenetes-extra

## deploy nginx-ingress-controller

```bash
$ kubectl create ns ingress-nginx
$ kubectl apply -f ./deploy/nginx-ingress-controller/
```

## deploy mectris-server

```bash
$ kubectl apply -f ./deploy/metrics-server/
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
$ kubectl create -f ./deploy/flask-demo/ -n demo
```
