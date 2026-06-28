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

Nneka Asuzu

Data Scientist applying machine learning, statistical analysis, and data visualization to solve business problems and support data-driven decision-making.


<a href="/assets/docs/Nneka_Asuzu_resume.pdf" target="_blank" rel="noopener noreferrer" class="btn">
  📄 View Resume (PDF)
</a>

---

## About Me

I apply machine learning and statistical techniques to uncover patterns in data and translate analytical findings into actionable business insights.

My work includes exploratory data analysis, data preparation, feature engineering, model development, evaluation, and communicating insights through dashboards and visualizations to support business decision-making.


---


## Core Focus Areas

- **Machine Learning:** Supervised (classification, regression) and unsupervised learning (clustering, dimensionality reduction) using linear and tree-based models.
- **Applied Machine Learning:** Data preprocessing, feature engineering, model training, hyperparameter tuning, and model evaluation.
- **Statistical & Analytical Methods:** Exploratory data analysis, descriptive statistics, hypothesis testing, A/B testing.
- **Data Visualization & BI:** Dashboard development and insights communication using Power BI, Tableau, and Plotly.
- **Tools & Platforms:** Python, SQL, Git, Jupyter Notebook, Azure Machine Learning, AWS (project exposure), Power BI.
---

## Achievements & Impact

- Improved model performance over baseline through feature engineering and hyperparameter tuning across multiple projects.
- Built machine learning models that supported data-driven business decisions across multiple analytical projects.
- Designed dashboards that reduced reporting and analysis time by up to 30%, improving decision-making efficiency.
- Developed reusable analytical workflows that improved consistency and efficiency of data analysis.

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

- <a href="https://github.com/NnekaAsuzu/credit_risk_loan_default_prediction" target="_blank" rel="noopener noreferrer"><b>Credit Risk Prediction</b></a> – Classification (Logistic Regression → Random Forest → XGBoost), SHAP Model Explainability, Azure ML, Power BI  
- <a href="https://github.com/NnekaAsuzu/supply_chain_risk_prediction" target="_blank" rel="noopener noreferrer"><b>Supply Chain Risk & Inventory Optimization</b></a> – Classification (Logistic Regression → XGBoost → AutoML benchmarking), Azure ML, Power BI  
- <a href="https://github.com/NnekaAsuzu/customer_value_lifecycle_modeling" target="_blank" rel="noopener noreferrer"><b>Customer Value & Lifecycle Modeling</b></a> – Clustering (K-Means + PCA), Regression (XGBoost for CLV), A/B Testing, Streamlit  
- <a href="https://github.com/NnekaAsuzu/healthcare_workforce_optimization" target="_blank" rel="noopener noreferrer"><b>Healthcare Workforce Analytics</b></a> – Regression and Random Forest models for healthcare demand prediction and staffing analysis.


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