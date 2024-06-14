# Resumo do projeto

Segundo projeto de Infraestrutura como código, utilizando Terraform para provisionamento, Ansible para as configurações e dependências, e AWS como provedor da infraestrutura.

## 🔨 Funcionalidades do projeto

A partir desse projeto você pode:

- Criar maquinas virtuais na EC2
- Separar o seu codigo em 2 ambientes, um de produção e um de desenvolvimento
- configurar as maquinas para executar uma API em Django automaticamente
- preparar uma infraestrutura elastica
- criar um Load Balancer para a sua aplicação

## ✔️ Técnicas e tecnologias utilizadas

Neste App são exploradas as seguintes técnicas e tecnologias:

- **Criação de maquinas na EC2**: criação de maquinas virtuias no ambiente EC2 (Elastic Compute Cloud) da AWS
- **Configuração das maquinas**: configura as maquians de forma automatica ultilizando o Ansible
- **Criação de playbooks**: os playbooks são parte integral do ansible e descrevem quais os passos a serem seguidos
- **Separação de ambientes**: 2 ambientes separados, construidos de forma automatica pelo Terraform, reultilizando codigo.
- **Execução de APIs**: como iniciar um API automaticamente apos a configuração da maquina
- **Criação do load balancer**: o load balancer é um programa ultilziado para distribuir requisições entre multiplas maquinas