# Developing Data Products - Johns Hopkins University on Coursera
## Assignment: Course Project: Shiny Application and Reproducible Pitch
***
As part of the requirements for completing the Coursera course: Developing Data Products, part of the Data Science Specialization organized by Johns Hopkins University on Coursera, students are required to create a Shiny application and to store it on an RStudio’s  sever.  Secondly, students are required to create a Reproducible Pitch about the application.

This repository, on my GitHub account, holds all the files that I have created and used to produce my Shiny Application and its Reproducible Pitch.

My Shiny web application can be found on: <https://teuton2015.shinyapps.io/MyShinyApp/>

### Course Project Description
***
My Shiny Application seeks to do some exploratory analysis based on the training set of Kaggle's Titanic dataset, which provides information on the characteristics of the RMS Titanic’s passengers <https://www.kaggle.com/c/titanic>.   My exercise is based on the exercise presented by Trevor Stephens on his blog: “Titanic: Getting Started With R”: <http://trevorstephens.com/post/72916401642/titanic-getting-started-with-r>.

The training dataset of Kaggle’s Titanic Challenge provides characteristic information on Titanic’s passengers.  My Shiny Application seeks to provide answers, in a comparative way, to:

*	The survivors’ sex

*	The survivors’ passenger class

*	The survivor’s age

### To Reproduce this Project Locally
***
Please follow these instructions for running locally this application on your computer and avoid forking this repository:

1. Install the necessary R packages to run RStudio's Shiny Server locally, as instructed in the following instructions: <http://shiny.rstudio.com/articles/shinyapps.html>.

2. Run the following command in RStudio:

> runGitHub("MyShinyApp", "Teuton2015")

### About Kaggle's RMS Titanic Challenge
***
"The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

This Kaggle "Getting Started" Competition provides an ideal starting place for people who may not have a lot of experience in data science and machine learning. The data is highly structured, and we provide tutorials of increasing complexity for using Excel, Python, pandas in Python, and a Random Forest in Python (see links in the sidebar).  We also have links to tutorials using R instead." (Source: <https://www.kaggle.com/c/titanic>)