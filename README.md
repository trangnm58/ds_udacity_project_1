# Project 1: Write a Data Science Blog Post
Submission of Project 1 in Data Scientist Nanodegree Program - Udacity

# Installations
The code was developed using Python version 3.x. We recommend using [Anaconda](https://docs.anaconda.com/anaconda/install/index.html) for installing **Python 3** as well as other required libraries, although you can install them by other means.

Other required libraries that are not included in the Anaconda package:
- plotly==2.7.0

# Project Motivation
Every year, Stack Overflow conducts a massive survey of people on the site, covering all sorts of information like programming languages, salary, code style and various other information. This year, they amassed more than 64,000 responses fielded from 213 countries.

By using the [Stack Overflow Data - 2017 Survey](https://www.kaggle.com/stackoverflow/so-survey-2017) data, we try to answer some business questions to better understand the status of the field:
-   What is the gender diversity and gender equality status in the field?
-   What is the average salary in each country around the world?
-   Do people tend to work remotely more the longer they are in the field?

# File Descriptions

Within the download you'll find the following directories and files:
```
root/
├── data/
│   ├── country_codes.json
│   ├── survey_results_public.csv
│   └── survey_results_schema.csv
├── .gitignore
├── README.md
├── LICENSE.txt
└── Project1.ipynb
```

# How to Use

The "Project1.ipynb" notebook contains all the code and documentation. There are 4 main sections:

-  **Data Understanding:** load the data and have a look at its structure. Then, some relevent columns are visualized for better understanding.
- **Question 1: What is the gender diversity and gender equality status in the field?:** analysing the data to find insights that can answer the 1st question
- **Question 2: What is the average salary in each country around the world?:** analysing the data to find insights that can answer the 2nd question
- **Question 3: Do people tend to work remotely more the longer they are in the field?:** analysing the data to find insights that can answer the 3rd question

The notebook can be used as a start for more data wrangling and analysis to answer more business questions.

# Copyright and license
Code released under the [MIT License](https://github.com/trangnm58/ds_udacity_project_1/LICENSE.txt).