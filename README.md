# Hi, I'm Daniel Dickerson

Software Engineering & Data Science student building data platforms, validation systems, and developer tooling.

I'm particularly interested in improving **trust in data and AI systems** through reproducibility, validation, lineage, and runtime safeguards.

My recent work focuses on:

- data engineering on AWS
- automated data quality and CI-integrated validation
- AI-assisted developer tooling
- governance-aware system design
- applied machine learning and analytics

---

## What I'm Working On

### Data Platform Reliability
Building tooling to improve confidence in data systems through:

- automated validation
- reproducible infrastructure
- CI/CD quality enforcement
- governance and traceability

### AI-Assisted Engineering
Exploring how AI can safely participate in engineering workflows through:

- runtime validation
- controlled recovery
- semantic pipeline generation
- developer automation

### Applied Systems & Analytics
Building practical systems that turn messy real-world inputs into structured, useful outputs.

---

## Featured Projects

### Automated Data Quality Framework *(CBA Internship)*
**Python · AWS Glue · Athena · Terraform · CI/CD**

Config-driven framework for validating AWS Glue and Athena datasets before and after transformations.

Designed to improve trust in data systems by shifting quality enforcement earlier into engineering workflows.

Built to support reproducible validation across isolated environments while producing structured evidence for observability and downstream debugging.

**Key areas**
- schema validation and contract enforcement  
- partition verification and reconciliation checks  
- row-level and aggregate validation logic  
- extensible registry-based architecture  
- Tested within Terraform-managed AWS environments

---

### DevSecOps Toolchain for ETL Pipelines — Honours Thesis
**AWS · Terraform · MWAA · OpenLineage · OPA · CI/CD**

Large-scale honours thesis project exploring how governance, security, and traceability can be embedded directly into ETL and data platform workflows through a DevSecOps approach.

The project investigates how traditionally manual governance activities; including validation, policy enforcement, lineage, and auditability; can be shifted into executable system controls integrated across the software and data lifecycle.

The proposed toolchain combines Infrastructure-as-Code, policy-as-code, governed CI/CD, runtime validation, and metadata-driven traceability to improve trust, reproducibility, and confidence in downstream data assets.

Rather than treating governance as a separate compliance process, the project explores how controls can become part of normal engineering workflows; from pull requests and infrastructure changes through to deployment, orchestration, and ETL execution.

**Areas explored**
- DevSecOps practices for ETL pipelines  
- governed CI/CD workflows for data systems  
- Infrastructure-as-Code using Terraform  
- policy-as-code using OPA/Rego  
- lineage and metadata traceability  
- reproducible data platform environments  
- validation and deployment gates  
- workflow orchestration with MWAA/Airflow

---

### auto-py (Autopsy)
**Python · Runtime Systems · LLMs · Software Reliability**

Experimental runtime framework exploring how Python applications can recover from failures through checkpointing, controlled execution, and AI-assisted remediation.

The project investigates whether AI-generated or dynamically changing software can be made more reliable by introducing runtime safeguards rather than relying solely on pre-deployment testing.

At its core, the system explores Python execution contexts in depth; examining how programs fail, what execution state can be preserved, and how systems might safely recover after runtime errors.

Rather than restarting execution from scratch, the framework captures checkpoints, restores execution context, proposes candidate fixes, validates changes, and attempts controlled continuation of execution.

**Areas explored**
- Python execution contexts and interpreter behaviour  
- checkpointing and controlled state recovery  
- exception handling and failure boundaries  
- runtime validation of AI-generated fixes  
- hot patching and execution continuation  
- reliability engineering for AI-assisted software development  
- observability and execution tracing

---

### Data Pipeline Generation Skill
**LLMs · dbt · Metadata-Driven Engineering**

Framework for generating structured dbt pipeline artifacts from business requirements and semantic context.

Designed to accelerate early-stage data engineering by producing reviewable models, mappings, documentation, and transformation logic while maintaining consistency and traceability.

Explores how generative AI can assist engineering workflows without sacrificing structure, transparency, or maintainability.

**Key areas**
- dbt pipeline generation  
- semantic requirement interpretation  
- metadata-driven development  
- documentation and mapping generation  
- structured AI-assisted engineering workflows

---

### Fencing Visual Analysis Platform
**Computer Vision · Streamlit · PyTorch · Pose Estimation**

End-to-end platform for analysing fencing footage using pose estimation and movement analytics.

Transforms unstructured video into structured performance insights by tracking joint trajectories and movement patterns across bouts.

Built to explore practical computer vision workflows in a real-world sporting context.

**Key areas**
- pose estimation and tracking  
- movement analytics and visualisation  
- applied computer vision workflows  
- interactive Streamlit deployment

---

### Foam Booth Analytics Platform

**Data Engineering · LLMs · Data Cleaning · Analytics**

Data engineering and analytics platform built around **18 years of messy free-text sales records** across commercial and residential foam products.

The project explored how AI-assisted workflows and agentic processing could be used to transform inconsistent operational data into structured, analysable datasets suitable for forecasting and business decision-making.

A key challenge was handling fragmented naming conventions, inconsistent descriptions, and highly variable historical records across product categories, dimensions, and materials.

Rather than relying purely on manual cleaning, the system experimented with AI-driven categorisation and enrichment to improve consistency while preserving useful historical information.

**Key areas**

- AI-assisted categorisation and enrichment  

- feature extraction from historical records  

- analytics and forecasting preparation  

- exploratory agentic workflows

## Technologies

**Languages**  
Python · SQL · Java · Rust

**Data & Cloud**  
AWS (Glue, Athena, S3) · PostgreSQL · Supabase · dbt · Pandas

**Infrastructure**  
Terraform · GitHub Actions · Docker · CI/CD

**ML & Analytics**  
PyTorch · Computer Vision · LLM Workflows

---

## Current Interests

- trustworthy AI systems
- data platform engineering
- MLOps & validation
- developer tooling
- governance and observability

---

## Contact

- Email: dannydickerson03@gmail.com
