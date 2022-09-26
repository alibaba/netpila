# Overview
Netpila is a high-performance network system for 'upper layer applications'.

Within the system framework, an abstraction layer (a.k.a 'Fabric') is delineated in Network Domain Specific Language to describe fundamental models (including network access and connectivity), as well as atomic network functionalities (as building blocks) to formulate network services on top of 'Fabric' for the network requirements of applications.

Modular design allows users to quickly build up a high-performance data plane with libraries provided by Netpila, based on the capabilities of their environment e.g. managed infrastructure, and easily offload functionalities of network services wherever it is possible. Also, 'Fabric' which has pluggable adapters embedded for different data plane backends, is a good choice to build up the efficient control plane as as whole, for the large-scale application infrastructure e.g. hybrid clouds.

Specifically, Netpila supports IP networking of application workload nodes including Containers, Virtual Machines or Bare Metals, by integration with Kubernetes or other virtualization platforms. It is also compatible with existing container network solutions, like Flannel, that their users can reap the benefits of hardware acceleration.

In the future, Netpila can integrate with Mesh solutions and offload the implementation of traffic management, observability and security into network services for optimum performance.

# Getting Started
TBD

# Community
TBD

# License
Netpila is under the Apache 2.0 license, see the LICENSE file.
