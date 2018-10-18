# Kubernetes Tools

## Developer Tools
- [Draft](https://github.com/Azure/draft): Draft makes it easy to build applications that run on Kubernetes. Draft targets the "inner loop" of a developer's workflow: as they hack on code, but before code is committed to version control.
- [Kubectx](https://github.com/ahmetb/kubectx): Fast way to switch between clusters and namespaces in kubectl 
- [Kube-ps1](https://github.com/jonmosco/kube-ps1): Kubernetes prompt info for bash and zsh
- [Skaffold](https://github.com/GoogleContainerTools/skaffold): Easy and Repeatable Kubernetes Development
- [kube-shell](https://github.com/cloudnativelabs/kube-shell): An integrated shell for working with the Kubernetes
- [Copper](https://github.com/cloud66-oss/copper): Copper is a configuration validator for Kubernetes
- [kubefwd](https://github.com/txn2/kubefwd): Bulk port forwarding Kubernetes services for local development.
## Package Manager
- [Helm](https://github.com/helm/helm): Helm is a tool that streamlines installing and managing Kubernetes applications. Think of it like apt/yum/homebrew for Kubernetes.

## Ingress Controller
- [Contour](https://github.com/heptio/contour): Contour is a Kubernetes ingress controller for Lyft's Envoy proxy.
- [Kubemci](https://github.com/GoogleCloudPlatform/k8s-multicluster-ingress): kubemci is a tool to configure Kubernetes ingress to load balance traffic across multiple Kubernetes clusters.
- [Ambassador](https://www.getambassador.io): Ambassador is a Kubernetes-native API gateway for microservices. Ambassador is deployed at the edge of your network, and routes incoming traffic to your internal services.

## Debugging
- [Telepresence](https://www.telepresence.io/): Local development against a remote Kubernetes
- [Stern](https://github.com/wercker/stern): Stern allows you to tail multiple pods on Kubernetes and multiple containers within the pod. Each result is color coded for quicker debugging.
- [Ksync](https://github.com/vapor-ware/ksync): 
ksync speeds up developers who build applications for Kubernetes. It transparently updates containers running on the cluster from your local checkout. 

## Security
- [Kubesec](https://kubesec.io/)
- [Kube-hunter](https://github.com/aquasecurity/kube-hunter): Hunt for security weaknesses in Kubernetes clusters
- [Kube-bench](https://github.com/aquasecurity/kube-bench): The Kubernetes Bench for Security is a Go application that checks whether Kubernetes is deployed according to security best practices
- [Cert-manager](https://github.com/jetstack/cert-manager/): Automatically provision and manage TLS certificates in Kubernetes

## Chaos Engineering
-[kube-monkey](https://github.com/asobti/kube-monkey): An implementation of Netflix's Chaos Monkey for Kubernetes clusters

## Distributions
- [Typhoon](https://github.com/poseidon/typhoon): Minimal and free Kubernetes distribution 

## Extensions
- [kubernetes-ldap](https://github.com/apprenda-kismatic/kubernetes-ldap): ightweight Directory Access Protocol (LDAP) for Kubernetes

### GKE
- [kubernetes-rbac-synchroniser](https://github.com/google-cloud-tools/kubernetes-rbac-synchroniser): RBAC Synchroniser pulls a Google Group, extracts Google Group Member Emails and updates the Kubernetes RoleBinding in the given namespace.
