# vanguard-ab-test

This project is about uncover the results from a digital experiment -A/B Test- that was set into motion from 3/15/2017 to 6/20/2017 by the Customer Experience (CX) team at Vanguard, the US-based investment management company. The main goal was to evaluate if the new design leads to a better user experience and higher process completion rates.

The A/B/ Test, was composed of two groups: 
- Control Group: clients interacted with Vanguard’s traditional online process.
- Test Group: clients experienced the new, spruced-up digital interface.
Both groups navigated through an identical process sequence: an initial page, three subsequent steps, and finally, a confirmation page signaling process completion.

To aim the goal, this project was divided in four main steps, as following:

1. EDA and Data Cleaning of three data sets:

- Client Profiles (df_final_demo): Demographics like age, gender, and account details of our clients.
- Digital Footprints (df_final_web_data): A detailed trace of client interactions online, divided into two parts: pt_1 and pt_2, which were further merged (df_pt_1&_2_merged.csv)
- Experiment Roster (df_final_experiment_clients): A list revealing which clients were part of the grand experiment.

After performing exploration and cleaning actions in datasets, the list of clients 
a. pt_1 and pt_2, merged, cleaned and filtered: (df_pt_1&2_ABC.csv)
b. Client profiles, cleaned and filtered: (merged_dataframeSF_gendr2.csv)
c. Experiment Roster, cleaned: (df_final_clients.csv)

Some other Data Frame where further created to enhace and explore visualizations. Also available on the file "Datasets_cleaned".

First EDA with different graphics where performed in ("Demo_filtered").

2. Performance Metrics (on file: "KPIs").  

Three KPIs where calculating using Python:

2.1. Completion Rate: The proportion of users who reach the final ‘confirm’ step ("KPI_Completion_rate").
2.2. Time Spent on Each Step: The average duration users spend on each step ("KPI_time").
2.3. Error Rates: If there’s a step where users go back to a previous step, it may indicate confusion or an error. You should consider moving from a later step to an earlier one as an error ("KPI_errors").

3. Hypothesis testing (on file: "Hypotheses"): 

After having the metrics results, three hypotheses testing where calculated: two for the completion rate, to establish if there was a statistically significant difference between the completion rates and additionally to measure if the cost-effectiveness threshold of 5% -set as a minimum by Vangard- was also statistically significant ("Hypotheses_Completion_Rate").

We also tested if there were statistically significant average age differences between the groups that where tested (extra_hypothesis_age).

4. Experiment Evaluation: 

We reflected about the design effectiveness and the duration of the assesment, answering some addressed question (see the presentation).

5. Tableau: 

Finally we created a dashboard in Tableau showcasing the A/B test results including completion rates, time spent on each step, error rates for both the Test and Control groups. 
Additionaly we resproduce some visualizations made also in the first step of EDA in Python regarding client demographics, this time using Tableau. 


Link Kanban: https://trello.com/b/T43vX0MQ/ironhack

Link Presentatio: https://docs.google.com/presentation/d/1bnvXSfy3QBfNgh57pbH_tVHeg8G_mXOo/edit
