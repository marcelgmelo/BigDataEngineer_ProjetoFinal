# BigDataEngineer_ProjetoFinal
Projeto final de spark sobre a campanha de vacinação contra o covid-19
## Nível Básico:
Dados: https://mobileapps.saude.gov.br/esus-vepi/files/unAFkcaNDeXajurGB7LChj8SgQYS2ptm/04bd3419b22b9cc5c6efac2c6528100d_HIST_PAINEL_COVIDBR_06jul2021.rar
Referência das Visualizações:
• Site: https://covid.saude.gov.br/
• Guia do Site: Painel Geral
1. Enviar os dados para o hdfs
2. Otimizar todos os dados do hdfs para uma tabela Hive particionada por município.
3. Criar as 3 vizualizações pelo Spark com os dados enviados para o HDFS:
4. Salvar a primeira visualização como tabela Hive
5. Salvar a segunda visualização com formato parquet e compressão snappy
6. Salvar a terceira visualização em um tópico no Kafka
7. Criar a visualização pelo Spark com os dados enviados para o HDFS:
8. Salvar a visualização do exercício 6 em um tópico no Elastic
9. Criar um dashboard no Elastic para visualização dos novos dados enviados

## Nível Avançado:
Replicar as visualizações do site “https://covid.saude.gov.br/”, porém acessando diretamente a API de Elastic.
Link oficial para todas as informações: https://opendatasus.saude.gov.br/dataset/covid-19-vacinacao
Informações para se conectar ao cluster: 
• URL https://imunizacao-es.saude.gov.br/desc-imunizacao 
• Nome do índice: desc-imunizacao 
• Credenciais de acesso
o Usuário: imunizacao_public 
o Senha: qlto5t&7r_@+#Tlstigi
Links utéis para a resolução do problema:
• Consumo do API:
https://opendatasus.saude.gov.br/dataset/b772ee55-07cd-44d8-958f-b12edd004e0b/resource/5916b3a4-81e7-4ad5-adb6-b884ff198dc1/download/manual_api_vacina_covid-19.pdf
• Conexão do Spark com Elastic:
https://www.elastic.co/guide/en/elasticsearch/hadoop/current/spark.html
https://docs.databricks.com/data/data-sources/elasticsearch.html#elasticsearch-notebook
https://github.com/elastic/elasticsearch-hadoop
https://www.elastic.co/guide/en/elasticsearch/hadoop/current/configuration.html
• Instalar Dependências:
https://www.elastic.co/guide/en/elasticsearch/hadoop/current/install.html
