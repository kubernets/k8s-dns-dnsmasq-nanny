# k8s-dns-dnsmasq-nanny

github addr [https://github.com/kubernets/k8s-dns-dnsmasq-nanny](https://github.com/kubernets/k8s-dns-dnsmasq-nanny)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/k8s-dns-dnsmasq-nanny/raw/master/get-k8s-dns-dnsmasq-nanny-image.sh

## Arch and Version

- [**amd64** 1.14.10](https://hub.docker.com/r/kubernets/k8s-dns-dnsmasq-nanny-amd64)

    > docker pull kubernets/k8s-dns-dnsmasq-nanny-amd64:1.14.10

    > docker tag kubernets/k8s-dns-dnsmasq-nanny-amd64:1.14.10 gcr.io/google_containers/k8s-dns-dnsmasq-nanny-amd64:1.14.10 

    > docker rmi kubernets/k8s-dns-dnsmasq-nanny-amd64:1.14.10
