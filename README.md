# awesome-devops
List of all the awesome tools for devops.

* [Kubernetes](#kubernetes)

# Kuberenetes
##### Security
[Kube-linter](https://github.com/stackrox/kube-linter) - KubeLinter analyzes Kubernetes YAML files and Helm charts, and checks them against a variety of best practices, with a focus on production readiness and security.
[Kube-Scape](https://github.com/kubescape/kubescape) - An open-source Kubernetes security platform for your clusters, CI/CD pipelines, and IDE that seperates out the security signal from the scanner noise.
[Popeye](https://popeyecli.io/) - Popeye is a utility that scans live Kubernetes clusters and reports potential issues with deployed resources and configurations.
[k8sgpt](https://k8sgpt.ai/) - K8sGPT is a tool for scanning your kubernetes clusters, diagnosing and triaging issues in simple english. It has SRE experience codified into its analyzers and helps to pull out the most relevant information to enrich it with AI.


##### Provisioning
[k3d](https://k3d.io/v5.7.1/) - k3d makes it very easy to create single- and multi-node k3s clusters in docker, e.g. for local development on Kubernetes.
[Mirrod](https://mirrord.dev/) - mirrord solves the problems every modern cloud developer faces during microservice development by making remote services feel local.

##### Monitoring
[Kubecost](https://www.kubecost.com/) - Monitor & reduce Kubernetes spend
[Kubeshark](https://www.kubeshark.co/) - Real-time Kubernetes protocol-level visibility, capturing and monitoring all traffic going in, out and across containers, pods, namespaces, nodes and clusters.
[kubectl-tree](https://ahmet.im/blog/kubectl-tree/) - This plugin shows you which Kubernetes objects are owned by which ones.
[cilium](https://cilium.io/) - Cilium is an open source, cloud native solution for providing, securing, and observing network connectivity between workloads, fueled by the revolutionary Kernel technology eBPF.

##### Management
[K9s](https://k9scli.io/)  - K9s is a terminal based UI to interact with your Kubernetes clusters
[kdash](https://github.com/kdash-rs/kdash) - A simple terminal dashboard for Kubernetes built with Rust

##### Deployment
[Helmfile](https://helmfile.readthedocs.io/en/latest/) - Helmfile is a declarative spec for deploying helm charts for Kubernetes clusters.
[Flux](https://fluxcd.io/) - Flux is a set of continuous and progressive delivery solutions for Kubernetes that are open and extensible.
[kaniko](https://github.com/GoogleContainerTools/kaniko) - kaniko is a tool to build container images from a Dockerfile, inside a container or Kubernetes cluster.
[werf](https://werf.io/) - werf follows the principles of the IaC (Infrastructure as Code) approach and encourages the user to store the project delivery configuration along with the application code in Git and to use external dependencies responsibly.
[kluctl](https://kluctl.io/) - Easily handle Kubernetes deployments of any size, complexity, and across various environments using Kluctl.
[kubeflow](https://www.kubeflow.org/) - The Kubeflow project is dedicated to making deployments of machine learning (ML) workflows on Kubernetes simple, portable and scalable.


##### Testing
[KUTTL](https://kuttl.dev/) - The KUbernetes Test TooL (KUTTL) is a toolkit that makes it easy to test Kubernetes Operators (opens new window), just using YAML.

