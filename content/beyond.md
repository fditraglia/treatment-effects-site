+++
title = "Treatment Effects: Beyond the Basics"
+++

## Overview
This is the website for my [summer school course](https://ouess.web.ox.ac.uk/september-summer-school) which takes place in Oxford each September.

<!--For more information about the summer school see the [course brochure](https://ouess.web.ox.ac.uk/sites/default/files/ouess/documents/media/september_summer_school_final_1.pdf). If you're interested in attending, you can [apply here](https://docs.google.com/forms/d/11FbbGxtKZuLp4DX4hgfKaHv5JDOmRrK9v9SiVHviqVY/viewform?edit_requested=true).-->


## Pre-reading
This course assumes introductory-level knowledge of causal inference along with basic familiarity with the R programming language. If you need to brush up on either of these pre-requisites, you may find the following resources helpful.
- The slides for my short course course [Treatment Effects: The Basics](/basics/)
- My [short video lectures](/videos) on treatment effects basics.
- Chapters 1-2, 4-5, and 7-8 of my [lecture notes](/treatment-effects.pdf) 
- My [crash course on R programming](https://ditraglia.com/erm/01-r-programming.html) and [solutions](https://ditraglia.com/erm/01-r-programming-solutions.html).
- My [introduction to `dplyr`](https://ditraglia.com/erm/02-dplyr-intro.html) with [solutions](https://ditraglia.com/erm/02-dplyr-intro-solutions.html) and [introduction to `ggplot2`](https://ditraglia.com/erm/03-ggplot2-intro.html) with [solutions](https://ditraglia.com/erm/03-ggplot2-intro-solutions.html).

## Lectures
Lectures will take place each morning each morning in the [Manor Road Building](https://maps.apple.com/place?q=Manor%20Road%20Building&ll=51.75676%2C-1.2468&auid=1776925928559182676&lsp=9902&address=Manor%20Road%2C%20Oxford%2C%20OX1%203UQ%2C%20England). 


<!--- Welcome and Course Outline: [slides](/slides-summer-school-welcome.pdf)-->
- Partial Identification: [slides](/slides-partial-ID.pdf), [lecture notes](/treatment-effects.pdf) Chapter 3.
  - [Manski (2003)](https://link.springer.com/book/10.1007/b97478) 
  - [Fan & Park (2010)](/Fan-Park-2010.pdf)
- Testing the LATE Assumptions: [slides](/slides-testing-LATE.pdf), [lecture notes](/treatment-effects.pdf) Chapters 5-6
  - [Huber & Mellace (2015)](/Huber-Mellace-2015.pdf)
  - [Kitagawa (2015)](/Kitagawa-2015.pdf)
  - [Mourifié & Wan (2017)](/Mourifie-Wan-2017.pdf)
- Marginal Treatment Effects: [slides part 1](/slides-MTE1.pdf), [slides part 2](/slides-MTE2.pdf), [lecture notes](/treatment-effects.pdf) Chapter 7
  - [Heckman, Tobias & Vytlacil (2001)](/Heckman-Tobias-Vytlacil-2001.pdf)
  - [Angrist (2004)](/Angrist-2004.pdf)
  - [Cornelissen et al. (2016)](/Cornelissen-et-al-2016.pdf)
  - [Mogstad & Torgovitsky (2018)](/Mogstad-Torgovitsky-2018.pdf)
  - [Cornelissen et al. (2018)](/Cornelissen-et-al-2018.pdf)
- Spillovers: [slides](/slides-spillovers.pdf) 
  - [Hudgens & Halloran (2008)](/Hudgens-Halloran-2008.pdf)
  - [Manski (2013)](/Manski-2013.pdf)
  - [DiTraglia et al. (2022)](https://ditraglia.com/pdf/spillovers-paper.pdf) 


## Applied Sessions 
Applied sessions will take place each morning in the [Manor Road Building](https://maps.apple.com/place?q=Manor%20Road%20Building&ll=51.75676%2C-1.2468&auid=1776925928559182676&lsp=9902&address=Manor%20Road%2C%20Oxford%2C%20OX1%203UQ%2C%20England).

1. Monday: [R Refresher](/01-r-refresher.html)
2. Tuesday: [Simulation Basics in R](/02-simulation-basics.html)
3. Wednesday [Running a Simulation Study](/03-simulation-study.html)
4. Thursday: [Testing the LATE Assumptions](/04-testing-LATE.html)
5. Friday: [Gaussian MTEs](/05-gaussian-MTE.html)


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
