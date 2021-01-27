# cicd-automation
Description of Code / PoC for CI/CD automation


<b>Deploy containers on k8s cluster (eks/gcp)</b>

With IaC a k8s cluster is built on EKS (Amazon)/GKE (Google Cloud) + apps are deployed to this cluster

There are multiple ways to do this:

```bash
1. K8s deployment via Gitlab CI/CD with Terraform (PoC passed)
2. K8s deployment via Github Actions CI/CD with Terraform (PoC preparing)</i>
3. K8s deployment via Jenkins CI/CD with Terraform (PoC preparing)</i>
```
-----------------

<t>1. K8s deployment via Gitlab CI/CD with Terraform (PoC passed)

The code for this K8s deployment via CI/CD is here (private repos):

https://gitlab.com/a_achter/poc-deploy-eks-cluster-using-terraform
