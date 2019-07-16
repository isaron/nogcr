# nogcr

k8s related docker images.

FROM k8s.gcr.io/kube-apiserver-amd64:v1.11.6

FROM k8s.gcr.io/kube-controller-manager-amd64:v1.11.6

FROM k8s.gcr.io/kube-scheduler-amd64:v1.11.6

FROM k8s.gcr.io/kube-proxy-amd64:v1.11.6

FROM k8s.gcr.io/k8s-dns-dnsmasq-nanny-amd64:1.14.10

FROM k8s.gcr.io/k8s-dns-kube-dns-amd64:1.14.10

FROM k8s.gcr.io/k8s-dns-sidecar-amd64:1.14.10

FROM k8s.gcr.io/etcd-amd64:3.2.18

FROM k8s.gcr.io/pause-amd64:3.1

FROM quay.io/coreos/flannel:v0.10.0-amd64

FROM gcr.io/google_containers/cluster-autoscaler:v1.3.3

FROM k8s.gcr.io/kubernetes-dashboard-amd64:v1.10.1

FROM k8s.gcr.io/metrics-server-amd64:v0.3.1

FROM registry.opensource.zalan.do/teapot/external-dns:latest

FROM gcr.io/google-containers/nginx-ingress-controller:0.9.0-beta.15

FROM gcr.io/google_containers/defaultbackend:1.5

FROM quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.19.0


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

FROM k8s.gcr.io/kube-addon-manager:v8.6

FROM k8s.gcr.io/addon-resizer:1.7


FROM k8s.gcr.io/elasticsearch:v6.3.0

FROM k8s.gcr.io/fluentd-elasticsearch:v2.3.2

FROM docker.elastic.co/kibana/kibana-oss:6.3.2
