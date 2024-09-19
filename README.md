# MenuGuru

Este reposit�rio cont�m os scripts de Terraform para o Cluster EKS da aplica��o [Menuguru](https://github.com/perisatto/menuguru), que implementa um sistema fict�cio de gest�o de pedidos para restaurantes como parte do trabalho de avalia��o do curso de P�s Gradua��o em Software Architecture da FIAP.

O MenuGuru tem como objetivo principal registrar e acompanhar o status de pedidos para restaurantes, onde o cliente pode realizar seu pedido e acompanhar o status do mesmo at� a retirada.

Funcionalidades:
* Cadastro e Identifica��o de Clientes
* Gest�o de Produtos (cria��o, consulta, edi��o e remo��o)
* Gest�o de Pedidos (solicita��o, consulta e finaliza��o de pedidos)
* Integra��o com Mercado Pago para processamento dos pagamentos

# Guia para execu��o do projeto

## Pr�-Requisitos

* Terraform CLI
* AWS CLI

## Execu��o

1. Execute o comando para inicializar o Terraform

``` bash
$ terraform init
```

2. Execute o comando para valida��o dos scripts

``` bash
$ terraform validate
```

3. Execute o comando para aplicar as altera��es

``` bash
$ terraform apply
```