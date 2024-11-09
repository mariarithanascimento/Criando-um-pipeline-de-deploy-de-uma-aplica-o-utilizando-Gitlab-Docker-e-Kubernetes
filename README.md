# Projeto 2: Criando um pipeline de deploy de uma aplicação utilizando Gitlab, Docker e Kubernetes

## Descrição

Neste projeto será criado um pipeline de deploy de uma aplicação com dois cenários:

- **Deploy da aplicação Node.js em um container Docker**
- **Deploy da aplicação Node.js em um cluster Kubernetes em nuvem utilizando o GCP**

Este projeto deverá ser apresentado em duas branches:

- Uma branch com o deploy da aplicação sendo executada em um container Docker.
- Outra branch com o deploy da aplicação sendo executada em um cluster Kubernetes utilizando o GCP.

## Arquitetura do Cluster e da Aplicação

- **Aplicação:** Node.js
- **Cluster Kubernetes:**
  - Distribuição dos nodes em três instâncias (Node 1, Node 2, Node 3)
  - Balanceamento de carga (Load Balancer)
  - Volume Persistente (PV)

---

