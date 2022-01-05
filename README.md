# kubenetes-extra

## nginx-ingress-controller

```bash
$ kubectl create ns ingress-nginx
$ kubectl apply -f ./deploy/nginx-ingress-controller/
```

## metrics-server

```bash
$ kubectl apply -f https://raw.githubusercontent.com/crazytaxii/kubernetes-extra/master/deploy/metrics-server/all.yaml
```

## prometheus-operator

```bash
$ kubectl apply -f ./deploy/prometheus-operator/
```

## monitoring

```bash
$ kubectl create ns monitoring
$ kubectl apply -f ./deploy/monitoring/
```

## flask-demo (ClusterIP)

```bash
$ kubectl create -f https://raw.githubusercontent.com/crazytaxii/kubernetes-extra/master/deploy/flask-demo/all.yaml
```

## local static provisioner

```bash
$ kubectl create -f https://raw.githubusercontent.com/crazytaxii/kubernetes-extra/master/deploy/local-static-provisioner/all.yaml
```

## nfs-subdir-external-provisioner

- `NFS_IPADDR`: nfs server addr
- `SHARED_PATH`: nfs shared path

```bash
$ kubectl create -f deploy/nfs-subdir-external-provisioner/all.yaml
```
