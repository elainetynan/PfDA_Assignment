# PfDA_Assignment
Programming for Data Analysis Assignment

About this README file
----------------------
This file has the following sections:
1. Running the Project
2. Conclusions
3. Interim Notes - Each time I worked on the project I added the date and some information about
                   the work I had completed in each particular instance. I felt this could
                   suplement the commit messages in my github repository.


Running the Project
-------------------
The project is completed in a Jupyter Notebook called PfDA_Assignment.ipynb. this is a Python 3 Jupyter Notebook.
There is nothing extraordainary about the notebook and any user should be able to run it in the normal way a Jupyter Notebook is run. All the data is stored in the folder/directory data and this folder needs to be stored in the same directory as the Jupyter Notebook so that it can run and import the data.
There were no additional libraries downloaded in creating this notebook.


Conclusions
-----------
This project was a great learning tool. Although I have been using Jupyter Notebook in the modules in this course this is the first Project I have completed where I was not entirely directed as to what to put into the notebook.
I learned about Creating a table of contents, which was actually straight forward as it is simply a list of links. I also learned of some of the limitations (and work-arounds) of Jupyter Notebook with regards to formatting and Styling the text and layout.
I also learned a great deal about various distributions, not just the ones I ioncluded in my Project, but also the ones that did not suit my data also.
Finally, as always, I learned some more really useful Python coding. I come from a coding background and thoroughly enjoy programming in any language and learning new languages. Before this course I had no experience with Python and had been trying to get the time to learn if for some years. This course has been just the thing to get me learning it.



Interim Notes
-------------


04/12/2022
----------
Completed the simulation of the data and did the conclusions.

Did some tidy up of the Jupyter notebook and completed my table of contents


03/12/2022 b
------------
Completed research section of notebook.

Worked on simulating data in 2 different distributions.

Next job is to make the grade colum dependant on the Engagement and Attendance columns.


03/12/2022
----------

Continuing with research into the type of data for grades, attendance and VLE activity of students.
Started the simulation of data for same.


02/12/2022 b
------------

Further work on the research of the distribution of grades, attendance and engagement of students.

I also resourced more of my own data in relation to student engagement.

Started the data simulation

Reading for Attendance - Grade Correlation:
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5678706/


02/12/2022 a
------------
Updated graphs to ake them easier to read.
Did some tidy up of Notebook.
Did a little more analysis on Pre-covid attendance and updated interim conclusions.


01/12/2022
----------
Worked on getting datasets on grades and attendance as well as engagement with classes. I am importing this data and plotting them in histograms to see the distribution so that I can determine the type of distribution each variable falls into.

Also doing some secondary reseacrh on the distributions for the various variables.


Possible research on distribution of grades and attendance:

https://michaelminn.net/tutorials/normal-curve-grading/

https://www.researchgate.net/figure/Distribution-of-Student-Attendance_fig1_245622925

https://www.analyticsvidhya.com/blog/2017/09/6-probability-distributions-data-science/

https://datasciencedojo.com/blog/types-of-statistical-distributions-in-ml/

https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0187078

https://www.researchgate.net/publication/245622925_Causes_and_Consequences_of_Skipping_Class_in_College
(pdf downloaded)

https://homework.study.com/explanation/high-school-gpas-are-normally-distributed-with-a-mean-of-3-06-and-a-standard-deviation-of-0-40-what-is-the-probability-of-a-randomly-chosen-student-having-a-gpa-between-3-54-and-3-80.html



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