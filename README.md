# Customer Support AI Agent: EDA & Foundation for Intelligent Automation

This repository explores how **AI-powered automation** can transform customer support by reducing backlog, improving SLA compliance, and enhancing customer satisfaction.  
The project uses the [Kaggle Customer Support Ticket Dataset](https://www.kaggle.com/datasets/suraj520/customer-support-ticket-dataset) as the foundation.

---

## Project Overview
Customer support centers face high volumes of tickets, uneven SLA compliance, and inconsistent priority handling. This project aims to demonstrate how **data-driven insights and AI agents** can tackle these challenges by:
- Classifying ticket types
- Monitoring SLA performance
- Automating responses with **RAG-powered agents**
- Suggesting actions to support managers

---

## EDA Findings
The initial Exploratory Data Analysis (EDA) on **8,469 tickets** revealed:

- **Balanced demand:** Issues spread across refunds, technical, cancellations, product, and billing inquiries.  
- **Backlog challenge:** Over half of tickets remain unresolved or pending.  
- **Resolution times:** Typically **7–8 hours**, with billing resolved fastest and cancellations/refunds slower.  
- **Priority handling gaps:** Medium priority tickets resolved fastest, high priority the slowest.  
- **Channel performance:** Phone & chat faster, email & social media slower — a risk to brand reputation.  
- **Customer satisfaction:** Very slow resolutions linked to poor ratings, though satisfaction depends on more than speed.  
- **Work patterns:** Responses and resolutions align to business hours, leaving off-hours unmet.

---

## Next Phase: AI Support Agent
Building on EDA insights, the project will develop a **multi-agent system**:
- **Classifier Agent:** Predict ticket type.  
- **Analytics Agent:** Monitor backlog, SLA trends, and escalation needs.  
- **Suggestion Agent:** Recommend operational improvements.  
- **RAG-powered Agent:** Provide automated, knowledge-base driven responses with escalation when confidence is low.  

These agents will leverage the cleaned dataset and embeddings (via FAISS or similar) to ensure accurate and trustworthy support.

---

## Tech Stack
- **Python**: Pandas, NumPy, Seaborn, Matplotlib  
- **NLP/ML**: scikit-learn, embeddings, FAISS  
- **Visualization**: Matplotlib, Seaborn (EDA), Streamlit/Power BI (dashboard)  
- **Future AI**: RAG pipelines, self-learning loop for feedback  

---

## Business Impact
- **Reduce backlog** by automating repetitive cases  
- **Improve SLA compliance** for critical tickets  
- **Boost customer satisfaction** by faster resolutions  
- **Inform product strategy** via analytics of common issues  

---

## References
- Kaggle Dataset: [Customer Support Ticket Dataset](https://www.kaggle.com/datasets/suraj520/customer-support-ticket-dataset)  
- Agresti, Alan. *Categorical Data Analysis, 3rd Edition*. 2013  
- Charpentier, Arthur. *Computational Actuarial Science with R*. 2014  

---

## Next Steps
- Train ticket classification models (LogReg, RF, XGBoost)  
- Build multi-agent AI pipeline  
- Integrate RAG for knowledge-based responses  
- Deploy interactive dashboard (Streamlit/Power BI)  
