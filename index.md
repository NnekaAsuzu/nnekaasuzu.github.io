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

  /* Featured Projects button styling */
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
I apply machine learning and data visualization to help organizations turn raw data into clear, actionable insight.

[📄 Download Resume (PDF)](/assets/docs/Nneka_Asuzu_resume.pdf){: .btn }

---

## About Me

I love transforming complex data into solutions that solve real problems.  
My work spans:

- Building AI & ML models that drive operational and business decisions  
- Designing interactive dashboards for real-time insight  
- Implementing scalable, cloud-based pipelines with Python, SQL, and Azure  

I believe that **data becomes powerful only when it leads to measurable outcomes**.  
I’m always learning, improving, and asking: *How can we make this better?*

---

## How I Work

I thrive on uncovering insights from complex datasets, validating ideas through evidence-driven analysis, and designing solutions that are both technically sound and practical to use.

I am passionate about making data science accessible, impactful, and results-focused, balancing technical rigor with real-world usability.

---

## Core Focus Areas

### Key Skills
- **Machine Learning & Modeling:** XGBoost, Random Forest, Linear & Logistic Regression, Time-Series Forecasting  
- **Data Visualization:** Power BI, Tableau, Plotly Dash  
- **Automation & MLOps:** Python & SQL pipelines, Azure ML, MLflow  
- **Analytics & Statistics:** A/B Testing, Hypothesis Testing, Monte Carlo Simulation  
- **Tools & Platforms:** GitHub, Jupyter Notebook, VS Code, Azure  

---

## Achievements & Impact
- Built ML models achieving **92% accuracy** on predictive tasks  
- Designed dashboards that reduced reporting time by **70%**  
- Delivered scalable cloud solutions for analytics workloads  
- Automated pipelines to increase reliability and efficiency  

---

## Soft Skills
- **Communication:** Explain complex ideas clearly to non-technical teams  
- **Problem-Solving:** Create practical, data-driven solutions  
- **Adaptability:** Quickly learn new tools and methodologies  
- **Collaboration:** Work effectively across cross-functional teams

  </div> <!-- closes content-block -->
</div> <!-- closes flex container -->

<!-- Featured Projects -->
<div class="featured-projects">

## Featured Projects
<hr style="border: 1px solid #ccc; margin-top: 5px; margin-bottom: 10px;">

- **<a href="https://github.com/NnekaAsuzu/Credit_Risk_Prediction" target="_blank">Credit Risk Prediction Model</a>** – XGBoost & Random Forest, Azure ML, Power BI  
- **<a href="https://github.com/NnekaAsuzu/Healthcare_Resource_Forecasting" target="_blank">Healthcare Resource Forecasting</a>** – ARIMA, Monte Carlo, Plotly Dash  
- **<a href="https://github.com/NnekaAsuzu/Operations_Efficiency_Dashboard" target="_blank">Operations Efficiency Dashboard</a>** – SQL & Python automation, Power BI  

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
