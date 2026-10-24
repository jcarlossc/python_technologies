# 🐍 Tecnologias Python para Engenharia de dados

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

> Estas ferramentas são utilizadas durante a implementação, testes, revisão e manutenção do código. Em um projeto Poetry, podem ser declaradas no grupo dev para não serem instaladas como dependências regulares quando esse grupo for excluído.

### 2.1. Testes

| Tecnologia | Descrição |
| ---------- | --------- |
| pytest | Framework principal para escrever e executar testes automatizados. |
| pytest-cov | Mede a cobertura dos testes por meio do Coverage.py. |
| coverage | Calcula e gera relatórios de cobertura de código. |
| pytest-mock | Integra mocks ao pytest. |
| unittest.mock | Ferramenta de simulação incluída na biblioteca padrão do Python. |
| responses | Simula requisições HTTP feitas com requests. |
| requests-mock	Simula | respostas HTTP para testes de código que usa requests. |
| respx | Simula requisições feitas com HTTPX. |
| freezegun | Congela ou controla datas e horários durante os testes. |
| time-machine | Controla o tempo em testes automatizados. |
| factory-boy | Gera objetos de teste por meio de factories. |
| Faker | Gera dados fictícios para testes e desenvolvimento. |
| Hypothesis | Testes baseados em propriedades, gerando muitos casos de entrada automaticamente. |
| testcontainers | Cria dependências de teste em containers, como bancos de dados, quando Docker e os recursos necessários estão disponíveis. |
| pytest-xdist | Executa testes em paralelo. |
| pytest-randomly | Altera a ordem dos testes para ajudar a revelar dependências ocultas. |
| pytest-timeout | Impõe limites de tempo aos testes. |
| schemathesis | Testa APIs automaticamente a partir de seus schemas. |
| moto | Simula vários serviços AWS para testes. |
| vcrpy | Grava e reproduz interações HTTP em testes. |

### 2.2. Formatação, lint e qualidade do código

| Tecnologia | Descrição |
| ---------- | --------- |
| Ruff | Linter e formatador Python de alto desempenho; pode substituir várias ferramentas tradicionais. |
| Black | Formata código Python de maneira consistente. |
| isort | Organiza imports. |
| Flake8 | Analisa estilo e possíveis problemas no código. |
| Pylint | Analisa erros, convenções e qualidade do código. |
| autopep8 | Ajusta a formatação para seguir o PEP 8. |
| pycodestyle | Verifica aspectos de estilo PEP 8. |
| pyflakes | Detecta erros comuns, como imports e variáveis não utilizados. |
| mccabe | Avalia complexidade ciclomática. |
| eradicate | Detecta código comentado que pode ser desnecessário. |
| refurb | Sugere melhorias e expressões mais idiomáticas em Python. |
| vulture | Procura código potencialmente não utilizado.
| codespell | Detecta erros de grafia em código e documentação. |

### 2.3. Tipagem estática e análise

| Tecnologia | Descrição |
| ---------- | --------- |
| mypy | Verifica tipos estáticos em Python. |
| Pyright | Análise estática e verificação de tipos. |
| basedpyright | Variante do Pyright com verificações adicionais. |
| Pyre | Verificador de tipos estáticos para Python. |
| MonkeyType | Ajuda a inferir anotações de tipo com base na execução. |
| stubgen | Gera stubs de tipagem para módulos Python, disponível no ecossistema mypy. |
| types-requests | Tipagens para requests. |
| types-PyYAML | Tipagens para PyYAML. |
| pandas-stubs | Tipagens para melhorar a análise estática de código que utiliza Pandas. |
| types-python-dateutil | Tipagens para python-dateutil. |

### 2.4. Debug e desenvolvimento interativo

| Tecnologia | Descrição |
| ---------- | --------- |
| python | Terminal Python interativo aprimorado. |
| ipykernel | Kernel Python para notebooks. |
| jupyterlab | Ambiente interativo para exploração e experimentação de dados. |
| notebook | Ambiente Jupyter Notebook clássico. |
| debugpy | Depuração de Python por IDEs e editores. |
| pdb | Depurador incluído na biblioteca padrão do Python. |
| icecream | Ajuda a inspecionar valores durante a depuração. |
| memray | Analisa alocações de memória em aplicações Python. |
| py-spy | Profiler para investigar o desempenho de programas Python. |
| scalene | Profiler de CPU e memória para Python. |
| line-profiler | Mede o tempo gasto em linhas de funções selecionadas. |

### 2.5. Pré-commit, automação e hooks

| Tecnologia | Descrição |
| ---------- | --------- |
| pre-commit | Executa verificações automáticas antes de commits. |
| pre-commit-hooks | Hooks prontos para detectar problemas como espaços indevidos e arquivos não finalizados corretamente. |
| commitizen | Ajuda a padronizar mensagens de commit e versões. |
| Commitlint | Valida mensagens de commit de acordo com regras configuradas. |
| detect-secrets | Pode ser executado em hooks para evitar a inclusão de credenciais. |
| nbstripout | Remove saídas de notebooks antes de armazená-los no Git, quando configurado. |

### 2.6. Documentação

| Tecnologia | Descrição |
| ---------- | --------- |
| Sphinx | Gera documentação técnica a partir de arquivos e docstrings. |
| MkDocs | Gera sites de documentação a partir de Markdown. |
| Material for MkDocs | Tema e recursos para documentação com MkDocs. |
| pdoc | Gera documentação de APIs Python. |
| mkdocstrings | Integra documentação de código ao MkDocs. |
| sphinx-rtd-theme | Tema para documentação Sphinx. |
| interrogate | Verifica a cobertura de docstrings. |
| docformatter | Formata docstrings Python. |
| myst-parser | Permite usar Markdown na documentação Sphinx. |
| towncrier | Monta changelogs a partir de fragmentos de alterações. |

### 2.7. Build, publicação e versionamento de pacotes

| Tecnologia | Descrição |
| ---------- | --------- |
| Poetry | Gerencia dependências, ambientes e empacotamento Python. |
| build | Constrói distribuições Python, como wheel e sdist. |
| twine | Valida e publica distribuições em repositórios como PyPI. |
| setuptools | Ferramenta de build e empacotamento Python. |
| wheel | Suporte ao formato de distribuição wheel. |
| hatch | Ferramenta de build e gerenciamento de ambientes. |
| hatchling | Backend de build do ecossistema Hatch. |
| Flit | Ferramenta de empacotamento Python. |
| PDM | Gerenciamento de dependências e projetos Python. |
| uv | Gerenciamento rápido de dependências, ambientes e ferramentas Python. |
| pip-tools | Gera arquivos de dependências fixadas a partir de requisitos. |
| bump-my-version | Automatiza a atualização de versões. |
| semantic-release | Automatiza releases seguindo regras de versionamento semântico. |
| Commitizen | Também pode automatizar changelogs e versionamento com configuração apropriada. |

### 2.8. CI/CD e automação de entrega

| Tecnologia | Descrição |
| ---------- | --------- |
| GitHub Actions | Executa testes, lint, builds e publicações em workflows. |
| GitLab | CI/CD	Automatiza validação e entrega em pipelines GitLab. |
| Jenkins | Servidor de automação de builds e pipelines. |
| Azure | Pipelines	CI/CD no ecossistema Azure DevOps. |
| pre-commit.ci | Automatiza verificações e correções de hooks em repositórios compatíveis. |
| act | Executa localmente muitos workflows do GitHub Actions com Docker. |
| Release Please | Automatiza criação de releases e atualização de changelogs com base em commits convencionais. |
| Renovate | Automatiza propostas de atualização de dependências. |
| Dependabot | Abre pull requests para atualizar dependências e tratar alertas compatíveis. |

### 2.9. Segurança e auditoria no desenvolvimento

| Tecnologia | Descrição |
| ---------- | --------- |
| Bandit | Analisa código Python em busca de problemas de segurança. |
| pip-audit | Verifica vulnerabilidades conhecidas em dependências Python. |
| Safety | Verificação de vulnerabilidades em dependências, conforme os recursos e condições de uso da ferramenta. |
| Semgrep | Análise estática de código com regras de segurança e qualidade. |
| CodeQL | Análise de código para identificar vulnerabilidades e outros problemas. |
| Gitleaks | Detecta possíveis segredos em repositórios e histórico Git. |
| detect-secrets | Detecta possíveis credenciais e segredos em arquivos. |
| Checkov | Analisa configurações de infraestrutura como código. |
| Trivy | Analisa imagens de containers, dependências e configurações em busca de vulnerabilidades.v
| pip-licenses | Ajuda a inspecionar licenças das dependências instaladas. |

### 2.10. Testes de integração, bancos e migrações

| Tecnologia | Descrição |
| ---------- | --------- |
| Alembic | Controla migrações de schema de bancos SQLAlchemy. |
| SQLFluff | Analisa e formata SQL. |
| SQLGlot | Analisa, transforma e transpila SQL entre dialetos. |
| dbt-fusion | Motor de execução do ecossistema dbt, com recursos e disponibilidade próprios; não é equivalente a uma simples biblioteca de testes. |
| pytest-docker | Auxilia testes que dependem de ambientes Docker, conforme a configuração. |
| pytest-postgresql | Facilita testes com PostgreSQL. |
| pytest-mysql | Integração para testes com MySQL, conforme o plugin e a configuração usados. |

### 2.11. Ferramentas para desenvolvimento de DAGs e pipelines

| Tecnologia | Descrição |
| ---------- | --------- |
| apache-airflow-providers-standard | Operadores e componentes padrão do Airflow em versões que utilizam esse pacote de provider. |
| apache-airflow-providers-postgres | Integrações do Airflow com PostgreSQL. |
| apache-airflow-providers-mysql | Integrações do Airflow com MySQL. |
| apache-airflow-providers-amazon | Integrações do Airflow com serviços AWS. |
| apache-airflow-providers-google | Integrações do Airflow com serviços Google Cloud. |
| apache-airflow-providers-apache-spark | Integrações do Airflow com Apache Spark. |
| apache-airflow-providers-apache-kafka | Integrações relacionadas ao Kafka nas versões compatíveis. |
| apache-airflow-providers-http | Operadores e hooks HTTP. |
| apache-airflow-providers-docker | Execução e integração com containers Docker. |
| apache-airflow-providers-slack | Integrações para notificações via Slack. |

> Atenção: os providers do Airflow devem ser escolhidos de acordo com os serviços utilizados e a versão instalada. O Airflow também possui requisitos específicos de dependências; não é recomendável instalar uma versão arbitrária junto com todas as outras.

## 3. Tecnologias complementares que não são apenas pacotes Python

### 3.1. Bancos, armazenamento e plataformas analíticas

> São importantes em Engenharia de Dados, mas não devem ser tratadas automaticamente como dependências main ou dev do Poetry.

| Tecnologia | Descrição |
| ---------- | --------- |
| PostgreSQL | Banco relacional para aplicações e dados analíticos. |
| MySQL | Banco relacional para sistemas transacionais e pipelines. |
| SQL Server | Banco relacional da Microsoft. |
| Oracle Database | Banco relacional empresarial. |
| MongoDB | Banco documental NoSQL. |
| Cassandra | Banco distribuído orientado a colunas largas. |
| Redis | Armazenamento em memória, cache e estruturas de dados. |
| Elasticsearch | Busca e análise de documentos e eventos. |
| OpenSearch | Plataforma de busca e análise de dados. |
| ClickHouse | Banco colunar para consultas analíticas. |
| Snowflake | Plataforma de dados e data warehouse na nuvem. |
| BigQuery | Data warehouse gerenciado do Google Cloud. |
| Amazon Redshift | Data warehouse da AWS. |
| Databricks | Plataforma de engenharia de dados, lakehouse e analytics. |
| Microsoft Fabric | Plataforma integrada de dados, analytics e BI. |
| Apache Hive | Infraestrutura SQL para dados em ecossistemas Hadoop compatíveis. |
| Trino | Motor SQL distribuído para consultas em múltiplas fontes. |
| Presto | Motor SQL distribuído para análise de dados. |
| ClickHouse Cloud | Serviço gerenciado de analytics com ClickHouse. |

### 3.2. Data Lake, Lakehouse e formatos

| Tecnologia | Descrição |
| ---------- | --------- |
| Apache Parquet | Formato de arquivo colunar eficiente para analytics. |
| Apache ORC | Formato colunar para armazenamento e consulta analítica. |
| Apache Avro | Formato de serialização com schema. |
| Apache Iceberg | Formato de tabela aberto para grandes conjuntos de dados analíticos. |
| Delta Lake | Camada de armazenamento com transações e recursos de lakehouse. |
| Apache Hudi | Plataforma de tabelas para ingestão incremental e gerenciamento de dados. |
| Amazon S3 | Armazenamento de objetos usado frequentemente em data lakes. |
| Azure Data Lake Storage | Armazenamento de dados analíticos na Azure. |
| Google Cloud Storage | Armazenamento de objetos na Google Cloud. |
| MinIO | Armazenamento de objetos compatível com APIs S3. |
| Apache Hadoop HDFS | Sistema de arquivos distribuído do ecossistema Hadoop. |

### 3.3. Streaming e computação distribuída

| Tecnologia | Descrição |
| ---------- | --------- |
| Apache Kafka | Plataforma distribuída para eventos e streaming. |
| Kafka Connect | Integra fontes e destinos ao Kafka por meio de conectores. |
| Apache Spark | Motor de processamento distribuído. |
| Apache Flink | Motor de processamento de streams e eventos. |
| Apache Beam | Modelo unificado para pipelines batch e streaming. |
| Apache Pulsar | Plataforma de mensageria e streaming distribuído. |
| RabbitMQ | Broker de mensageria. |
| Amazon Kinesis | Serviços de streaming gerenciados na AWS. |
| Google Cloud Dataflow | Serviço gerenciado de processamento de pipelines Apache Beam. |
| Amazon EMR | Plataforma gerenciada para frameworks de processamento distribuído. |
| Azure Event Hubs | Serviço gerenciado de ingestão de eventos. |

### 3.4. Containers, infraestrutura e execução

| Tecnologia | Descrição |
| ---------- | --------- |
| ocker | Empacota aplicações e suas dependências em containers. |
| Docker Compose | Define e executa aplicações com múltiplos containers. |
| Kubernetes | Orquestra containers em clusters. |
| Helm | Gerencia aplicações Kubernetes por meio de charts. |
| Terraform | Provisiona infraestrutura por meio de configuração declarativa. |
| OpenTofu | Ferramenta de infraestrutura como código compatível com o ecossistema Terraform. |
| Ansible | Automatiza configuração e administração de infraestrutura. |
| Linux | Sistema operacional comum em ambientes de dados. |
| WSL2 | Executa um ambiente Linux integrado ao Windows. |
| Make | Automatiza comandos de build e tarefas de projeto. |

### 3.5. Governança, catálogo e linhagem

| Tecnologia | Descrição |
| ---------- | --------- |
| OpenLineage | Padrão aberto para registrar metadados de execução e linhagem. |
| DataHub | Catálogo de dados, metadados, descoberta e governança. |
| OpenMetadata | Plataforma aberta de catálogo, governança e observabilidade de metadados. |
| Apache Atlas | Gerenciamento de metadados e governança no ecossistema Hadoop. |
| Amundsen | Catálogo de dados de código aberto. |
| Marquez | Plataforma de metadados e linhagem relacionada ao ecossistema OpenLineage. |
| Monte Carlo | Plataforma comercial de observabilidade de dados. |
| Soda | Ferramentas de qualidade e observabilidade de dados. |
| Great Expectations | Framework de validação de qualidade. |
| dbt | Transformações analíticas, documentação e testes de modelos. |

### 3.6. Visualização e consumo dos dados
| Tecnologia | Descrição |
| ---------- | --------- |
| Power BI | Criação de relatórios e dashboards. |
| Tableau | Visualização e análise visual de dados. |
| Qlik Sense | Analytics e visualização de dados. |
| Looker | Plataforma de BI e modelagem analítica. |
| Metabase | BI e consultas para usuários de negócio. |
| Apache Superset | Plataforma de exploração e visualização de dados. |
| Streamlit | Criação de aplicações interativas em Python. |
| Dash | Aplicações analíticas interativas com Python. |
| Plotly | Gráficos interativos. |
| Matplotlib | Gráficos estáticos e visualização científica. |
| Seaborn | Visualização estatística baseada em Matplotlib. |


