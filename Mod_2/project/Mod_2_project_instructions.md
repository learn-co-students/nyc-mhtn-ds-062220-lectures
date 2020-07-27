
# Module 2 Final Project


## Introduction

In this lesson, we'll review all of the guidelines and specifications for the final project for Module 2.

## Objectives
You will be able to:
* Describe all required aspects of the final project for Module 2
* Describe all required deliverables
* Describe what constitutes a successful project

## Final Project Summary

Another module down--you're almost half way there!

![awesome](https://raw.githubusercontent.com/learn-co-curriculum/dsc-mod-2-project-v2-1/master/halfway-there.gif)

All that remains in Module 2 is to put our newfound data science skills to use with a final project! You should expect this project to take between 20 and 25 hours of solid, focused effort. If you're done way quicker, go back and dig in deeper or try some of the optional "level up" suggestions. If you're worried that you're going to get to 30 hrs and still not even have the data imported, reach out to an instructor in Slack ASAP to get some help!

## The Dataset

We encourage you to be very thoughtful when identifying your problem and selecting your data set--an overscoped project goal or a poor data set can quickly bring an otherwise promising project to a grinding halt.

To help you select an appropriate data set for this project, we've set some guidelines:

1. Your dataset should work for regression. Therefore the target variable that you are trying to predict, should be continuous.

2. Your dataset needs to be of sufficient complexity. Try to avoid picking an overly simple dataset. Try to avoid extremely small datasets, as well as the most common datasets like wine, mpg, boston housing, etc. We want to see all the steps of the Data Science Process in this project--it's okay if the dataset is mostly clean, but we expect to see some preprocessing and exploration. See the following section, **_Data Set Constraints_**, for more information on this.

3. On the other end of the spectrum, don't pick a problem that's too complex, either. Stick to problems that you have a clear idea of how you can use machine learning to solve it. For now, we recommend you stay away from overly complex problems in the domains of Natural Language Processing or Computer Vision--although those domains make use of Supervised Learning, they come with a lot of other special requirements and techniques that you don't know yet (but you'll learn soon!). If you're chosen problem feels like you've overscoped, then it probably is.

4. When trying to identify a data set ask yourself two questions. What is the variable that I will try to model/predict? Why/how will this model be useful for other people or businesses?

5. **All data sets must be approved before you can move forward with yoru project.**


#### Data Set Constraints

When selecting a data set, be sure to take into consideration the following constraints:

1. Your data set can't be one we've already worked with in any labs.
2. Your data set should contain a minimum of 1000 rows.
3. Your data set should contain a minimum of 10 predictor columns, before any one-hot encoding is performed.
4. Your instructor must provide final approval on your data set.

#### Problem First, or Data First?

There are two ways that you can about getting started: **_Problem-First_** or **_Data-First_**.

**_Problem-First_**: Start with a problem that you want to solve with classification, and then try to find the data you need to solve it.  If you can't find any data to solve your problem, then you should pick another problem.

**_Data-First_**: Take a look at some of the most popular internet repositories of cool data sets we've listed below. If you find a data set that's particularly interesting for you, then it's totally okay to build your problem around that data set.

There are plenty of amazing places that you can get your data from. We recommend you start looking at data sets in some of these resources first:

* [UCI Machine Learning Datasets Repository](https://archive.ics.uci.edu/ml/datasets.html)
* [Kaggle Datasets](https://www.kaggle.com/datasets)
* [Awesome Datasets Repo on Github](https://github.com/awesomedata/awesome-public-datasets)
* [New York City Open Data Portal](https://opendata.cityofnewyork.us/)
* [Inside AirBNB ](http://insideairbnb.com/)


## The Deliverables

For online students, there will be five deliverables for this project (Note: On-campus students may have different requirements, please speak with your instructor):

1. A well documented **Jupyter Notebook** containing any code you've written for this project and comments explaining it. This work will need to be pushed to your GitHub repository in order to submit your project.
2. An organized **README.md** file in the GitHub repository that describes the contents of the repository. This file should be the source of information for navigating through the repository.
3. A short **Keynote/PowerPoint/Google Slides presentation** (delivered as a PDF export) giving a high-level overview of your methodology and recommendations for non-technical stakeholders. Make sure to also add and commit this pdf of your non-technical presentation to your repository with a file name of presentation.pdf.
4. **[A Blog Post](https://github.com/learn-co-curriculum/dsc-welcome-blogging-v2-1)**
5. A **Video Walkthrough** of your non-technical presentation. Some common video recording tools used are Zoom, Quicktime, and Nimbus. After you record your presentation, publish it on a service like YouTube or Google Drive, you will need a link to the video to submit your project.

Note: On-campus students may have different requirements, please speak with your instructor.

### Jupyter Notebook Must-Haves

For this project, your Jupyter Notebook should meet the following specifications:

#### Organization/Code Cleanliness

* The notebook should be well organized, easy to follow,  and code should be commented where appropriate.
    * Level Up: The notebook contains well-formatted, professional looking markdown cells explaining any substantial code.  All functions have docstrings that act as professional-quality documentation
* The notebook is written for technical audiences with a way to both understand your approach and reproduce your results. The target audience for this deliverable is other data scientists looking to validate your findings.

#### Visualizations & EDA

* Your project contains at least 4 meaningful data visualizations, with corresponding interpretations. All visualizations are well labeled with axes labels, a title, and a legend (when appropriate)
* You pose at least 3 meaningful questions and answer them through EDA.  These questions should be well labeled and easy to identify inside the notebook.
    * **Level Up**: Each question is clearly answered with a visualization that makes the answer easy to understand.
* Your notebook should contain 1 - 2 paragraphs briefly explaining your approach to this project.

#### Statistical Tests

* Your project must report and interpret at least 3 meaningful statistical test. You can choose from any of the tests we learned during the stats part of the module.
* The tests that you report should be connected to your linear regression model.
* When interpreting the tests, explain how the information gained from the test help you to build a more accurate model.

#### Model Quality/Approach

A linear regression model can serve two purposes:
  1. Predict a continuous variable.
  2. Determine and quantify the relationship between a continuous variable and many explanatory variables.

At the beginning of your project, you need to determine what your goal is. Do you want a model that is as accurate as possible, or do you want a model that is highly interpretable and explains the relationship.  The answer to this question will shape the way you complete your model.  


* Your model should not include any predictors with p-values greater than .05.
* Your notebook shows an iterative approach to modeling, and details the parameters and results of the model at each iteration.
    * **Level Up**: Whenever necessary, you briefly explain the changes made from one iteration to the next, and why you made these choices.
* You provide at least 1 paragraph explaining your final model.
* You pick at least 3 coefficients from your final model and explain their impact on the price of a house in this dataset.


### Non-Technical Presentation Must-Haves

Another deliverable should be a Keynote, PowerPoint or Google Slides presentation delivered as a pdf file in your fork of this repository with the file name of `presentation.pdf` detailing the results of your project.  Your target audience is non-technical people interested in using your findings to maximize their profit when selling their home.

Your presentation should:

* Contain between 5 - 10 professional-quality slides.
    * **Level Up**: The slides should use visualizations whenever possible, and avoid walls of text.
* Take no more than 5 minutes to present.
* Avoid technical jargon and explain the results in a clear, actionable way for non-technical audiences.

**_Based on the results of your models, your presentation should discuss at least two concrete features that highly influence housing prices._**

### Blog Post Must-Haves

Refer back to the [Blogging Guidelines](https://github.com/learn-co-curriculum/dsc-welcome-blogging-v2-1) for the technical requirements and blog ideas.


## The Process
The process for this project is identical to the process you followed for your module 1 project. We specified it again below as a refresher.
(Note: On-campus students may have different processes, please speak with your instructor)

### 1. Getting Started

Please start by reviewing this document. If you have any questions, please ask them in Slack ASAP so (a) we can answer the questions and (b) so we can update this repository to make it clearer.

Be sure to let the instructor team know when you’ve started working on a project, either by reaching out over Slack or, if you are in a full-time or part-time cohort, by connecting with your Cohort Lead in your weekly 1:1. If you’re not sure who to reach out to, post in the #online-ds-sp-000 channel in Slack.

Once you're done with this module, please start on the project. Do that by forking this repository, cloning it locally, and working in the student.ipynb file. Make sure to also add and commit a pdf of your presentation to the repository with a file name of `presentation.pdf`.

### 2. The Project Review

_Note: On-campus students may have different review processes, please speak with your instructor._

> **When you start on the project, please also reach out to an instructor immediately to schedule your project review** (if you're not sure who to schedule with, please ask in Slack!)

#### What to expect from the Project Review

Project reviews are focused on preparing you for technical interviews. Treat project reviews as if they were technical interviews, in both attitude and technical presentation *(sometimes technical interviews will feel arbitrary or unfair - if you want to get the job, commenting on that is seldom a good choice)*.

The project review is comprised of a 45 minute 1:1 session with one of the instructors. During your project review, be prepared to:

#### 1. Deliver your PDF presentation to a non-technical stakeholder.
In this phase of the review (~10 mins) your instructor will play the part of a non-technical stakeholder that you are presenting your findings to. The presentation  should not exceed 5 minutes, giving the "stakeholder" 5 minutes to ask questions.

In the first half of the presentation (2-3 mins), you should summarize your methodology in a way that will be comprehensible to someone with no background in data science and that will increase their confidence in you and your findings. In the second half (the remaining 2-3 mins) you should summarize your findings and be ready to answer a couple of non-technical questions from the audience. The questions might relate to technical topics (sampling bias, confidence, etc) but will be asked in a non-technical way and need to be answered in a way that does not assume a background in statistics or machine learning. You can assume a smart, business stakeholder, with a non-quantitative college degree.

#### 2. Go through the Jupyter Notebook, answering questions about how you made certain decisions. Be ready to explain things like:
    * "How did you pick the question(s) that you did?"
    * "Why are these questions important from a business perspective?"
    * "How did you decide on the data cleaning options you performed?"
    * "Why did you choose a given method or library?"
    * "Why did you select those visualizations and what did you learn from each of them?"
    * "Why did you pick those features as predictors?"
    * "How would you interpret the results?"
    * "How confident are you in the predictive quality of the results?"
    * "What are some of the things that could cause the results to be wrong?"

Think of the first phase of the review (~30 mins) as a technical boss reviewing your work and asking questions about it before green-lighting you to present to the business team. You should practice using the appropriate technical vocabulary to explain yourself. Don't be surprised if the instructor jumps around or sometimes cuts you off - there is a lot of ground to cover, so that may happen.

If any requirements are missing or if significant gaps in understanding are uncovered, be prepared to do one or all of the following:
* Perform additional data cleanup, visualization, feature selection, modeling and/or model validation
* Submit an improved version
* Meet again for another Project Review

What won't happen:
* You won't be yelled at, belittled, or scolded
* You won't be put on the spot without support
* There's nothing you can do to instantly fail or blow it

**Please note: We need to receive the URL of your repository at least 24 hours before and please have the project finished at least 3 hours before your review so we can look at your materials in advance.**


## Submitting your Project

 You’re almost done! In order to submit your project for review, include the following links to your work in the corresponding fields on the right-hand side of Learn.

 1. **GitHub Repo:** Now that you’ve completed your project in Jupyter Notebooks, push your work to GitHub and paste that link to the right. (If you need help doing so, review the resources [here](https://docs.google.com/spreadsheets/d/1CNGDhjcQZDRx2sWByd2v-mgUOjy13Cd_hQYVXPuzEDE/edit#gid=0).)
_Reminder: Make sure to also add and commit a pdf of your non-technical presentation to the repository with a file name of presentation.pdf._
2. **Blog Post:** Include a link to your blog post.
3. **Record Walkthrough:** Include a link to your video walkthrough.

 Hit "I'm done" to wrap it up. You will receive an email in order to schedule your review with your instructor.


## Grading Rubric
Online students can find a PDF of the grading rubric for the project [here](https://github.com/learn-co-curriculum/dsc-mod-2-project-v2-1/blob/master/mod2_project_rubric.pdf). On-campus students may have different review processes, please speak with your instructor.


## Summary

The end of module projects and project reviews are a critical part of the program. They give you a chance to both bring together all the skills you've learned into realistic projects and to practice key "business judgement" and communication skills that you otherwise might not get as much practice with.
