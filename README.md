
![Terraform - S3 Bucket](https://github.com/Lopeswaprojetos/aws-s3-terraform/assets/161225187/c79a49d6-4d62-432b-aa07-65a8613cbd50)

## Estrutura do Projeto AWS S3 Terraform ##

Este repositório contém um exemplo simples de como usar o Terraform para provisionar um bucket no Amazon S3.

##Arquivos Principais##
main.tf: Este arquivo contém a configuração principal do Terraform. Nele, especificamos o provedor AWS que será usado e definimos o recurso do bucket S3 que queremos criar. Também incluímos tags para identificar informações importantes sobre o bucket.

##Descrição dos Arquivos##
terraform.tf: Este arquivo é usado pelo Terraform para armazenar o estado da infraestrutura provisionada. Ele contém informações sobre os recursos criados e sua configuração atual.

##Como Usar##
Para usar este projeto, siga as etapas abaixo:

1 Certifique-se de ter o Terraform instalado em sua máquina.
2 Clone este repositório para sua máquina local.
3 Execute terraform init para inicializar o diretório do projeto.
4 Execute terraform plan para visualizar as alterações que serão feitas na infraestrutura.
5 Execute terraform apply para aplicar as alterações e criar o bucket S3.
6 Verifique o bucket criado na AWS Console ou usando a CLI da AWS.
