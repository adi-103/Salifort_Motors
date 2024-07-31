# Salifort_Motors

## Overview

This project was completed as part of the Google Advanced Data Analytics Capstone project. The capstone project is comprehensive because it requires skills and knowledge developed across the whole program, including:

- Python
- EDA
- Data visualization
- Stats
- Modeling
- PACE

## Project Description

In this project, you’ll take on the role of a newly hired data analytics professional. Within the capstone project scenario, you’ll be responsible for tasks like:

- Setting up your teams’ workflow
- Creating a project proposal
- Carrying out EDA
- Building models

Along the way, you’ll interact with a variety of internal and external stakeholders, sharing your insights and final recommendations through an executive summary.

## Capstone Project: What to Expect

In the capstone project, the entire data analysis process is covered by a single project scenario with one project deliverable that showcases the skills you’ve learned across the certificate. To complete this project, you will begin by familiarizing yourself with the capstone project scenario. Next, you’ll determine the necessary tasks, and decide the order in which they need to be carried out.

Throughout the capstone project, you will use the skills and experience that you acquired in each course and the accompanying end-of-course projects. The capstone project scenario will offer opportunities to:

- Gather information pertaining to a business problem or an organizational inquiry
- Answer questions relevant to coding with Python
- Conduct exploratory data analysis
- Build statistical data models and machine learning models
- Consider ethical issues related to the task
- Present your findings for a general audience of stakeholders

## Capstone Project Scenario Overview: Working for Salifort Motors

### About the Company

Salifort Motors is a fictional French-based alternative energy vehicle manufacturer. Its global workforce of over 100,000 employees research, design, construct, validate, and distribute electric, solar, algae, and hydrogen-based vehicles. Salifort’s end-to-end vertical integration model has made it a global leader at the intersection of alternative energy and automobiles.

### Your Business Case

As a data specialist working for Salifort Motors, you have received the results of a recent employee survey. The senior leadership team has tasked you with analyzing the data to come up with ideas for how to increase employee retention. To help with this, they would like you to design a model that predicts whether an employee will leave the company based on their department, number of projects, average monthly hours, and any other data points you deem helpful.

### The Value of Your Deliverable

For this deliverable, you are asked to choose a method to approach this data challenge based on your prior coursework. Select either a regression model or a tree-based machine learning model to predict whether an employee will leave the company. Both approaches are shown in the project exemplar, but only one is needed to complete your project.

The capstone project will provide you with valuable experience and data analysis examples that you can share with potential employers.

## Project Overview

In this project, you will showcase your ability to use Python for model building and data analysis. You will deploy different models to analyze a dataset and generate business insights for your stakeholders. In particular, you will build and evaluate a logistic regression model or the following machine learning models: decision tree, random forest, XGBoost. You will also update your stakeholders through an executive summary, demonstrating your ability to organize and communicate key information.

Be sure to complete this activity before moving on. The next course item will provide you with completed exemplars to compare to your own work. You will not be able to access the exemplars until you have completed this activity.

## Scenario

You are a data professional working for Salifort Motors. Currently, there is a high rate of turnover among Salifort employees. (Note: In this context, turnover data includes both employees who choose to quit their job and employees who are let go). Salifort’s senior leadership team is concerned about how many employees are leaving the company. Salifort strives to create a corporate culture that supports employee success and professional development. Further, the high turnover rate is costly in the financial sense. Salifort makes a big investment in recruiting, training, and upskilling its employees.

If Salifort could predict whether an employee will leave the company, and discover the reasons behind their departure, they could better understand the problem and develop a solution.

### Your Tasks

As a first step, the leadership team asks Human Resources to survey a sample of employees to learn more about what might be driving turnover.

Next, the leadership team asks you to analyze the survey data and come up with ideas for how to increase employee retention. To help with this, they suggest you design a model that predicts whether an employee will leave the company based on their job title, department, number of projects, average monthly hours, and any other relevant data points. A good model will help the company increase retention and job satisfaction for current employees, and save money and time training new employees.

As a specialist in data analysis, the leadership team leaves it up to you to choose an approach for building the most effective model to predict employee departure. For example, you could build and evaluate a statistical model such as logistic regression. Or, you could build and evaluate machine learning models such as decision tree, random forest, and XGBoost. Or, you could choose to deploy both statistical and machine learning models.

For any approach, you’ll need to analyze the key factors driving employee turnover, build an effective model, and share recommendations for next steps with the leadership team.

## Capstone Project: Providing Data-Driven Suggestions for HR

### Description and Deliverables

This capstone project is an opportunity for you to analyze a dataset and build predictive models that can provide insights to the Human Resources (HR) department of a large consulting firm.

Upon completion, you will have two artifacts that you would be able to present to future employers:

1. A brief one-page summary of this project that you would present to external stakeholders as the data professional in Salifort Motors.
2. A complete code notebook provided here. Please consider your prior coursework and select one way to achieve this given project question. Either use a regression model or machine learning model to predict whether or not an employee will leave the company. The exemplar following this activity shows both approaches, but you only need to do one.

In your deliverables, you will include the model evaluation (and interpretation if applicable), a data visualization(s) of your choice that is directly related to the question you ask, ethical considerations, and the resources you used to troubleshoot and find answers or solutions.

## PACE Stages

### PACE: Plan

Consider the questions in your PACE Strategy Document to reflect on the Plan stage. In this stage, consider the following:

- Understand the business scenario and problem
- The HR department at Salifort Motors wants to take some initiatives to improve employee satisfaction levels at the company. They collected data from employees, but now they don’t know what to do with it. They refer to you as a data analytics professional and ask you to provide data-driven suggestions based on your understanding of the data. They have the following question: what’s likely to make the employee leave the company?

### Goals

Your goals in this project are to analyze the data collected by the HR department and to build a model that predicts whether or not an employee will leave the company.

If you can predict employees likely to quit, it might be possible to identify factors that contribute to their leaving. Because it is time-consuming and expensive to find, interview, and hire new employees, increasing employee retention will be beneficial to the company.

## Dataset Overview

Familiarize yourself with the HR dataset. The dataset that you'll be using in this lab contains 15,000 rows and 10 columns for the variables listed below. Note: you don't need to download any data to complete this lab. This project uses a dataset called HR_capstone_dataset.csv. It represents 10 columns of self-reported information from employees of a multinational vehicle manufacturing corporation.

### Dataset Information

The dataset contains:

- 14,999 rows – each row is a different employee’s self-reported information
- 10 columns

### Columns

| Column Name            | Type  | Description                                                  |
|------------------------|-------|--------------------------------------------------------------|
| satisfaction_level      | int64 | The employee’s self-reported satisfaction level [0-1]        |
| last_evaluation         | int64 | Score of employee's last performance review [0–1]            |
| number_project          | int64 | Number of projects employee contributes to                   |
| average_monthly_hours   | int64 | Average number of hours employee worked per month            |
| time_spend_company      | int64 | How long the employee has been with the company (years)      |
| work_accident           | int64 | Whether or not the employee experienced an accident while at work |
| left                    | int64 | Whether or not the employee left the company                 |
| promotion_last_5years   | int64 | Whether or not the employee was promoted in the last 5 years |
| department              | str   | The employee's department                                    |
| salary                  | str   | The employee's salary (low, medium, or high)                 |
