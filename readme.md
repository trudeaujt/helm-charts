This release is using https://github.com/acjohnson/hcloud-cloud-controller-manager fork of Hetzner's CCM to be compatible with kubeadm installations of Kubernetes.
Make sure to add the instance.hetzner.cloud/is-root-server=true label to the nodes otherwise they will not be able to be scheduled to.
