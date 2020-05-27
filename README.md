# Employee Absenteeism
Employee Absenteeism at work analysis and prediction using Python, MYSQL, Tableau

# Problem Statement
As a whole the purpose of this business exercise will be to explore whether a person presenting certain characteristics is expected to be away from work at some point in time or not.

From a business perspective the exercise will address absenteeism at a company during work time. The problem is that the business environment of today is more competitive than it used to be. This leads to increased pressure in the workplace. Therefore, it is reasonable to expect that unachievable business goals and an elevated risk of unemployment can raise people's stress levels.
Often the continuous presence of such factors becomes detrimental to a person's health. Sometimes this may result in minor illness which of course is not desired. However, it may happen that the employee develops a long-term condition. An example being depression.

That being said since I will be solving the problem from the point of view of the person in charge of productivity in the company I will not focus on that facet of the problem. Rather I will look at predicting absenteeism from work. More precisely we would like to know whether or not an employee can be expected to be missing for a specific number of hours in a given work day. Having such information in advance can improve our decision making how by reorganizing the work processing a way that will allow us to avoid a lack of productivity and increase the quality of work generated in our firm.


# Technical Explanation


# a.Data Pre-processing:
First, data in ‘Absenteeism_data.csv’ file is being pre-processed and make it to a usable state(‘df_preprocessed.csv’) to apply a machine learning algorithm.

# b.Apply machine learning algorithm on processed data:
apply a statistical model that will deliver predictions based on the data and saved the code in a module called the ‘absenteeism module’.

# c.Loading the ‘absenteeism module’ and integrating Python and SQL:
Load the ‘absenteeism module’ and use its methods to obtain predictions. At the end, export the final version of the data set as a *.csv file that will be ready for further analysis and visualization.

# d.Analyzing the predicted outputs in Tableau:
At last, I will use Tableau to analyse three separate dependencies between the inputs of our model.

