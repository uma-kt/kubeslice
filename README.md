# Kubeslice Community Kubernetes Helm Charts

KubeSlice provides network services to applications that need secure and highly available connectivity between multiple clusters. KubeSlice creates a flat overlay network to connect the clusters. The overlay network can be described as an application slice that provides a slice of connectivity between the pods of an application running in multiple clusters. It can also be described as an application-specific VPC that spans across clusters. Pods can connect to the slice overlay network and communicate with each other seamlessly across cluster boundaries.

#### Architecture
See [Learn: Kubeslice Reference Architecture](https://docs.avesha.io/opensource/kube-slice-architecture) to get an overview of the overall architecture and core components.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add avesha https://kubeslice.github.io/charts/
```

You can then run `helm search repo avesha` to see the charts.


Quick Start
---

#### Testing
See [Learn: Getting Started](https://docs.avesha.io/opensource/getting-started-with-kind-clusters) for instructions on setting up a local kubeslice setup using kind for non-production use.

Guide
---
Full, comprehensive documentation is available on the our opensource documentation website: https://docs.avesha.io/opensource/
