# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
## Data 26/07/2023
## Empresa: AMC Industrias
## Responsável: A. Morlin

# Introdução

Esse relatório apresenta um processo de implementação de ferramentas na empresa AMC Indústrias, realizado por A. Morlin.

O objetivo do projefo foi elencar 3 serviços AWS, com a finalidade de realizar a diminuição de custos imediatos na empresa.

# Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos.
A seguir, serão descritas as etapas do projeto:

## Etapa 1:
* **Amazon EC2 - Elastic Compute Cloud**

* O AWS EC2 oferece capacidade de computação em nuvem ampla e aprofundada com mais de 600 instâncias e opções de processadores, armazenamento, redes e sistemas operacionais.

* Descrição de caso de uso: Migrar os servidores da empresa que utilizam hardware obsoleto e sem garantia para instâncias no EC2, reduzindo o custo no investimento em novos hardwares, hacks, energia, resfriamento, elasticidade e reduzindo o valor com licenciamento.

## Etapa 2:
* **Amazon RDS - Relational Database Service**

* Com o AWS RDS é possível utilizar uma coleção de serviçoes gerenciados que facilitam a configuração, operação e escalabilidade de banco de dados na nuvem. Podem ser utilizados o Aurora que é compativel com MySQL e PostgreSQL, o MySQL, MariaDB, PostgreSQL, Oracle e SQL Server.

* Descrição de caso de uso: Utilizar o AWS Migration Service (DMS)
 para descobrir, acessar, converter e migrar esquemas de origem para um banco de dados de destino no Amazon Aurora database. Deste modo, é possível reduzir custos com infraestrutura de banco de dados local utilizando tecnologia sem servidor, eliminar tarefas administrativas de banco de dados ineficientes e onerosas, além de ser possível integrar com diversos serviços da AWS.

## Etapa 3:
* **Amazon S3 - Simple Storage Service**

* O Amazon S3 fornece serviço de armazenamento de objetos com alta escalabilidade, disponibilidade, segurança e performance. Possui controles de acesso robustos, ferramentas de replicação flexíveis, visibilidade em toda a organização e é facilmente gerenciado.

* Descrição de caso de uso: Migrar todos os sites estáticos da empresa AMC Indústrias para o serviço Amazon S3, armazenando todos os arquivos do site estático como objetos dentro de um "bucket" no S3. Dessa forma é possível eliminar servidores físicos de hospedagem web, reduzindo custos com hardware, manutenção e obtendo alta escalabilidade. Dessa forma, podemos integrar os sites estáticos no bucket com serviços da AWS como API Gateway chamando funções de backend no Amazon Lamba

## Conclusão
* A implementação de ferramentas na empresa AMC Indústrias tem como esperado a redução de custos com infraestrutura computacional, elasticidade nos serviços na nuvem e a facilidade no gerenciamento utilizando serviços sem servidor, o que aumentará a eficiência e produtividade da empresa. É indispensável a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias afim de melhorar ainda mais os processos da empresa.

## Anexos:
EC2 - https://aws.amazon.com/pt/ec2/
RDS - https://aws.amazon.com/pt/rds/
DMS - https://aws.amazon.com/pt/dms/
Aurora - https://aws.amazon.com/pt/rds/aurora/
S3 - https://aws.amazon.com/pt/s3/
API Gateway - https://aws.amazon.com/pt/api-gateway/
Lamba - https://aws.amazon.com/pt/lambda/


**Responsável pelo Projeto**
***Alexandre Morlin***
