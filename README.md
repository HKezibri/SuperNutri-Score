# SuperNutri-Score

## Description

SuperNutri-Score is a group academic data science project focused on building a transparent and explainable food evaluation model.

The project combines the official Nutri-Score calculation with a multicriteria decision-making method, ELECTRE TRI, in order to provide a richer and more interpretable food score. The final model also integrates environmental and quality-related criteria such as Green-Score, organic label and additives.

An interactive interface was developed with Gradio to allow users to understand how the final score is calculated and how each criterion impacts the result.

## Project Context

This project was carried out as a group project in the context of the Master MIAGE – Informatique Décisionnelle program at Université Paris Dauphine – PSL.

The objective was to design a transparent algorithmic decision-support model and to make the scoring process understandable for non-expert users.

## Objectives

- Implement the official Nutri-Score algorithm in Python
- Compare calculated scores with OpenFoodFacts data
- Build an explainable multicriteria model using ELECTRE TRI
- Integrate Green-Score, organic label and additives into a final SuperNutri-Score
- Visualize and compare results using charts and confusion matrices
- Develop an interactive interface with Gradio
- Improve transparency and explainability in algorithmic decision-making

## Main Features

- Nutri-Score calculation
- ELECTRE TRI classification
- SuperNutri-Score computation
- Integration of nutritional, environmental and quality criteria
- Comparison between Nutri-Score, ELECTRE TRI and SuperNutri-Score
- Data visualization
- Interactive Gradio interface
- Explanation of the impact of criteria on the final score

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Gradio
- OpenFoodFacts data
- ELECTRE TRI method

## Dataset

The project uses food product data inspired by OpenFoodFacts, including nutritional information and additional criteria such as:

- Energy
- Sugars
- Saturated fat
- Sodium
- Proteins
- Fibers
- Fruits / vegetables / nuts percentage
- Additives
- Green-Score
- Organic label

The dataset used in the project focuses mainly on food products from the sauces category.

## Methodology

1. Data collection and preparation
2. Implementation of the official Nutri-Score algorithm
3. Validation of calculated Nutri-Score results using OpenFoodFacts labels
4. Definition of criteria for the ELECTRE TRI model
5. Construction of category profiles and criteria weights
6. Implementation of pessimistic and optimistic ELECTRE TRI classifications
7. Comparison of Nutri-Score, ELECTRE TRI and SuperNutri-Score results
8. Visualization of results using distributions, heatmaps and confusion matrices
9. Development of an interactive Gradio interface

## ELECTRE TRI Approach

ELECTRE TRI is a multicriteria decision-making method used to assign alternatives to ordered categories.

In this project, each food product is evaluated according to several criteria. Some criteria are minimized, such as energy, sugars, saturated fat, sodium and additives. Others are maximized, such as proteins, fibers and fruits/vegetables percentage.

The method helps reduce excessive compensation between criteria and makes the decision process more transparent.

## SuperNutri-Score

The final SuperNutri-Score combines:

- ELECTRE TRI classification
- Green-Score
- Organic label
- Additives
- Nutritional criteria from the Nutri-Score

The goal is to provide a more complete and explainable food evaluation than the classic Nutri-Score.

## Visualizations

Several visualizations were created to analyze and compare the results:

- Nutri-Score distributions
- Confusion matrices
- ELECTRE TRI category distributions
- Heatmaps comparing Nutri-Score and SuperNutri-Score
- Concordance analysis between models

## Interactive Interface

A Gradio interface was developed to allow users to:

- Enter nutritional and environmental values
- Calculate the Nutri-Score
- Calculate ELECTRE TRI classifications
- Calculate the final SuperNutri-Score
- Understand how each criterion affects the final result
- Modify input values and observe the impact on the score
