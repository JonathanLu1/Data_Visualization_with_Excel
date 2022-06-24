# Data_Visualization_with_Excel

1. Project Overview:

The contents of the project analyze a range of different types of creative projects, such as music, games, and movies, that require funding and analyze the success of the funding for the projects. These projects are supposedly new and innovative ideas that require a certain amount of funding (the goal) to create a product that can be used and perhaps enhanced with further support after they are created. The data provided takes each product and depicts the success or failure of the funding. It shows the total amount of support and actual raised funds to aid with the creation of the product. From this data set, we are able to see the different types of products and the amount that is needed to be created. With this information we are able to see if the funding was a success or a failure based by comparing the goal to the actual raised funds. 

2. Analysis of Outcomes by Date:

In the analysis of this data set, we can take the different categories of creative projects and see the success and failures of each one. We first created a pivot table adjusting the data with different categries displaying the different values to see the impact of different variables determining the success or failure of the projects. One of the ways that we determined the success and failure of these different projects were by organizing them by date. 

2.1 Line Graph of Theater outcomes by Date:
![image](https://user-images.githubusercontent.com/107448860/175468157-83bf5d3c-c3e1-4b2f-9e2d-a954cc66978e.png)
When taking a look at this graph, we can see a trend in the outcomes of the Theater category of these projects. The data set provided ranges from years 2009 to 2017. We can see an increasing amount of theater projects starting from 2009 to 2015. At 2015, the amount of successful creative projects dealing with theaters that required funding peaked at nearly 300. Although the total amount of projects peaked, it shows that the percentage of successes closely followed with failed attempts. 

2.3 Line Graph of Music Outcomes by Date:
![image](https://user-images.githubusercontent.com/107448860/175467853-6a471022-3995-40ff-bcad-94f5b307ddcb.png)
Comparing music to the theater category, we can see that it peaked in 2012 instead of 2015. The biggest difference comes from the amount of sucessful fundings versus the amount of cancelled and failed projects. The amount of success was not as closely followed with other failed projects meaning that perhaps the barriers of entry to the music industry was much lower than theater. 

2.4 Line Graph of Publishing Outcomes by Date:
![image](https://user-images.githubusercontent.com/107448860/175468780-3d033520-04e4-4765-a3ba-12b2696503c9.png)
When we take a look at publishing of books, we can see that the success of these are extremely rare, and exactly on 2015 where theater was thriving, publishing was in its worst time, where funding was hard to find and many projects did not receive enough to be created.

2.5 Conclusion from analysing with Date:
When we analyze the data using the date based on years, we can see the different trends that different categories had and even compare them to different categories. Many companies can take this data and use it to make a decision on what type of products and projects they want to take on to generate the most support. They are not only able to take a look at the success to failure ratio of a certain category, but they are also able to compare different cateogries and determine which one is more successful based on the time period. 

3. Analysis of Outcomes Based on Goals:

The second portion of this project is to analyze the compare the amount needed for funding to the success rate of the projects. To separate the data in even data sets, we incremented the goals by $5000, ranging from $0 to $50,00 and compared it to the percentage of either success, failure, or cancellation based on each increment. 

3.1 Line Graph of Outcomes Based on Goal:
![image](https://user-images.githubusercontent.com/107448860/175470019-88f476cb-c46d-4a89-8155-8d39039870c0.png)
After looking at this graph, is seems to clearly depict the relationship between success, failure, or cancellation. The amount of successes seem to start at an extremely high point of 70% at a funding of $1,000 or less. When the funding amount begins to increase, the number of successful projects begin to decline. The failed projects have an inverse relationship to the successes, where there are less failed projects at lower funding goals and hit thje highest point when it reaches a $50,000 or more funding goal. The cancelled projects follow the same trend as the failed projects, but it increases at a much slower pace than the failed projects. We can draw the conclusion that lower funding goals for projects tend to be much more successful then projects that require large amounts of funding. 

4. Challenges:

One of the biggest challenges that I ran into was determining the different categories that had impacted each other directly. Some of the categories of the data had graphs and numbers that did not coincide with the data produced from the other categories. It took some time to comb through the different categories and find data that actually had relevance and impact on the performance of the other categories. Although the pivot table does organize the data for you very fast and efficiently, it still took a fairly large amount of time to go through all the data and find comparisons between them. 

Another challenge that I had encountered was figuring out how to properly filter data on the pivot table. To this point, I still have not figured out how to change the years to months to analyze the data in a different perspective. I believe that there is good information that can be provided by analyzing the different months within a year and how they impact each category.

5. Limitations with this dataset:

Although there is a lot of good data provided by this dataset, one of the biggest limitations of the data set is the categories. The categories are very generic and a few of the projects barely dip their toes into the category that it is placed in. With each of the categories, there should be subcategories dividing them into an even more detailed genre of the subject that they are in. The generic categories that are given may skew the data because the different subcategories could have numbers that would change the accuracy of the information generated from the visualizations that are created. 

6. Additional Tables and Graphs:

We should also create a graph where we compare whether or not they hit their funding to the success or failure of the project. With this information, we may be able to see some outliers that are within this dataset and remove them because they could be outliers that may skew the data that we see. There could be projects that hit their goal and never succeeded, or projects that did not hit their goal, but still managed to be successful. We can do this by creating a column with a IF function to generate a true or false and using that to generate a graph based on goal achieved versus success and failures. 

Another additional table and graph that we can create is by using the amount of time that they had between deadline/launch and looking the amount of funds raised within that time. The funding timetable should have a large impact on the amount that could be received by the projects. Some projects had a larger funding period than others, and using that information we can see whether or not some of the projects should even be compared. 
