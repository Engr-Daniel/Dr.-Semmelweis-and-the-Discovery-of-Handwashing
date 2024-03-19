# Dr. Semmelweis and the Discovery of Handwashing
-------------------------------------------------------------
![Dr. Semmelweis.png](https://www.google.com.ng/imgres?imgurl=https%3A%2F%2Fassets.datacamp.com%2Fproduction%2Fproject_20%2Fimg%2Fignaz_semmelweis_1860.jpeg&tbnid=ep2ENGgj-1Rs3M&vet=12ahUKEwjFyLTe2ICFAxXVUqQEHf3LDx4QMygCegQIARBY..i&imgrefurl=https%3A%2F%2Fgoodboychan.github.io%2Fpython%2Fdatacamp%2F2020%2F05%2F29%2F01-Dr-Semmelweis-and-the-Discovery-of-Handwashing.html&docid=KXHAAj-CMEjnuM&w=250&h=338&q=Dr.%20Semmelweis%20and%20the%20Discovery%20of%20Handwashing%20picture&ved=2ahUKEwjFyLTe2ICFAxXVUqQEHf3LDx4QMygCegQIARBY)

In 1847, the Hungarian physician Ignaz Semmelweis made a breakthough discovery: he discovers handwashing. Contaminated hands was a major cause of childbed fever and by enforcing handwashing at his hospital he saved hundreds of lives.
The Hungarian physician, Dr. Ignaz Semmelweis worked at the Vienna General Hospital with childbed fever patients. Childbed fever is a deadly disease affecting women who have just given birth, and in the early 1840s, as many as 10% of the women giving birth died from it at the Vienna General Hospital. Dr.Semmelweis discovered that it was the contaminated hands of the doctors delivering the babies, and on June 1st, 1847, he decreed that everyone should wash their hands, an unorthodox and controversial request; nobody in Vienna knew about bacteria.


I reanalyze the data that made Semmelweis discover the importance of handwashing and its impact on the hospital using both **Python** and **R** programming

### PROJECT INSTRUCTION:
How much did handwashing reduce monthly death rates on average?

1. Load the CSV files into yearly and monthly data frames and check the data.
2. Add a proportion_deaths column to each df, calculating the proportion of deaths per number of births for each year in yearly and month in monthly.
3. Create two ggplot line plots: one for the yearly proportion of deaths and another for the monthly proportion of deaths. For the yearly plot, create a different colored line for each clinic.
4. Add a handwashing_started boolean column to monthly using June 1st, 1847 as the threshold; TRUE should mean that handwashing has started at the clinic. Plot the new df with different colored lines depending on handwashing_started.
5. Calculate the mean proportion of deaths before and after handwashing from the monthly data, and store the result as a 2x2 df named monthly_summary with the first column containing the handwashing_started groups and the second column having the mean proportion of deaths.



#### Steps Used To Approach The Project
1. Load and inspect the data
2. Add a new column with the proportions
3. Make a line plot for each data frame
4. Visualize the threshold
5. Calculate the mean proportion of deaths

### Acknowledgement
Thanks to DataCamp and ingressive(I4G) for the scholarship provide to take this project on datacamp.

