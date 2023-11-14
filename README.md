# Project Insight

Welcome dear visitor!

You're on the page of Stephane De Barros, PhD, astrophysicist, data scientist / analyst / manager (in a nutshell, data specialist).

I have worked for the University of Geneva, University of California (Riverside), the Italian National Institute for Astrophysics, and now for the World Health Organization.

You can find my Linkedin page here: https://www.linkedin.com/in/stephane-de-barros/

If you reached this page, I assume that you're interested about my profile, so first of all: thanks for your interest!

In this directory, you can find some examples of different things I have done regarding a variety of data. For now, there is a work performed on epidemiological data, but soon, you'll also find astrophysical data (with more to come).

## Brazil COVID19 hospitalized patients end-to-end analysis
The first project shown is about public COVID19 clinical data from Brazil. For this project, public data about hospitalized patients with positive COVID19 test is gathered and the outcome (death/cure) is studied.
I show how to 

- [extract raw data](https://github.com/stefdebarros/ProjectInsight/blob/master/extract_raw_data.ipynb) from the Ministry of Health webpage
- [format/prepare the data](https://github.com/stefdebarros/ProjectInsight/blob/master/extract_format_data.ipynb) for analysis
- [do some data exploration and cleaning](https://github.com/stefdebarros/ProjectInsight/blob/master/analysis_severe_cases_data_exploration.ipynb) to get a grasp of what it is about
- [perform a univariate logistic regression](https://github.com/stefdebarros/ProjectInsight/blob/master/analysis_severe_cases_univariate_logistic_regression.ipynb),  used as a preliminary analysis, to see how each individual parameter impact the outcome. The [result vizualisation](https://github.com/stefdebarros/ProjectInsight/blob/master/analysis_severe_cases_univariate_logistic_regression_results.ipynb) are shown elsewhere for more clarity.
- [perform a complete multivariate logistic regression analysis](https://github.com/stefdebarros/ProjectInsight/blob/master/analysis_severe_cases_multivariate_logistic_regression.ipynb), with stepwise approach.
- [use a supervised Machine Learning algorithm (logistic regression)](https://github.com/stefdebarros/ProjectInsight/blob/master/supervised_Machine_Learning_logistic_regression.ipynb) to identify the performance of the method, and the ability of such method to predict the outcome
- soon more to come...

## Brazil COVID19: ALL patients data, hospitalized or not

As you may not know, in Brazil, healthcare is universal and free for everyone. This is important because it limits biases in healthcare data since (theoretically) there is no reason for someone sick not to enter the healthcare system.

Another important point, it is that at the very early stage of the COVID19 outbreak, Brazil officials took advantage of an existing flu surveillance system to extend this system to COVID19, thus providing a wealth of data (age, sex, ethnicity, state of residence, comorbidities, symptoms, vaccinal status, etc), data consistent across the board. To the best of my knowledge, this is the largest existing database about COVID19

- [how to extract the whole dataset](LINK) through an Elastic API (and I admit it took me some time to find the right method to do it in Python)

