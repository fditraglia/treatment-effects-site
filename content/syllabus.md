+++
title = "Treatment Effects: Beyond the Basics"
+++

## Overview
This is the website for my [summer course](https://www.economics.ox.ac.uk/econometrics-pathway) which will take place at Oxford from 12-16 September 2022. If you're interested in attending, you can [apply here](https://www.economics.ox.ac.uk/econometrics-pathway). 


## Pre-reading
This course assumes basic knowledge of causal inference along with basic familiarity with the R programming language. If you need to brush up on either of these pre-requisites, you may find the following resources helpful.
- Chapters 1-2 and 4-7 of my [lecture notes](/treatment-effects.pdf) 
- [Hands-On Programming with R](https://rstudio-education.github.io/hopr/). See also [my notes](https://qyocwwdd4c.joplinusercontent.com/shares/OsJNRF8AGMOE9NGxpt7YK1) on this book.
- Lessons 1-4 of [Empirical Research Methods](https://empirical-methods.com/)

## Lectures
Lectures will take place in the Skills Lab of the Manor Road Building from 9am-11am on September 12th-16th. Because two hours is a long time, we'll take a twenty minute break halfway through each lecture.
1. Partial Identification: Chapter 3 of my [lecture notes](https://www.treatment-effects.com/treatment-effects.pdf).
  - [Manski (2003) - Partial Identification of Probability Distributions](https://link.springer.com/book/10.1007/b97478) 
  - [Fan & Park (2010; ET) - Sharp Bounds on the Distribution of Treatment Effects](https://scholar.archive.org/work/yadgi2yy4neirlnrba5mjbquie/access/wayback/http://www.unc.edu/depts/econ/papers/DistTreatFanParkET2.pdf)
2. Testing the LATE Assumptions 
  - [Huber & Mellace (2015; ReStat) - Testing Instrument Validity for LATE](https://scholar.archive.org/work/yadgi2yy4neirlnrba5mjbquie/access/wayback/http://www.unc.edu/depts/econ/papers/DistTreatFanParkET2.pdf)
  - [Kitagawa (2015; Ecma) - A Test for Instrument Validity](https://raw.githubusercontent.com/Mixtape-Sessions/Instrumental-Variables/main/Readings/Lecture3/Kitagawa_2015.pdf)
  - [Mourifié & Wan (2017; ReStat) - Testing Local Average Treatment Effect Assumptions](https://www.economics.utoronto.ca/public/workingPapers/tecipa-514.pdf)
3. Marginal Treatment Effects
  - [Cornelissen et al. (2016; Labour Economics) - From LATE to MTE](https://pure.york.ac.uk/portal/services/downloadRegister/49272936/LATE_to_MTE_paper_10June_with_tables.pdf)
  - [Mogstad & Torgovitsky (2018) - Identification and Extrapolation of Causal Effects](https://www.annualreviews.org/doi/10.1146/annurev-economics-101617-041813)
  - [Cornelissen et al. (2018; JPE) - Who benefits from universal child care?](http://www.christiandustmann.com/content/4-research/6-who-benefits-from-universal-childcare-estimating-marginal-returns-to-early-childcare-attendance/699979.pdf)
4. Spillovers 
  - [Hudgens & Halloran (2008; JASA) - Towards Causal Inference with Interference](https://scholar.archive.org/work/3cm6qflagjg4lgns6z6xepueze/access/wayback/https://cdr.lib.unc.edu/downloads/5m60r0829)
  - [DiTraglia et al. (2022; WP) - Identifying Causal Effects in Experiments with Spillovers & Non-compliance](https://ditraglia.com/pdf/spillovers-paper.pdf) 
5. Additional Topics TBA (Time Permitting) 

Further details will follow soon.

## Practical Classes
Because most students who are taking this course are also registered for Max Kasy's afternoon session on [Machine Learning](https://maxkasy.github.io/home/files/teaching/ML_Oxford_summerschool_2022/Syllabus_ML_Oxford_Summerschool_2022.pdf) we will hold a *joint practical session* for the two courses from 4:30pm-6pm each day. You are welcome to attend these joint sessions regardless of whether you are in fact registered for the Machine Learning course. A small number of students are registered for Treatment Effects in the morning session and something *other than* Machine Learning in the afternoon session. To prevent scheduling clashes for these students, we will hold alternative practical class sesssions covering *only* the Treatment Effects material from 11:30am-1pm on Monday, Tuesday, and Thursday. 


<!--Class meetings this term will take place over Zoom. Login details will be posted on the *Advanced Econometrics 1* canvas page on Monday, November 23rd. For each class meeting, I list the relevant chapters of the [lecture notes](/treatment-effects.pdf) along with papers for discussion. You should be able to access all of the assigned papers using your Oxford login. Let me know if you encounter any problems. 
1. November 24th (Tuesday): 12-1:30pm
    * Read in advance: Lecture notes chapters 1-2
    * Watch in advance: [The Potential Outcomes Framework](https://expl.ai/QHUAVRV), [Conditional Independence](https://expl.ai/LXPVDDN), [Selection Bias](https://expl.ai/DWVNRZU)
    * Discussion: Analyzing data from randomized controlled experiments. Please skim [Athey & Imbens (2017)](https://www.sciencedirect.com/science/article/pii/S2214658X16300174) Sections 1-8 and 10, along with [Mutz, Pemantle & Pham (2019)](https://amstat.tandfonline.com/doi/full/10.1080/00031305.2017.1322143) in advance.
2. November 27th (Friday): 1:30-3pm
    * Read in advance: Lecture notes chapter 3
    * Watch in advance: [Regression Adjustment](https://expl.ai/BJWTFKG), [Propensity Score Weighting](https://expl.ai/BASRRGX)
    * Discussion: Matching and weighting methods. Please skim [Todd (2010)](https://pdfs.semanticscholar.org/f21e/b74cebd5fd3cd8275b522baceba3ae4cfd52.pdf), and [King & Nielsen (2019)](https://www.cambridge.org/core/journals/political-analysis/article/whypropensity-scoresshould-not-be-usedformatching/94DDE7ED8E2A796B693096EB714BE68B) in advance. This [blog post](http://econjeff.blogspot.com/2010/10/on-matching.html) by Jeff Smith may also be of interest. 
3. December 1st (Tuesday): 12-1:30pm
    * Read in advance: Lecture notes chapter 4
    * Watch in advance: TBC (posted by Monday, Nov. 30th)
    * Discussion: Noncompliance in RCTs and Treatment effect heterogeneity. Please read [Athey & Imbens 2017) Section 9](https://www.sciencedirect.com/science/article/pii/S2214658X16300174) and [Angrist (2004)](https://academic.oup.com/ej/article/114/494/C52/5086004), in advance.
4. December 4th (Friday): 1:30-3pm
    * Read in advance: Lecture notes chapter 5
    * Watch in advance: TBC
    * Discussion: Regression discontinuity designs. Please read [Lee & Lemieux (2010)](https://www.aeaweb.org/articles?id=10.1257/jel.48.2.281) in advance. 
5. May 24th, 2021 (Monday): 2-3:30pm 
    * **Revision Lecture** ~~Manor Road Building~~ *Unfortunately, I have just learned that I will not be permitted to give this lecture in-person, so it will have to take place on zoom. Details will appear on canvas soon.*
    * [problems](/ps.pdf), [solutions](/ps-soln.pdf)
-->
