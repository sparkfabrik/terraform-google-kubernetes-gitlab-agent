# Gitlab Agent on Kubernetes

This module installs using the corresponding Helm chart the Gitlab Agent on a 
Kubernetes cluster.

The token for registering the agent is supposed to be passed to the module via a 
secret stored on Secret Manager on Google Cloud Platform.

The token is then stored on a secret on Kubernetes and read from it.

<!-- BEGIN_TF_DOCS -->
<!-- END_TF_DOCS -->
