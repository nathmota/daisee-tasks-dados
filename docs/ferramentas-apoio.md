# Possíveis Ferramentas de Apoio à Geração de Dashboards

## 1. Interação Cliente x Sistema e Geração de Consultas SQL

- ### **AI2sql**

  -  Nome Comercial: AI2sql
  -  Site: https://ai2sql.io/
  -  Tipo de licença de uso: Pago para qualquer uso. 
  -  Custo financeiro: Possui quatro categorias de planos:
      * Start: 
          + Suporta SQl, SQL, MySQL, SQL Server e PostgreSQL.
          + Gera até 100 consultas SQL por mês
          + Inclui a capacidade de adicionar até 10 tabelas
          + Ferramentas SQL
          + Gerador de Fórmula
          + Plug-in ChatGPT
          + Assistência ao esquema do diagrama ER
          + Suporte por bate-papo
      * Pro:
          + Suporta Oracle PL/SQL, NoSQL - Pandas, MongoDB, BigQuery, MariaDB, Redshift, SnowSQL
          + Limite de consultas até 300 por mês
          + Pode adicionar até 50 tabelas
          + Conectores de banco de dados
      * Business:
          + Permite até 1000 consultas por mês
          + Tabelas ilimitadas
          + Times de até 5 pessoas
      * Enterprise:
          + Acesso à API
          + Fine Tunes
          + Treinamento de modelo personalizado
          + Solução personalizada no local
  -  Qual desafio endereça: Permite gerar as querys sql atráves de linguagem natural.

- ### T5 Text-to-transfer Transformer
 
  - Nome comercial: T5 Text-to-transfer Transformer
  - Autor: Google
  - Site: [T5](https://github.com/google-research/text-to-text-transfer-transformer)
  - Tipo de Licença: Apache-2.9
  - Custo: Free
  - Tipo: modelo LLM
  - Qual desafio endereça: Um modelo da Google que pode ser ajustado para várias tarefas de NLP, incluindo a tradução de texto para SQL.
  
  - Descrição detalhada: T5 (Text-to-Text Transfer Transformer) é uma série de grandes **modelos** de linguagem desenvolvidos pela Google AI. Introduzidos em 2019,os modelos T5 são treinados em um enorme conjunto de dados de texto e código usando uma estrutura de texto para texto. Os modelos T5 são capazes de realizar as tarefas baseadas em texto para as quais foram pré-treinados. Eles também podem ser ajustados para executar outras tarefas. Eles têm sido empregados em diversas aplicações, incluindo chatbots, sistemas de tradução automática, ferramentas de resumo de texto, geração de código e robótica.

- ### Google Cloud Natural Language API
 
  - Nome comercial: Google Cloud Natural Language API
  - Autor: Google
  - Site: [Google API](https://cloud.google.com/natural-language)
  - Tipo:  Sistemas Pré-construídos
  - Tipo de Licença: Google Cloud Platform (GCP)
  - Custo: Pago. Diferentes formas de [precificação](https://cloud.google.com/natural-language/pricing).
  - Qual desafio endereça: Oferece várias funcionalidades de NLP e pode ser usada para entender e processar linguagem natural, embora a tradução direta para SQL possa requerer ajustes adicionais.
  
  - Descrição detalhada: O Google Cloud Natural Language API oferece uma variedade de recursos poderosos para análise de texto. Alguns dos principais recursos incluem: Análise de Sentimento, Extração de Entidades, Classificação de texto, Análise de sintaxe.
 
- ### Seq2SQL
  - Nome comercial: Seq2SQL
  - Site: [Seq2SQL](https://arxiv.org/abs/1709.00103)
  - Tipo de Licença: --
  - Custo: --
  - Tipo: Framework
  - Qual desafio endereça: Geração de consultas estruturadas a partir de linguagem natural usando aprendizado por reforço
  
  - Descrição detalhada: Uma rede neural profunda para traduzir questões de linguagem natural em consultas SQL correspondentes. Nosso modelo aproveita a estrutura das consultas SQL para reduzir significativamente o espaço de saída das consultas geradas. Além disso, usamos recompensas da execução de consultas in-the-loop no banco de dados para aprender uma política para gerar partes não ordenadas da consulta, que mostramos serem menos adequadas para otimização via perda de entropia cruzada. Além disso, publicaremos o WikiSQL, um conjunto de dados de 80.654 exemplos de perguntas e consultas SQL anotados à mão, distribuídos em 24.241 tabelas da Wikipedia. Este conjunto de dados é necessário para treinar nosso modelo e é uma ordem de magnitude maior do que conjuntos de dados comparáveis. Ao aplicar o aprendizado por reforço baseado em políticas com um ambiente de execução de consultas ao WikiSQL, nosso modelo Seq2SQL supera os modelos de atenção para sequência, melhorando a precisão da execução de 35,9% para 59,4% e a precisão da forma lógica de 23,4% para 48,3%.

## 2. Geração da representação intermediária dos dados em formato visual

- ### **Plotly**
  -  Nome Comercial: Plotly
  -  Site: [Plotly](https://plotly.com/)
  -  Tipo de licença de uso: Open-source para uso básico, com planos comerciais para recursos avançados.
 -  Custo financeiro: Planos gratuitos disponíveis; planos comerciais variam dependendo dos recursos e suporte necessários, mas um básico seria em torno de $59/mês.
 -  Qual desafio endereça: Permite a criação de gráficos e visualizações interativas que podem ser usadas como representação intermediária de dados, facilitando a geração de Dashboards visuais, ele também tem uma nova opção de gerar gráficos automáticos usando alguma LLM (Não é informado qual) a partir dos dados fornecidos.

## 3. O framework de geração das visualizações

- ### **Apache Superset**
 
  - **Nome Comercial:** Apache Superset
  - **Site:** [Apache Superset](https://superset.apache.org/)
  - **Tipo de licença de uso:** Gratuito (Open Source)
  - **Custo financeiro:** Gratuito
  - **Qual desafio endereça:** Plataforma de visualização de dados open-source que permite criar, explorar e compartilhar dashboards interativos de maneira eficiente e escalável.
  
  **Descrição Detalhada:**
  
  Apache Superset é uma solução robusta e gratuita para visualização de dados, desenvolvida pela Airbnb e agora um projeto incubado pela Apache Software Foundation. Ele oferece uma interface gráfica intuitiva, que facilita a criação de dashboards sofisticados, mesmo para usuários sem muita experiência técnica.


