# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 28/05/2023
Empresa: Abstergo Industries 
Responsável: Roger Felipe Pereira

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries , realizado por Roger Felipe Pereira. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon EC2 Spot Instances
- Objetivos:
  - Redução significativa nos custos de computação, pois as Spot Instances podem ser até 90% mais baratas do que as instâncias sob demanda.
  - Maior eficiência no uso dos recursos, aproveitando a capacidade não utilizada da AWS.
- O serviço Amazon EC2 (Elastic Compute Cloud) oferece instâncias de computação escaláveis na nuvem. As Spot Instances são uma opção econômica que permite aproveitar a capacidade de computação não utilizada da AWS a preços significativamente reduzidos em comparação com as instâncias sob demanda ou reservadas. Ao utilizar as Spot Instances, o pode obter uma economia considerável nos custos de computação, desde que esteja disposta a lidar com a possibilidade de interrupções quando a capacidade excedente não estiver mais disponível.

Etapa 2: 
- Amazon S3 Intelligent-Tiering
- Objetivos:
  - Redução dos custos de armazenamento, uma vez que os dados menos acessados são movidos para classes de armazenamento mais baratas.
  - Automatização do processo de movimentação de dados, eliminando a necessidade de intervenção manual para otimizar o armazenamento.
- O Amazon S3 (Simple Storage Service) é um serviço de armazenamento altamente escalável e durável na nuvem. O recurso Intelligent-Tiering é uma maneira eficiente de reduzir os custos de armazenamento ao automatizar a movimentação dos dados entre diferentes classes de armazenamento com base em seu padrão de acesso. Os dados menos acessados são movidos para as classes de armazenamento mais baratas, enquanto os dados frequentemente acessados permanecem nas classes de armazenamento mais rápidas e caras.

Etapa 3: 
- Amazon RDS
- Objetivos:
  - Redução nos custos de infraestrutura, ajustando a capacidade do banco de dados de acordo com a demanda.
  - Otimização de custos por meio de opções de instâncias reservadas e a capacidade de "parar e iniciar" o banco de dados quando não estiver em uso.
  - Simplificação da administração do banco de dados, permitindo que a equipe de TI se concentre em atividades mais estratégicas.
- O Amazon RDS é um serviço gerenciado de banco de dados relacional oferecido pela AWS. Ele suporta vários mecanismos de banco de dados, como MySQL, PostgreSQL, Oracle, SQL Server e outros. Através da implantação desse serviço iremos obter economia de custos, manutenção simplificada e escalabilidade do serviço para atender a demanda da empresa.


## Conclusão
A implementação de ferramentas na empresa *[nome da empresa] tem como esperado [benefícios das ferramentas]*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

RDS - https://aws.amazon.com/pt/rds/
EC2 - https://aws.amazon.com/pt/ec2/
S3 - https://aws.amazon.com/pt/s3/


Autor: Roger Felipe Pereira