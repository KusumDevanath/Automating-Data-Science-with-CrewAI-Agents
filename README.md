# Automating Data Science with CrewAI Agents

## 📌 Project Overview
This project demonstrates how **agentic AI systems** can automate the complete data science lifecycle using **CrewAI**. 
Instead of relying on a single monolithic pipeline or AutoML black box, this system models a real-world data science team 
by assigning specialized responsibilities to multiple AI agents that collaborate autonomously.

The project focuses on **regression-based predictive analytics** and showcases how tasks such as data understanding, 
feature preparation, model training, evaluation, and reporting can be orchestrated with minimal human intervention.

---

## 🎯 Problem Statement
Traditional data science workflows are:
- Manual and time-intensive
- Difficult to scale across datasets and teams
- Prone to human bias and inconsistency
- Hard to reproduce reliably

While AutoML tools exist, they often function as opaque systems with limited interpretability.

**Objective:**  
Design an **intelligent, transparent, and modular multi-agent system** that automates data science workflows while 
maintaining explainability and extensibility.

---

## 🧠 Solution Approach
This project introduces an **AI-powered data science team** built using CrewAI.  
Each agent has:
- A well-defined role
- Explicit responsibilities
- Clear communication pathways

The agents collaborate to simulate how professional data scientists work together in enterprise environments.

---

## 🏗️ System Architecture

### Agent Roles

#### 1. Data Analyst Agent
- Performs exploratory data analysis (EDA)
- Understands feature distributions and correlations
- Identifies potential data quality issues
- Provides insights to downstream agents

#### 2. Machine Learning Engineer Agent
- Selects appropriate regression algorithms
- Trains models using scikit-learn
- Tunes hyperparameters where applicable
- Ensures proper train-test splits

#### 3. Model Evaluation Agent
- Computes evaluation metrics (R², MAE, RMSE)
- Compares multiple models
- Detects overfitting or underfitting
- Validates model reliability

#### 4. Manager / Orchestrator Agent
- Coordinates agent execution order
- Manages task dependencies
- Aggregates results into a final report
- Ensures smooth agent communication

---

## 🔁 Workflow Pipeline

1. **Data Ingestion**
   - Load structured tabular dataset
   - Perform basic validation checks

2. **Exploratory Data Analysis**
   - Feature summaries
   - Distribution analysis
   - Correlation insights

3. **Feature Preparation**
   - Handling missing values
   - Feature selection
   - Data splitting

4. **Model Training**
   - Linear Regression
   - Other regression variants (if applicable)
   - Reproducible experiments

5. **Model Evaluation**
   - Metric-based comparison
   - Performance interpretation

6. **Automated Reporting**
   - Consolidated results
   - Actionable insights

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Agent Framework:** CrewAI  
- **Machine Learning:** scikit-learn  
- **Data Handling:** Pandas, NumPy  
- **Environment:** Jupyter Notebook  

---

## 📊 Models & Evaluation Metrics

### Models Used
- Linear Regression  
- Extensible to Ridge, Lasso, ElasticNet  

### Evaluation Metrics
- R² Score  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  

Metrics are computed and interpreted autonomously by the evaluation agent.

---

## 🚀 Key Highlights

- Demonstrates **agentic AI design principles**
- Automates the full ML pipeline end-to-end
- Highly modular and extensible architecture
- Emphasizes explainability over black-box automation
- Industry-aligned system design

---

## 🧪 Experimental Results
The system successfully:
- Reduced manual intervention in ML workflows
- Ensured consistent evaluation across models
- Produced reproducible and explainable results

This validates the feasibility of **multi-agent AI systems** for real-world data science automation.

---

## 📈 Use Cases

- Enterprise analytics automation
- AutoML platforms with explainability
- AI-assisted data science teams
- Research on agent-based AI systems

---

## 🎓 Academic Relevance
This project demonstrates:
- Strong foundations in machine learning
- Understanding of modern AI paradigms (agentic AI)
- System design and orchestration skills
- Readiness for graduate-level AI research

---

## 📁 Repository Structure
```
├── Automating Data Science with CrewAI Agents.ipynb
├── README.md
└── requirements.txt
```
