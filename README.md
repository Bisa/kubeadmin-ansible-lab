# kubeadmin ansible lab

- copy inventories/lab.yaml.example
- init (and reset!) the cluster with playbooks/init-cluster.yaml
- bootstrap all controllers/workers with site.yaml

## TODO

- configurable kubernetes version, currently hard coded
- configurable pod CIDR, hard coded in kubeadm-config.yaml
