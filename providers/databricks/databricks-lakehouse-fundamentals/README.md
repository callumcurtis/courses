# Databricks Lakehouse Fundamentals

The learning plan can be found [here](https://customer-academy.databricks.com/learn/lp/215/databricks-fundamentals-learning-plan).

## Progress

- [x] [Databricks Fundamentals](https://customer-academy.databricks.com/learn/course/2206/databricks-fundamentals) (7/13)
- [x] [Databricks Fundamentals Accreditation](https://customer-academy.databricks.com/learn/course/2308/databricks-fundamentals-accreditation)

## Notes

- Data warehouses
    - Used for analytics/BI
    - ETL from transactional databases
    - Inflexible schemas, slow
- Data lakes
    - Structured to unstructured
    - Streaming support
    - Slow, unreliable
- Data lakehouses: unified benefits of warehouses and lakes
    - Transactions
    - Schema enforcement
    - Streaming support
    - Open storage formats
    - Architecture: data lake | storage management | governance | applications
- Databricks lakehouse
    - Data lake: open data lake format
    - Storage management: Delta Lake
    - Governance: Unity Catalog
- Databricks Data Intelligence (DI) platform: lakehouse plus generative AI
    - Architecture: data lake | storage management | governance | generative AI | applications
    - MLflow for end-to-end management
    - NL interaction with data/metadata
- Delta Lake: transactions, audit history, time travel, schema enforcement
and evolution, streaming and batch processing, change data capture, backfill
    - Uses Delta Tables
- Delta Tables: based on parquet
- Unity Catalog: unified tool for data governance
- Data governance: cataloging, classification, auditing, discovery,
sharing, lineage, security, quality
- Delta Sharing: sharing data between organizations, data kept with provider
- Databricks Marketplace: commercialization of data
- Databricks Cleanrooms: private compute shared between organizations,
allowing combining of data without replication
- Security: through control and data plane separation
    - Table ACLs
    - IAM instance profiles
- Control plane: configurations, notebooks, and cluster management lives in Databricks
- Data plane: compute for data processing, lives within cloud provider account (unless serverless)
- Cloud storage: data stored in cloud provider account
- Databricks serverless data plane
    - Motivations: slow cluster creation/startup, over provisioning
    - Pool of warm clusters
- Photon: query engine, up to 80% cost savings over Spark while implementing all Spark APIs
- Workloads:
    - Data warehousing (Databricks SQL)
    - Orchestration (Workflows)
    - ETL and real-time analytics (Delta Live Tables)
    - Data science and AI (Databricks AI)
- Workflows
    - Intelligent pipeline triggering (scheduled, event-based)
    - Automatic resource allocation
    - Automatic checkpointing and recovery
    - Automatic monitoring and alerting
- Delta Live Tables: automating stream ingestion, transformation, and scaling
- Data science and AI
    - Own the models and train securely on your own data
    - Transition POCs into production with support over entire lifecycle (MLflow)
    - Data collection and preparation | build/train model | serve and monitor

