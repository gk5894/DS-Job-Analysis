# Job-finder

The objective of this project is to study and analyze current Data Science job market in east-coast cities. I have developed a python web crawler which will help you obtain the data from indeed.com
The python notebooks are used to perform the NLP and EDA analysis on the gathered data.

### Steps

 - Open Terminal
 - Clone the repository using  `git clone https://github.com/gk5894/Job-finder.git`
 - Go to the 'Job-Finder' directory using `cd Job-Finder`
 - Run python script __GetData.py__ using `python GetData.py` or use `python3 GetData.py` if you have python 2 as default compiler
 - The data will be populated in the csv files. 
 - You can change the cities and job titles by editing the *city_set* and *job_set* parameter in __GetData.py__.
 - Run the __Job Analysis.pynb__ notebook to see the results.
 
I have also created a static Tableau Dashboard using this data for a visual representation of the findings.
- Dashboard Link - https://public.tableau.com/profile/gaurav.kshirsagar#!/vizhome/DataScienceJobinEast-Coast/Dashboard1?publish=yes
