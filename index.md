---
papersize: a4
documentclass: scrartcl
classoption: DIV=14
colorlinks: true
---
  
<!-- ![LSE](images/lse-logo.jpg) -->
<!-- # MY457 Causal Inference for Observational and Experimental Studies  -->
  
### Instructors

* Course convenor and lecturer: [Dr. Daniel de Kadt](mailto:d.n.de-kadt@lse.ac.uk), Methodology.
* Seminar leader: [Dr. Michael Ganslmeier](mailto:m.g.ganslmeier@lse.ac.uk), Methodology.
* GTA (no office hours): [Pedro Torres-Lopez](mailto:p.torres-lopez@lse.ac.uk), Social Policy. 

Office hour may be booked via LSE's StudentHub. If you have questions or concerns about class material, problem sets, or the exam, please use the [class forum on Moodle](https://moodle.lse.ac.uk/mod/forum/view.php?id=1232310). We will not reply to emails about the course material, but we will reply promptly to questions posted on the forum. Of course, if you questions or concerns are of a private or personal nature, please do email or attend office hours. 

### Readings and textbooks

There is a reasonable amount of reading for this class, especially in the early weeks. You are strongly encouraged to do the reading **before class**, paying close attention to details (i.e., do not skim over equations). In addition to some key articles, throughout the term we will dip into three main textbooks, which we will refer to by their acronyms: 

* **MHE**: Angrist and Pischke, _Mostly Harmless Econometrics: An Empiricist's Companion_, 2009, Princeton University Press. 
* **CIS**: Imbens and Rubin, _Causal Inference for Statistics, Social, and Biomedical Sciences_, 2015, Cambridge University Press. 
* **TE** Huntington-Klein, _The Effect: An Introduction to Research Design and Causality_, 2022, CRC Press. 

If you are particularly interested in the course material, there will be additional readings set from the following textbooks (as well as a few articles): 

* **CMRI**: Pearl, _Causality: Models Reasoning and Inference (2nd Ed)_, 2009, Cambridge University Press.
* **CISAP**: Pearl, Glymour, and Jewell, _Causal Inference in Statistics: A Primer_, 2016, Wiley.
* **CIWI**: Hernan and Robins, _Causal Inference: What If_, 2020, Routledge. 

_Note_: if you are particularly interested in graphical models and their application to causal inference, it is strongly recommended that you do all the readings from either CMRI or CISAP. CMRI is extremely technical and dense, while CISAP is a gentler (though not that gentle) introduction to some of the basics introduced in CMRI. If there are suggested readings from both books, you should choose either, not both.

### Formative problem sets

Statistics is best learned by doing. Formative problem sets will be released every two weeks at 5pm, after seminar. You must submit one week later at 5pm, on **Moodle**. Your submission should be written in **RMarkdown**, and must be a **knitted .pdf**, formatted as shown in this [problem set template](psets/template/pset_template.Rmd). If you do not follow the formatting requirements your problem set will not be marked. Comments will be returned via Moodle within two weeks of submission. 

|  |  Type | Release date | Due date  |
|:--:|:-------:|:-----:|:-----|
| 1 | [Formative problem set 1](#problem-set-1) | 25 January 2023 - 5pm | 1 February 2023 - 5pm |
| 2 | [Formative problem set 2](#problem-set-2) | 8 February 2023 - 5pm | 15 February 2023 - 5pm  |
| 3 | [Formative problem set 3](#problem-set-3) | 29 February 2023 - 5pm | 7 March 2023 - 5pm  |
| 4 | [Formative problem set 4](#problem-set-4) | 14 March 2023 - 5pm  | 21 March 2023 - 5pm  |
| 5 | [Formative problem set 5](#problem-set-5) | 28 March 2023 - 5pm | 4 April 2023 - 5pm  |

### Quick links to lectures

| Week |  Topic |  
|:--:|:-------|
| 1  | [Causal Frameworks](#1-causal-frameworks) |   
| 2  | [Randomization](#2-randomization) | 
| 3  | [Selection on Observables 1](#3-selection-on-observables-1) | 
| 4  | [Selection on Observables 2](#4-selection-on-observables-2) | 
| 5  | [Selection on Observables 3](#5-selection-on-observables-3) | 
| 6  | _Reading week_ |  
| 7  | [Difference-in-Differences 1](#7-difference-in-differences-1) |
| 8  | [Difference-in-Differences 2](#8-difference-in-differences-2) | 
| 9  | [Instrumental Variables 1](#9-instrumental-variables-1) |  
| 10 | [Instrumental Variables 2](#10-instrumental-variables-2) |  
| 11 | [Regression Discontinuity](#11-regression-discontinuity) | 

### Quick links to seminars

| Week |  Topic | 
|:--:|:-------|
| 2  | [Causality and Randomization](#seminar-causality-and-randomization) |  
| 4  | [Selection on Observables](#seminar-selection-on-observables) |
| 7  | [Difference-in-Differences](#seminar-difference-in-differences) |
| 9  | [Instrumental Variables](#seminar-instrumental-variables) |  
| 11 | [Regression Discontinuity](#seminar-regression-discontinuity) | 

### Detailed course schedule

_Note:_ Links to slides and code will be updated/added in advance of each week's teaching.

#### 1. Causal Frameworks

This week begins with an introduction to the class, both substantively and administratively. 

We then introduce the potential outcomes framework, which will provide the technical foundations that are used throughout the rest of the class. We will also briefly introduce the graphical approach to causal inference. 

##### Lecture

- [Lecture Slides - Introduction](slides/L1_intro.pdf)
- [Lecture Slides - Causal Frameworks](slides/L1_causalframeworks.pdf)

##### Readings
* MHE: Chapter 1
* CIS: Chapters 1, 2, and 3.1
* TE: Chapter 6 

##### Additional readings
* [Holland, P.W., 1986. Statistics and causal inference. _Journal of the American statistical Association_, 81(396), pp.945-960.](https://www.jstor.org/stable/2289064) (highly recommended)
* CISAP: Chapters 1 & 2 or CMRI: Chapters 1 & 2 
* TE: Chapters 1 & 2

#### 2. Randomization

This week we will introduce the concept of randomization and its value for causal inference. We will discuss, at a high level, design, analysis, and inference in randomized experiments. 

##### Lecture

- [Lecture Slides - Randomization](slides/L2_randomization.pdf)

##### Seminar: Causality and Randomization

- [Seminar Paper](seminars/seminar1/paper/MY457_seminar1_paper.pdf) 
- [Seminar Slides](seminars/seminar1/slides/MY457_intro_seminars.pdf)
- [Seminar Code](seminars/seminar1/coding/seminar1_randomized_experiments.Rmd)
- [Seminar Questions](seminars/seminar1/paper/MY457_seminar1_questions.pdf)

##### Readings
* MHE: Chapter 2
* CIS: Chapters 3 & 4
* TE: Chapters 7 & 8

##### Additional readings
* CISAP: Chapter 3 OR CMRI: Chapters 3 & 4 

##### Problem Set 1
- [Problem Set](psets/pset1/pset1.pdf)
- [Data](psets/pset1/how_to_elect_more_women.dta)
- [Solution Set](psets/pset1/pset1_solutions.pdf)

#### 3. Selection on Observables 1

This week we will depart from the safe shores of randomization, into the dangerous waters of observational research design. We will begin with a theoretical exploration of the selection on observables design -- its assumptions and identification results -- using both potential outcomes and graphical theory. 

We will then begin an extended discussion (which will continue next week and the week after) of estimation of causal estimands in this setting, focusing first on subclassification. **Update**: Please note that we did not cover subclassification in the lectures. You can still read the slides to see how it works, but it will not be examinable this year. 

##### Lecture

- [Lecture Slides - Selection on Observables 1](slides/L3_soo_part1.pdf)

##### Readings
* MHE: Chapter 3
* CIS: Chapters 12, 13, 18
* TE: Chapter 14

##### Additional readings
* [Cinelli, C., Forney, A., & Pearl, J. (2022). A Crash Course in Good and Bad Controls. Sociological Methods & Research](https://doi.org/10.1177/00491241221099552) (highly recommended)
* CISAP: Chapter 4 or CMRI: Chapter 5

#### 4. Selection on Observables 2

This week we will consider the three core estimation strategies for selection-on-observables designs: matching (including propensity scores), weighting, and regression. 

##### Lecture

- [Lecture Slides - Selection on Observables 2](slides/L4_soo_part2.pdf)

##### Seminar: Selection on Observables

- [Group allocation](seminars/group_allocation_for_presentations.xlsx)
- [Seminar Code](seminars/seminar2/coding/Class02-MatchingAndWeighting.Rmd)
- [Seminar Paper](seminars/seminar2/paper/MY457_seminar2_paper.pdf) 
- [Seminar Questions](seminars/seminar2/paper/MY457_seminar2_questions.pdf)

##### Readings
* MHE: Sections 3.2 and 3.3
* CIS: Chapter 13
* TE: Chapter 14

##### Additional readings
* TE: Chapter 13 (gentler introduction to regression)
* [Lin, W. (2013). Agnostic Notes on Regression Aadjustments to Experimental Data: Reexamining Freedman’s Critique
. Annals of Applied Statistics](https://doi.org/10.1177/00491241221099552](https://projecteuclid.org/journals/annals-of-applied-statistics/volume-7/issue-1/Agnostic-notes-on-regression-adjustments-to-experimental-data--Reexamining/10.1214/12-AOAS583.full)https://projecteuclid.org/journals/annals-of-applied-statistics/volume-7/issue-1/Agnostic-notes-on-regression-adjustments-to-experimental-data--Reexamining/10.1214/12-AOAS583.full) (very technical but worth reading if interested in regression adjustment) 
* [Abadie, A. & Imbens, G. (2006). Large Sample Properties of Matching Estimators for Average Treatment Effects. Econometrica.](https://doi.org/10.1111/j.1468-0262.2006.00655.x) (if you want to understand matching bias -- very technical)
* [King, G. & Nielsen, R. (2019). Why Propensity Scores Should Not Be Used for Matching. Political Analysis.](https://doi.org/10.1017/pan.2019.11) (a critique of propensity score matching)

##### Problem Set 2
- [Problem Set](psets/pset2/pset2.pdf)
- [Data](psets/pset2/dollars_on_the_sidewalk.dta)

#### 5. Selection on Observables 3

This week we will consider partial identification and sensitivity analysis. 

##### Lecture

- [Lecture Slides - Selection on Observables 3](slides/L5_soo_part3.pdf)

##### Readings
* [Manski, C.F., 1990. Nonparametric bounds on treatment effects. The American Economic Review, 80(2), pp.319-323.](https://www.jstor.org/stable/2006592) (very technical but worth reading, even if only for the intuition.)
* [Imbens, G. W. (2003). Sensitivity to exogeneity assumptions in program evaluation. American Economic Review, 93(2), 126-132.](https://www.jstor.org/stable/3132212)
* [Cinelli, C., & Hazlett, C. (2020). Making sense of sensitivity: Extending omitted variable bias. Journal of the Royal Statistical Society Series B: Statistical Methodology, 82(1), 39-67.](https://academic.oup.com/jrsssb/article/82/1/39/7056023)

##### Additional readings
* [Rosenbaum, P. R., & Rubin, D. B. (1983). Assessing sensitivity to an unobserved binary covariate in an observational study with binary outcome. Journal of the Royal Statistical Society: Series B (Methodological), 45(2), 212-218.](https://www.jstor.org/stable/2345524) (technical but foundational)
* [Duarte, G., Finkelstein, N., Knox, D., Mummolo, J., & Shpitser, I. (2023). An automated approach to causal inference in discrete settings. Journal of the American Statistical Association, (just-accepted), 1-25.](https://www.tandfonline.com/doi/pdf/10.1080/01621459.2023.2216909) (very technical but very interesting)

#### 6. Reading Week

#### 7. Difference-in-Differences 1

We now introduce situations in which a treatment is rolled out such that we have variation over two dimensions: _time_ and _units_. Instead of relying on conditional ignorability in treatment assignment between units, we will now rely on assumptions about trends over time. In week 1 we will focus almost exclusively on canonical cases in which we have only two time-periods and two treatment groups of units. We will close by briefly considering falsification tests in situations with two pre-treatment periods.

##### Lecture

- [Lecture Slides - Difference-in-Differences 1](slides/L7_DinD_part1.pdf)

##### Seminar: Difference-in-Differences

- [Seminar Code](seminars/seminar3/coding/Class03-DifferenceInDifferences.Rmd)
- [Seminar Data](seminars/seminar3/coding/simdata.rds)
- [Seminar Paper](seminars/seminar3/paper/MY457_seminar3_paper.pdf) 
- [Seminar Questions](seminars/seminar3/paper/MY457_seminar3_questions.pdf)

##### Readings
* MHE: Section 5.2
* TE: Chapter 18

##### Additional readings
* [Card, D., & Krueger, A. B. (1993). (1994). Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania. The American Economic Review, 84(4), 772-793.](https://davidcard.berkeley.edu/papers/njmin-aer.pdf) (foundational example)
* [Bertrand, M., Duflo, E., & Mullainathan, S. (2004). How much should we trust differences-in-differences estimates?. The Quarterly journal of economics, 119(1), 249-275.](https://academic.oup.com/qje/article-abstract/119/1/249/1876068) (classic focused on inference)
* [Roth, J. (2022). Pretest with caution: Event-study estimates after testing for parallel trends. American Economic Review: Insights, 4(3), 305-322.](https://www.aeaweb.org/articles?id=10.1257/aeri.20210236) (technical, focused on issues with pre-trend tests)

##### Problem Set 3
- [Problem Set](psets/pset3/pset3.pdf)
- [Data](psets/pset3/Norway-MSD.dta)

#### 8. Difference-in-Differences 2

Continuing with difference-in-differences, in week 2 we broaden our focus to cases with more than 2 time periods. We will discuss first the two-way fixed effects estimator that has been a dominant tool for estimating 'generalised difference-in-differences' and then explore the implied assumptions in this approach and its weaknesses, specifically staggered and non-saturating treatments, and heterogeneous treatment effects. We introduce alternative 'modern' estimators that are robust to these settings. 

##### Lecture

- [Lecture Slides - Difference-in-Differences 1](slides/L8_DinD_part2.pdf)

##### Readings
* [Baker, A. C., Larcker, D. F., & Wang, C. C. (2022). How much should we trust staggered difference-in-differences estimates?. Journal of Financial Economics, 144(2), 370-395.](https://www.sciencedirect.com/science/article/pii/S0304405X22000204) (has some quite accessible discussions)
* [Roth, J., Sant’Anna, P. H., Bilinski, A., & Poe, J. (2023). What’s trending in difference-in-differences? A synthesis of the recent econometrics literature. Journal of Econometrics.](https://doi.org/10.1016/j.jeconom.2023.03.008) (technical but a good overview)
* TE: Chapter 18, especially 18.3

##### Additional readings
* [Goodman-Bacon, A. (2021). Difference-in-differences with variation in treatment timing. Journal of Econometrics, 225(2), 254-277.](https://doi.org/10.1016/j.jeconom.2021.03.014) (very technical but parts can be read quite easily)
* [Callaway, B., & Sant’Anna, P. H. (2021). Difference-in-differences with multiple time periods. Journal of econometrics, 225(2), 200-230.](https://doi.org/10.1016/j.jeconom.2020.12.001)
* [Liu, L., Wang, Y., & Xu, Y. (2024). A practical guide to counterfactual estimators for causal inference with time‐series cross‐sectional data. American Journal of Political Science, 68(1), 160-176.](https://onlinelibrary.wiley.com/doi/full/10.1111/ajps.12723)
* [Dube, A., Girardi, D., Jorda, O., & Taylor, A. M. (2023). A local projections approach to difference-in-differences event studies (No. w31184). National Bureau of Economic Research.](https://www.nber.org/papers/w31184)


#### 9. Instrumental Variables

##### Seminar: Instrumental Variables

- [Seminar Paper](seminars/seminar4/paper/MY457_seminar4_paper.pdf) 


