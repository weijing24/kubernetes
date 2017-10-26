# kubernetes
kubernetes 1.5.1
由于kubernetes安装的时候需要下载很多镜像，而这些镜像都在google服务器里。由于国内被墙了，各种下不了，所以利用docker hub中转

kube 1.5.1需要的镜像:
REPOSITORY                                               TAG
gcr.io/google_containers/kube-apiserver-amd64            v1.5.1
gcr.io/google_containers/kube-controller-manager-amd64   v1.5.1
gcr.io/google_containers/kube-proxy-amd64                v1.5.1
gcr.io/google_containers/kube-scheduler-amd64            v1.5.1
gcr.io/google_containers/kubernetes-dashboard-amd64      v1.5.0
gcr.io/google_containers/etcd-amd64                      3.0.14-kubeadm
gcr.io/google_containers/kubedns-amd64                   1.9
gcr.io/google_containers/dnsmasq-metrics-amd64           1.0
gcr.io/google_containers/kube-dnsmasq-amd64              1.4
gcr.io/google_containers/kube-discovery-amd64            1.0
gcr.io/google_containers/exechealthz-amd64               1.2
gcr.io/google_containers/pause-amd64                     3.0
