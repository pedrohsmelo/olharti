# Servidor de Monitoramento e Gerenciamento de TI

## Tecnologias utilizadas:
* Ubuntu Server 22.04
* Apache 2.4.52
* Python 3.10.6
* Samba 4.15.13 (AD Linux)
* Kerberos 1.19.2
* PHP 8.1.2
* MariaDB 10.6.12 (MySql) 
* GLPI 10.0.2
* Zabbix 6.2
* Grafana 9.0.4

>Status: Em Desenvolvimento ⚠️

## Sobre o projeto:
### Implementação de um servidor de monitoramento e gerenciamento de TI de uma empresa fictícia (Olhar TI). 
### Uma empresa com 20 colaboradores e ativos de TI para suprir toda a demanda.  
### Nesse projeto utilizei um servidor local, onde o Samba4(AD) ficou responsável por fazer o controle do domínio, o GLPI por realizar o gerenciamento dos ativos de TI, o Zabbix para fazer o monitoramento do servidor e o Grafana como ferramenta de análise desse monitoramento. 

## Passo a passo de como realizar o provisionamento de um servidor como esse:

**1. Primeiramente precisamos de uma máquina para utilizar como servidor. Podemos instalar o Ubuntu server tanto em uma maquina fisica, em uma VM que está alocada em uma máquina fisica ou até uma VM em núvem.**
**2. Agora precisamos instalar o sistema operacional nesse sistema. Eu optei pelo Ubuntu Server 22.04, mas somente por preferencia pessoal.**

![Terminal]
