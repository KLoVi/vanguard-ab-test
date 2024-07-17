# vanguard-ab-test

This project is about uncover the results from a digital experiment -A/B Test- that was set into motion from 3/15/2017 to 6/20/2017 by the Customer Experience (CX) team at Vanguard, the US-based investment management company. The main goal was to evaluate if the new design leads to a better user experience and higher process completion rates.

The A/B/ Test, was composed of two groups: 
- Control Group: clients interacted with Vanguard’s traditional online process.
- Test Group: clients experienced the new, spruced-up digital interface.
Both groups navigated through an identical process sequence: an initial page, three subsequent steps, and finally, a confirmation page signaling process completion.

The project was divided in four main steps, as following:

1. EDA and Data Cleaning of three data sets:

- Client Profiles (df_final_demo): Demographics like age, gender, and account details of our clients.
- Digital Footprints (df_final_web_data): A detailed trace of client interactions online, divided into two parts: pt_1 and pt_2, which were further merged (df_pt_1&_2_merged.csv)
- Experiment Roster (df_final_experiment_clients): A list revealing which clients were part of the grand experiment.

After performing exploration and cleaning actions in datasets, the list of clients 
a. pt_1 and pt_2, merged, cleaned and filtered: (df_pt_1&2_ABC.csv)
b. Client profiles, cleaned and filtered: ()
c. Experiment Roster, cleaned: (df_final_clients.csv)

Besides, for further steps, we decided to split the "Digital Footprints, last version" in two datasets:
- Control Group (df_control.csv) 
- Test Group (df_test.csv)

2. Performance Metrics: 

3. Hypothesis testing: 

4. Experiment Evaluation: 

5. Tableau: 


Link Kanban: https://trello.com/b/T43vX0MQ/ironhack
