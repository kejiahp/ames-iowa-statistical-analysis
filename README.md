# Ames Iowa Statistical Analysis

Pre-processing, exploration (EDA) and statistical analysis of the Ames Iowa Housing Dataset. This notebook was created in fulfilment of course work 1 for the module details listed below:

- Module Code: CS4S767
- Module Title: Data Mining
- Submission Date: 17th November 2025
- Return Date: 19th January 2026
- Module/Leader: Ieuan Griffiths
- Student Name: Morenikeji Elijah Popoola

# Assessment Description

The work for this assessment can be broken down into 5 sections, each worth a percentage of your overall grade from this assessment. It is required that you use the Python Programming Language for this assessment. The Dataset Information and data file is available in the "AmesHousing.csv" file within the `data` directory.

## Dataset Information

Within the provided dataset, each row represents a single house sale, with the sale price as the target variable. The dataset includes property characteristics such as lot size, living area, quality ratings, neighbourhood, and building style. For each house, is the documented sale price of that
house.

More information on the variables within the dataset, an official documentation PDF has been
attached in the "Ames Data Documentation.txt" file within the `data` directory.

The tasks required to complete are provided below in this assessment brief.

---

## Pre-Processing & EDA (10%):

The following tasks should be undertaken as a part of your Exploratory Data Analysis:

- Reading and Manipulating the dataset using the Python Programming Language.

- Preliminary Investigation of the dataset.

- Provide suitable discussion for your preliminary analysis and your findings.

---

## Statistical Analysis (30%):

Using the Provided Dataset (with any additional pre-processing you may have conducted as part in Task 1), produce statistical analyses using the methods discussed during this module.

- You should create three different statistical tests\*

  - State clearly the hypothesis required for each statistical test.

  - The test/methods used to conduct the test.

  - Check the assumptions associated with the conducted test, validating the assumptions hold where required.

  - Provide the conclusion of the statistical test relating to the hypothesis, based on the p-value.

  - Provide some suitable discussion for the meaning of the findings from the statistical
    test.

\* _each statistical test, should test a different hypothesis. For example, three tests which “compare a
variable to a hypothetical value” is the same hypothesis, regardless of whether or not they use
different variables/data. This is the same type of statistical test and will only be counted once._ \*

---

## Data Visualization (30%):

In support of your Statistical Analysis, you should look to produce visualizations that provide meaningful insight into each of the statistical test you’ve conducted, providing additional evidence for hypothesis you’ve investigated.

- You should provide three visualizations plots, one for each statical test you’ve completed.

  The plots should be appropriate for the statistical test & data you’ve used.

  - Briefly outline the purpose of the chosen visualization within the investigation.

  - Include clearly defined axis labels & titles for your visualization.

  - Provide an information discussion of the findings from each visualization and how they support (or don’t support) the findings of your statistical analysis.

## Linear Regression (20%):

Utilising only the listed feature provided below as input, build a Multiple Linear Regression model capable of modelling the sales price of a house. Ensuring you follow the correct statistical procedures.

In addition, answer the following questions:

- Which (if any) of the provided features were unimportant within the model? Explain the process for identifying this.

- What variable contributed was the most important/ contributed the most to the predictive power of your model? Explain the process for identifying this.

Features to use in the model (see Dataset section for more information on these features):

- `GrLivArea`
- `OverallQual`
- `GarageCars`
- `LotArea`
- `Neighborhood`
- `HouseStyle`
- `CentralAir`
