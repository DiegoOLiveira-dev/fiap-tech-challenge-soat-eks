# Learn Terraform - Provision an EKS Cluster

This repo is a companion repo to the [Provision an EKS Cluster tutorial](https://developer.hashicorp.com/terraform/tutorials/kubernetes/eks), containing
Terraform configuration files to provision an EKS cluster on AWS.


Pre requisito para funcionamento do deploy automatico: 

- Criar um bucket s3 para guardar o terraform.tfstate para ser possivel realizar o destroy automatico e tambem nao ocorrer duplicacao de provisionamento, criar via painel aws um bucket chamado terraform-state-fiap.
