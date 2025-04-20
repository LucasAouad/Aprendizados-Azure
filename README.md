# Aprendizados-Azure
Aprendizados criação de banco de dados Azure
Durante os estudos sobre computação em nuvem, tive a oportunidade de realizar a configuração de uma instância de banco de dados utilizando a plataforma Microsoft Azure. Abaixo, compartilho os principais aprendizados adquiridos durante esse processo:

1. Escolha do tipo de banco de dados
Um dos primeiros passos foi identificar o tipo de banco de dados mais adequado para a aplicação. O Azure oferece diversas opções, como:

Azure SQL Database (relacional)

Azure Database for MySQL/PostgreSQL

Cosmos DB (NoSQL)

Entendi que essa escolha deve estar alinhada às necessidades específicas do projeto, especialmente em relação à estrutura dos dados e ao tipo de aplicação utilizada.

2. Seleção da camada de preço
Outro aspecto importante foi a definição da camada de serviço. Optei por uma configuração básica, considerando que o objetivo era aprendizado. No entanto, percebi que o Azure permite escalar verticalmente de forma flexível, ajustando o desempenho conforme a demanda.

3. Organização por grupo de recursos
Criei um Resource Group específico para o banco de dados, prática recomendada para manter os recursos organizados, facilitando o gerenciamento e controle de custos dentro da plataforma.

4. Definição da região
Configurei a instância em uma região próxima ao local de uso, pois aprendi que isso influencia diretamente na latência e desempenho da aplicação.

5. Backup e retenção
Durante a criação, ativei o backup automático, com retenção padrão de 7 dias. Essa configuração garante maior segurança dos dados, permitindo recuperação em caso de falhas.

6. Regras de firewall e segurança
Foi necessário configurar regras de firewall para permitir o acesso à instância apenas a partir do meu endereço IP. Isso garante maior controle de segurança. Também entendi a importância de não utilizar a conta administrativa para acessos regulares em ambientes de produção.

7. Monitoramento e alertas
Ativei o Azure Monitor para acompanhar o desempenho da instância, observando métricas como uso de CPU e conexões. Essa etapa é essencial para garantir a estabilidade e o bom funcionamento do banco.

8. Teste de conexão
Por fim, utilizei o Azure Data Studio para testar a conexão com o banco, utilizando a string de conexão gerada pela plataforma. A conexão foi bem-sucedida, comprovando que a instância estava devidamente configurada.

Conclusão
A atividade permitiu compreender, na prática, os principais passos para a configuração de um banco de dados em ambiente cloud. Ressalto a importância da atenção aos detalhes durante o processo, especialmente em relação à segurança, organização e monitoramento do serviço. A experiência foi enriquecedora e contribuiu significativamente para meu entendimento sobre infraestrutura em nuvem.
