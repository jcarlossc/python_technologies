# 🐍 Tecnologias Python

## 1. Desenvolvimento regular — dependências de produção

### 1.1. Linguagens, processamento e manipulação de dados

| Tecnologia | Descrição |
| ---------- | --------- |
| Python | Linguagem principal para construir pipelines, ETLs, integrações e aplicações de dados. |
| pandas | Manipulação, limpeza, transformação e análise de dados tabulares. |
| NumPy | Computação numérica e operações com arrays. |
| Polars | Processamento tabular de alta performance. |
| PyArrow | Integração com Apache Arrow e leitura/escrita de formatos colunares. |
| Dask | Computação paralela e distribuída em Python. |
| DuckDB | Banco analítico embutido, útil para consultas SQL sobre arquivos. |
| PySpark | API Python do Apache Spark para processamento distribuído. |
| Ibis | API Python para expressar operações analíticas em diferentes mecanismos de execução. |
| Vaex | Exploração de grandes conjuntos de dados tabulares com uso eficiente de memória. |
| Numba | Compilação de determinadas funções numéricas Python para acelerar cálculos. |

### 1.2. Conexão com bancos de dados

| Tecnologia | Descrição |
| ---------- | --------- |
| SQLAlchemy | ORM e camada de acesso a bancos de dados SQL. |
| psycopg | Driver Python para PostgreSQL. |
| PyMySQL | Driver Python para MySQL. |
| mysql-connector-python | Driver oficial da Oracle para MySQL. |
| pyodbc | Conexão com bancos e fontes que disponibilizam drivers ODBC. |
| oracledb | Driver Python para Oracle Database. |
| pymssql | Conexão Python com Microsoft SQL Server. |
| SQLite / sqlite3 | Banco relacional embutido e módulo de conexão incluído no Python. |
| asyncpg | Driver assíncrono para PostgreSQL. |
| aiomysql | Conexão assíncrona com MySQL. |
| SQLModel | Modelos e acesso a dados baseados em Pydantic e SQLAlchemy. |
| ConnectorX | Leitura de dados de bancos relacionais para estruturas tabulares. |

### 1.3. APIs e ingestão de dados

| Tecnologia | Descrição |
| ---------- | --------- |
| requests | Requisições HTTP síncronas para consumir APIs. |
| httpx | Cliente HTTP síncrono e assíncrono. |
| aiohttp | Comunicação HTTP assíncrona. |
| FastAPI | Criação de APIs para disponibilizar dados e serviços. |
| Pydantic | Validação e tipagem de dados de entrada e saída. |
| pydantic-settings | Configuração de aplicações a partir de variáveis de ambiente e arquivos de configuração compatíveis. |
| urllib3 | Cliente HTTP de baixo nível e gerenciamento de conexões. |
| tenacity | Políticas de repetição de operações que falharam, com espera configurável. |
| backoff | Repetição de operações com estratégias de espera. |
| python-multipart | Tratamento de uploads multipart em aplicações web. |
| Beautiful Soup | Extração de informações de documentos HTML. |
| Scrapy | Framework para coleta automatizada de dados na web. |
| Selenium | Automação de navegadores para páginas dinâmicas. |
| Playwright | Automação de navegadores e testes de aplicações web. |

### 1.4. Arquivos, formatos e serialização

| Tecnologia | Descrição |
| ---------- | --------- |
| PyYAML | Leitura e escrita de arquivos YAML. |
| types-PyYAML | Tipagens para melhorar a análise estática de código que utiliza PyYAML; normalmente é dependência de desenvolvimento. |
| openpyxl | Leitura e escrita de arquivos Excel .xlsx. |
| XlsxWriter | Criação de arquivos Excel com formatação. |
| python-calamine | Leitura de diferentes formatos de planilhas, incluindo Excel. |
| fastparquet | Leitura e escrita de arquivos Parquet. |
| orjson | Serialização e desserialização JSON de alto desempenho. |
| msgpack | Serialização binária compacta. |
| avro | Suporte ao formato de dados Apache Avro. |
| fastavro | Leitura e escrita eficiente de Avro. |
| python-snappy | Compressão Snappy. |
| zstandard | Compressão Zstandard. |
| chardet | Detecção provável da codificação de caracteres de arquivos. |
| charset-normalizer | Identificação de codificações de texto. |
| fsspec | Interface comum para acessar diferentes sistemas de arquivos e armazenamentos. |
| s3fs | Acesso a arquivos do Amazon S3 por meio de uma interface de sistema de arquivos. |
| adlfs | Acesso a armazenamento Azure Data Lake e Blob Storage. |
| gcsfs | Acesso ao Google Cloud Storage por meio de uma interface de sistema de arquivos. |
| smart-open | Leitura e escrita de arquivos locais e remotos, conforme os protocolos suportados. |

### 1.5. Orquestração de pipelines

| Tecnologia | Descrição |
| ---------- | --------- |
| Apache Airflow | Agenda, orquestra e monitora workflows de dados representados por DAGs.
| Prefect | Orquestração de workflows Python.
| Dagster | Orquestração com foco em ativos de dados, dependências e observabilidade.
| Luigi | Construção de pipelines com tarefas e dependências.
| Kedro | Estrutura projetos de dados em pipelines, nós e catálogos.
| Apache DolphinScheduler | Plataforma de orquestração de workflows.
| Flyte | Orquestração de workflows de dados e machine learning.
| Temporal | Execução confiável de workflows duráveis, inclusive em integrações de dados.
| dbt Core | Transformações SQL, organização de modelos e testes de dados.
| Meltano | Plataforma extensível para ELT e integração de dados.

> Algumas ferramentas de orquestração exigem serviços próprios, como banco de metadados, scheduler, workers ou servidor. Instalar o pacote Python, sozinho, pode não ser suficiente para ter uma instalação operacional.

### 1.6. Streaming, mensageria e processamento em tempo real

| Tecnologia | Descrição |
| ---------- | --------- |
| confluent-kafka | Cliente Python de alto desempenho para Kafka, baseado na biblioteca librdkafka. |
| aiokafka | Cliente assíncrono para Apache Kafka. |
| pyspark | Também permite processamento estruturado de streams com Spark Structured Streaming. |
| faust-streaming | Framework Python para processamento de streams com Kafka, mantido pela comunidade. |
| pika | Cliente Python para RabbitMQ. |
| aio-pika | Cliente assíncrono para RabbitMQ. |
| redis | Cliente Python para Redis, incluindo recursos de mensageria e streams. |
| boto3	SDK | AWS para interagir com serviços como S3, SQS e Kinesis. |
| google-cloud-pubsub | Integração Python com Google Cloud Pub/Sub. |
| azure-servicebus | Integração Python com Azure Service Bus. |
| azure-eventhub | Integração Python com Azure Event Hubs. |
| apache-flink | Integração Python com Apache Flink por meio do PyFlink. |

### 1.7. Cloud e armazenamento

| Tecnologia | Descrição |
| ---------- | --------- |
| boto3 | SDK para serviços AWS. |
| s3fs | Acesso ao Amazon S3. |
| awswrangler (aws-sdk-pandas) | Integração entre Pandas e serviços analíticos da AWS. |
| google-cloud-storage | Acesso a buckets do Google Cloud Storage. |
| google-cloud-bigquery | Consultas e operações no BigQuery. |
| google-cloud-bigquery-storage | Transferência de dados entre BigQuery e aplicações. |
| google-cloud-pubsub | Publicação e consumo de mensagens no Google Cloud. |
| azure-storage-blob | Acesso ao Azure Blob Storage. |
| azure-identity | Autenticação com serviços Azure. |
| azure-keyvault-secrets | Acesso a segredos armazenados no Azure Key Vault. |
| databricks-sdk | Integração com recursos da plataforma Databricks. |
| snowflake-connector-python | Conexão Python com Snowflake. |
| snowflake-snowpark-python | Processamento de dados no ambiente Snowflake com Python. |
| redshift-connector | Conexão com Amazon Redshift. |
| delta-spark | Integração do Delta Lake com Apache Spark. |
| pyiceberg | Acesso e gerenciamento de tabelas Apache Iceberg. |

### 1.8. Transformação, qualidade e validação de dados

| Tecnologia | Descrição |
| ---------- | --------- |
| Great Expectations | Define e executa expectativas para validar a qualidade dos dados. |
| Soda Core | Executa verificações de qualidade e métricas em dados. |
| Pandera | Valida schemas e regras de DataFrames, especialmente com Pandas e outras integrações. |
| Frictionless | Valida estruturas e recursos tabulares, como arquivos CSV. |
| dbt tests | Testes de modelos SQL e integridade dos dados no dbt. |
| Deequ | Biblioteca de verificação de qualidade de dados construída para o ecossistema Spark, originalmente em Scala. |
| PyDeequ | Interface Python para utilizar recursos do Deequ em ambientes Spark compatíveis. |
| pointblank | Validação de dados tabulares com regras e relatórios. |
| Pydantic | Valida estruturas de dados Python, objetos e registros de entrada. |
| jsonschema | Valida documentos JSON de acordo com schemas. |
| cerberus | Validação de estruturas de dados com regras configuráveis. |
| voluptuous | Validação de dados por meio de schemas Python. |

### 1.9. Logging, monitoramento e observabilidade

| Tecnologia | Descrição |
| ---------- | --------- |
| logging | Módulo padrão do Python para registrar eventos, erros e avisos. |
| structlog | Logging estruturado para aplicações Python. |
| loguru | Biblioteca alternativa para logging simplificado. |
| rich | Saídas formatadas no terminal, tabelas, progresso e mensagens legíveis. |
| prometheus-client | Exposição de métricas para Prometheus. |
| opentelemetry-api | API de instrumentação para rastreamento e métricas. |
| opentelemetry-sdk | Implementação dos recursos de instrumentação OpenTelemetry. |
| sentry-sdk | Captura e envio de erros e exceções para Sentry. |
| evidently | Monitoramento e análise de qualidade, distribuição e comportamento de dados, incluindo aplicações de ML. |
| whylogs | Geração de perfis e estatísticas de dados para monitoramento. |
| openlineage-python | Instrumentação e integração com o padrão OpenLineage para linhagem de dados. |
| datahub (acryl-datahub) | Cliente e ferramentas Python para integrar metadados ao catálogo DataHub. |
| monte-carlo | O nome Monte Carlo se refere principalmente a uma plataforma comercial de observabilidade; a integração Python depende do produto, SDK ou API disponível. |

### 1.10. Segurança e gerenciamento de credenciais

| Tecnologia | Descrição |
| ---------- | --------- |
| python-dotenv | Carrega variáveis de ambiente de um arquivo .env. |
| keyring | Integração com armazenamentos de credenciais do sistema operacional. |
| cryptography | Primitivas criptográficas e recursos de segurança. |
| PyJWT | Criação e validação de JSON Web Tokens. |
| Authlib | Implementação de recursos de autenticação e OAuth. |
| hvac | Cliente Python para HashiCorp Vault. |
| detect-secrets | Detecta possíveis segredos expostos em arquivos. |
| bandit | Identifica problemas de segurança comuns no código Python. |
| pip-audit | Verifica vulnerabilidades conhecidas nas dependências Python. |

### 1.11. Configuração, modelos e utilitários

| Tecnologia | Descrição |
| ---------- | --------- |
| pydantic-settings | Gerenciamento tipado de configurações. |
| dynaconf | Configuração de aplicações com suporte a diferentes ambientes. |
| omegaconf | Configuração hierárquica e composição de arquivos. |
| Hydra | Gerenciamento de configurações e execução de aplicações com múltiplos cenários. |
| python-dateutil | Operações avançadas com datas e intervalos. |
| pendulum | Tratamento de datas, fusos horários e intervalos; também usado pelo Airflow. |
| croniter | Interpretação e cálculo de ocorrências de expressões cron. |
| click | Criação de interfaces de linha de comando. |
| typer | Criação de CLIs com base em type hints. |
| fire | Geração automática de interfaces de linha de comando para funções e objetos Python. |
| Jinja2 | Templates de texto, SQL e configurações. |
| packaging	| Manipulação de versões, requisitos e metadados de pacotes. |
| importlib-metadata | Consulta de metadados de pacotes; útil em versões do Python que precisam do backport. |

## 2. Desenvolvimento — grupo dev

