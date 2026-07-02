# Assignment 3

**Name of Student:** Vishnu Thangaraj  
**Roll Number:** 845488

**Date:** 18 June 2026

---

## Part 1

### 1. What have you learned from the Titanic Disaster?

#### Introduction
The Titanic disaster is one of the most significant historical examples used in statistics and machine learning. The Titanic dataset helps analyze how different factors influenced a passenger's chances of survival.

#### Key Learnings
- **Data helps identify patterns:** Statistical analysis showed that survival was not random but influenced by multiple factors.
- **Passenger class mattered:** First-class passengers had a higher survival rate than second- and third-class passengers.
- **Gender influenced survival:** Women had a much higher chance of survival than men due to the "women and children first" policy.
- **Age was important:** Children generally had better survival rates than adults.
- **Data quality is essential:** Missing values, such as age information, demonstrate the importance of cleaning data before analysis.
- **Machine learning applications:** The dataset is widely used to build classification models that predict whether a passenger survived.

#### Conclusion
The Titanic dataset teaches us how statistical analysis and machine learning can uncover meaningful insights from real-world data and support predictive decision-making.

---

### 2. Distractions are dangerous. Elaborate.

#### Introduction
Distractions reduce concentration and increase the likelihood of making mistakes. In data analysis, machine learning, and everyday life, maintaining focus is essential for achieving accurate and reliable outcomes.

#### Explanation
- Distractions reduce productivity and efficiency.
- They increase the chances of human errors during data collection and analysis.
- In machine learning projects, distractions can lead to incorrect preprocessing, poor model selection, or coding mistakes.
- In real-life situations, such as driving or operating machinery, distractions can result in serious accidents.
- Maintaining focus improves decision-making and work quality.

#### Conclusion
Distractions should be minimized because they negatively affect accuracy, productivity, and safety. Staying focused leads to better decisions and improved performance.

---

### 3. Stakeholders should be kept informed. Yes or No?

**Answer:** Yes

#### Reasons
- Stakeholders need regular updates to understand project progress.
- Clear communication helps build trust and confidence.
- Early feedback allows issues to be identified and resolved quickly.
- Keeping stakeholders informed supports better decision-making.
- It ensures that project objectives remain aligned with stakeholder expectations.
- Regular communication reduces misunderstandings and project risks.

#### Conclusion
Stakeholders should always be kept informed because effective communication contributes to project success and ensures everyone works toward the same objectives.

---

### 4. Traceability is essential. What do you think?

#### Introduction
Traceability refers to the ability to track every stage of a process, from data collection to the final result.

#### Importance
- It improves transparency and accountability.
- Errors can be identified and corrected more easily.
- It helps verify how decisions or predictions were made.
- In machine learning, traceability ensures models can be reproduced and validated.
- It supports compliance with organizational and legal requirements.
- Proper traceability simplifies maintenance and future improvements.

#### Conclusion
I believe traceability is essential because it increases reliability, accountability, and trust in both software systems and machine learning projects.

---

### 5. Documentation may have lasting benefits. True or False? Why?

**Answer:** True

#### Reasons
- Documentation explains how the system works.
- It makes future maintenance and updates easier.
- New team members can understand the project quickly.
- It records important design decisions and assumptions.
- Documentation improves collaboration among team members.
- It serves as a valuable reference for troubleshooting and future development.

#### Conclusion
Documentation provides long-term benefits by improving understanding, maintainability, collaboration, and the overall quality of a project. It is an essential part of any successful software or machine learning project.

---

## Part 2: Investigation Questions and Answers

### 1. What were the key factors that influenced passenger survival on the Titanic?

#### Answer
Several factors significantly influenced a passenger's chance of survival during the Titanic disaster. The most important factors include:
- **Gender:** Female passengers had a much higher survival rate than males due to the "women and children first" evacuation policy.
- **Passenger Class (Pclass):** First-class passengers had better access to lifeboats and therefore higher survival rates than second- and third-class passengers.
- **Age:** Children generally had a higher probability of survival than adults.
- **Fare Paid:** Passengers who paid higher fares were often in higher classes and had better survival chances.
- **Family Size:** Passengers traveling with small families had better survival rates than those traveling alone or in very large groups.
- **Embarkation Port:** The port where passengers boarded showed slight differences in survival rates due to varying passenger demographics.

#### Conclusion
The analysis shows that survival was influenced by a combination of demographic, social, and economic factors rather than chance alone.

---

### 2. How did variables such as age, gender, ticket class, and family size affect the chances of survival?

#### Answer
Each variable had a noticeable impact on survival probability.

##### Age
- Children had a higher survival rate than adults.
- Elderly passengers generally had lower survival rates.

##### Gender
- Women were significantly more likely to survive than men.
- The evacuation policy prioritized women and children.

##### Ticket Class (Pclass)
- First-class passengers had the highest survival rates.
- Second-class passengers had moderate survival rates.
- Third-class passengers experienced the lowest survival rates because of limited access to lifeboats and delayed evacuation.

##### Family Size
- Passengers traveling with one or two family members often had better survival chances.
- Those traveling alone or with very large families generally had lower survival rates.

#### Conclusion
Age, gender, ticket class, and family size all played important roles in determining a passenger's likelihood of survival.

---

### 3. Can we identify significant predictors of survival based on the available data?

#### Answer
Yes. Statistical analysis and machine learning techniques can identify the variables that best predict passenger survival.

#### Significant Predictors
- **Gender (Sex):** One of the strongest predictors.
- **Passenger Class (Pclass):** Strong indicator of survival.
- **Age:** Younger passengers generally had higher survival rates.
- **Fare:** Higher fares often indicated better survival chances.
- **Family Size (SibSp and Parch):** Influenced survival depending on the size of the family group.

Machine learning algorithms such as Logistic Regression, Decision Trees, and Random Forests can use these variables to accurately predict whether a passenger survived.

#### Conclusion
The available dataset contains several statistically significant predictors that can be used to build effective survival prediction models.

---

### 4. Are the differences in survival rates of different demographics really statistically significant to make conclusions from them?

#### Answer
Yes, statistical tests can determine whether the observed differences are significant rather than occurring by chance.

#### Evidence
- Statistical hypothesis tests (such as the Chi-Square Test and t-test) help compare survival rates among different demographic groups.
- A p-value less than 0.05 indicates that the difference is statistically significant.
- Studies of the Titanic dataset consistently show statistically significant differences based on:
  - Gender
  - Passenger class
  - Age

These findings support the conclusion that demographic characteristics had a real influence on survival.

#### Conclusion
The differences in survival rates among demographic groups are statistically significant, allowing researchers to draw reliable conclusions from the Titanic dataset. These insights also demonstrate the value of statistical analysis in understanding real-world events and building predictive machine learning models.

---

## Part 3: Statistics for Machine Learning

### Hands-On Exercise Sheet: "Exploring Statistics in the Titanic Dataset"

---

### Part 1: Descriptive Statistics

#### Mean and Median of Age and Fare
The mean provides the average value, while the median represents the middle value after sorting the data.

**Typical Results (Titanic Dataset):**
- **Mean Age:** ~29.7 years
- **Median Age:** 28 years
- **Mean Fare:** ~32.2
- **Median Fare:** ~14.45

#### Survival Rate
The survival rate is calculated using the `Survived` column.
- **Total Survival Rate:** ~38.4%
- Approximately 61.6% of passengers did not survive.

#### Age Distribution
A histogram of passenger ages shows that:
- Most passengers were between 20 and 40 years old.
- There were relatively fewer children and elderly passengers.
- The age distribution is slightly right-skewed due to older passengers.

#### Interpretation
The descriptive statistics indicate that the majority of passengers were young adults, and less than half survived the disaster. The difference between the mean and median fare suggests that a few passengers paid significantly higher fares, creating a skewed distribution.

---

### Part 2: Variance and Correlation

#### Variance and Standard Deviation of Fare
Variance measures how widely fare values are spread, while the standard deviation measures the average deviation from the mean.

**Observation:**
- Fare has a high variance, indicating large differences in ticket prices.
- The high standard deviation reflects the wide range of ticket costs across passenger classes.

#### Correlation Analysis
The correlation heatmap reveals relationships among the variables.

**Key Observations:**
- **Passenger Class (Pclass):** Has a negative correlation with survival because first-class passengers were more likely to survive.
- **Fare:** Has a positive correlation with survival since higher-paying passengers generally had better survival chances.
- **Age:** Shows only a weak relationship with survival.
- **No variable** shows a perfect correlation, indicating that survival depended on multiple factors.

#### Interpretation
Correlation analysis helps identify the strongest predictors of survival and assists in selecting important features for machine learning models.

---

### Part 3: Hypothesis Testing

#### Objective
To determine whether women had a significantly higher survival rate than men.

#### Hypotheses
- **Null Hypothesis ($H_0$):** There is no significant difference in survival rates between male and female passengers.
- **Alternative Hypothesis ($H_1$):** Female passengers had a significantly higher survival rate than male passengers.

#### Result
A two-sample t-test is performed to compare the survival rates.
- If $p\text{-value} < 0.05$, reject the null hypothesis.
- If $p\text{-value} \ge 0.05$, fail to reject the null hypothesis.

#### Interpretation
For the Titanic dataset, the p-value is typically much smaller than 0.05. Therefore, the null hypothesis is rejected, indicating that women had a significantly higher survival rate than men.

---

### Part 4: Regression

#### Logistic Regression Model
A Logistic Regression model is built using:
- Age
- Fare
- Passenger Class (Pclass)

to predict passenger survival.

#### Working
- Missing values are handled before training.
- The model learns patterns from the available data.
- Given a passenger's characteristics, it predicts whether the passenger is likely to survive.

**Example:** For a passenger aged 25 years, with a fare of 50, traveling in second class, the model predicts whether the passenger would survive based on learned patterns.

#### Interpretation
Logistic Regression is an effective classification algorithm because the target variable (`Survived`) has only two possible outcomes:
- Survived (1)
- Not Survived (0)

---

### Part 5: Reflection (100–150 words)

#### 1. Which statistical measure gave the most insight?
Among the statistical measures used in this exercise, correlation analysis provided the most valuable insight into the Titanic dataset. While descriptive statistics such as the mean and median summarized the characteristics of passenger age and fare, correlation analysis revealed the relationships between different variables and passenger survival. For example, it showed that passenger class and fare had a stronger association with survival than age. This helped identify which variables were likely to be important predictors in a machine learning model. Correlation also reduced the need for guesswork by providing numerical evidence of how variables were related. Understanding these relationships is an essential step before building predictive models because it helps in selecting meaningful features and avoiding irrelevant ones. Therefore, correlation analysis not only improved the understanding of the dataset but also served as a bridge between descriptive statistics and machine learning by highlighting the variables that contributed most to predicting passenger survival.

---

#### 2. How did hypothesis testing validate your assumptions?
Hypothesis testing was useful because it provided a scientific method for determining whether the observed differences in the data were statistically significant. In this exercise, the hypothesis test was used to compare the survival rates of male and female passengers. The null hypothesis assumed that there was no significant difference between the two groups, while the alternative hypothesis stated that women had a higher survival rate. After performing the statistical test and examining the p-value, the null hypothesis was rejected because the p-value was less than 0.05. This result confirmed that the difference in survival rates was unlikely to have occurred by chance. Instead of relying on assumptions or visual observations alone, hypothesis testing offered objective statistical evidence to support the conclusion. This process increased confidence in the findings and demonstrated how statistical methods help validate real-world observations before they are used for decision-making or machine learning model development.

---

#### 3. How does regression connect statistics to machine learning prediction?
Regression provides a direct connection between statistics and machine learning because it uses statistical relationships to make predictions from data. In this exercise, logistic regression was applied to predict whether a passenger survived based on features such as age, fare, and passenger class. The model learns patterns from historical data by estimating the influence of each predictor on the probability of survival. Unlike descriptive statistics, which summarize data, regression uses these statistical relationships to predict outcomes for new, unseen observations. This makes it one of the most widely used algorithms in supervised machine learning. Logistic regression also demonstrates the importance of feature selection, probability estimation, and statistical inference in building predictive models. By combining statistical concepts with computational algorithms, regression enables machines to learn from data and make informed predictions. Therefore, it serves as a strong foundation for many advanced machine learning techniques used in real-world applications such as healthcare, finance, and customer analytics.
