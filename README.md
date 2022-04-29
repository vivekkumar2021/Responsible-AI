# Responsible AI

## Introduction

In the real world, Data Science teams often face the major challenge of evaluating and testing a model's performance. We all must have gone through claims such as "Model ABC is 92% on a given benchmark". But, what does this mean in terms of practical usage? 


Let me tell you the ground reality, all teams are well acquainted with the fact that model performance may not be similar across subgroups of the data. This "may" could cause a lack of trust in machine learning altogether as model failures have direct consequences related to lack of safety, unfairness and reliability. 


Imagine a traffic sign detector which is unable to operate well in certain daylight conditions or any other unexpected inputs. The overall accuracy of the model is still high, however, it is still crucial for the developers to know about this fact and that the model could not be blindly trusted in such situations. To rectify such problems, practitioners often have to create custom infrastructure, which is tedious and time-consuming. 

To resolve this issue, we have Responsible AI. It is a single glass pane bringing together several mature Responsible AI tools in the areas of machine learning interpretability, unfairness assessment and mitigation, error analysis, causal inference, and counterfactual analysis for a holistic assessment and debugging of models and making informed business decisions. 

## Usage
We will assess income level predictions on the adult census dataset where the target variable is "income". 

* **Step 1:** Import all the required libraries and define split and clean data pipelines. 
* **Step 2:** Load the dataset and classify different types of features.
* **Step 3:** Create Model and Data Insights.
* **Step 4:** Create a Responsible AI Dashboard.



