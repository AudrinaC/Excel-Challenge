# Excel-Challenge

Background

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. For this project organize and analyze a database of 4,000 past projects in order to uncover any hidden trends.

This project generates insights about the Kickstart My Chart dataset and defines the outcomes by using tables, graphs, and statistical summaries. Final Workbook

Solution

Conditional formatting was implimented to fill in each cell in the "state" and "Percent Funded" column with different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live. The "Percent Funded" also is newly created to uncover how much money a campaign made to reach its initial goal.
Conditional Formating

Another column P called "Average Donation" was created that uses a formula to uncover how much each backer for the project paid on average.

Two new columns, one called "Category" at Q and another called "Sub-Category" at R, which uses formulas to split the "Category and Sub-Category" column into two-part was created.

A pivotal table was analyzed, and implemented to see the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category. In addition to that, a stacked column pivot chart that can be filtered by country based on the table has been created.

Category Stats

A new sheet with a pivot table was created and analyzed the initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category. In addition to that, a stacked column pivot chart was created that can be filtered by country and parent-category.
Subcategory Stats

The format of dates stored within the "deadline" and "launched_at" columns was converted from Unix timestamps format into Excel's date format and new columns named "Date Created Conversion" and "Date Ended Conversion" was created respectively.

A new sheet with a pivot table was created with a column of "state",rows of "Date Created Conversion", values based on the count of "state", and filtered based on "parent category" and "Years". Subsequently, a pivot chart line graph that visualizes this new table was created. "Date Created Conversion", values based on the count of "state", and filtered based on "parent category" and "Years". Subsequently, a pivot chart line graph that visualizes this new table was created.
