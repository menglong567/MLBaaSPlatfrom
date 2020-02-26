## Welcome to MLBaaSPlatfrom
> A simple platform based on docker &amp; Kubernetes to setup block system (currently for multichain and corda system).

### Introduction

> This Simple Platform consists of below sub-projects:

```markdown
multichain-docker-kubernetes
<https://github.com/menglong567/multichain-docker-kubernetes>

corda-docker-kubernetes
<https://github.com/menglong567/corda-docker-kubernetes.git>

MultichainClient
<https://github.com/menglong567/MultichainClient>

CordaClient
<https://github.com/menglong567/CordaClient.git>

KubernetesClient
<https://github.com/menglong567/KubernetesClient>

MultiChainJavaAPI
<https://github.com/menglong567/MultiChainJavaAPI>

HelmChart
<https://github.com/menglong567/MLBaaSHelmChart>

Web-console
<https://github.com/menglong567/BaasFrontConsole>

Besides the above projects you also need to be familiar with multichain which is an opensource blockchain
(It also provides commercial version starting from 2.x version) <https://www.multichain.com/> and corda 

Current the whole BaaS system is still in developing status and for front-end server you can build on your own 
based on the api from MultichainClient project and KubernetesClient using whatever frameworks you like or you can use 
the testing web console I developed from <https://github.com/menglong567/BaasFrontConsole>

For helm chart please refer to <https://github.com/menglong567/MLBaaSHelmChart>
```
### Purpose of the BaaS System
Without BaaS system there're much more details you need to consider if you want to deploy blockchain networks to docker or even kubernetes for any blockchain product.

This simple platform provides the ability to deploy blockchain network to kubernetes for multichain and corda for current and maybe other blockchain products in the future

### Architecture
> Here i'm giving the whole picture of this simple project as below

![avatar](img/arch.png)

### How to get started
> Please refer to <https://github.com/menglong567/BaasFrontConsole>

### Support or Contact
> If you have question please contact me via menglong567@aliyun.com