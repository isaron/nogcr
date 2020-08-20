# nogcr

k8s related docker images.

FROM k8s.gcr.io/kube-apiserver-amd64:v1.15.2

FROM k8s.gcr.io/kube-controller-manager-amd64:v1.15.2

FROM k8s.gcr.io/kube-scheduler-amd64:v1.15.2

FROM k8s.gcr.io/kube-proxy-amd64:v1.15.2

FROM k8s.gcr.io/k8s-dns-node-cache-amd64:1.15.0

FROM k8s.gcr.io/k8s-dns-dnsmasq-nanny-amd64:1.14.13

FROM k8s.gcr.io/k8s-dns-kube-dns-amd64:1.14.13

FROM k8s.gcr.io/k8s-dns-sidecar-amd64:1.14.13

FROM k8s.gcr.io/etcd-amd64:3.3.10

FROM k8s.gcr.io/pause-amd64:3.1

FROM quay.io/coreos/flannel:v0.11.0-amd64

FROM gcr.io/google_containers/cluster-autoscaler:v1.15.0

FROM k8s.gcr.io/kubernetes-dashboard-amd64:v1.10.1

FROM k8s.gcr.io/metrics-server-amd64:v0.3.3

FROM registry.opensource.zalan.do/teapot/external-dns:latest

FROM us.gcr.io/k8s-artifacts-prod/ingress-nginx/controller:v0.34.1

FROM gcr.io/google_containers/defaultbackend:1.5

FROM quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.25.0

FROM k8s.gcr.io/cluster-proportional-autoscaler-amd64:1.6.0

FROM gcr.io/runconduit/controller:v0.5.0

FROM gcr.io/runconduit/grafana:v0.5.0

FROM gcr.io/runconduit/proxy:v0.5.0

FROM gcr.io/runconduit/proxy-init:v0.5.0

FROM gcr.io/runconduit/web:v0.5.0


FROM gcr.io/kubernetes-helm/tiller:v2.14.2

FROM k8s.gcr.io/heapster:v1.3.0

FROM k8s.gcr.io/heapster-amd64:v1.5.4

FROM k8s.gcr.io/heapster-grafana-amd64:v5.0.4

FROM k8s.gcr.io/heapster-influxdb-amd64:v1.5.2

FROM k8s.gcr.io/kube-addon-manager:v9.0.1

FROM k8s.gcr.io/addon-resizer:1.7


FROM k8s.gcr.io/elasticsearch:v6.7.2

FROM k8s.gcr.io/fluentd-elasticsearch:v2.5.2

FROM docker.elastic.co/kibana/kibana-oss:6.6.1
