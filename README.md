# nogcr

k8s related docker images.

FROM k8s.gcr.io/kube-apiserver-amd64:v1.10.5
FROM k8s.gcr.io/kube-controller-manager-amd64:v1.10.5
FROM k8s.gcr.io/kube-scheduler-amd64:v1.10.5
FROM k8s.gcr.io/kube-proxy-amd64:v1.10.5
FROM k8s.gcr.io/k8s-dns-dnsmasq-nanny-amd64:1.14.10
FROM k8s.gcr.io/k8s-dns-kube-dns-amd64:1.14.10
FROM k8s.gcr.io/k8s-dns-sidecar-amd64:1.14.10
FROM k8s.gcr.io/etcd-amd64:3.1.12
FROM k8s.gcr.io/pause-amd64:3.1
FROM quay.io/coreos/flannel:v0.10.0-amd64
FROM gcr.io/google_containers/cluster-autoscaler:v1.2.2
FROM k8s.gcr.io/kubernetes-dashboard-amd64:v1.8.3

FROM gcr.io/google-containers/nginx-ingress-controller:0.9.0-beta.15
FROM gcr.io/google_containers/defaultbackend:1.4
FROM quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.15.0

FROM gcr.io/runconduit/controller:v0.4.3
FROM gcr.io/runconduit/grafana:v0.4.3
FROM gcr.io/runconduit/proxy:v0.4.3
FROM gcr.io/runconduit/proxy-init:v0.4.3
FROM gcr.io/runconduit/web:v0.4.3

FROM gcr.io/kubernetes-helm/tiller:v2.9.1
FROM k8s.gcr.io/heapster:v1.3.0
FROM k8s.gcr.io/heapster-amd64:v1.5.0
FROM k8s.gcr.io/heapster-grafana-amd64:v4.4.3
FROM k8s.gcr.io/heapster-influxdb-amd64:v1.3.3
FROM k8s.gcr.io/kube-addon-manager:v8.6
FROM k8s.gcr.io/addon-resizer:1.7

FROM gcr.io/spinnaker-marketplace/clouddriver:2.0.0-20180221152902
FROM gcr.io/spinnaker-marketplace/echo:0.8.0-20180221133510
FROM gcr.io/spinnaker-marketplace/deck:2.1.0-20180221143146
FROM gcr.io/spinnaker-marketplace/igor:0.9.0-20180221133510
FROM gcr.io/spinnaker-marketplace/orca:0.10.0-20180221133510
FROM gcr.io/spinnaker-marketplace/gate:0.10.0-20180221133510
FROM gcr.io/spinnaker-marketplace/front50:0.9.0-20180221133510
FROM gcr.io/spinnaker-marketplace/rosco:0.5.0-20180221133510
