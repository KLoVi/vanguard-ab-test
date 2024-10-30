# Vanguard-ab-test analysis

This project analyzes the results of a digital experiment—an A/B test—conducted by the Customer Experience (CX) team at Vanguard, a US-based investment management company, from March 15, 2017, to June 20, 2017. The main objective was to determine whether a new digital design improved user experience and increased process completion rates

The A/B Test setup consisted of two groups:

**- Control Group:** Clients used Vanguard's traditional online process.

**- Test Group:** Clients used the updated, enhanced digital interface. Both groups navigated through the same process sequence: an initial page, three subsequent steps, and a final confirmation page indicating process completion.


**Project Steps:**

**1. Exploratory Data Analysis (EDA) and Data Cleaning:** Three datasets were used:

**- Client Profiles** (df_final_demo): Contained demographics like age, gender, and account details.

**- Digital Footprints** (df_final_web_data): Tracked detailed client interactions online, merged from two parts (pt_1 and pt_2).

**- Experiment Roster** (df_final_experiment_clients): Listed clients participating in the experiment.

After exploring and cleaning these datasets, cleaned versions were compiled to facilitate further analysis.


**2. Performance Metrics:** Using Python, three key performance indicators (KPIs) were calculated:

**- Completion Rate:** The proportion of users who reached the final 'confirm' step.

**- Time Spent on Each Step:** The average duration users spent on each step.

**- Error Rates:** The frequency of users navigating backward, indicating potential confusion or errors.


**3. Hypothesis Testing:** Based on the KPIs, three hypothesis tests were conducted:

Two tests focused on determining whether there was a statistically significant difference in completion rates between the control and test groups, including whether Vanguard's minimum cost-effectiveness threshold of 5% was met.

An additional test examined whether there were statistically significant differences in average age between the groups.


**4. Experiment Evaluation:** We evaluated the effectiveness of the new design and the assessment period, addressing key questions about user experience and design improvements.

**Tableau Dashboard:** Finally, a Tableau dashboard was created to visualize the A/B test results, including completion rates, time spent on each step, and error rates for both groups. Additionally, client demographic visualizations were reproduced in Tableau to complement the initial EDA conducted in Python.


Example KPI (Tableau):

![image](https://github.com/user-attachments/assets/e800d1d9-1493-4609-8204-23eca736528e)


Link-Kanban: https://trello.com/invite/b/6694cf3308ac14f029da8a61/ATTI1a0c0608b09312848303474411070ee34A45FAD3/ironhack

Link-Presentation: https://docs.google.com/presentation/d/1bnvXSfy3QBfNgh57pbH_tVHeg8G_mXOo/edit
