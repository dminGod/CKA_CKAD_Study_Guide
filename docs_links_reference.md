# Documentation Cheat-sheet

My reference notes for the CKA and CKAD exams

Links in the sections:

|Section Name | Number of links | High level purpose |
|--- | --- | --- |
|Setup | 	41 | 	Installation related information |
|Concetps | 	91 | 	Theory about the application |
|Tasks |  	170	 | Simple specific tasks that need to be carried out |
|Tutorials |  	38 | 	Tutorials that cover end to end tasks -- more suited for beginers |
|Reference |  	68 |  Reference of specific tools (kubectl, kubeadm) and components |

### Setup
Instructions for setting up a Kubernetes cluster

- What solutions to pick
- Download v1.14 alpha1, current release (all binaries) and page to do your own build
- **Section - Kubeadm**:
  - Bootstrap your own server using kubeadm
  - Make Highly available(HA) clusters and HA etcd clusters
  - Kubelet configuration using kubeadm
  - Troubleshooting kubeadm
- Section turnkey solutions (AWS EC2, Alibaba cloud, Azure, Google Compute ... etc)
- **Section Custom Cloud Solutions**:
  - Kubespray to install on-premise/cloud providers
  - Kops to install on AWS
- **Section On-Premises VMs** - Cloudstack, K8s on DC/OS, oVirt
- **Section Windows in K8s** 
  - Intro to windows in k8s
  - Adding windows nodes in k8s
  - scheduling windows containers in k8s
- K8s Version and Version Skew support policy
- Building Large Cluster
- Running in Multiple Zones
- CRI (Container Runtime Interface) Installation -- Docker, CRI-O, Containerd, frakti
- Install K8s with Digital Rebar Provision ( On premise installation helper )
- **PKI Certificates and Requirements** What component utilizes which certificates. Very good page.
- Running K8s locally with minikube ( Detailed page )
- Validate Node Setup (Node Conformance Test)



|Section | Page description |
| --- | --- |
|[Setup](https://kubernetes.io/docs/setup/)|  |
|[Picking the Right Solution](https://kubernetes.io/docs/setup/)|  |
|[Downloading Kubernetes](https://kubernetes.io/docs/setup/)|  |
|[Building a release](https://kubernetes.io/docs/setup/)|  |
|[v1.14 Release Notes](https://kubernetes.io/docs/setup/)|  |
|[Bootstrapping Clusters with kubeadm](https://kubernetes.io/docs/setup/)|  |
|[Installing kubeadm](https://kubernetes.io/docs/setup/)|  |
|[Creating a single master cluster with kubeadm](https://kubernetes.io/docs/setup/)|  |
|[Customizing control plane configuration with kubeadm](https://kubernetes.io/docs/setup/)|  |
|[Options for Highly Available Topology](https://kubernetes.io/docs/setup/)|  |
|[Creating Highly Available Clusters with kubeadm](https://kubernetes.io/docs/setup/)|  |
|[Set up a High Availability etcd cluster with kubeadm](https://kubernetes.io/docs/setup/)|  |
|[Configuring each kubelet in your cluster using kubeadm](https://kubernetes.io/docs/setup/)|  |
|[Troubleshooting kubeadm](https://kubernetes.io/docs/setup/)|  |
|[Turnkey Cloud Solutions](https://kubernetes.io/docs/setup/)|  |
|[Running Kubernetes on AWS EC2](https://kubernetes.io/docs/setup/)|  |
|[Running Kubernetes on Alibaba Cloud](https://kubernetes.io/docs/setup/)|  |
|[Running Kubernetes on Azure](https://kubernetes.io/docs/setup/)|  |
|[Running Kubernetes on CenturyLink Cloud](https://kubernetes.io/docs/setup/)|  |
|[Running Kubernetes on Google Compute Engine](https://kubernetes.io/docs/setup/)|  |
|[Running Kubernetes on Multiple Clouds with IBM Cloud Private](https://kubernetes.io/docs/setup/)|  |
|[Running Kubernetes on Multiple Clouds with Stackpoint.io](https://kubernetes.io/docs/setup/)|  |
|[Custom Cloud Solutions](https://kubernetes.io/docs/setup/)|  |
|[Installing Kubernetes On-premises/Cloud Providers with Kubespray](https://kubernetes.io/docs/setup/)|  |
|[Installing Kubernetes on AWS with kops](https://kubernetes.io/docs/setup/)|  |
|[On-Premises VMs](https://kubernetes.io/docs/setup/)|  |
|[Cloudstack](https://kubernetes.io/docs/setup/)|  |
|[Kubernetes on DC/OS](https://kubernetes.io/docs/setup/)|  |
|[oVirt](https://kubernetes.io/docs/setup/)|  |
|[Windows in Kubernetes](https://kubernetes.io/docs/setup/)|  |
|[Intro to Windows support in Kubernetes](https://kubernetes.io/docs/setup/)|  | 
|[Guide for adding Windows Nodes in Kubernetes](https://kubernetes.io/docs/setup/)|  |
|[Guide for scheduling Windows containers in Kubernetes](https://kubernetes.io/docs/setup/)|  |
|[Kubernetes Version and Version Skew Support Policy](https://kubernetes.io/docs/setup/)|  |
|[Building Large Clusters](https://kubernetes.io/docs/setup/)|  |
|[Running in Multiple Zones](https://kubernetes.io/docs/setup/)| |
|[CRI installation](https://kubernetes.io/docs/setup/)|  |
|[Installing Kubernetes with Digital Rebar Provision (DRP) via KRIB](https://kubernetes.io/docs/setup/)|  |
|[PKI Certificates and Requirements](https://kubernetes.io/docs/setup/)|  |
|[Running Kubernetes Locally via Minikube](https://kubernetes.io/docs/setup/)|  |
|[Validate Node Setup](https://kubernetes.io/docs/setup/)|  |




