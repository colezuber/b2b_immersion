# b2b_immersion

## Mentors

* Nick Coleman -- Paid Search Bidding
* Minjoo Kim -- Sales and Service, B2B
* Cole Zuber -- Product Recommendations

## Project overview

Business-to-business (B2B) sales are a large component of the Wayfair portfolio, and strong growth in this business segment is primarily driven by repeat customers. In order to sustain this growth, Wayfair invests heavily in ensuring that our B2B customers receive best-in-class service. Outbound B2B sales calls are expensive, however, with an average cost of $16 per call. In order to inform how sales resources should be allocated, the B2B Data Science team develops models that 1) identify which customers are likely to convert, and 2) estimate the amount that different customers are likely to spend. 

Given a repository of customer information, sales call records, and purchase history, you task is to predict the following:
Which B2B customers will make a purchase in the next 30 days?
Of the customers who are expected to make a purchase, how much will they spend?

You will use your data-driven predictions to recommend a specific course of business actions and estimate the value-add that your recommendation would provide to Wayfair. A successful project will demonstrate sound technical analyses and a strong business sense. 

## Intro to B2B

Minjoo to fill in

## Data

Info on how the data was pulled
Features
To-dos: clean data, dummify categorical variables, create new features (e.g., number of days since enrollment), dimension reduction such as PCA

## Evaluation metrics

ROC AUC, RMSE
+ Maybe it would be helpful to tie in business context/use case here
E.g., Are we more concerned about false positives or false negatives, given that an outbound call is expensive ($16/call)?

## Proposed timeline

Monday
* Help set up python
* Provide business context
* Describe modeling problem
* Share data and have participants do initial EDA

Tuesday
* More EDA
* Initial modeling

Wednesday
* More modeling
* Maybe we can provide more features

Thursday
* Final touches on modeling
* Make presentation

Friday
* Presentation


## Setup

### Using Git

Git is a version-control system used to coordinate and share work among multiple team members It comes pre-installed on Mac and Linux systems, but you will most likely need to download and install it if you are using it on Windows for the first time. You can download it from Git's official website [here](https://git-scm.com/download/win). The download should start automatically. Feel free to just select all the default install options during setup.

Once you have git installed, run the command below in your terminal (Mac/Linux) or command prompt (Windows) to clone this repo: 

`git clone https://github.com/colezuber/b2b_immersion.git`

You'll most likely want to create separate branches for each member of the team to work on to make merging your work easier. You can find out how to do this and other useful git features [here](https://git-scm.com/docs/gittutorial)

### Setting up Jupyter and Python

We suggest installing Anaconda to run python, Jupyter, and several useful python libraries commonly used in Data Science. You can download Anaconda for your OS [here](https://www.anaconda.com/download/) (downloading the Python 3.7 version is recommended).

Once you have Anaconda installed you'll want to start your jupyter server. To do this on Mac/Linux run the command below

`jupyter notebook`

For Windows, the easiest way to start your jupyter server is by launching the Jupyer Notebook Desktop app. This will automatically launch the UI in a separate browser window.

You can navgiate to the repo you cloned by enter the url in your browser that is displayed in the output (most likely http://localhost:8888/) From there, you can create a Python 3 notebook where you can store all your work.
