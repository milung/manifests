# INSTALL KUBEFLOW on Docker for Desktop on Windows 10

## Prerequisites

* [Docker for desktop](https://www.docker.com/products/docker-desktop) (tested with version 2.4.0 (48506) with [WSL 2](https://docs.docker.com/docker-for-windows/wsl/) backend  
* Install [KinD](https://kind.sigs.k8s.io/docs/user/quick-start/) using the config file [kind-cluster.md] from this repository. 
* open wsl terminal and install kubeflow on existing cluster. Follow steps at [tutorial](https://www.kubeflow.org/docs/started/k8s/kfctl-k8s-istio/) but use different `CONFIG_URI`

```sh
export CONFIG_URI="https://raw.githubusercontent.com/milung/manifests/v1.1-kind_on_wsl2/kfdef/kfctl_k8s_istio.v1.1.0-kind.yaml
```


