# Nuese Salaries Project

## Introduction

The aim of this project is to establish a model of a complete software development cycle applied to a simple research project. This is the Capstone Project for the Master in Data Analytics of the University of Dublin.

The structure of the project is consisting in 4 main phases, each one deliverying specific types of insights:

1. Data Preparation
2. Exploratory Data Analysis
3. Statistical Analysis
4. Machine learning to answer research questions.

The idea is that the insights gathered in each phase inform the next, and eventually, the process turn iterative, since subsequent analysis and advancing with the research points the team to start working from scratch, or with the same supplies, but in a different direction.

This Git version controlled repository includes the notebooks that describe the four main phases of the project, as well as the documents that help shape the knowledge aquired about the topic of choice.

The complete datasets used were available publicly and without any license, from the OCDE website.

## Problem:

The particular problem of choice is: "What are the characteristics of the salaries of nurses in the countries od the European Union, in particular in Ireland, from the data publicly available?". This project started during 2023 running experiments to gather data, transform it and test if it was feasible to answer business questions with it.

Then, after a lenghty analysis of the datasets, there were defined new descriptive variables in a **Feature Engineering** process that involved domain knowledge from the nursing field to generate new descriptors and classifiers. Using that information, a **Clustering Model** for countries were developed. And finally, many different **Machine Learning algorithms** were implmented using those new features in order to try to answer more difficult questions.

## Users, audience and Technology

This project is public. This project is intended for the use of the developers and academic purposes for the program.

It is also expected that the user is familiarized with programing, executing and debugging Data Analytics tasks, like data cleaning, data wrangling and statistical description of the data. Libraries used include Pandas, Scikit-learn, NLTK, Plot.ly, Seaborn, among others.

Here is a Datafolio description of the process:
![image.png](./static/images/Datafolio1.jpg)

![image.png](./static/images/Datafolio2.jpg)

## Goals

The goals of this project are

-
- Provide a Dashboard to visualize the dataset.

_Demo: Recommender System Proof of concept for Placetopay._

You can check the resulting web page in [https://t67-ptp-recosystem.herokuapp.com/](https://t67-ptp-recosystem.herokuapp.com/) (page in English)

## How to run this app (locally)

(The following instructions apply to macOS/linux command line.)

To run this app first clone repository and then open a terminal.

```
git clone https://github.com/edward0rtiz/team67-ptp.git
```

Install the requirements:
it is suggested that you use a virtual environment (virtualenv / Anaconda / docker image) where all the requirement packets will be stored.

```
pip install -r requirements.txt
```

Run the app:

```
python3 app.py
```

You can run the app on your browser at http://127.0.0.1:8050

## Screenshots

![image.png](./static/images/PeekIntro.gif)
![image.png](./static/images/PeekDescriptive 2.gif)
![image.png](./static/images/PeekGeo2.gif)
![image.png](./static/images/PeekRecommender.gif)
