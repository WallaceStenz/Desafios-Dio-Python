RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 12/01/2026 Empresa: Stenz Analytics E BI Responsável: Wallace Stenz de Carvalho

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Stenz Analytics E BI, realizado por Wallace Stenz de Carvalho. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: Otimização de Armazenamento
Nome da ferramenta: Amazon S3 (Simple Storage Service)

Foco da ferramenta: Armazenamento de Dados e Otimização de Custo

Descrição de caso de uso: Configuração de buckets S3 com a classe Intelligent-Tiering para mover automaticamente dados acessados com pouca frequência (logs antigos, backups frios) para camadas de armazenamento mais baratas (Infrequent Access e Archive), garantindo economia sem intervenção manual.

Etapa 2: Modelagem e Previsão (M&P)
Nome da ferramenta: Amazon SageMaker

Foco da ferramenta: Modelagem e Previsão (Machine Learning)

Descrição de caso de uso: Migração dos pipelines de treinamento de Machine Learning para o SageMaker, utilizando instâncias efêmeras (desligadas após o treinamento). Implementação de SageMaker Endpoints com auto-escalabilidade para servir modelos, garantindo que os recursos de computação só sejam cobrados durante o uso real das previsões, promovendo a otimização de custo por predição.

Etapa 3: Preparação e Consumo de Dados para BI
Nome da ferramenta: AWS Glue (Serverless ETL)

Foco da ferramenta: Preparação de Dados para Relatórios (Criação de Relatórios)

Descrição de caso de uso: Implementação de Jobs ETL Serverless no AWS Glue para limpar, transformar e consolidar os dados brutos armazenados no S3, preparando-os para o consumo pelo Power BI. Esta abordagem elimina a necessidade de manter servidores ETL 24/7 (como instâncias EC2), resultando em economia imediata ao pagar apenas pelo tempo de execução dos jobs.

Conclusão
A implementação de ferramentas na empresa Stenz Analytics E BI tem como esperado [Benefícios das ferramentas], o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.