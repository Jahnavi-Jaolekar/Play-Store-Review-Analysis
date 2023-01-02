# Play-Store-Review-Analysis
A complete review on the apps in google play store

PROBLEM STATEMENT

The data from Play Store apps has a great deal of potential to help app development companies succeed. Developers can get useful knowledge to work on and conquer the Android market.
Values for the following and more categories are present for each app (row). Customer evaluations of Android apps are included in another dataset.

![logo](https://user-images.githubusercontent.com/112775752/210236293-4945e0ca-9ec4-4041-bc3b-d721c27f2e1e.png)


Methodology:

![methodology](https://user-images.githubusercontent.com/112775752/210236263-91ac1369-ee45-43f9-818c-8f6e80bfac4c.png)

We collected the data of play store and user reviews from website of alma better. Our basic approach was to make a copy of original clean the data and make it ready for data analysis and data visualization. Steps will be explained in details below.

APPROACHES

Step 1:  
Viewing and cleaning data being the initials, we started with importing necessary libraries, mounting drive and storing data in variables for deriving meaningful insights. Presence of null values would have created possible errors in the further steps, making its removal or replacement a mandate task. Followed by removal of duplicate values from datasets for the same reason. 

Step 2:
Preparing was second step where we dealt with presence of unnecessary details added in data (for example: presence of M, K in size column or presence of $ in price column). We also removed columns which were not required or necessary to create visuals and for interpretation of data (for example: current_ver column was irrelevant so it was removed from the data frame)

Step 3:
Final step being data analysis and visualization, in which we determined number of categories of apps in play store, average rating, percentage of free and paid apps, highly installed categories, under that top 10 apps installed in that category. We also established expensive apps on play store, average size of apps, top 10 genres, dataset correlation, and sentiment count of user reviews.

Some relevant graphs of the project:

![top 10 categories](https://user-images.githubusercontent.com/112775752/210235873-e9e6d7db-650c-40ed-bf41-fa96e31c4237.png)

![free or paid](https://user-images.githubusercontent.com/112775752/210235897-2fefc6fa-c403-4d78-a515-c30bad6e2060.png)


![installs](https://user-images.githubusercontent.com/112775752/210236022-5c96876c-ad71-4e0d-8b55-ddffc1c994aa.png)

![heatmap](https://user-images.githubusercontent.com/112775752/210236062-091d8939-8562-44fd-9107-001ea92b8fb6.png)

![sentiment count](https://user-images.githubusercontent.com/112775752/210236086-9552ed3c-28d9-476d-b9c6-46bcf1ef76af.png)

CONCLUSION

Joining the dots from given datasets, we came across a lot of information. After analysis and visualization, information can be classified into beneficial for customers and beneficial for developers and we found out top categories of apps, which categories were highly rated, how many apps were free and paid, average size of apps, this data helps the customers/users to make a firm decision for downloading apps. As for developers’ side of information includes top categories, and apps installed, top genres, dataset correlation and regression plots, and finally sentiment counts (percentage of positive, negative and neutral reviews).
