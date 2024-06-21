# Resumo do projeto

Projeto de Infraestrutura como código, utilizando Terraform para provisionamento, Ansible para as configurações e dependências, e AWS como provedor da infraestrutura.

## 🔨 Funcionalidades do projeto

A partir deste projeto você pode:

- Criar máquinas virtuais na EC2
- Separar o seu código em dois ambientes, um de produção e outro de desenvolvimento
- Configurar as máquinas para executar uma API em Django automaticamente
- Preparar uma infraestrutura elástica
- Criar um Load Balancer para a sua aplicação

## ✔️ Técnicas e tecnologias utilizadas

Neste App são exploradas as seguintes técnicas e tecnologias:

- **Criação de máquinas na EC2**: Criação de máquinas virtuais no ambiente EC2 (Elastic Compute Cloud) da AWS.
- **Configuração das máquinas**: Configuração das máquinas de forma automática utilizando o Ansible.
- **Criação de playbooks**: Os playbooks são parte integral do Ansible e descrevem quais os passos a serem seguidos.
- **Separação de ambientes**: Dois ambientes separados, construídos de forma automática pelo Terraform, reutilizando código.
- **Execução de APIs**: Como iniciar uma API automaticamente após a configuração da máquina.
- **Criação do load balancer**: O load balancer é um programa utilizado para distribuir requisições entre múltiplas máquinas.
