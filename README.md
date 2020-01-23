# Terraform + Kubernetes (AWS EKS) + Blue/Green Deployments

Simple repo to work out setting up an AWS EKS cluster with Terraform and automated blue/green deployments.

Goals:

* Provision an autoscaling EKS cluster in AWS with Terraform for a simple Node.js app
* Automate deployments based on semver tag creation using CircleCI
* Make deployments blue/green, provisioning new instances with new image running and not directing traffic to them until they are all up
* Automate rollback?
