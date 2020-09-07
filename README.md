
<img src="http://plant-up.cloud/assets/logo.png" height="250px" >  

# Awesome Plant.Up🌿

[![awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/PlantUp/awesome)

_Just the cool_ things you may need to get started with [__vertical farming in the cloud__](https://plant-up.cloud)

## Table of context 📜 
0. [Open-Source-Concept](#open-source-concept 🕍)
1. [Infrastructure](#infrastructure)
2. [Development](#development)
3. [Plants](#plants)
4. [Dataflow](#dataflow)
5. [Devices](#devices)
4. [Knowledge](#knowledge)  
```...```

## Open-Source-Concept 🕍
* _TODO_  
```...```
## Infrastructure 🔩  
* [AWS EKS](https://aws.amazon.com/eks)  
  We want to be able to scale to the size needed, but retain the freedom of moving between clouds.
  Who has time to manage a K8S? We want to Code! ❤️
* [Grafana](https://grafana.com/)  
  Is there any other service for dashboards? At least not a better one!
* [Grafana Operator](https://operatorhub.io/operator/grafana-operator)  
  Grafana with k8S-integration is a perfect match with Gitops.
* [Pulumi](https://www.pulumi.com/)  
  The benefits of a _real_ programming language and IaCaaS.  
* [Prometheus Monitoring Stack](https://github.com/prometheus-operator/prometheus-operator)  
  The perfect app-specific monitoring.
* [KEDA](https://keda.sh/)  
  Autoscaling microservices based on real-world events.
* [FAAS]()  
  We are searching for a FAAS framework with the capability of running a go/rust-function without a docker-registry and above one scaling.  
  Maybe Fission or Kubeless.
* [Keycloak](https://www.keycloak.org/)  
  OAuth2 for everyone! The Operator is quite nice.
* [NGINX Ingress](https://kubernetes.github.io/ingress-nginx/)  
  The most used Ingress-controller for K8S.
* [Cert Manager](https://cert-manager.io/)
  BugMeNot for TSL Encryption.  
```...```
## Development 🖼️ 
* [GitHub Actions](https://github.com/features/actions)
  A nice and easy workflow plattform for GitHub projects.  
  Has a good Pulumi integration.  
* [Golang](https://golang.org/)  
  A static-typed systems programming language with grabage-collection.
* [Github Packages](https://github.com/features/packages)  
  All in one place :D
* [Codecov](https://codecov.io/)  
  A modern take on codeanalysis.
* [React](https://reactjs.org/)  
  A framework for building Web UIs.
* [Redux](https://redux.js.org/)  
  State needs to be in one state. Especially settings ...  
* [H3](https://eng.uber.com/h3/)  
  Uber mapped the world in hexagons. One number to know a specific location.  
```...```
## Plants 🌵
* _TODO_  
```...```
## Dataflow 🌊 
* [CockroachDB](https://www.cockroachlabs.com/)  
  This incredible oss pendant to spanner is the heart of our data-plattform. We love it's ease to use and scalability.
* [EMQX Broker](https://www.emqx.io/)  
  Due to a huge spike tolerance we are in need of a cloud-native message-queue with rich capabilties and [Kubernetes](https://kubernetes.io) support.
* [AWS S3](https://aws.amazon.com/s3)  
  Easier Storage? Nope.
* [Protobuf](https://developers.google.com/protocol-buffers/)  
  Integrated in MQTT we have a small and safe package to deliver.  
```...```
## Devices 📟 
* [The Update Framework](https://theupdateframework.io/)  
  A safety framework on how to handle things with and around updates.  
```...```
## Knowledge 📚 
* [WikiJS](https://wiki.js.org/)  
  A wiki that can used to read and write from a git repository.
* [GitHub](https://github.com/)  
  GutHub is our single source of truth.  
```...```

---
Thanks for being interested in this project!
We are open to collaboration.
