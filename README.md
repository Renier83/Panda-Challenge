# Panda-Challenge
Bootcamp Data Set, Pt. 1
In this assignment, you will consolidate your knowledge of Pandas and NumPy by cleaning a data set containing over 15,000 records.

Instructions
The goal for this assignment is to recreate BootcampOutputPart1.xlsx.

Using Pandas, load the CSV provided in Resources

Create a new table using the following columns: [0, 1, 2, 3, 4, 7, 8, 9, 10, 11, 29, 30, 32, 36, 37, 45, 48, 56, 110, 111].

The data set currently uses 0.0 to represent "No" or "False", and "1.0" to represent "Yes"/"True"—an entry of 0.0 for row 2 in the Attended Bootcamp column, for instance, indicates that the respondent with ID 2 did not attend a bootcamp. Replace all instances of "0.0" with No, and all instances of "1.0" with "Yes".

Calculate the total number of respondents in the subtable you built.

Create a table out of the rows corresponding only to people who did attend a bootcamp.

Calculate the number of people who attended a bootcamp.

Calculate the average age of bootcamp attendees.

Calculate the number of bootcamp attendees who self-identify as male; female; or neither.

Calculate the number of bootcamp attendees who hold college degrees.

Calculate the percentage of respondents who attended a bootcamp.

Calculate the percentage of people who attended a bootcamp and hold a college degree.

Calculate the average post-bootcamp salary.

Create a new, two-row table collecting the above data.

Use the format method to prettify your table—i.e., use format to display percents as percents; display numbers to a reasonable number of decimal points; etc.

Finally, export the final table into an Excel file.

Hints
When extracting columns, see the documentation for iloc.

See the documentation for replace.

When extracting rows matching a certain condition, see the documentation for loc.

See the documentation for Python's format method.

![Capture2](https://user-images.githubusercontent.com/68042445/120900221-ab87c200-c601-11eb-8dd4-ef1115d74be9.PNG)


![Capture3](https://user-images.githubusercontent.com/68042445/120900224-b0e50c80-c601-11eb-8019-36a0615cbbe9.PNG)


![Capture4](https://user-images.githubusercontent.com/68042445/120900231-b5a9c080-c601-11eb-9f32-4adc61ca40ad.PNG)





Bootcamp Data Set, Pt. 2
In this activity, you will be cleaning the same data set from before, but this time, extracting different data.

Instructions
The goal for this assignment is to recreate BootcampOutputPart2.xlsx.

Using Pandas, load the CSV provided in Resources.

Create a new table using the following columns: [0, 1, 2, 3, 4, 6, 7, 8, 9, 10, 11, 29, 30, 32, 36, 37, 45, 48, 56, 110, 111].

The data set currently uses 0.0 to represent "No" or "False", and "1.0" to represent "Yes"/"True"—an entry of 0.0 for row 2 in the Attended Bootcamp column, for instance, indicates that the respondent with ID 2 did not attend a bootcamp. Replace all instances of "0.0" with No, and all instances of "1.0" with "Yes".

Extract rows corresponding only to respondents who attended a bootcamp.

Create a DataFrame with two columns: One with the bootcamp name, and one with the number of respondents who went to each bootcamp.

Create another DataFrame with two columns: One for the bootcamp name, and one for the number of respondents who recommend it.

Create a new DataFrame by merging the previous two DataFrames on the appropriate column.

In your new DataFrame, create a new column containing the percentage of respondents for each bootcamp who would recommend that bootcamp.

Sort the new DataFrame in descending order of the percentage of recommenders you just calculated.

Use map and format to make the "% Recommended" column look more presentable.

Finally, export your DataFrame to an Excel file.
