<img src="/Larrahona_Data.png">

## Data & Analytics Engineer
I focus on building data systems where integrity and technical validation are the foundation. My background in high-precision environments has shaped my approach to engineering: I prioritize traceability and the elimination of silent failures in critical workflows.

Currently, I lead technical and data operations at **CENTEC TDF**, where I focus on modernizing legacy systems—transitioning manual, ad-hoc processes into stable, containerized, and orchestrated architectures. My goal is to build data platforms that are easy to maintain, auditable, and provide a reliable source of truth for decision-making.

---

### Areas of Focus
*   **Operational Reliability:** Moving critical workloads from local scripts to isolated, monitored environments using **Docker** and **Apache Airflow**.
*   **Data Integrity:** Implementing multi-phase quality gates—from source freshness to logic-specific unit testing—to catch issues before they impact the business.
*   **Technical Refactoring:** Mapping dependencies in monolithic systems and resolving complex data grain challenges through centralized semantic layers.

---

### Selected Projects

#### **[ISO 17025 Data Compliance Framework](https://github.com/andreslarrahona/iso-data-compliance-framework)**
A production-grade analytical warehouse designed for a regulated laboratory. It implements an **append-only** ingestion pattern and an automated validation strategy to ensure 100% data traceability and compliance with international quality standards.

#### **[Legacy Metadata & Dependency Mapper](https://github.com/andreslarrahona/lineage-mapper)**
A data engineering tool built in Python to map file and database dependencies in monolithic environments. It identifies orphaned assets and resolves hidden SQL lineage to reduce operational risk during infrastructure migrations.

#### **[Laboratory Telemetry Pipeline](https://github.com/andreslarrahona/lab-telemetry-elt)**
An event-driven ELT architecture using **MQTT** and **dbt** to standardize instrument data. It replaces manual logging with a resilient pipeline that captures raw readings and transforms them into audit-ready datasets.

#### **[Stability Audit: USD-Pegged Assets](https://github.com/andreslarrahona/data-metrology-finance)**
A technical assessment of digital asset parity using industrial metrology standards. It treats financial data as a measurement process, quantifying out-of-tolerance events and recovery rates during market stress.

---

### Technical Stack
*   **Languages & Tools:** SQL (PostgreSQL, MySQL), Python, dbt, Apache Airflow, Docker.
*   **Infrastructure:** AWS (EC2, S3, RDS, Lambda), Linux/Ubuntu, On-premise servers.
*   **Analytics:** Metabase, Power BI, LookML (POC), Streamlit.
