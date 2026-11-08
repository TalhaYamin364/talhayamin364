# Hi, I'm Talha Yamin 👋

**Analytics Engineer · pipelines, warehouses and streaming** · Dhaka, Bangladesh

Nearly five years building the data infrastructure behind analytics, currently as a Senior Data Analyst (Analytics Engineering) at Optimizely. My day-to-day is production engineering: Python ingestion into Snowflake on Kubernetes, tested dbt marts, cost-controlled warehouses with Terraform, and CI that builds and diffs changes against production before review.

**Right now:** building an end-to-end streaming lakehouse for telecom usage records: Kafka into Spark Structured Streaming and Iceberg on HDFS/YARN, with idempotent writes, deduplication, late-arriving data handling and safe day-level backfills.

## Tech I work with

**Daily use**

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white) ![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

**Building now**

![Apache Hadoop](https://img.shields.io/badge/Hadoop%203.4-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black) ![Apache Spark](https://img.shields.io/badge/Spark%204.0-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white) ![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white) ![Apache Iceberg](https://img.shields.io/badge/Iceberg-4A90E2?style=for-the-badge) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Also used**

![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

## Selected work

- **Quote-to-revenue reconciliation:** sole developer of a quarterly dbt build (17 models, 13 matching macros, primary-key tests across 20+ source tables) that reconciles multi-year quotes to signed-contract terms, raising the match rate from 61% to 92%.
- **Finance close:** built the tested dbt suite behind the monthly close, cutting the manual rebuild from 4–5 days to about 1, and rewrote a 14M-row shared model with zero differences across 9.6M rows compared.
- **Warehouse cost control:** designed the analyst Snowflake warehouse and its cost monitor in Terraform, shipped through GitHub Actions: auto-suspend, query timeout and a daily credit cap with alerts.
- **Safer changes:** Python pre-push hooks that build each changed dbt model against production and diff row counts and nulls before review.

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [telecom-lakehouse-streaming-platform](https://github.com/TalhaYamin364/telecom-lakehouse-streaming-platform) | A mobile operator's call, SMS and data records streamed through Kafka and Spark into an Iceberg lakehouse (bronze, silver, gold), run locally in Docker. **Status:** HDFS + YARN cluster and Spark-on-YARN verified; Kafka ingestion and the lakehouse layers are in build. Every change goes through an issue, a PR, CI and review. | Hadoop, Spark, Kafka, Iceberg, Docker |
| [dse-stock-screener](https://github.com/TalhaYamin364/dse-stock-screener) | Scrapes Dhaka Stock Exchange data, scores stocks on stability, and outputs a diversified allocation, with a step that re-checks live prices before acting. | Python |
| [Full-Stack-Expense-Tracker](https://github.com/TalhaYamin364/Full-Stack-Expense-Tracker) | A CLI expense tracker rebuilt as a three-tier web app: FastAPI backend, Flask frontend, SQLAlchemy persistence. | FastAPI, Flask, SQLAlchemy |
| [Chicago-Taxi-Cab-Tableau-Analysis](https://github.com/TalhaYamin364/Chicago-Taxi-Cab-Tableau-Analysis) | A Tableau story of the taxi business's decline, set against ridesharing and COVID-19. | Tableau |

## Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/talha-yamin/) [![Website](https://img.shields.io/badge/Website-222222?style=for-the-badge&logo=githubpages&logoColor=white)](https://TalhaYamin364.github.io) [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@talhayamin9311) [![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/Wolfsbane169/)

![Followers](https://img.shields.io/github/followers/TalhaYamin364?style=for-the-badge&logo=github&color=181717) ![Public repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FTalhaYamin364&query=%24.public_repos&label=Public%20repos&style=for-the-badge&logo=github&color=181717)

[![GitHub streak](https://streak-stats.demolab.com/?user=TalhaYamin364&theme=dark&hide_border=true)](https://github.com/TalhaYamin364)
