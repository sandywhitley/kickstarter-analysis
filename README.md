# Module 1 Challenge: Kickstarting with Excel

## Overview of Project
This project analyzed completed Kickstarter campaign funding outcome success in the Theater category based on launch date and Play subcategory based on funding goals amounts.
The dataset included only campaigns in which the campaign deadline date had been met (i.e. completed). The funding outcomes included those labeled "successful", "failed" and "canceled."
The launch date range was 2009-2017 and funding goal range was from $1 to $200,000. The dataset included campaigns in several countries. 

### Purpose
The two purposes of this project were to analyze funding outcomes of completed Kickstarter Theater campaigns based on launch date and completed Play (Theater subcategory) campaigns funding outcomes based on funding goals.

## Analysis and Challenges
Since both analyses reviewed Kickstarter campaign funding outcomes, we need to understand how Kickstarter defined their funding outcome labels. Funding outcomes were labeled as successful, live, failed, or canceled. 
If the campaign deadline date had been reached, the campaigns were completed and therefore labeled as "successful", "failed", or "canceled". If the campaign deadline had not been reached, it was labeled as "live."
Since this project focused on only completed campaigns, live campaigns were excluded from both analyses.
Campaigns were defined as "successful" if the pledged to goal ratio (i.e Funding percentage) was 100% or greater and "failed" if the Funding percentage was less than 100%. 
The "canceled" campaign outcome label was determined independently of Funding percentage.

### Analysis of Outcomes Based on Launch Date
The Outcomes Based on Launch Date included the Theater category data for 2009-2017 and several countries. Since this project focused on only completed campaigns, only funding Outcomes of "successful", "failed" and "canceled" were included.
The number of successful, failed, and canceled outcomes were plotted across Launched Date months. 
The two conclusions of this analysis are Theater campaigns launched in May were the most successful and those launched in December were the least successful.

![Theater Outcomes vs Launch Date Chart](/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The Outcomes Based on Goal included only data for Plays, a Theater subcategory. The Play dataset also included 2009-2017 data, only "successful", "failed" and "canceled" campaign outcomes across all Goal data which ranged from $1 to $200,000. 
The percentage of campaigns Outcomes were plotted across the Goal ranges. The conclusion of this analysis is Plays with funding goals of less than $20,000 and between $35,000 and $45,000 had more successes than failures.

![Outcomes vs Goal Chart](/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The Theater Outcomes based on Launch Date analysis included the primary category of Theater which included subcategories of Plays, Musicals, and Spaces. 
The Outcomes based on Goals analysis included only the subcategory of Plays and "Play" was excluded from the graph title which could lead to confusion.

## Results
Q1: What are two conclusions you can draw about the Outcomes based on Launch Date?

A1: The two conclusions of this analysis are Theater campaigns launched in May were the most successful and those launched in December were the least successful.

Q2: What can you conclude about the Outcomes based on Goals?

A2: It can be concluded Kickstarter campaigns for Plays with funding goals of less than $20,000 and between $35,000 and $45,000 had more successes than failures.

Q3: What are some limitations of this dataset?

A3: The two analyses did not contain the same datasets. Outcomes based on Launch Date included the entire Theater category which included the subcategories Plays, Musicals, and Spaces.
The Outcomes based on Goals had a limited dataset including only the Plays subcategory. 
Also the Outcomes based on Goals graph did not contain "Play" in its title therefore the information could lead to confusion.

Q4: What are some other possible tables and/or graphs that we could create?

A4: In order to perform a thorough overview of Kickstarter funding outcomes for the Theater category, these are suggestions as to how the analysis could have been structured. 
Firstly, the funding outcomes of all three Theater subcategories, Plays, Musicals, and Spaces could have been compared to determine their success rankings.
Secondly, the funding success of each subcategory could have been reviewed based on launch date and goals.
This approach would have provided "an apples to apples" comparison of the Theater subcategories.
If desired, the analyses could have been further comminuted by staff pick, spotlight, country or launched year.
