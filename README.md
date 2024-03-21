# Scientific Data Visualization



## TABLEAU TUTORIAL





### Task 1

Tutorial 1: Power Query(Data Transformation and Group By)

Group By  feature allows us to aggregate the data based on specific criteria. We will be performing Aggregation functions like sum, average, count, etc. using group by which is like SQL.


#### Step 1:- Load the 1st Dataset Named Transactions.csv and click on Transform Data.









#### Step 2:- Once you click on Transform Data it takes you to the Power Query Editor where you can make changes to the dataset.
Now, Click on New Source Located at the Top and load the rest of the Datasets.













#### Step 3:- I Have loaded 3 Datasets or Tables in total where there is no common attributes except the Date Column in the DailyDelhiClimateTest.csv










#### Step 4:- Now I want to get the columns min and max values. You can do that by using a query.
Right click and click on New Query -> Blank Query.
I have renamed the Date to permitdate. You can also rename the attributes name just by clicking on the attribute and renaming it with the other name.













#### Step 5:- You can observe a new Query1 added to the Queries tab where I have selected the transactions table to perform modifications. 
















#### Step 6:- The “=transactions” display the Transactions table. You will be able to find the Applied steps at the right side under Query settings where the steps performed in that table will be displayed. You can click on the X mark on that step if you want to remove that step from the changes made.













#### Step 7:- In add column, Click on Custom column to create a new column. But our main purpose is to perform Group by. The cells will be inserted with a 1.





#### Step 8:- Right click on the attribute and click on group By.

#### Step 9:- Go the advanced options and type the same min and max dates as shown in the fig below and select the attribute for which you want the group by function to be applied.


















#### Step 10:- Now the min date and the max date are displayed. From 1/1/2013 and 8/15/2017. You can even round the dates to the nearest day, month, and year. For ex:- 8/15/2017 can be rounded until 8/31/2017.
As my dates are already in order I don’t want to sort them again based on the years starting from 2013 to 2017.

















#### Step 11:- Change the query where the sales and onpromotion is greater than 1.
