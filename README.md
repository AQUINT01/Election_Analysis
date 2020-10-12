# Election Analysis
## Overview of Election Audit:
You’ll be assisting a Colorado board of elections employee, Tom, in an election audit of the tabulated results for the U.S. Congressional precinct in Colorado.  You are tasked is to provide reports on the election results:
- Total Votes
- Total Votes per each candidate
- The percentage of votes per each candidate
- Winner of the election based on the popular vote

In the past this was usually performed in Excel but Tom’s manager wants to know if there is a way to automate this process using Python.  If successfully performed using Python, this process can be implemented to other elections, i.e. senatorial and local elections.

After all the votes are counted, your job is to generate an audit report to certify the results of this congressional race including some additional information:

1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout


## Election-Audit Results:

- A total of **369,711** votes were casted in this congressional election.

- **Breakdown of County Votes** 

![Breakdown of county votes]( https://github.com/AQUINT01/Election_Analysis/blob/main/PyPoll_Challenge_county.png)

- **Denver** county had the largest voting turnout with **306,055** votes, **82.8%**. 

- **Breakdown of Candidate Vote**

![Breakdown of candidate votes](https://github.com/AQUINT01/Election_Analysis/blob/main/PyPoll_Challenge_candidate.png)
- **Diana Degette** won the congressional election with **272,892** votes, a definitive **73.8%** win!  

  
## Election-Audit Summary:
The purpose of this project was to build a dynamic automated program using Python.  When used, this tool is able to perform complex, repetitive operations for any dataset, yielding election results.  

To apply this program to other elections, open a terminal application and follow these simple steps.


  ### Step1:
  Import the new "lection_results.csv" file in the Resources folder to replace the old file. 

  ### Step2:
  Launch VS Code and click on the *Open folder...*  from the **Welcome** Screen. Then open the folder where the "PyPoll_Challenge.py" file is located in the computer’s director.  


  ### Step3:
  Once the "PyPoll_Challenge.py" file is open run the program by clicking on the red-highlighted arrow on the upper-right corner.

  ### Step4:
  Go to the *Resources* folder and open the ***election_results.txt*** file to review updated election summary.

NOTE: This script can be modify to show more or less additional information on the ***election_results.txt*** file by updating the syntax command lines in the script. 

  Examples 

  Add *Largest County Vote Count* and *Largest County Vote Percentage* below the *Largest County Turnout* command line.
 
          f"Largest County Turnout: {winning_county}\n"
          f"Largest County Vote Count: {winning_count:,}\n"
          f"Largest County Vote Percentage: {winning_percentage:.1f}%\n")

