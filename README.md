<!-- font: frutiger -->

### Bayesian Learning

![](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/Images/BayesTheoremNeon.jpg "Bayesian Learning")

---

### Aims

The course aims to give a solid introduction to the Bayesian approach to statistical inference, with special emphasis on models in modern statistics and machine learning. After an introduction to the subjective probability concept that underlies Bayesian inference, the course moves on to the mathematics of the prior-to-posterior updating in basic statistical models, such as the Bernoulli, normal and multinomial models. Linear regression and nonlinear regression are also analyzed using a Bayesian approach. The course subsequently shows how complex models can be analyzed with simulation methods like Markov Chain Monte Carlo (MCMC) or approximate methods like Variational Inference. Bayesian prediction and marginalization of nuisance parameters is explained, and introductions to Bayesian model selection and Bayesian decision theory are also given.

---

### Course literature and Schedule

The course will use the following book as the main course literature:

* Gelman, Carlin, Stern, Dunson, Vehtari, Rubin (2014).
Bayesian Data Analysis. Chapman & Hall/CRC: Boca Raton, Florida. 3rd edition.
* My slides on this page
* Additional course material linked from this page, such as articles and tutorial.

The course schedule on TimeEdit is here: [Schedule](https://cloud.timeedit.net/su/web/stud1/ri161XQQ580Z50Qv17043gZ6y1Y7406Q5Y65Y3.html).

---

### Computer labs

* The computer labs is a central part of this course and you should expect to allocate substantial time for each lab. Many of the exam questions will be computer based, so working on the labs will also help you with the exam.
* You are strongly encouraged to do the labs in R, but any programming language is ok to use.
* The labs should be done in pairs of students.
* Each lab report should be submitted as a PDF along with the .R file with code. Submission is done through the [Mondo system](https://mondo.su.se/portal/site/39bc4842-de2a-463b-838c-4e25ba04ea80/page/2b6b510b-6580-40bc-b0d8-3fe4da0e2329)(Stockholm) or LISAM (Linköping).
* There is only two hours of supervised time allocated to each lab. This will not be enough time to complete each lab. The idea is that you should start working on the lab before the computer session, so that you are in a position to ask questions at the session.

---

### Teachers

<img src="Misc/VillaniFotoMindre.jpg" width="100">\
[Mattias Villani](https://mattiasvillani.com), Lecturer \
Professor \
Department of Statistics, Stockholm University \
Division of Statistics and Machine Learning, Linköping University

<img src="Misc/Oscar.jpg" width="100">\
[Oscar Oelrich](https://www.su.se/english/profiles/ooelr-1.342298), Assistant \
PhD Candidate \
Department of Statistics, Stockholm University

---

#### Part 1 - The Basics
**Lecture 1** - Basics concepts. Likelihood. The Bernoulli model.\
Reading: BDA Ch. 1, 2.1-2.4 |  [Slides](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/BL_L1.pdf) \
Code: [Beta density](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/ManipBeta.R) | [Bernoulli model](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/PriorPosteriorManipBern.R)

**Lecture 2** - Gaussian model. The Poisson model. Conjugate priors. Prior elicitation.\
Reading: BDA Ch. 2.-2.9 | [Slides](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/BL_L2.pdf) \
Code: [One-parameter Gaussian model](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/PriorPosteriorManipNormal.R)\
Python Notebook: Poisson eBay data in [Notebook](https://github.com/mattiasvillani/BayesLearnCourse/blob/master/Code/Notebooks/eBayPoisson.ipynb) and [HTML](https://github.com/mattiasvillani/BayesLearnCourse/blob/master/Code/Notebooks/eBayPoisson.html)

**Lecture 3** - Multi-parameter models. Marginalization. Multinomial model. Multivariate normal model.\
Reading: BDA Ch. 3 | [Slides](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/BL_L3.pdf) \
Code: [Two-parameter Gaussian model](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/NormalNonInfoPrior.R)\
R Notebook: Multinomial survey data in [Notebook](https://github.com/mattiasvillani/BayesLearnCourse/blob/master/Code/Notebooks/DirichletSurveyData.Rmd) and [HTML](https://github.com/mattiasvillani/BayesLearnCourse/blob/master/Code/Notebooks/DirichletSurveyData.nb.html)

**Exercise session 1** \
Exercises: [Exercise 1](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/MathExercises/BLExercise1.pdf) \
Assistant: [Oscar Oelrich](https://www.su.se/english/profiles/ooelr-1.342298)

**Computer Lab 1** - Exploring posterior distributions in one-parameter models by simulation and direct numerical evaluation.\
Lab: [Lab 1](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Labs/Lab1.pdf) \
Assistant: [Oscar Oelrich](https://www.su.se/english/profiles/ooelr-1.342298) \
Submission tool: [Mondo](https://mondo.su.se/portal/site/39bc4842-de2a-463b-838c-4e25ba04ea80/page/2b6b510b-6580-40bc-b0d8-3fe4da0e2329).

---

#### Part 2 - Bayesian Regression and Classification
**Lecture 4** - Prediction. Making Decisions.\
Reading: BDA Ch. 9.1-9.2. | [Slides](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/BL_L4.pdf) \
Code: [Prediction with two-parameter Gaussian model](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/PostAndPredIIDNormalNonInfoPrior.R)

**Lecture 5** - Linear Regression. Nonlinear regression. Regularization priors.\
Reading: BDA Ch. 14 and Ch. 20.1-20.2 | [Slides](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/BL_L5.pdf)  

**Lecture 6** - Classification. Posterior approximation. Logistic regression.\
Reading: BDA Ch. 16.1-16.3 | [Slides](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/BL_L6.pdf) \
Code: [Logistic and Probit Regression](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/MainOptimizeSpam.zip)

**Exercise session 2** \
Exercises: [Exercise 2](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/MathExercises/BLExercise2.pdf) \
Assistant: [Oscar Oelrich](https://www.su.se/english/profiles/ooelr-1.342298)

**Computer Lab 2** - Polynomial regression and classification with logistic regression.\
Lab: [Lab 2](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Labs/Lab2.pdf) | [Temp in Linköping dataset](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Labs/TempLinkoping.txt) | [WomenWork dataset](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Labs/WomenWork.dat)\
Assistant: [Oscar Oelrich](https://www.su.se/english/profiles/ooelr-1.342298) \
Submission tool: [Mondo](https://mondo.su.se/portal/site/39bc4842-de2a-463b-838c-4e25ba04ea80/page/2b6b510b-6580-40bc-b0d8-3fe4da0e2329).

---

#### Part 3 - More Advanced Models, MCMC and Variational Bayes
**Lecture 7** - Monte Carlo simulation. Gibbs sampling. Data augmentation. \
Reading: BDA Ch. 10-11 | [Slides](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/BL_L7.pdf) \
Code: [Gibbs sampling for a bivariate normal](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/GibbsBivariateNormal.R) | [Gibbs sampling for a mixture of normals](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/NormalMixtureGibbs.R) \
Extra material: [Illustration](https://www.youtube.com/watch?v=iLKR9tCiwvA) of Gibbs sampling when parameters are strongly correlated.

**Lecture 8** - MCMC and Metropolis-Hastings \
Reading: BDA Ch. 11 | [Slides](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/BL_L8.pdf) \
Code: [Simulating Markov Chains](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/SimulateDiscreteMarkovChain.R)

**Lecture 9** - HMC, Variational Bayes and Stan. \
Reading: BDA Ch. 12.4 and Ch. 13.7 | [RStan vignette](https://cran.r-project.org/web/packages/rstan/vignettes/rstan.html) | [Slides](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/BL_L9.pdf) \
Code: [RStan - Three Plants](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/RStanCode/Code/ThreePlants.R) | [RStan - Bernoulli model](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/RStanCode/Code/BernBetaRStan.R) | [RStan - Logistic regression](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/RStanCode/Code/LogisticRegRStan.R) | [RStan - Logistic regression with random effects](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/RStanCode/Code/LogisticRegRandEffectsRStan.R) | [RStan - Poisson model](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/RStanCode/Code/RoachesPoissonRStan.R)

**Computer Lab 3** - Gibbs sampling for the normal model, mixture of normals. Metropolis-Hastings for Poisson regression. \
Lab: [Lab 3](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Labs/Lab3.pdf) | [Rainfall dataset](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Labs/rainfall.dat) | [eBay dataset](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Labs/eBayNumberOfBidderData.dat) | [How to code](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Labs/HowToCodeRWM.pdf) up Random Walk Metropolis \
Assistant: [Oscar Oelrich](https://www.su.se/english/profiles/ooelr-1.342298) \
Submission tool: [Mondo](https://mondo.su.se/portal/site/39bc4842-de2a-463b-838c-4e25ba04ea80/page/2b6b510b-6580-40bc-b0d8-3fe4da0e2329).

---

#### Part 4 - Model Inference and Variable Selection
**Lecture 10 - Bayesian model comparison.**\
Reading: BDA Ch. 7 | [Slides](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/BL_L10.pdf) \
Code: [Comparing models for count data](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Code/MainGeoVsPois.R)

**Lecture 11** - Computing the marginal likelihood, Bayesian variable selection, model averaging.\
Reading: [Article](http://www-stat.wharton.upenn.edu/~edgeorge/Research_papers/GeorgeMcCulloch97.pdf) on Bayesian variable selection | [Slides](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/BL_L11.pdf)

**Lecture 12** - Model evaluation and course summary.\
Reading: BDA 6.1-6.4 | [Slides](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/BL_L12.pdf)

**Computer Lab 4** - HMC for time series in RStan.\
Lab: [Lab 4](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Labs/Lab4.pdf) | [campylobacter dataset](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Labs/campy.dat)\
Assistant: [Oscar Oelrich](https://www.su.se/english/profiles/ooelr-1.342298) \
Submission tool: [Mondo](https://mondo.su.se/portal/site/39bc4842-de2a-463b-838c-4e25ba04ea80/page/2b6b510b-6580-40bc-b0d8-3fe4da0e2329).

---

#### Examination

The course examination consists of:

* Written lab reports (deadlines given in Mondo/LISAM)
* Computer exam


---

#### R

* The main page with links to downloads for the [programming language R](https://www.r-project.org/)
* [RStudio](https://www.rstudio.com/) - a very nice developing environment for R.
* Short introduction to R | A little [longer introduction](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf) | John Cook's [intro to R for programmers](https://www.johndcook.com/blog/r_language_for_programmers/).


---
