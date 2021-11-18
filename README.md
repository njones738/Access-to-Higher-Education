# Access to Higher Education

The U.S. Department of Education's Integrated Post-Secondary Education Data System (IPEDS) collects data from post-secondary institutions receiving federal student aid through twelve interrelated survey components. In tandem, IPEDS collects information about the income, debt, and earnings of the students at the institution through aggregated tax information from the IRS and data collected by the National Student Loan Data System (NSLDS) on federal student aid. Institutions who have a Program Participation Agreement (PPA) with the Department of Education's Office of Post-secondary Education (OPE) and Federal Student Aid Office (FSA) are required to report IPEDS survey components. The College Scorecard was created to compile the data collected by IPEDS each year in order to create institution profiles. This data was updated to the most recent collected school year (2017-18) on December 2nd,2020. There is 6,806 post-secondary institutions in the College Scorecard dataset. Many metrics were collected and compiled from the IPEDS surveys. 

- __Project Purpose:__    
The purpose of this project is to study institutions with a majority of their student population receiving a Pell grant. A students eligibility for the Pell grant is based on several factors that include family-income and cost of attendance. This program is used to aid students that display a financial need while attending Post-secondary school. This project seeks to explore the outcome and effect an institution with a majority population of their student body receiving a Pell grant has on their students graduation rate, 2-year loan default rate, and dropout rate.
- __Tools used:__    
R was used to conduct parametric and nonparametric tests, clean and manipulate parameters, and visualize the data. Packages such as tidyverse, ggplot, magrittr, jmuoutliers, perms, and stats were used.
- __Results:__    
In 2016, the Brookings institute found that Pell recipients attended colleges with a higher loan default rate and a lower graduation rate. This project verified that the results the Brookings institute found in 2016 were still true for the 2017-2018 school year. In addition, I found that majority Pell institutions had a higher dropout rate and that there is an unequal relationship between the typical amount of debt accumulated by an independent and dependent student. In future research, I will explore this relationship, as well as continue in my exploration of the outcomes that we are seeing in majority Pell institutions.

## Questions

1. [Is the average Net Price of a 4-year Title IV Post-secondary institution $18,500?](https://github.com/njones738/Access-to-Higher-Education/raw/main/documents/DeliverableOne.NathanielJones.Stat4400HARDY.SP21.docx)
2. [Does the proportion of federal loan borrowers at institutions with a minority Pell schools differ from majority Pell schools?](https://github.com/njones738/Access-to-Higher-Education/raw/main/documents/DeliverableTwo.NathanielJones.Stat4400.SP21.docx)
3. [Is there a relationship between loan default rate and graduation rate quartiles?](https://github.com/njones738/Access-to-Higher-Education/raw/main/documents/DeliverableThree.NathanielJones.Stat4400HARDY.SP21.docx)
4. [Do students who are independent from their parents take on the same amount of debt as students who are dependent?](https://github.com/njones738/Access-to-Higher-Education/raw/main/documents/DeliverableFour.NathanielJones.Stat4400HARDY.SP21.docx)

## Folder structure

```
- readme.md
- data
---- collegescorecardatadictionary-2.xlsx
---- Data_Dictionary_plus_Data.xlsx
---- MERGED2018_19_PP.csv
---- RANKING_DATA.csv
- documents
---- Abstract.docx
---- DeliverableOne.NathanielJones.Stat4400HARDY.SP21.docx
---- DeliverableTwo.NathanielJones.Stat4400HARDY.SP21.docx
---- DeliverableThree.NathanielJones.Stat4400HARDY.SP21.docx
---- DeliverableFour.NathanielJones.Stat4400HARDY.SP21.docx
---- JONES.PowerPoint.FINAL.SSS2021.pptx
- scripts
---- DeliverableOne.NathanielJones.Stat4400HARDY.SP21.rmd
---- DeliverableTwo.NathanielJones.Stat4400HARDY.SP21.rmd
---- DeliverableThree.NathanielJones.Stat4400HARDY.SP21.rmd
---- DeliverableFour.NathanielJones.Stat4400HARDY.SP21.rmd
---- MASTER_CODEFILE.rmd
---- SSS.rmd
---- SSS_2.rmd
```

## Data sources and Articles

### [The CollegeScorecard dataset](https://collegescorecard.ed.gov/data/)
### [The CollegeScorecard data Dictionary](https://data.ed.gov/dataset/college-scorecard-all-data-files-through-6-2020/resources?resource=658b5b83-ac9f-4e41-913e-9ba9411d7967)
### [Average amount of grant, scholarship aid, and net price](https://nces.ed.gov/programs/digest/d19/tables/dt19_331.30.asp)
### [Unemployment Rate x Median Weekly Earnings by Degree](https://www.bls.gov/emp/chart-unemployment-earnings-education.htm)
 * These education categories reflect only the highest level of educational attainment. They do not take into account completion of training programs in the form of 
   apprenticeships and other on-the-job training, which may also influence earnings and unemployment rates. For more information on training, see the [link](https://www.bls.gov/emp/documentation/education-training-system.htm)

### [College Quality x Class Background](https://www.brookings.edu/blog/social-mobility-memos/2016/02/19/a-college-degree-is-worth-less-if-you-are-raised-poor/) 
 * It turns out that the proportional increase for those who grew up poor is much less than for those who did not. College graduates from families with an income below 
   185 percent of the federal poverty level (the eligibility threshold for the federal assisted lunch program) earn 91 percent more over their careers than high school graduates from the same income group. By comparison, college graduates from families with incomes above 185 percent of the FPL earned 162 percent more over their careers (between the ages of 25 and 62) than those with just a high school diploma.

### [College Quality x Race, Class Background](https://www.brookings.edu/research/the-stubborn-race-and-class-gaps-in-college-quality/)
 * The average black undergraduate is enrolled in a college with a graduation rate rank in the 40th centile of all colleges, compared to the 55th centile for whites, 
   and with a default rate that is 50 higher. Median alumni earnings six years after attendance are almost 10 percent higher at the colleges attended by the average white student.
 * First-generation borrowers—students with federal loans whose parents did not attend college—are more likely to attend colleges with moderately high earnings 
   outcomes but extremely poor graduation and loan default outcomes.

### [STEM Attrition](https://nces.ed.gov/pubs2014/2014001rev.pdf)
 * This Statistical Analysis Report (SAR) presents an examination of students’ attrition from STEM fields over the course of 6 years in college using data from the 
   2004/09 Beginning Postsecondary Students Longitudinal Study (BPS:04/09) and the associated 2009 Postsecondary Education Transcript Study (PETS:09). In this SAR, the term STEM attrition refers to enrollment choices that result in potential STEM graduates (i.e., undergraduates who declare a STEM major) moving away from STEM fields by switching majors to non-STEM fields or leaving postsecondary education before earning a degree or certificate.
 
### [Debt x Public or Private Institutions](https://web.stanford.edu/~kjytay/courses/stats32-aut2018/projects/College_Data.html)
 * Since the R^2 value of the relationship between the median earnings of a college’s graduates and the median family income of the college’s students is the highest 
   among the three variables examined (i.e., admit, med_fam_inc, and price), it is the better predictor of the potential economic outcome of an institution’s students.

### [Skills, Knowledge x Financial Capability](https://www.financialcapability.gov.au/files/research_factors-that-influence-capability-and-effectiveness.pdf)
 * We report that financial counsellors view confidence, self-esteem and self-belief as equally important determinants of financial capability. Also, gender and family 
   socio economic status influence an individual’s ability to engage in financially effective behavior. The results also found that adopting a short-term focus, rather than future orientation, is a key inhibitor of financial effectiveness. Consequently, it is suggested that those developing financial capability programs address these behavioral and contextual factors rather than concentrating purely on literacy.

### [Loan Default and Unemployment Rates (2013)](https://upcea.edu/wp-content/uploads/2018/03/Exploring-the-Determinants-of-Student-Loan-Default-Rates.pdf)
 * While the majority of loan defaults come from traditional college graduates or students who do not finish their degree, professional, continuing, and online 
   education units may be able to play a part in adding value to credits earned through degree completion or alternative credentialing. The latter may also play a role in helping to reduce loan defaults by increasing an employee’s value in the workplace. Other factors that could also increase value are more convenient delivery of programming through online delivery and more modular learning.

### [LinkedIn Learning’s Top Skills Companies Need](https://www.linkedin.com/business/learning/blog/top-skills-and-courses/the-skills-companies-need-most-in-2020and-how-to-learn-them) 
 * Soft skills: Creativity, persuasion, collaboration, adaptability, emotional intelligence
 * Hard skills: Blockchain, cloud computing, analytical reasoning, artificial intelligence, UX design, business analysis, affiliate marketing, sales, scientific 
   computing, video production

### [Classification of Instructional Programs Code Documentation](https://www.ice.gov/sites/default/files/documents/stem-list.pdf) 
 * The U.S. Department of Homeland Security (DHS) STEM Designated Degree Program List is a complete list of fields of study that DHS considers to be science, 
   technology, engineering or mathematics (STEM) fields of study for purposes of the 24-month STEM optional practical training extension described at 8 CFR 214.2(f).
 
### [Definition of “Heightened Cash Monitoring”](https://studentaid.gov/data-center/school/hcm)
 * The U.S. Department of Education (ED) may place institutions on a Heightened Cash Monitoring (HCM) payment method to provide additional oversight of cash 
   management. Heightened Cash Monitoring is a step that FSA can take with institutions to provide additional oversight for a number of financial or federal compliance issues, some of which may be serious and others that may be less troublesome.

### [Definition of Public “non-profit”](https://www.edmit.me/blog/whats-the-difference-between-a-for-profit-and-a-nonprofit-university)
 * By definition, public universities, which are mainly funded by state governments, are not-for-profit.

### [Why we think there are zeros for the variables PCTFLOAN and PCTPELL: students mistakenly are not applying](http://www.collegescholarships.org/loans/community.htm)
 * “Many community college students mistakenly believe that they are not eligible to benefit from college financial aid programs. Consequently, they fail to fill out 
   and submit their Free Application for Federal Student Aid.”
 * “The Federal Direct Loan Program provides low interest loans to students at every stage of their college career.”

### [Why we think schools that allocated more to instructional expenditures give a better education than not](https://files.eric.ed.gov/fulltext/EJ973834.pdf)
 * “School districts that spent less than 60% on instruction had lower passing rates in all five subject areas than districts that spent more than 65%.”
 * “Further, the less than 60% expenditure districts had statistically significant lower Math passing rates scores than the 63-63.99% expenditure districts.”





