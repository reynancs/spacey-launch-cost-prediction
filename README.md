# 🚀 spacey-launch-cost-prediction

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/landing_1.gif)


## 📘 Project Overview

The commercial space era has arrived — private companies are making space travel more accessible than ever. As the space industry becomes more competitive, a new player, **SpaceY**, aims to challenge giants like SpaceX.

This capstone project places you in the role of a **Data Scientist** at SpaceY, a startup aerospace company founded to compete with SpaceX (created by the fictional Allon Musk). Your mission is to analyze launch data, understand the cost drivers behind rocket launches, and build predictive models using publicly available SpaceX data.

## 🛰 Objectives

- 🧮 **Estimate the cost of rocket launches**, particularly those involving the Falcon 9.
- 📊 **Build interactive dashboards** to support decision-making within your team.
- 🔍 **Predict whether the Falcon 9 first stage will be reused**, based on mission and payload parameters.
- 🤖 **Apply machine learning models** to classify the outcome of the first-stage recovery (landed or not landed).

## 💡 Context

SpaceX has significantly reduced the cost of launching spacecraft (approx. $62M vs. competitors at $165M+). A key factor is the **reusability of the Falcon 9's first stage**, which is responsible for the majority of the lift and cost.

However, not every mission results in a successful recovery:
- Some first stages crash or are intentionally sacrificed.
- Recovery depends on mission parameters such as payload weight, orbit type, and customer requirements.

## 🔬 Technical Focus

You will:
- Collect and analyze public SpaceX launch data.
- Visualize trends using dashboard tools (Plotly).
- Train ML models (logistic regression, SVM, decision trees, KNN) to predict first-stage reuse.

## 📦 Project Deliverables

- Cleaned dataset from public SpaceX launch data.
- Machine learning model to predict reuse of the first stage.
- Cost estimation model for launch prediction.
- Dashboards for stakeholder insights.

## 🎯 Success Criteria

- Accurate predictions of first stage recovery status.
- Insightful dashboards that help guide business decisions.
- A structured, well-documented data science workflow.

## 📁 File Structure (Recommended)

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         src and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── src   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes src a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

---


## 📚 References

- [SpaceX Launch Archive](https://www.spacex.com/launches/)
- Infographics by Forest Katsch (zlsadesign.com)

---

Ready for liftoff? Let’s build the future of affordable spaceflight. 🌌
