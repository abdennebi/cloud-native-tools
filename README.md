# Kubernetes Tools

## Developer Tools
- [crane](https://github.com/google/go-containerregistry/tree/main/cmd/crane): a tool for interacting with remote images and registries.
- [crossplane](https://github.com/crossplane/crossplane): Crossplane is a framework for building cloud native control planes without needing to write code. It has a highly extensible backend that enables you to build a control plane that can orchestrate applications and infrastructure no matter where they run, and a highly configurable frontend that puts you in control of the schema of the declarative API it offers.
- [Draft](https://github.com/Azure/draft): Draft makes it easy to build applications that run on Kubernetes. Draft targets the "inner loop" of a developer's workflow: as they hack on code, but before code is committed to version control.
- [ko](https://github.com/ko-build/ko): ko is a simple, fast container image builder for Go applications
- [Kubectx](https://github.com/ahmetb/kubectx): Fast way to switch between clusters and namespaces in kubectl 
- [Kube-ps1](https://github.com/jonmosco/kube-ps1): Kubernetes prompt info for bash and zsh
- [Skaffold](https://github.com/GoogleContainerTools/skaffold): Easy and Repeatable Kubernetes Development
- [kube-shell](https://github.com/cloudnativelabs/kube-shell): An integrated shell for working with the Kubernetes
- [Copper](https://github.com/cloud66-oss/copper): Copper is a configuration validator for Kubernetes
- [kubefwd](https://github.com/txn2/kubefwd): Bulk port forwarding Kubernetes services for local development.
- [kubernetes-deploy](https://github.com/Shopify/kubernetes-deploy): A command-line tool that helps you ship changes to a Kubernetes namespace and understand the result

## Ops
- [Gravity](https://github.com/gravitational/gravity): Gravity is an open source tooklit for creating "snapshots" of Kubernetes clusters and the applications running inside the clusters. The resulting snapshots are called *application bundles*.
- [Machine Controller Manager](https://github.com/gardener/machine-controller-manager): Declarative way of managing machines for Kubernetes cluster


## Visualization
- [Weave Scope](https://github.com/weaveworks/scope): Monitoring, visualisation & management for Docker & Kubernetes 
- [Kubebox](https://github.com/astefanutti/kubebox): Terminal and Web console for Kubernetes 

## Package Manager
- [Helm](https://github.com/helm/helm): Helm is a tool that streamlines installing and managing Kubernetes applications. Think of it like apt/yum/homebrew for Kubernetes.

## Ingress Controller
- [Contour](https://github.com/heptio/contour): Contour is a Kubernetes ingress controller for Lyft's Envoy proxy.
- [Kubemci](https://github.com/GoogleCloudPlatform/k8s-multicluster-ingress): kubemci is a tool to configure Kubernetes ingress to load balance traffic across multiple Kubernetes clusters.
- [Ambassador](https://www.getambassador.io): Ambassador is a Kubernetes-native API gateway for microservices. Ambassador is deployed at the edge of your network, and routes incoming traffic to your internal services.

## Monitoring & Observality
- [Hubble](https://github.com/cilium/hubble): Hubble is a fully distributed networking and security observability platform for cloud native workloads. It is built on top of Cilium and eBPF to enable deep visibility into the communication and behavior of services as well as the networking infrastructure in a completely transparent manner.
- [Kubewatch](https://github.com/robusta-dev/kubewatch): Watch k8s events and trigger Handlers.
- [Kubeshark](https://github.com/kubeshark/kubeshark): Kubeshark, the API Traffic Viewer for kubernetes, provides deep visibility and monitoring of all API traffic and payloads going in, out and across containers and pods inside a Kubernetes cluster. Think of a combination of Chrome Dev Tools, TCPDump and Wireshark, re-invented for Kubernetes.


## Debugging
- [Telepresence](https://www.telepresence.io/): Local development against a remote Kubernetes
- [Stern](https://github.com/wercker/stern): Stern allows you to tail multiple pods on Kubernetes and multiple containers within the pod. Each result is color coded for quicker debugging.
- [Ksync](https://github.com/vapor-ware/ksync): 
ksync speeds up developers who build applications for Kubernetes. It transparently updates containers running on the cluster from your local checkout. 

## Security
- [connaisseur](https://github.com/sse-secure-systems/connaisseur): A Kubernetes admission controller to integrate container image signature verification and trust pinning into a cluster.
- [SecretScanner](https://github.com/deepfence/SecretScanner): Deepfence SecretScanner can find unprotected secrets in container images or file systems
- [grype](https://github.com/anchore/grype): A vulnerability scanner for container images and filesystems. Works with [Syft](https://github.com/anchore/syft), the powerful SBOM (software bill of materials) tool for container images and filesystems.
- [falco](https://github.com/falcosecurity/falco): Falco can detect and alert on any behavior that involves making Linux system calls. Falco alerts can be triggered by the use of specific system calls, their arguments, and by properties of the calling process.
- [kubeclarity](https://github.com/openclarity/kubeclarity): KubeClarity is a tool for detection and management of Software Bill Of Materials (SBOM) and vulnerabilities of container images and filesystems. It scans both runtime K8s clusters and CI/CD pipelines for enhanced software supply chain security.
- [Kubesec.io](https://kubesec.io/)
- [kubesec](https://github.com/shyiko/kubesec): Secure Secret management for Kubernetes (with gpg, Google Cloud KMS and AWS KMS backends)
- [Kube-hunter](https://github.com/aquasecurity/kube-hunter): Hunt for security weaknesses in Kubernetes clusters
- [Kube-bench](https://github.com/aquasecurity/kube-bench): The Kubernetes Bench for Security is a Go application that checks whether Kubernetes is deployed according to security best practices
- [Cert-manager](https://github.com/jetstack/cert-manager/): Automatically provision and manage TLS certificates in Kubernetes
- [kubescape](https://github.com/armosec/kubescape): Kubescape is a K8s open-source tool providing a multi-cloud K8s single pane of glass, including risk analysis, security compliance, RBAC visualizer and image vulnerabilities scanning.
- [syft](https://github.com/anchore/syft): A CLI tool and Go library for generating a Software Bill of Materials (SBOM) from container images and filesystems. Exceptional for vulnerability detection when used with a scanner like [Grype](https://github.com/anchore/grype).
- [trivy](https://github.com/aquasecurity/trivy): Trivy is a comprehensive security scanner. It is reliable, fast, extremely easy to use, and it works wherever you need it.
- [kubeaudit](https://github.com/Shopify/kubeaudit): kubeaudit is a tool to audit Kubernetes clusters for various different security concerns, such as: run as non-root, use a read-only root filesystem, drop scary capabilities, don't add new ones, don't run privileged and more!
- [Container Structure Tests](https://github.com/GoogleContainerTools/container-structure-test) : The Container Structure Tests provide a powerful framework to validate the structure of a container image. These tests can be used to check the output of commands in an image, as well as verify metadata and contents of the filesystem.
- [Tetragon](https://github.com/cilium/tetragon): Cilium’s new Tetragon component enables powerful realtime, eBPF-based Security Observability and Runtime Enforcement.
- [ThreatMapper](https://github.com/deepfence/ThreatMapper): Deepfence ThreatMapper hunts for threats in your production platforms, and ranks these threats based on their risk-of-exploit. It uncovers vulnerable software components, exposed secrets and deviations from good security practice. ThreatMapper uses a combination of agent-based inspection and agent-less monitoring to provide the widest possible coverage to detect threats.

## Chaos Engineering
- [kube-monkey](https://github.com/asobti/kube-monkey): An implementation of Netflix's Chaos Monkey for Kubernetes clusters

## Distributions
- [Typhoon](https://github.com/poseidon/typhoon): Minimal and free Kubernetes distribution 

## Extensions
- [kubernetes-ldap](https://github.com/apprenda-kismatic/kubernetes-ldap): ightweight Directory Access Protocol (LDAP) for Kubernetes

### GKE
- [kubernetes-rbac-synchroniser](https://github.com/google-cloud-tools/kubernetes-rbac-synchroniser): RBAC Synchroniser pulls a Google Group, extracts Google Group Member Emails and updates the Kubernetes RoleBinding in the given namespace.
