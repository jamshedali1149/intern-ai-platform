# Intern Management AI Platform — Project Charter

## Vision
A single AI-powered platform that predicts intern performance, understands intern sentiment,
recommends learning paths, generates interview questions, identifies skill gaps, and answers
queries via a chatbot — all served through one unified API.

## Project-to-Paradigm Mapping

| # | Project | ML Paradigm | Core Technique | Business Goal |
|---|---------|-------------|-----------------|----------------|
| 1 | Performance Prediction | Supervised Learning (Regression) | Tree-based models (Random Forest / XGBoost) | Flag at-risk interns early, reduce attrition cost |
| 2 | Sentiment Classification | Supervised Learning (Classification) | NLP text classification | Understand how interns actually feel from feedback |
| 3 | Recommendation System | Unsupervised Learning | Matrix Factorization | Recommend relevant courses/tasks to interns |
| 4 | Interview Question Generator | Generative AI / LLMs | Prompt-based generation | Auto-generate relevant interview questions |
| 5 | Skill Gap Clustering | Unsupervised Learning (Clustering) | K-Means / similar | Group interns by skill gaps for targeted training |
| 6 | HR Chatbot | Generative AI / Conversational AI | LLM-based chatbot | Instantly answer HR/intern queries |

## Development Order (per Book Roadmap)
Simplest algorithms (trees) → Text/NLP → Similarity-based systems (clustering, recommenders)
→ Generative models (LLMs, chatbots) → Unified API deployment.

## Tech Stack
- **Environment:** Anaconda / Miniconda (`hrml` env, Python 3.10+)
- **Experimentation:** Jupyter Notebook / JupyterLab, Google Colab (GPU for LLM chapters)
- **Development:** VS Code
- **Version Control:** Git & GitHub
- **Core Libraries:** numpy, pandas, scikit-learn, matplotlib, seaborn, xgboost
