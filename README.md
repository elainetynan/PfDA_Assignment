# PfDA_Assignment
Programming for Data Analysis Assignment

30/11/2022
----------
Added more data to original dataset.
Started the import of baseline data for comparison to simulated data.
Looking at how to clean the data.

Interesting sites on data cleaning:

https://towardsdatascience.com/data-cleaning-with-python-and-pandas-detecting-missing-values-3e9c6ebcf78b

https://www.geeksforgeeks.org/drop-rows-from-pandas-dataframe-with-missing-values-or-nan-in-columns/

https://sparkbyexamples.com/pandas/pandas-drop-rows-with-nan-values-in-dataframe/

https://www.machinelearningplus.com/pandas/pandas-dropna-how-to-drop-missing-values/#:~:text=Dropping%20rows%20if%20missing%20values,names%20to%20the%20subset%20parameter.

https://stackoverflow.com/questions/49841989/python-drop-value-0-row-in-specific-columns



Possible reference site for later:
https://towardsdatascience.com/a-simple-way-to-analyze-student-performance-data-with-python-cc09c7508c4c


29/11/2022
----------
Adding data from existing sources so that when I simulate the data I can compare it to see if it is similar.

09/11/2022
----------
Some research

Poisson Distribution
"The Poisson distribution is a probability distribution that is used to model the probability that a certain number of events occur during a fixed time interval when the events are known to occur independently and with a constant mean rate." (Statology, 2021)

"You can use a Poisson distribution if:

    Individual events happen at random and independently. That is, the probability of one event doesn’t affect the probability of another event.
    You know the mean number of events occurring within a given interval of time or space. This number is called λ (lambda), and it is assumed to be constant." (Scribbr, 2022)

Possible simulated datasets for me:
1. Number of Website Visitors per Hour
2. Influenza/Covid cases per year, month, etc.


Normal Distribution
Normal distribution "is the most important probability distribution in statistics because it accurately describes the distribution of values for many natural phenomena" (Statisticsbyjim, 2018), it " is a bell-shaped graph which encompasses two basic terms- mean and standard deviation."(Studiousguy, no date)

Possible simulated datasets for me:
1. Students average grades
2. Birth Weight of babies
3. Shoe size

On further inspection I have decided to do my investigation on Students grades. In my current role I have access to information on students and am interesting is investigating the correlation between variables. The variables I will be looking at is:
•	% Attendance
•	Logon to moodle (or time on Moodle)
•	% of CA submitted
•	Grade




References
----------

Scribbr (2022) Poisson Distributions | Definition, Formula & Examples. Available at: https://www.scribbr.com/statistics/poisson-distribution/ (Accessed: 09 November 2022)

Statisticsbyjim (2018) Normal Distribution in Statistics. Available at: https://statisticsbyjim.com/basics/normal-distribution/ (Accessed: 09 November 2022)

Statology (2021) 5 Real-Life Examples of the Poisson Distribution. Available at: https://www.statology.org/poisson-distribution-real-life-examples/ (Accessed: 09 November 2022)

Studiousguy (no date) 9 Real Life Examples Of Normal Distribution. Available at: https://studiousguy.com/real-life-examples-normal-distribution/ (Accessed: 09 November 2022)