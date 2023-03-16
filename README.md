# k8s-cluster-footprint-strategies

## tl;dr

If you meet the organizational requirements for running a shared cluster, you should start with a shared cluster.

As you onboard workloads into a shared cluster, eventually certain sensitive workloads may call for harder isolation than a shared cluster can provide. 

If you run into this, you should isolate these to individual _but standardized and audited_ clusters. 

## Overview

TODO

## Cluster footprint strategies

Everyone is probably doing multi-cluster, in a form. 

But here's how I think of the three paths organizations and teams can take with regard to multi-cluster:

* Fewer, large clusters
* Many, small to medium clusters
* Somewhere in between
    * Fewer, large clusters with special workload-based exceptions for specific small to medium clusters

### Fewer, large clusters

TODO

### Many, small to medium clusters

TODO

### Somewhere in between

TODO
