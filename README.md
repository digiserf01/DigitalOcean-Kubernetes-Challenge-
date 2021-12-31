## <span style="color:blue">DigitalOcean Kubernetes Challenge</span>

##
<span style="color:blue">DigitalOcean Kubernetes (DOKS) </span> is a managed Kubernetes service which takes care of the control plane and containerized infrastructure. 

K8 toolchain is available and nodes are built on Digital Ocean <code> droplets </code> which are customized to your optimization & use cases.

<code>doctl</code> is used to interact with a DOKS cluster. You can find [more information here](https://github.com/digitalocean/doctl). 

To start with the challenge, follow the instructions to create a cluster

![](static/clustercreate.png?raw=true)

Instructions to install Harbor are fairly simple with Helm providing the handholding

<code>helm install doks-release harbor/harbor -f harbor-values.yaml</code>

![](static/clusterharborinstall.png?raw=true)





