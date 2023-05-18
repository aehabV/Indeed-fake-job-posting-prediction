# NLP in PySpark's MLlib - Fake Job Posting Predictions
[![Language Badge](https://img.shields.io/badge/Language-Python-blue.svg)](https://www.python.org/)
[![PySpark Badge](https://img.shields.io/badge/PySpark-3.1.2-e25a1c.svg)](https://spark.apache.org/docs/latest/api/python/index.html)
[![License Badge](https://img.shields.io/badge/License-CC%20BY--NC%204.0-0a2c46.svg)](https://creativecommons.org/licenses/by-nc/4.0/legalcode)

Indeed.com has hired us to create a system that automatically flags suspicious job postings on its website. Due to the high volume of job postings, their employees do not have the capacity to check every posting, so they would like to prioritize which postings to review before deleting them. Our task is to use the attached dataset with NLP to create an algorithm that automatically flags suspicious posts for review.

## Dataset

This dataset contains 18K job descriptions out of which about 800 are fake. The data consist of both textual information and meta-information about the jobs.

Data Source: https://www.kaggle.com/shivamb/real-or-fake-fake-jobposting-prediction

The dataset has the following columns with their data types:

| Column Name       | Description                                       |
|-------------------|---------------------------------------------------|
| job_id            | Unique identifier for each job posting            |
| title             | Job title                                         |
| location          | Location of the job                               |
| department        | Department of the company                         |
| salary_range      | Salary range of the job                            |
| company_profile   | Description of the company                        |
| description       | Description of the job                             |
| requirements      | Requirements for the job                           |
| benefits          | Benefits offered by the company                    |
| telecommuting     | Whether the job allows telecommuting or not        |
| has_company_logo  | Whether the company has a logo or not              |
| has_questions     | Whether the job has questions for applicants or not|
| employment_type   | Type of employment (full-time, part-time, etc.)     |
| required_experience | Required experience for the job                    |
| required_education | Required education for the job                     |
| industry          | Industry of the company                            |
| function          | Function of the job                                |
| fraudulent        | Whether the job posting is fraudulent or not        |

## Prerequisites

Before running the code, you will need to have the following installed:

- PySpark: the Python API for Apache Spark
- Jupyter Notebook: an interactive development environment for Python

## Usage

To run the code, open the `Fake_Job_Posting_Predictions.ipynb` file in Jupyter Notebook and execute the cells in order. The notebook contains detailed explanations of each step in the code and the results obtained.
