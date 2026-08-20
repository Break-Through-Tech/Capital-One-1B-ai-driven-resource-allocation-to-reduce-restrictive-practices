# AI-Driven Resource Allocation to Reduce Restrictive Practices

**Company / Org:** Capital One  
**Challenge Advisor:** Caroline Bell, carolinetentor@gmail.com
**AI Studio Coach:** Shaun Figueiro, shaun.figueiro@breakthroughtech.org                        
**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About Capital One

Capital One is a technology company that aims at changing banking for good. Though Capital One is not specifically related to the task of this project, Capital One is a trailblazer in the technology space, searching for opportunities to leverage AI and data engineering to create its products.

---

## 🎯 The Challenge

### Project Summary
In this project, you will use publicly available school-level data on seclusion incidents, student populations, staffing, and school resources to build a machine learning model that identifies schools with elevated rates of seclusion and helps administrators understand factors associated with these outcomes. This will help organizations and school counties explore data-informed ways to better support schools and reduce the use of restrictive practices.

### Success Criteria
A successful outcome is an interpretable model and simple dashboard that:

- Identifies schools with elevated seclusion rates
- Shows the factors most strongly associated with those outcomes
- Provides administrators with data-informed areas to consider for additional support or resources

The project should emphasize association and decision support, rather than claiming that the model can determine which intervention will directly cause seclusion rates to decrease.

### Stretch Goals
- Intervention Recommendation Tool: Create a simple rule-based or similarity-based tool that suggests potential areas for support based on a school's characteristics and resource gaps.
- LLM Report Generator: Use an LLM or static template system to turn model results into a short, administrator-friendly summary of findings and potential areas for action.
- Computer Vision Exploration: Explore whether publicly available classroom or school-environment images could eventually be used to identify physical features related to accessibility or inclusive design. This is exploratory only and is not required for the core project.
  
### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month | Milestone | Key Activities |
|---|---|---|
| September | Data Exploration & Preparation | Explore the CRDC data, identify relevant seclusion and school resource variables, clean the data, handle missing values, and create features that describe school characteristics and resources. |
| October | Predictive Modeling | Build baseline models and an XGBoost or Random Forest model to identify schools with elevated seclusion rates. Compare models and examine feature importance and model interpretability. |
| November | Evaluation & Decision Support | Evaluate model performance, investigate potential sources of bias, and build a simple dashboard or reporting tool that summarizes school risk and the factors associated with the model's predictions. |
| December | Final Presentation | Finalize the model and dashboard, document limitations and ethical considerations, and prepare a presentation describing findings and potential applications. |

> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset

**Name and Source:** District-level seclusion data and school resource datasets from the Civil Rights Data Collection (CRDC)  
**Format:** CSV
**Size:** Less than 5 GB  
**Location:** https://catalog.data.gov/dataset/civil-rights-data-collection-crdc

### Key Details
- The CRDC is a biennial national dataset covering public schools and districts in the United States. It includes information about student enrollment, school characteristics, educational programs, staffing, discipline, and the experiences of students with disabilities. The data includes information related to restraint and seclusion.
- The project will use a subset of CRDC variables related to seclusion, student populations, staffing, and school resources. Preprocessing will include selecting relevant variables, handling missing or suppressed values, checking for outliers, and constructing school-level features and target variables.
- Known limitations include missing or suppressed values, differences in reporting across schools, and the observational nature of the data. Model results should be interpreted as associations rather than evidence that a particular resource or intervention causes a reduction in seclusion.
- The U.S. Department of Education provides detailed CRDC data-element documentation and questions-and-answers documents for each collection.
- The CRDC also provides specific guidance for reporting restraint and seclusion data, including definitions and examples.

**Primary documentation:** https://www.ed.gov/laws-and-policy/civil-rights-laws/civil-rights-data-collection-crdc/civil-rights-data

---

## 🛠️ Suggested Approach

**ML Problem Type:** Classification / Predictive Modeling / Interpretable Machine Learning

**Recommended Libraries:**
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn
- SHAP (optional)

**Evaluation Metrics:**
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix
- Feature importance / model interpretability

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- https://www.ed.gov/laws-and-policy/civil-rights-laws/civil-rights-data-collection-crdc/civil-rights-data
- https://www.ed.gov/laws-and-policy/civil-rights-laws/civil-rights-data-collection-crdc/civil-rights-data/civil-rights-data-collection-crdc-2020-2021-school-year
- https://crdc.communities.ed.gov/resources/restraint-and-seclusion-rstr-module

**Technical Tutorials:**
- https://scikit-learn.org/stable/supervised_learning.html
- https://xgboost.readthedocs.io/en/stable/python/python_intro.html
- https://scikit-learn.org/stable/modules/model_evaluation.html

**Code Examples:**
- https://scikit-learn.org/stable/auto_examples/index.html
- https://xgboost.readthedocs.io/en/stable/python/examples/index.html

**Other:**
- https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects
- https://github.com/topics/machine-learning

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Official check-ins:** During our biweekly 45-minute AI Studio Lab Section meeting block (2nd and 4th week of every month)

 **Other ways to reach out to me with questions:** 
* Email; please copy your teammates and AI Studio Coach. My email is carolinetentor@gmail.com
* Request a team check-in on Zoom
* Note: I will aim to respond within 48 hours. Please reach out to your AI Studio Coach with urgent questions.

> 💡 **Challenge Advisor: Please update the above based on your availability and preference. If you are not able to answer questions or meet with fellows outside of the biweekly Lab Section check-ins, simply write in "N/A (only available during the official check-in times)"**
> 
---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I’m excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech’s Bridge to Studio - Session C). 
