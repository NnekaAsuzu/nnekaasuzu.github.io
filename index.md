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

I’m **Nneka Asuzu**, a Data Scientist specializing in predictive modeling, advanced analytics, and cloud-enabled solutions.  
I build machine learning models and dashboards that turn complex data into actionable insights at scale.

[📄 Download Resume (PDF)](/assets/docs/Nneka_Asuzu_resume.pdf){: .btn }

---

## About Me

I transform complex data into actionable solutions that solve real-world problems.  
My work spans:

- Building AI & ML models that guide operational and business decisions
- Designing interactive dashboards for real-time insight  
- Implementing scalable, cloud-based pipelines with Python, SQL, and Azure  

I believe that **data is only powerful when it drives measurable outcomes**.  
I’m constantly learning, iterating, and asking: *How can we make this better?*

---


## How I Work

- Build and evaluate predictive and analytical models to solve real-world problems  
- Apply statistical analysis and machine learning to generate actionable insights  
- Cover end-to-end data science: cleaning, feature engineering, model selection, evaluation, and deployment

---

## Core Focus Areas

- **Machine Learning & Predictive Modeling:** XGBoost, Random Forest, Linear & Logistic Regression, Time-Series Forecasting (ARIMA, Prophet)  
- **Data Visualization & Business Intelligence:** Power BI, Tableau, Plotly Dash  
- **Automation & MLOps:** Python & SQL pipelines, Azure ML, MLflow  
- **Analytics & Statistical Methods:** A/B Testing, Hypothesis Testing, Monte Carlo Simulation  
- **Tools & Platforms:** GitHub, Jupyter Notebook, VS Code, Azure

---

## Achievements & Impact

- Built ML models achieving **high predictive accuracy** on multiple projects.  
- Designed dashboards that reduced reporting and analysis time by **30%**.  
- Delivered scalable cloud solutions for analytics workloads.  
- Automated pipelines to increase reliability and efficiency.

---

## Soft Skills

- **Communication:** Explain data insights clearly to non-technical stakeholders. 
- **Problem-Solving:** Deliver practical, data-driven solutions.
- **Adaptability:** Quickly learn and apply new tools and methods.  
- **Collaboration:** Work effectively across cross-functional teams on end-to-end projects.


</div> <!-- closes main content block -->

</div> <!-- closes flex container -->


<!-- Featured Projects -->
<div class="featured-projects" markdown="1" style="width: 100%;">

## Featured Projects
<hr style="border: 1px solid #ccc; margin-top: 5px; margin-bottom: 10px;">

- **[Credit Risk Prediction Model](https://github.com/NnekaAsuzu/Credit_Risk_Prediction)** – XGBoost & Random Forest, Azure ML, Power BI  
- **[Healthcare Resource Forecasting](https://github.com/NnekaAsuzu/Healthcare_Resource_Forecasting)** – ARIMA, Monte Carlo, Plotly Dash  
- **[Operations Efficiency Dashboard](https://github.com/NnekaAsuzu/Operations_Efficiency_Dashboard)** – SQL & Python automation, Power BI  

<div style="margin-top: 10px; text-align: center;">
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

</div>




