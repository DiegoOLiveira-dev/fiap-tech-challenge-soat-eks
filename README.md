# Learn Terraform - Provision an EKS Cluster

This repo is a companion repo to the [Provision an EKS Cluster tutorial](https://developer.hashicorp.com/terraform/tutorials/kubernetes/eks), containing
Terraform configuration files to provision an EKS cluster on AWS.


Pre requisito para funcionamento do deploy automatico: 

- Criar um bucket s3 para guardar o terraform.tfstate para ser possivel realizar o destroy automatico e tambem nao ocorrer duplicacao de provisionamento, criar via painel aws um bucket chamado terraform-state-fiap.
- Para executar com seguranca oriento realizar um fork do projeto na sua conta e entao configurar as suas secrets da aws AWS_ACCESS_KEY_ID e AWS_SECRET_ACCESS_KEY para evitar custos inesperados na conta dos colegas.
- Apos as configuracoes acima, para realizar o deploy basta subir um novo merge para a main.


  teste 123

