+++
title = "Treatment Effects References"
+++

## Standard Textbook References
* [Cameron & Trivedi (2005) - Microeconometrics: Methods and Applications](https://books.google.co.uk/books?id=Zf0gCwxC9ocC&lpg=PP1&dq=cameron%20and%20trivedi&pg=PP1#v=onepage&q=cameron%20and%20trivedi&f=false) - Chapter 25 covers Treatment Evaluation.
* [Wooldridge (2010) - Econometric Analysis of Cross Section and Panel Data](https://books.google.co.uk/books?id=yov6AQAAQBAJ&lpg=PP1&dq=wooldridge%20panel%20econometrics&pg=PR3#v=onepage&q=wooldridge%20panel%20econometrics&f=false) - Parts of my lecture notes follow Chapter 21 "Estimating Average Treatment Effects" fairly closely.

## Books on Causal Inference 
* [Angrist & Pischke (2009) - Mostly Harmless Econometrics: An Empiricist's Companion](http://www.mostlyharmlesseconometrics.com/)
* [Angrist & Pischke (2014) - Mastering 'Metrics: The Path from Cause to Effect](http://www.masteringmetrics.com/)
* [Hernan & Robins (2020) - Causal Inference: What If](https://cdn1.sph.harvard.edu/wp-content/uploads/sites/1268/2020/07/ci_hernanrobins_31july20.pdf) *Freely available online*
* [Imbens & Rubin (2015) - Causal Inference for Statistics, Social, and Biomedical Sciences: An Introduction](https://www.cambridge.org/core/books/causal-inference-for-statistics-social-and-biomedical-sciences/71126BE90C58F1A431FE9B2DD07938AB)
* [Lee (2016) - Matching, Regression Discontinuity, Difference-in-differences & Beyond](https://oxford.universitypressscholarship.com/view/10.1093/acprof:oso/9780190258733.001.0001/acprof-9780190258733)
* [Morgan & Winship (2015) - Counterfactuals and Causal Inference: Methods and Principles for Social Research](https://www.cambridge.org/core/books/counterfactuals-and-causal-inference/5CC81E6DF63C5E5A8B88F79D45E1D1B7) 

## Miscellaneous Resources
* [Online Causal Inference Seminar](https://sites.google.com/view/ocis/) - "A regular international causal inference seminar."
* [wooldridge R package](https://cran.r-project.org/web/packages/wooldridge/index.html) - "111 Data sets from *Introductory Econometrics: A Modern Approach 6e* by Jeffrey M. Wooldridge."
* [Using R for Introductory Econometrics](http://urfie.net/) - "This book introduces the popular, powerful and free programming language and software package R with a focus on the implementation of standard tools and methods used in econometrics." Free to view online.

## Journal Articles
Within topic, references are listed in chronological rather than alphabetic order.
Always in-progress; citation ≠ endorsement.

### Survey Articles
* Imbens & Wooldridge (2009) - Recent Developments in the Econometrics of Program Evaluation
* Abadie & Cattaneo (2018) - Econometric Methods for Program Evaluation

### High-level Methodology / Polemics
* [Rosenzweig & Wolpin (2000) - Natural "Natural Experiments" in Economics](https://www.aeaweb.org/articles?id=10.1257/jel.38.4.827)
* [Angrist & Pisckhe (2010) - The Credibility Revolution in Empirical Economics (with discussion)](https://www.aeaweb.org/issues/126)
* [Rust (2016) - Mostly Useless Econometrics? Assessing the Causal Effect of Econometric Theory](https://nowpublishers.com/article/Details/ACC-049)
* [Deaton & Cartwright (2018) - Understanding and Misunderstanding Randomized Controlled Trials (with commentaries)](https://www.sciencedirect.com/journal/social-science-and-medicine/vol/210/)

### Randomized Controlled Trials
* Chassang et al (2012) - Selective Trials: A Principal-Agent Approach to Randomized Controlled Experiments
* Morgan & Rubin (2012) - Rerandomization to Improve Covariate Balance in Experiments
* Lin (2013) - Agnostic Notes on Regression Adjustments to Experimental Data: Reexamining Freedman's Critique
* Bertsimas, Johnson & Kallus (2015) - The Power of Optimization Over Randomization in Designing Experiments Involving Small Samples
* Kasy (2016) - Why Experimenters Might Not Always Want to Randomize and What They Could Do Instead
* Athey & Imbens (2017) - The Econometrics of Randomized Experiments
* Banjeree, Chassang & Snowberg (2017) - Decision Theoretic Approaches to Experiment Design and External Validity
* Kallus (2017) - Optimal a Priori Balance in the Design of Controlled Experiments
* Mutz, Pemantle & Pham (2019) - The Perils of Balance Testing in Experimental Design
* Banjeree et al (2020) - A Theory of Experimenters: Robustness, Randomization, and Balance

### Inference: Sampling-based vs. Design-based
* Samii & Aronow (2012) - On Equivalencies Between Design-based and Regression-based Variance Estimators for Randomized Experiments
* Li & Ding (2017) - General Forms of Finite Population Central Limit Theorems with Applications to Causal Inference
* Young (2019) - Channeling Fisher: Randomization Tests and the Statistical Insignificance of Seemingly Significant Experimental Results
* Abadie et al (2020) - Sampling-based versus Design-based Uncertainty in Regression Analysis

### Conditional Independence
* Dawid (1979) - Conditional Independence in Statistical Theory
* Florens & Mouchart (1982) - A Note on Noncausality
* Angrist (1997) - Conditional Independence in Sample Selection Models
* Contantinou & Dawid (2017) - Extended Conditional Independence and Applications in Causal Inference

### Selection on Observables - Choosing Covariates / Model Averaging
* De Luna et al (2011) - Covariate Selection for the Nonparametric Estimation of an Average Treatment Effect
* Lu (2015) - A Covariate Selection Criterion for Estimation of Treatment Effects
* Kitagawa & Muris (2016) - Model Averaging in Semiparametric Estimation of Treatment Effects
* Cefalu et al (2016) - Model Averaged Double Robust Estimation
* Luo et al (2017) - On Estimation Regression-based Causal Effects Using Sufficient Dimension Reduction
* Koch et al (2018) - Covariate Selection with Group LASSO and Doubly Robust Estimation of Causal Effects


### Matching / Propensity Score Methods 
* Rosenbaum & Rubin (1983) - The Central Role of the Propensity Score in Observational Studies for Causal Effects 
* Imbens (2000) - The Role of the Propensity Score in Estimating Dose-response Functions
* Ichimura & Taber (2001) - Propensity Score Matching with Instrumental Variables
* Dehejia & Wahba (2002) - Propensity Score Matching Methods for Nonexperimental Causal Studies
* Smith & Todd (2005) - Does Matching Overcome LaLonde's Critique of Nonexperimental Estimators?
* Ho et al (2007) - Matching as Nonparametric Preprocessing for Reducing Model Dependence in Parametric Causal Inference
* [Todd (2010) - Matching Estimators (from *Microeconometrics* - Palgrave Macmillan)](https://pdfs.semanticscholar.org/f21e/b74cebd5fd3cd8275b522baceba3ae4cfd52.pdf)
* Stuart (2010) - Matching Methods for Causal Inference: A Review and a Look Forward
* Iacus, King & Porro (2011) - Multivariate Matching Methods that are Monotonic Imbalance Bounding
* Imai & Ratkovic (2014) - Covariate Balancing Propensity Score
* Iacus, King & Porro (2012) - Causal Inference without Balance Checking: Coarsened Exact Matching
* [Li et al. (2018) - Balancing Covariates via Propensity Score Weighting](https://www.tandfonline.com/doi/full/10.1080/01621459.2016.1260466)
* King & Nielsen (2019) - Why Propensity Scores Should Not be Used for Matching 

### Instrumental Variables / LATE - General
* Heckman & Robb (1985) - Alternative Methods for Evaluating the Impact of Interventions
* Imbens & Angrist (1994) - Identification and Estimation of Local Average Treatment Effects
* Angrist, Imbens & Rubin (1996) - Identification of Causal Effects Using Instrumental Variables  
* Imbens & Rubin (1997) - Estimating Outcome Distributions for Compliers in Instrumental Variables Models
* Vytlacil (2002) - Independence, Monotonicity, and Latent Index Models: An Equivalence Result

### Testing the LATE Assumptions / Bounding the ATE 
* Balke & Pearl (1997) - Bounds on Treatment Effects from Studies with Imperfect Compliance
* Huber & Mellace (2015) - Testing Instrument Validity for LATE Identification Based on Inequality Moment Constraints
* Kitagawa (2015) - A Test for Instrument Validity
* Mourifie & Wan (2017) - Testing Local Average Treatment Effect Assumptions
* Machado, Shaikh & Vytlacil (2019) - Instrumental Variables and the Sign of the Average Treatment Effect

### Marginal Treatment Effects / Beyond LATE
* Heckman & Vytlacil (2001) - Policy-Relevant Treatment Effects
* Angrist (2004) - Treatment Effect Heterogeneity in Theory and Practice
* Heckman & Vytlacil (2005) - Structural Equations, Treatment Effects, and Econometric Policy Evaluation
* Angrist & Fernandez-Val (2010) - ExtrapoLATE-ing: External Validity and Over-identification in the LATE Framework
* Carneiro, Heckman & Vytlacil (2011) - Estimating Marginal Returns to Education
* Brinch, Mogstad, & Wiswall (2017) - Beyond LATE with a Discrete Instrument
* Mogstad, Santos, & Torgovitsky (2018) - Using Instrumental Variables for Inference about Policy Relevant Treatment Parameters
* Mogstad, Torgovitsky & Walters (2019) - Identification of Causal Effects with Multiple Instruments: Problems and Some Solutions

### Regression Discontinuity
* Thistlewaite & Campbell (1960) - Regression Discontinuity Analysis: An Alternative to the Ex-post Facto Experiment
* Hahn, Todd, & Van der Klaauw (2001) - Identification and Estimation of Treatment Effects with a Regression-Discontinuity Design
* Imbens & Lemieux (2008) - Regression Discontinuity Designs: A Guide to Practice
* Lee & Lemieux (2010) - Regression Discontinuity Designs in Economics
* Dong & Lewbel (2013) - Identifying the Effect of Changing the Policy Threshold in Regression Discontinuity Models
* Calonico, Cattaneo & Titiunik (2014) - Robust Nonparametric Confidence Intervals for Regression Discontinuity Designs
* Keele & Titiunik (2015) - Geographic Boundaries as Regression Discontinuities
* Choi & Lee (2017) - Regression Discontinuity: Review with Extensions
* Arai et al (2019) - Testing Identifying Assumptions in Fuzzy Regression Discontinuity Designs
* Bertanha & Imbens (2019) - External Validity in Fuzzy Regression Discontinuity Designs
* Gelman & Imbens (2019) - Why High-Order Polynomials Should Not Be Used in Regression Discontinuity Designs



