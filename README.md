
# Principles of Data Science Project

## Overview

This project explores critical public health questions using extensive survey data, focusing on disparities and behavioral outcomes among sexual minority youth in the United States. The analysis centers on the 2023 Youth Risk Behavior Surveillance System (YRBSS) dataset, which for the first time includes questions on transgender identity alongside other sexual orientation metrics.

Motivated by personal experience and scholarly interest, the project investigates differences between sexual minority and majority youth in areas including bullying, substance use, mental health, and victimization. The ultimate goal is to identify risk factors influencing adverse health outcomes while carefully addressing potential biases and confounding variables.

---

## Research Questions

- Are LGBT students bullied more frequently than their heterosexual peers?
- Are sexual minority youth more prone to substance abuse, including illicit drugs and prescription opioids?
- How does sexual identity associate with mental health outcomes such as suicidal ideation, suicide attempts, and feelings of hopelessness?
- What role do experiences such as bullying, parental abuse, and discrimination play in shaping these health behaviors and outcomes?
- Can predictive models identify key factors mediating these disparities?

---

## Dataset Description

- **Source:** 2023 Youth Risk Behavior Surveillance System (YRBSS)
- **Population:** U.S. adolescents (ages ~13-17) in grades 9-12 from a representative sample of public, private, and Catholic schools.
- **Sample Size:** Approximately 20,103 usable questionnaires after rigorous data cleaning.
- **Variables:** Over 117 comprehensive variables covering demographics, health risk behaviors, mental health, bullying experiences, substance use, sexual activity, and victimization.
- **Unique Data:** First inclusion of transgender identity data in the survey, along with detailed sexual identity questions.

---

## Methodology

- **Data Cleaning:** Handling missingness through stratification, matching, and replication strategies. Differentiating between missing completely at random (MCAR), missing at random (MAR), and missing not at random (MNAR).
- **Feature Engineering:** Creating composite sexual minority variables from sexual identity and sexual contact data.
- **Statistical Analysis:** Comparing behavioral and experiential differences between groups while controlling for confounding factors like age, sex, and parental environment.
- **Predictive Modeling:** Using mental health outcomes as key dependent variables, assessing the predictive power of bullying and substance use patterns.
- **Visualization:** Comprehensive exploratory data analysis including distribution plots, correlation matrices, and subgroup comparisons to detect patterns and paradoxes like Simpson’s paradox.

---

## Initial Findings & Hypotheses

- Sexual minority youth report higher rates of bullying (both in-person and electronic), substance use, and mental health challenges compared to heterosexual peers.
- Experiences of discrimination and victimization mediate the higher risk for suicidal ideation and attempts among LGBT youth.
- Certain parental and social factors (such as family dysfunction and unstable housing) exacerbate these disparities.
- The dataset is largely free of duplicates and outliers, with a key challenge being the treatment of missing and sensitive data.

---

## Project Structure

- **Data Preparation:** Code notebooks and scripts for cleaning and feature engineering.
- **Exploratory Analysis:** Visualization scripts and reports.
- **Modeling:** Statistical and predictive models with validation.
- **Documentation:** Detailed codebook/explanation of variables and analytical choices.

---

## Usage

This repository contains Jupyter notebooks and scripts to replicate the analysis. Key dependencies include pandas, numpy, matplotlib, and statistical libraries for modeling.

---

## Future Work

- Refine models for causal inference and bias mitigation.
- Expand analysis by integrating additional datasets.
- Explore intersectionality, including race/ethnicity and gender identity interactions.
- Develop an interactive dashboard for stakeholders to explore findings.

---

## Contact

For questions or collaborations, please contact:  
Anupama Sharma  
Email: sharma25@umd.edu  
LinkedIn: https://linkedin.com/in/anupama-sharma22

---

*This project is ongoing and will be updated as I complete my course*
