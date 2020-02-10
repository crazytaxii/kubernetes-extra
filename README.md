# kubenetes-extra

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
