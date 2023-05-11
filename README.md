# Election Analysis Challenge

## Overview of Election Audit
The election audit results have been submitted to the election commission, however, they have requested we provide additional data to complete the audit. Utilizing Python and working from a csv we want to use for loops and conditional statements to find the comission's requested results to create a final text file of the results. 
### Additional Data Needed
- Voter turnout for each county
- Percentage of votes from each county out of the total count
- County with the highest turnout

## Election Audit Results
![Election Results](https://github.com/Jall3n/Election_Analysis/assets/119149740/bf8b3e5f-8426-4674-95fd-bbe9f5523f28)

- Total Votes: 369,711
- Highest County Votes: Denver with 82.8% or 306,055 votes
- Winner: Diana DeGette with 73.8% or 272,892 votes

## Election Audit Summary

The initial code was looking for the winning candidate data. However, to expand upon and make the results more dynamic we wanted to pull in the county data. Especially, since having the county data helps determine where the largest contributors are located.

Additionally, the commission can potentially add in county population, age, demographics, and socioeconomic status. Expanding upon this data can help the winner and future candiates pip point areas of interest.

Create a county list and county votes dictionary.

    county_list = []
    county_votes = {}

Track the largest county and county voter turnout.

    largest_county = ""
    largest_county_votes = 0
    largest_county_percentage = 0


## Challenge
### Import os: 
I was struggling to load the csv and save the file to the os path using the method below. So, for a solution I input the file path and removed os.path.join

Add a variable to load a file from a path.
- file_to_load = os.path.join("Resources", "election_results.csv")

Add a variable to save the file to a path.
- file_to_save = os.path.join("analysis", "election_analysis.txt")

        file_to_load = '../UNC_Bootcamp/0-Modules/Module-3/Code/Resources/election_results.csv'
        file_to_save = '../UNC_Bootcamp/0-Modules/Module-3/Code/analysis/election_results.txt'




1. https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
2. https://docs.python.org/3/library/os.html
