# Clinical Trial Site Selection: Applying Data Science Methodology

**Course:** Data Science Methodology (IBM / Coursera), final assignment, submitted January 2, 2024
**Course grade:** 97%
**Methods:** IBM Foundational Data Science Methodology (Rollins) / CRISP-DM

## Why this project
For this assignment I chose a problem from my own field. Pharmaceutical sponsors regularly need to find investigative sites that can actually enroll the patients a trial needs. The exercise was to frame that problem as a question data can answer and to lay out each stage of the analysis.

## The business problem
A pharmaceutical company's patient recruitment department wants to improve enrollment from the New York Tristate area for a new clinical trial of a medication intended to treat cardiac disease. The objective is to identify hospitals in the Tristate area that have taken part in similar trials and may therefore have the cardiovascular patient population the trial requires.

**The data question:**
> *"Can we automatically determine which hospitals in the NY Tristate have the trial specific cardiovascular patient population to enroll in the upcoming cardiovascular drug clinical research trial?"*

## Analysis plan by methodology stage

| Stage | Plan |
|---|---|
| **Analytic approach** | Descriptive analytics. Acquire structured data on each research center: location, studies, study indication, patient population and study status. |
| **Data requirements** | Previous and ongoing cardiovascular trials from public registries such as clinicaltrials.gov and nih.gov. Check that the raw data includes actual research institutions, their locations and the needed study details. |
| **Data collection** | Compile the dataset by web scraping into a structured table (CSV). Clean it, then use visualizations to check data quantity and quality, find gaps, and identify the most useful fields. |
| **Data understanding & preparation** | Filter step by step: (1) centers in the NY Tristate area → (2) centers that are hospitals → (3) hospitals with past or current cardiovascular trials and enrollment greater than 10 patients. |
| **Modeling & evaluation** | Descriptive models: pivot tables to summarize which hospitals run cardiovascular trials, a map of qualifying hospital sites, and histograms of the potential patient populations at each site. |

## What this demonstrates
- Turning a real operational need into a precise question data can answer
- Defining what data is required before collecting any
- Building data-quality checks into collection and preparation
- Choosing descriptive outputs (summaries, maps, distributions) that a recruitment team can act on

## My submitted answers (verbatim)

**Topic chosen:** "I chose the topic of hospitals to apply the data science methodology."

**Business understanding:**
> The patient recruitment department at a pharmaceutical company would like to improve the recruitment of patients from the NY Tristate area to participate in a new clinical trial involving their new medication intended to treat cardiac disease.
>
> The objective is to identify hospitals in the NY Tristate that participated in similar trials and therefore may have the cardiac patient population required for the trial researching their new drug.
>
> The problem is as follows: "Can we automatically determine which hospitals in the NY Tristate have the trial specific cardiovascular patient population to enroll in the upcoming cardiovascular drug clinical research trial?

**Analytic approach:**
> The goal is to acquire structured data that will contain each research center, its location, the studies they are participating in, the study indication, patient population and study status.
>
> The descriptive analytic approach will be employed to determine which research centers are hospitals and their respective locations, previous/current studies, patient enrollment information and study indications.

**Data requirements:**
> Web scraping several websites will be used to identify previous and currently ongoing cardiovascular clinical trials. Sites such as clinicaltrials.gov and www.nih.gov lists clinical studies.
>
> This initial raw data will be assessed to ensure that actual research institutions are included along with their respective location and appropriate study information as noted in the approach.

**Data collection:**
> The initial data set will be compiled from the web-scraping exercise from websites mentioned above and placed in a structured tabular from from the CVS file.
>
> Data cleaning will be performed in preparation for assessment of the quantity and quality of the data.
>
> Visualization techniques will be applied to assess the data for any gaps and also to determine the most useful aspects for further examination and consideration in preparation for analysis.

**Data understanding and preparation:**
> The list of research centers will be reduced to only show those that are located in the NY Tristate area. Once reduced, it will be filtered again to only list the centers that are hospitals. It will be filtered again to only show hospitals that have or are participating in cardiovascular trials and have enrolled a patient population greater than 10.
>
> Visualizations and descriptive statistics will be applied to depict the locations of target hospital research centers in the NY Tristate area.

**Modeling and evaluation:**
> In this case, pivot tables will be employed to create models that address the question of determining which hospitals in the NY Tristate area conducts cardiovascular clinical trials.
>
> The outcome models will be descriptive. Map charts and histograms will be models that visualize the hospital study site locations. Histograms will show the relevant potential patient populations that are associated with each hospital research site.

---
*Scope note: this is a methodology design exercise. No data was collected or analyzed for this assignment.*
