# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `2`

Describe the purpose of your survey:
```
This survey is designed to find out how the priorities, policy preferences, and views of undecided and indecisive voters with swing preferences across Canada change one month before the federal election, as the party seeks to maintain its lead in the polls and work toward a majority government. The political party will use these insights to improve its platform, strengthen its communication strategies, and address voter concerns.

```

Describe your target population, sampling frame, sampling units, and observational units:
```
-Target population: Canadian citizens aged 18 or older currently residing in competitive swing districts, who are eligible to vote in the upcoming federal election. 

-Sampling frame: commercial online panels,party contact lists, and supplemental mail or in person surveys if necessary. 

-Sampling units: specific households, chosen through a stratified random sampling method.

-Observational units: individual eligible voters randomly selected within each household who are then screened to determine whether they are undecided or have changed their voting preference in the past three months.
```

Your 5-10 question survey:
```
1. How likely are you to vote in the upcoming Canadian federal election? [Options: 1 - Definitely will not vote, 2 - Unlikely to vote, 3 - Somewhat likely to vote, 4 - Very likely to vote, 5 - Definitely will vote] 

2. If the federal election were today, which party’s candidate would you most likely support? [Options: Liberal Party, Conservative Party, New Democratic Party (NDP), Bloc Québécois, Green Party, People's Party, Other/Independent, Undecided]

3. What policy or commitment could our party announce in the last weeks of the campaign that would most help win your vote? [Options:  Lower grocery prices, Shorter healthcare waits, Affordable housing, Reduce immigration levels, Affordable education, None of these/something else]

4. Which statement best describes how you see our party’s current platform? [Options: It focuses on the right issues for Canada's future, It has some good ideas but lacks clarity on execution, It does not address the issues that matter to me, I do not feel informed enough about the platform]

5. Which age group do you belong to? [Options: 18–24, 25–34, 35–49, 50–64, 65 or older]

```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type:The survey used a stratified multi-stage probability sampling design. GSS Cycle 33 divided regions by province and Census Metropolitan Areas (CMAs) to cover all areas fairly.
2. Sample size: 16,149 people from across Canada completed the survey.
3. Target population: People aged 15 and older living in the ten Canadian provinces. It did not include people living full-time in institutions (like care homes, prisons, or hospitals), people on the Yukon, Northwest Territories, or Nunavut.
4. Sampling frame:The survey used a dual-frame approach, combining lists of phone numbers with Statistics Canada’s address-based Dwelling frame.
5. Survey mode(s): The survey used both online and phone methods. 
6. Timeline: Data was collected from September 4 to December 28, 2018. 
7. Response rate: The overall response rate is 41.9%.
8. Weights: The dataset includes a final person weight (WGHT_PER) that adjusts for household and person selection and non-response.
9. Data processing: Data capture occurred automatically through the system.
10. Cleaning, imputation, etc: The data were checked automatically for errors using the Social Survey Processing Environment (SSPE). Missing information, like age, sex, or income, was filled in using donor imputation methods.
11. Sources of error: There can be differences because the survey used a sample of 16,149 people instead of the whole country. Other source can be that three territories were not included.
12. Limitations, known biases, etc: The exclusion of the territories means the data cannot be generalized to Canada's northern population, and also the respondents can be subject to social desirability bias (a documented tendency to over-report their donation or give responses that can be more acceptable, even when it is not their true opinion).
13. Link to documentation and any additional sources used. 
-Statistics Canada Integrated Metadatabase (IMDB) Record Number 4430:https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&SDDS=4430

- Odesi Microdata Repository, GSS 2018 (Cycle 33) User Guide & Documentation: https://odesi.ca/en/details?id=/odesi/doi__10-5683_SP3_U1AYY0.xml
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09 February 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
