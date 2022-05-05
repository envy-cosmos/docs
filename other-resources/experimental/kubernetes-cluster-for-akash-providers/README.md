# Kubernetes Cluster for Akash Providers

## **Overview**

Akash leases are deployed via Kubernetes pods on provider clusters.  This guide details the build of the provider’s Kubernetes control plane and worker nodes.

The setup of a Kubernetes cluster is the responsibility of the provider. This guide provides best practices and recommendations for setting up a Kubernetes cluster. This document is not a comprehensive guide and assumes pre-existing Kubernetes knowledge.

The Kubernetes Cluster created is then ready for the Akash Provider build detailed [here](../akash-cloud-provider-build-with-helm-charts/).

* [Clone the Kubespray Project](step-1-clone-the-kubespray-project.md)
* [Install Ansible](step-2-install-ansible.md)
* [Ansible Access to Kubernetes Cluster](step-3-ansible-access-to-kubernetes-cluster.md)
* [Ansible Inventory](step-4-ansible-inventory.md)
* [Enable gVisor](step-5-enable-gvisor.md)
* [Create Kubernetes Cluster](step-6-create-kubernetes-cluster.md)
* [Confirm Kubernetes Cluster](step-7-confirm-kubernetes-cluster.md)
* [Disable Swap on Kubernetes Hosts](step-8-disable-swap-on-kubernetes-hosts.md)
* [Review Firewall Policies](step-9-review-firewall-policies.md)