# Desafio-de-projeto-Criando-m-quinas-Virtuais-na-Azure
Desafio de Projeto: Criando Máquinas Virtuais na Azure
Objetivo
Criar uma infraestrutura de máquinas virtuais na Microsoft Azure utilizando melhores práticas de segurança, escalabilidade e gerenciamento, garantindo um ambiente otimizado para aplicações web.
Requisitos
1.	Criar duas máquinas virtuais Linux (Ubuntu Server 22.04) na Azure: 
o	VM1: Servidor Web (Nginx ou Apache)
o	VM2: Servidor de Banco de Dados (MySQL ou PostgreSQL)
2.	Criar uma Rede Virtual (VNet) para comunicação segura entre as máquinas.
3.	Configurar Grupos de Segurança de Rede (NSG) para controle de acesso.
4.	Criar e anexar Disco de Dados (Managed Disk) de 50GB para a VM do banco de dados.
5.	Criar um Load Balancer para distribuir requisições para a VM1 (servidor web).
6.	Automatizar o provisionamento com Azure CLI, PowerShell ou Terraform.
7.	Criar um alerta de monitoramento para CPU acima de 80%.
8.	Configurar Backup e Snapshot das VMs.
