## How do we make sense of data?

Physics is an experimental science in which we make measurements and try to make sense of the data taken. Because of natural variations in the phenomenon and because of the measurements techniques, the numbers we collect generally vary. We will need to make conclusions by looking at an ensemble of data points. To do so we look at patterns and we use statistics. 

In this class, we will not assume any prior knowledge of statistics and we will not require detailed statistical calculations. Instead we will focus on knowing a few important concepts and we will focus on using statistical tools to visualize and compute for us all the important properties of our dataset. 

For example here is a data set of the age of students in an online course (this is fake, just an example). The students are marked whether they attend the World campus (WC) or the University Park (UP) campus. 

| Age       | WC or UP           | 
| :-------------: |:-------------:| 
| 19     | up | 
| 20      | up |   
| 17 | up |    
| 17     | up | 
| 18      | up |   
| 65 | up |
| 26     | up | 
| 25      | wc |   
| 40 | wc |
| 42      | wc | 
| 65 | wc |
| 30 | wc |
| 27 | wc |

Given this set of data, it looks like the UP students are younger than the WC students but it would be nice to be a bit more precise. 
Instead of computing all the statistics yourself, we will use tools to do the work for us. 

In this class we will primarily use StatKey. <a href="http://www.lock5stat.com/StatKey/" target="_blank">StatKey</a> which is a free Javascript application that is used with the textbook "Statistics: Unlocking the Power of Data". 

The first visual tool, we will learn is the **box plot** shown below. 

[ciscode|rev=1|tool=elmsmedia|item=4266|entity_type=node|render=display_mode|display_mode=image]

I will show in the video below how to create this image and what it means. On the right side next to the image are a list of statistic properties of the data. You do not need to know how to compute these numbers but you should have a basic understand of what they mean. 

* **Sample size**: Number of data points, here shown for each category UP, WC and then all together. 
* **Mean**: This is the average age. 
* **Standard Deviation**: This number quantitatively measures the spread of the data. 
* **Minimum**: This is the smallest number in the data set. 
* **Q1**: This is the first quartile. This the 25th percentile or 3/4 of the data is above Q1 while 1/4 is below
* ** Median**: This number divides the data exactly in 1/2
* **Q3**: This is the third quartile, the 75th percentile. 3/4 of the data is below Q3. 
* ** Maximum**: The biggest number in the data set.

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
The 95% rule. For most approximately symmetric data set, 95% fo the data should fall within 2 standard deviations around the mean. So a data point slightly beyond 2 standard deviations is unusual (to the 5% level). 
</lrndesign-sidenote>

The box plot is a way to visualize all this information in one graph. 

[ciscode|rev=1|tool=elmsmedia|item=4267|entity_type=node|render=display_mode|display_mode=image]

The boxplot also displays ** outliers **. These are points which are far from the range (Q3-Q1) of all the other points. They are represented by an asterisk. 

## Creating a box plot and making sense of data. 

In the following video, I will show how to create a box plot graph. You will need to do this in your lab. 

> All the data is fake but I tried to make it reasonable using real data that the average age of world campus students is 32 years old while the national average age of undergraduate students is 18-19 years old. 

[ciscode|rev=1|tool=elmsmedia|item=4269|entity_type=node|render=display_mode|display_mode=mediasvg__stretch__medium__lightboxed]

Things to remember
* you need to create a .csv file with a first row of header (a txt file can also work). For most using excel may be the easiest. 
* upload the file in StatKey. 

In the next video, I will show how outliers can have a large impact on data and it is sometimes good to not include them in the analysis. 

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
Never, never delete data. Just put it in a new column, the outliers may be crucial to understand a physical phenomena and you may need to present the data or include in a future analysis. 
</lrndesign-sidenote>


[ciscode|rev=1|tool=elmsmedia|item=4268|entity_type=node|render=display_mode|display_mode=mediasvg__stretch__medium__lightboxed]



