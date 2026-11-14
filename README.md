<h1 align="center">Hi, I'm Bikash Kushwaha 👋</h1>

<h3 align="center">AI / Machine Learning Engineer · LLMs and Generative AI · MLOps on AWS · 5× AWS Certified</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/bikash9cmd"><img src="https://img.shields.io/badge/LinkedIn-bikash9cmd-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:kushwahabikash9580@gmail.com"><img src="https://img.shields.io/badge/Email-kushwahabikash9580%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://bikash9cmd-portfolio.onrender.com"><img src="https://img.shields.io/badge/Portfolio-live%20demos-46E3B7?style=flat&logo=render&logoColor=white" alt="Portfolio with live demos" /></a>
  <a href="https://bikash9cmd.github.io"><img src="https://img.shields.io/badge/Website-bikash9cmd.github.io-222222?style=flat&logo=githubpages&logoColor=white" alt="Personal website" /></a>
  <img src="https://img.shields.io/badge/Based%20in-Kathmandu%2C%20Nepal-DC143C?style=flat" alt="Based in Kathmandu, Nepal" />
  <img src="https://komarev.com/ghpvc/?username=bikash9cmd&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>

I build, evaluate and ship machine learning and LLM systems on AWS: RAG and Amazon Bedrock assistants with grounding and safety checks, privacy-preserving AI workflows for banking, time-series forecasting backtested against baselines, edge computer vision, and MLOps pipelines with gated releases, automatic rollback and drift monitoring.

Most of my open-source work tackles real problems in Nepal (air, rain, roads, power, farming and earthquakes), built on real data and measured against honest baselines.

## 💼 What I'm doing now

- **AI Software Engineering Intern** at [Asterdio](https://github.com/asterdio), Lalitpur: AI tools for the Breqo app, 3 agentic-AI prototypes for Nepali commercial banks (KYC update, AML alert triage, credit review), and a bank-side **Privacy Shield** that tokenises 8 customer identifiers and blocks any upload that fails a PII leak test
- **Machine Learning Intern** at FlyRank AI, Kathmandu: applied ML, AI agents and AI search (SEO, GEO)
- **Independent Contractor, AI Training** at Mercor: rubric-based AI training and evaluation data for a leading AI research lab; member of Mercor's Machine Learning Engineer Talent Network
- 🎓 **BSc (Hons) Computer Science with AI**, Birmingham City University (Sunway College Kathmandu), expected 2028

**Previously:** Machine Learning Engineer Apprentice at TekBay Digital Solutions (full ML lifecycle on AWS, fraud-detection capstone with S3, Glue DataBrew and SageMaker) · Solutions Architect Apprentice at Adex International (Terraform infrastructure as code that cut manual provisioning time by 40%) · Data Engineer at DataCamp

## 🚀 Featured projects

| Project | What it does | Results |
|---|---|---|
| ⚡ [**Bijuli**: Grid demand forecasting + MLOps](https://github.com/bikash9cmd/electricity-demand-forecast-mlops) | Day-ahead hourly electricity demand for Nepal's grid, with a model registry, shadow rollout, automatic rollback and drift monitoring | **3.27% MAPE** over 23,184 walk-forward forecasts, 30% below the best naive baseline; gated releases cut worst-week error from 9.8% to 7.45% |
| 🚦 [**Chowk**: Edge AI traffic classification](https://github.com/bikash9cmd/traffic-vehicle-detection-edge) | Vehicle-mix counts for Kathmandu junctions from 30 real street videos, running on the edge with a serverless AWS backend | Accuracy **63.2% → 93.9%**; traffic-volume (PCU) error 45.7% → 1.3%; 24 ms per 720p frame on one CPU core |
| 🌾 [**Parkha**: Bilingual crop pest advisor](https://github.com/bikash9cmd/crop-pest-advisor-llm) | Nepali/English Amazon Bedrock assistant that computes safe-harvest dates from official pesticide labels, never from model output | Safety gate caught **290/290** seeded wrong answers; 18/20 on a held-out evaluation set |
| 🔐 [**Gopya**: Secure company RAG chatbot](https://github.com/bikash9cmd/rbac-rag-document-chatbot) | Role-based access control enforced inside the vector query, plus PII redaction and prompt-injection guards | Right document in the top 4 for **100% of 69** test questions; **0 leaks across 45 attacks** |
| 🌧️ [**Sodhnus**: Bilingual rainfall assistant](https://github.com/bikash9cmd/bilingual-rainfall-rag-assistant) | Bedrock tool-use assistant over 5 read-only tools that answers only from verified rainfall data | A deterministic number checker caught **97%** of wrong answers in a 350-case adversarial test; Guardrails cost cut 4.2× |
| 🏞️ [**Barsha**: Monsoon rainfall lakehouse](https://github.com/bikash9cmd/monsoon-rainfall-lakehouse-nepal) | Serverless lakehouse on S3, Lambda, DuckDB and Athena over 50 years of Nepal station data | 67,215 station-days for about **$1.20/month**; quality checks caught 4,599 false zero readings |
| 🌫️ [**Hawa**: Kathmandu PM2.5 forecasting](https://github.com/bikash9cmd/air-quality-forecast-kathmandu) | Hourly next-day air-quality forecasts with English/Nepali alerts on serverless AWS | **15% lower error** than the best naive forecast; 40% fewer missed bad-air days |
| 🆘 [**Surakshit**: Earthquake check-in service](https://github.com/bikash9cmd/earthquake-safety-checkin-nepal) | Multi-region, queue-first "I'm safe" check-ins by web or SMS | **0% lost** in a 15-million-user load simulation, vs 45% for a naive design |

<details>
<summary><b>More projects</b></summary>
<br>

- 🤖 [Bedrock AgentCore Support Agent](https://github.com/bikash9cmd/bedrock-agentcore-support-agent): customer support agent on Amazon Bedrock AgentCore with Strands Agents, Cognito JWT auth, Cedar policies and OpenTelemetry tracing
- ☸️ [AI Customer Service Agent on EKS](https://github.com/bikash9cmd/ai-customer-service-agent-eks): Strands Agents with self-hosted Qwen2.5-3B (vLLM + LiteLLM) on Amazon EKS
- 🚚 [Freight Rate Prediction](https://github.com/bikash9cmd/freight-rate-prediction): LightGBM truckload pricing with data-quality cleaning and a time-based backtest (about 3% MAPE vs 8% for a baseline)
- 📄 [PDF Q&A with Bedrock and LangChain](https://github.com/bikash9cmd/aws-bedrock-langchain-document-qa): RAG over a PDF with Titan embeddings, FAISS and Amazon Nova Lite
- 🏬 [Retail Data Warehouse Pipeline](https://github.com/bikash9cmd/retail-dataware-house-pipeline): S3 to Redshift ELT with Airflow, dbt tests, star schema and a FastAPI analytics API
- 🚲 [Bike Demand Forecast MLOps](https://github.com/bikash9cmd/bike-demand-forecast-mlops): Airflow DAGs, FastAPI + Redis serving, MariaDB star schema, Evidently drift reports and Grafana monitoring
- 💸 [AWS Cost Optimizer](https://github.com/bikash9cmd/cost-optimizer): Lambda + Cost Explorer spend alerts to Slack and idle-resource detection
- 🏗️ [3-Tier Web App on AWS](https://github.com/bikash9cmd/aws-3-tier-web-app): Terraform VPC, ALB, Auto Scaling and RDS MySQL
- 🧠 [MLOps Depression-Risk Pipeline](https://github.com/bikash9cmd/mlops-depression-risk-pipeline): Airflow, FastAPI, Redis, MariaDB, Evidently AI, Prometheus and Grafana on Docker Compose
- 🏔️ [Trekker Safety Alerts](https://github.com/bikash9cmd/trekker-safety-alerts-nepal): trek check-ins and storm holds for Himalayan passes using NOAA GEFS forecasts
- ♻️ [Waste Flow Pipeline](https://github.com/bikash9cmd/waste-flow-pipeline-kathmandu): lakehouse on AWS Open Data modelling Kathmandu Valley waste flows and landfill blockades
- 📂 [All repositories](https://github.com/bikash9cmd?tab=repositories)

</details>

## ☁️ Certifications

<p align="left">
<img src="https://img.shields.io/badge/AWS-ML%20Engineer%20Associate-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified Machine Learning Engineer Associate" />
<img src="https://img.shields.io/badge/AWS-Solutions%20Architect%20Associate-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified Solutions Architect Associate" />
<img src="https://img.shields.io/badge/AWS-Data%20Engineer%20Associate-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified Data Engineer Associate" />
<img src="https://img.shields.io/badge/AWS-AI%20Practitioner-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified AI Practitioner" />
<img src="https://img.shields.io/badge/AWS-Cloud%20Practitioner-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified Cloud Practitioner" />
<img src="https://img.shields.io/badge/AWS%20BeSA-Agentic%20AI%3A%20PoC%20to%20Production-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS BeSA Agentic AI: PoC to Production on AWS" />
</p>

## 🛠️ Tech stack

**Machine learning:** scikit-learn · LightGBM · time-series and quantile forecasting · walk-forward backtesting · computer vision (YOLOX, edge inference) · Amazon SageMaker · drift detection (Evidently AI)

**Generative AI and LLMs:** Amazon Bedrock (tool use, Guardrails, AgentCore) · RAG (LangChain, FAISS, Chroma, Milvus, BM25 hybrid search) · AI agents (Strands, MCP, multi-agent A2A) · LLM-as-a-Judge evaluation · vLLM · LiteLLM · Langfuse · PII masking

**AWS:** IAM · VPC · EC2 · S3 · Lambda · Step Functions · EventBridge · SQS · API Gateway · DynamoDB · RDS · Athena · Glue DataBrew · IoT Core · CloudFront · WAF · CloudWatch

**MLOps and DevOps:** Terraform · AWS SAM · Docker · Kubernetes (EKS) · GitHub Actions · MLflow · Apache Airflow · FastAPI · Prometheus · Grafana · Linux

**Languages and data:** Python · SQL · Bash · Pandas · NumPy · DuckDB · Parquet

<p align="left">
<img src="https://skillicons.dev/icons?i=python,aws,terraform,docker,kubernetes,fastapi,githubactions,grafana,prometheus,linux,bash,git&perline=12" alt="Python, AWS, Terraform, Docker, Kubernetes, FastAPI, GitHub Actions, Grafana, Prometheus, Linux, Bash, Git" />
</p>

## 💬 Ask me about

AWS architecture · MLOps · forecasting · RAG · building and evaluating agents on Amazon Bedrock · making LLM answers safe to trust

<p align="center"><i>Open to AI/ML engineering roles and collaborations. The fastest way to reach me is <a href="mailto:kushwahabikash9580@gmail.com">email</a> or <a href="https://www.linkedin.com/in/bikash9cmd">LinkedIn</a>.</i></p>
