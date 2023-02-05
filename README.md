# k8s-study

Este projeto é uma base para estudo de conceitos basicos de kubernetes, para isso estou utilizando o kind.

Pré requisitos:
  - Docker 
  - Kubectl

Para instalar o kind acesse: https://kind.sigs.k8s.io/

Com kind instalado execute os seguintes comandos 

```shell 
kind create cluster
alias k=kubectl
k cluster-info --context kind-kind
```

