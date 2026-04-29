---
layout: default
permalink: /
---

<style>
  /* Make all h2 headings bold */
  h2 {
    font-weight: bold;
  }

  /* Reduce spacing for h1, h2, h3 */
  .content-block h1,
  .content-block h2,
  .content-block h3 {
    margin-top: 1em;   
    margin-bottom: 0.5em; 
  }

  /* Tighter paragraph spacing */
  .content-block p,
  .content-block ul {
    margin-bottom: 0.6em; 
  }

  /* Reduce hr spacing */
  .content-block hr {
    margin: 1.5em 0;  
  }

  /* Featured Projects container spacing */
  .featured-projects {
    margin-top: 10px;  /* smaller gap from previous content */
    margin-bottom: 20px; /* space before footer */
    background-color: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 20px;
  }

  /* Image styling for bigger photo */
  .profile-pic {
    width: 100%;
    max-width: 480px;  
    object-fit: cover;
    border-radius: 50%;
  }

  /* Tighten spacing for View All Projects button */
  .featured-projects a.btn {
    display: inline-block;
    margin-top: 5px;
  }
</style>

<div style="display: flex; align-items: flex-start; gap: 40px; flex-wrap: wrap;">

  <!-- Left: Picture -->
  <div style="flex: 1.3; min-width: 300px;">
    <img src="/assets/images/nneka.jpg" alt="Nneka Asuzu" class="profile-pic">
  </div>

  <!-- Right: Main Content -->
  <div class="content-block" style="flex: 2; min-width: 260px;" markdown="1">

# Welcome!

I’m Nneka Asuzu, a Data Scientist focused on building machine learning models and end-to-end data-driven systems that support real-world decision-making.


<a href="/assets/docs/Nneka_Asuzu_resume.pdf" target="_blank" rel="noopener noreferrer" class="btn">
  📄 View Resume (PDF)
</a>

---

## About Me

I build machine learning models that uncover patterns in data and translate them into actionable insights.

My work spans the full data science lifecycle from data preparation and feature engineering to model evaluation and deployment, ensuring solutions are practical, scalable, and decision-oriented.


---


## Core Focus Areas

- **Machine Learning:** Supervised (classification, regression) and unsupervised learning (clustering, dimensionality reduction) using linear models, tree-based models, and SVMs.
- **Model Deployment & ML Systems:** End-to-end machine learning workflows, including model deployment to cloud and production environments.
- **Data Analytics & Statistical Methods:** Exploratory data analysis, hypothesis testing, A/B testing, and time series forecasting.
- **Data Visualization & BI:** Power BI, Tableau, and Plotly Dash.
- **Tools & Platforms:** Python, SQL, Git, Jupyter Notebook, Azure ML, Azure SQL, Power BI.

---

## Achievements & Impact

- Improved model performance over baseline through feature engineering and hyperparameter tuning across multiple projects.
- Built and deployed machine learning models to support real-world decision-making.
- Designed dashboards that reduced reporting and analysis time by up to 30%, improving decision-making efficiency.
- Automated data workflows to improve consistency, reduce manual effort, and enhance data reliability.


---

## Soft Skills
- **Communication:** Translate machine learning results into clear, actionable insights for decision-making.
- **Problem-solving:** Apply structured, data-driven thinking to solve business problems.
- **Adaptability:** Quickly learn and apply new tools, models, and techniques across projects.
- **Collaboration:** Work effectively with cross-functional teams to deliver data science solutions.


</div> <!-- closes main content block -->

</div> <!-- closes flex container -->

<!-- Featured Projects -->
<div class="featured-projects" markdown="1" style="width: 100%; max-width: 1300px; margin: 0 auto;">

## Featured Projects
<hr style="border: 1px solid #ccc; margin-top: 5px; margin-bottom: 10px;">

- <a href="https://github.com/NnekaAsuzu/credit_risk_loan_default_prediction" target="_blank" rel="noopener noreferrer"><b>Credit Risk Prediction System</b></a> – Classification (Logistic Regression → Random Forest → XGBoost), SHAP Explainability, Azure ML, Power BI  
- <a href="https://github.com/NnekaAsuzu/supply_chain_risk_prediction" target="_blank" rel="noopener noreferrer"><b>Supply Chain Risk & Inventory Optimization</b></a> – Classification (Logistic Regression → XGBoost → AutoML benchmarking), Azure ML, Power BI  
- <a href="https://github.com/NnekaAsuzu/customer_value_lifecycle_modeling" target="_blank" rel="noopener noreferrer"><b>Customer Value & Lifecycle Modeling</b></a> – Clustering (K-Means + PCA), Regression (XGBoost for CLV), A/B Testing, Streamlit  
- <a href="https://github.com/NnekaAsuzu/healthcare_workforce_optimization" target="_blank" rel="noopener noreferrer"><b>Healthcare Workforce Optimization</b></a> – Regression and Random Forest models for demand prediction, scenario simulation, and workforce planning under uncertainty  

</div>

<!-- View All Projects Button -->
<div style="margin-top: 20px; text-align: center;">
  <a href="/projects" style="
      display: inline-block;
      padding: 10px 40px;
      background-color: #007acc;
      color: white;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
      min-width: 250px;
  ">View All Projects →</a>
</div>