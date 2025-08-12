# ML/AI Engineering for Policy Research 

> Part of the **Massachusetts Education ML Analysis Suite** 
> 
> 🏠 [View Full Portfolio](https://rosalinatorres888.github.io) | 
> 📊 [Core Analysis](https://github.com/rosalinatorres888/ma-education-policy-analysis) | 
> 🔬 [Feature Engineering](https://github.com/rosalinatorres888/feature-engineering-dashboard) | 
> 📈 [ML Presentation](https://github.com/rosalinatorres888/ml-education-presentation)
>
> ![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![ML](https://img.shields.io/badge/ML-Scikit--learn-orange.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 🎯 Project Components

| Component | Description | Technologies | Live Demo |
|-----------|-------------|--------------|-----------|
| [Policy Dashboard](https://rosalinatorres888.github.io/ma-education-policy-analysis/) | Interactive education metrics visualization | D3.js, Plotly | ✅ |
| [Feature Engineering Lab](https://rosalinatorres888.github.io/feature-engineering-dashboard/) | ML feature analysis with SHAP | Python, SHAP, scikit-learn | ✅ |
| [Executive Presentation](https://rosalinatorres888.github.io/ml-education-presentation/) | ML-driven policy recommendations | Reveal.js | ✅ |
| [Model API](docs/api.md) | RESTful prediction service | Flask, Docker | 🚧 |
| [MLflow Tracking](docs/mlflow.md) | Experiment tracking & model registry | MLflow | 🚧 |

## 🏗️ Architecture

```mermaid
graph LR
    A[Raw Data] --> B[Feature Engineering]
    B --> C[Model Training]
    C --> D[Model Evaluation]
    D --> E[SHAP Analysis]
    E --> F[Policy Recommendations]
    F --> G[Interactive Dashboard]
