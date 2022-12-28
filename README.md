# Jetson Mate Kubernetes Cluster

I have some NVIDIA Jetson hardware that I have used for other projects (JetBot, etc..) and now I'd like to build an ARM-based Kubernetes cluster.

Seeed Studio Jetson Mate 
NVIDIA Jetson NX Xavier
NVIDIA Jetson Nano


Mac Mini (Intel) running:

* Ubuntu 18.04.6 LTS
* NVIDIA sdkmanager

I have DHCP and DNS configured for my home lab using BIND and Red Hat IdM. (you can use anything for this)

| Hostname | IP Address  | Purpose/Alias   | Module                   | 
|:---------|:------------|:----------------|:-------------------------|
| jane     | 10.10.10.53 | control-plane-0 | NVIDIA Jetson Nano       |
| xavier-0 | 10.10.10.55 | worker-0        | NVIDIA Jetson NX Xavier  |
| xavier-1 | 10.10.10.57 | worker-1        | NVIDIA Jetson NX Xavier  |

