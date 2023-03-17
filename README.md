# k8s-cluster-footprint-strategies

## tl;dr

If you meet the organizational requirements for running a shared cluster, you should start with a shared cluster.

As you onboard workloads into a shared cluster, eventually certain sensitive workloads may call for harder isolation than a shared cluster can provide. 

If you run into this, you should isolate these to individual _but standardized and audited_ clusters. 

## Overview

TODO

## Kubernetes cluster footprint strategies

Everyone is probably doing multi-cluster, in a form. Even the staunch single cluster model advocates probably have a separate staging cluster. 

With that said, here's how I think of the three paths organizations and teams can take around a multi-cluster strategy:

* Fewer, large clusters
    * Centralized team owns fewer, large multi-tenant clusters, exposing to service owners via automation
* Many, small to medium clusters
    * Service teams own their own individual clusters, with a centralized team owning cluster templates, guardrails, and provisioning 
* Somewhere in between
    * Centralized teams own fewer, large clusters and special workload-based exception clusters that can be small to medium in size

### Fewer, large clusters

TODO

### Many, small to medium clusters

TODO

### Somewhere in between

TODO
