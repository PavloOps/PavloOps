## Hi there 👋 I'm Olga Pavlova!

I'm a Machine Learning Engineer and Python Developer working on end-to-end machine learning projects in pharm retail in Krasnodar.

1. Detailed info

> Education: I completed my [Master's degree in HSE'24](https://www.hse.ru/ma/mds/news/909801290.html) in Data Science at the Higher School of Economics, graduating with a GPA of 9.45 and receiving the highest honors.

> Careerpath, skills are mostly listed at [LinkedIn](https://www.linkedin.com/in/ov-pavlova)

2. Sample projects

> While most of my projects are closed-source, I'm happy to share a few personal ones that highlight my skills and tech stack.

| Status | Project Type | Title / Link | Description | Technologies |
|--------|-------------|-------------------|----------|------------|
| ✅ (2024)   | Production-ready Sentiment Analysis App | [Master's Thesis](https://gitlab.com/mds7060534/bert_app) 📜 Graded 10/10 by the examination board | The development of a practical deployment of end-to-end machine learning pipeline for processing and analyzing sentiments of Sephora beauty products’ customer reviews is presented. The pipeline encompasses three main iterative phases: data ingestion and transformation, training of machine learning models, and deployment of these models in web applications using cloud technology. The data ingestion phase involves facilitating the automatic collection and storage of large datasets (up to 4 million text reviews with additional details) by web-scraping and the establishment of a database architecture. Based on the statistical analysis of significant variations in the distribution of the target variable across different review types and product categories there are formed 8 subsets with train, validation and test parts with equal target proportion for a fair comparison. During the model training phase, 17 experiments were conducted using both simple and advanced algorithms. The DistilBERT model was identified as the most efficient, balancing technical constraints and predictive accuracy. While the Naïve Bayes model served as a lightweight model even if not with the best accuracy rate. Using the title as an important summarization and source of sentiment along with the review text helped significantly improve model accuracy. Challenges in sentiment differentiation, particularly in the “Fragrance” category, and limitations in linguistic processing were discussed. The deployment phase involved creating a web-service architecture with frontend and backend components for both main and fallback solutions. DistilBERT model is used in the main application for making predictions and is used within the fallback application the Naïve Bayes model. Key technological implementations include Docker image’s build optimization, Kubernetes cluster deployment in the Cloud, and load balancer’s using for error handling with the default fallback. A CI/CD pipeline ensures reliable code updates. | Python, Flask, Huggingface & DistillBert, Streamlit, Docker, Helm, Terraform |
| ✅ (2025)    | Educational utility | [Grader](https://github.com/PavloOps/python_generation_grader) ⭐36 | I have a strong passion for learning and continuously invest in self-education. One of the courses I particularly enjoyed was [Python Generation](https://stepik.org/course/98974/info) To make completing the assignments more convenient, I found an open-source grader and heavily customized it to suit my needs. I expanded its functionality and fixed most of the non-working components. The grader supports solution template generation, test loading, and automatic code evaluation. It handles input/output, return vs. print-based functions, and class-based tasks. | Python, requests, ast, argparse, zipfile |
| ✅ (2025)   | End-to-End ML pipeline: forecasting shortages in unstationary time series | NDA | End-to-end project for shortage detection, covering ML system design, data engineering (ETL & DB), model development, production pipelines, dashboard support, and continuous product analytics. A custom Python framework was developed. As a result, the project was successfully integrated into business processes and demonstrated excellent results in forecasting product shortages on the pharm market. | Pandas, sklearn, CatBoost, Optuna, ClearML |
| ✅ (2026)  | Advanced ML Lab | [ClearML & PyTorch Lightning](https://github.com/PavloOps/pytorch_lightning_practice) | [Completed hands-on ML engineering course](https://stepik.org/course/214389/syllabus) focused on production-style deep learning workflows: modular PyTorch Lightning pipelines, ClearML experiment tracking, reproducible configs, callbacks, custom metrics, checkpointing, CLI training/inference, GAN experiments, and a final Food-101 ConvNeXt project with error analysis, Grad-CAM debugging, hard-case mining, and ONNX export. [Final Project on ClearML](https://app.clear.ml/projects/a7f426d19f9f493980c13330e8aa07b6/tasks/6f3b8f5d93854931b11f378d23be7e37/output/log) | PyTorch, PyTorch Lightning, ClearML, TorchMetrics, torchvision, ConvNeXt, ONNX |
| ✅ (2026)  | Airflow | [Apache Airflow для аналитика (Практикум)](https://github.com/PavloOps/airflow_practice) | Designed and deployed a production-ready Apache Airflow 3 environment for the analytics department, covering workflow orchestration, PostgreSQL-backed metadata storage, Docker Compose infrastructure, role-based user setup, resource pools for external systems, operational scripts for backup/restore, Adminer access, Airflow Code Editor, and integration readiness for analytical ETL jobs and Superset monitoring. [Course on Stepik](https://stepik.org/course/214389/syllabus) | Apache Airflow, Docker Compose, PostgreSQL, Bash, Adminer, Superset, ETL |
| 🚧 ⏳ (2026)  | DBT  | [Курс по dbt для инженеров и аналитиков данных с нуля до middle+](https://github.com/PavloOps/flights_datamart)  | in progress on [Stepik](https://stepik.org/course/240234/syllabus)...  |
<!--
**PavloOps/PavloOps** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
