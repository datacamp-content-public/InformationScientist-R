---
title: Template Chapter 1
description: >-
  This is a template chapter.


---
## Exercise 1 - Loan Risk

```yaml
type: NormalExercise
lang: r
xp: 100
skills: 1
key: c809db5a61
```

At PNC, we provide many types of loans for our customers. In the attached (fictitious) dataset, there are three types of loans represented, each with an associated Risk Score, Percent of Principal Remaning, and a Probability of Default score. Please use this data to complete the following exercise.

`@instructions`
For each type of loan and risk score, we want to know how each is performing both within and across groups. 
- Summarize the results of each group
- Determine the effect that loan type and risk score have on the performance of loans (i.e. remaining two variables). 
- Present all relevant (or interesting) findings in the form of plots or tables. Be prepared to explain your results.

When you are finished, copy and paste your code into the Skype chat and send to the interviewer.

`@hint`


`@pre_exercise_code`
```{r}
# File name: LoanRiskAssessment.csv
```








---
## Exercise 2 - HQLA

```yaml
type: NormalExercise

xp: NaN

key: ec0782eb02
```

Another area central to the Risk Management team here at PNC is managing High Qualaity Liquid Assets (HQLA). A certain percentage of our assets are required to be HQLA. Use the attached dataset to complete the following exercise. For this exercise, we have a dataset that has the following relevant variables: Date, Security_Identifier, Dummy_CUSIP, Balance, Legal_Entity, Portfolio_Classification_Type	Portfolio_Identifier,  and an HQLA_Eligible_Flag.

`@instructions`
Normally we would use the previous variables to determine whether an asset was flagged as HQLA or not (Y/N). Here, we would like you to build a model(s) to determine how HQLA status is derived. Specifically, we would like to know: 
- Which variables are important in determining HQLA status? 
- Can you determine which values for those variables lead to a "Y" status?

When you are finished, copy and paste your code into the Skype chat and send to the interviewer.

`@hint`



`@sample_code`
```{}
# File name: HQLA.csv
```






