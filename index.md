# COGS 108 - Project Proposal

# Names
- Nicole Gong
- Anastasia Meadows
- Allan Dong
- Frances Sy

# Research Question
- Include a specific, clear data science question.
- Make sure what you're measuring (variables) to answer the question is clear.

This question should be specific, answerable with data, and clear. A general question with specific subquestions is permitted. (1-2 sentences). When we read this we should know clearly what your project will be about.

## Background and Prior Work

Car insurers consider age to be one of their largest liabilities. For this reason, premium rates depend on age, decreasing annually until age 75, where they increase by about 4%[^1].

In our project, we’ve chosen to analyze premium rates of those under 25 and over 75 without regard to individual ages within those groups. At age 25, insurance rate decreases become less frequent and severe. According to Progressive, starting at age 19, insurance rates decrease between 12-13% every year until age 25, where they decrease about 6% within the next five years. These rates continue to decrease until age 75 and up. 

We could only find generalized statistics for how much they increase after an accident. On average, full coverage rates increase by 42% and minimum coverage rates increase 44%. We want to determine if the increase in after-accident rates is proportional to increases based on other liabilities, specifically age. 

A similar project by GitHub user rjsaito sought to predict insurance models based on policy holders' information, including age. They categorized age on a scale of 1 through 6, with 1 being the youngest and 6 the oldest. They found that age groups 1 and 6, the youngest and oldest, had the most claims.

<a name="Progressive1"></a> **[^1]** Example footnote.

# Hypothesis

- Put your hypothesis here; this is different than your question. This is what you think the answer will be.
- Ensure that this hypothesis is clear to readers.
- Explain why you think this will be the outcome (what was your thinking?)

If the question is "What is the association between X and Y" then a hypothesis might be "We predict a strong correlation between X and Y" or you might predict no correlation or any other possible relationship.

# Data

## Variables

- Insurance Premium Rate
- Age Group 
- Accident History
- State

# Ethics & Privacy

- Thoughtful discussion of ethical concerns included
- Ethical concerns consider the entire data science process (question asked, data collected, data being used, the bias in data, analysis, post-analysis, etc.)
- How your group handled bias/ethical concerns clearly described

Before the analysis, we need to read the entire dataset and see what fields it provides to assess if any important information is being left out. We can also consider historical trends or events that may have caused biases in the data and keep them in mind as we analyze the data. 

After the analysis, we can look for any trends that don’t look normal and detect biases there. We can also see what kind of data we were missing and use it to see if that affected our analysis.

There are privacy concerns, as many people do not like their insurance and car accident information collected and published publicly. We will use an anonymous dataset where names are not published.

We may not fully eliminate inherent age-related biases, but we can mitigate some of the problem by excluding extreme cases or only analyzing cases where everything else is the same except for age.

# Team Expectations

Read over the [COGS108 Team Policies](https://github.com/COGS108/Projects/blob/master/COGS108_TeamPolicies.md) individually. Then, include your group’s expectations below:

- *Team Expectation 1*
- *Team Expectation 2*
- *Team Expectation 3*

# Project Timeline Proposal

| Meeting Date  | Meeting Time| Completed Before Meeting  | Discuss at Meeting |
|---------------|-------------|---------------------------|--------------------|
| 10/20         | 6 PM        | Read & brainstorm topics  | Finalize topic, hypothesis, background research | 
| 10/28         | 5 AM        | Background research       | Ideal dataset(s) and ethics, draft proposal | 
| 10/30         | 9 PM        | Edit, submit proposal     | Wrangling, analytical approaches, assign tasks  |
| 11/4          | 5 PM        | Import & wrangle data     | Review/edit wrangling/EDA, analysis plan |
| 11/18         | 5 PM        | Finalize wrangling, EDA   | Analysis, project check-in |
| 11/25         | 5 PM        | Complete analysis         | Edit full project |
| 12/2          | Before 11:59 PM | NA                    | Turn in project & surveys |
