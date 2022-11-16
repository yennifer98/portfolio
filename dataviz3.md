# Part 1. Original Data Visualization
The original data visualization is fetched from the site: https://www.kaggle.com/code/joshuaswords/awesome-hr-data-visualization-prediction.
And the graph is shown as below:
![original graph](/original.png)


# Part 2. My thoughts
I think this graph is not that effective, because:
1. From the perspective of usefulness, the HR really needs the information in an intuitive and clean manner so that it could help make their decision efficiently. However, there are two many information of redundancy given the plot.
2. From the perspective of perceptibility and intuitiveness, it is even worse since the plot is using the colors of almost the same gray level to represent the difference. If I had the chance, I would try to plot the heatmap (or other format of the visualization in a much more efficient manner) using two different contrast colors.
Therefore, I have two thoughts on how to improve it:
1.  I would like to change the color set from the original one to the color set of different contrast manner.
2.  I would like to change the visualization manner to remove redundancy. Instead of the heatmap I might consider to use the bar plots (or frequency plots) for each company size, spanning all YOEs. We can observe a spike at the tail of each frequency plot, which could provide us a good view for the conclusion of the plot.

# Part 3. Wireframe
![version 1 graph](/ver1.png)

# Part 4. Feedback
- Student, mid 20’s:
This plot shows the distribution of the employees spanning across different type of companies. I think the major audience should definitely be the HRs or Analyst who want to learn the general insights of the employee patterns. 
BTW, I think there are some little flaws for the dimension of company size. The <10 entry seems to appear in the wrong position in the graph, since we should keep the entry in increasing order. As a result, I would like to put the row of <10 size under the row of 0 size. 

- Adult, mid 30’s:
The illustration does convey the information where employees with >20 YOE dominate the companies of all sizes in a plain and elegant manner. However, the raw title “Company size & Employee Experience” has poorly covered the information directly related to the semantics. Furthermore, we have few context about what the numbers in the heat map grid represent for, resulting in my confusion on understanding the details. 
I think the major audience for this would be the analyst from HR team, who would like to know more insights from the distribution so as to make their decision. As a result, I would like to change the title so that it could cover the interpretation of this plot so as to outline the most important message I want to convey.

# Part 5. Re-design
![version 2 graph](/ver2.png)

# Part 6. Summary
- Compare and Contrast of the feedback
From the feedback, we can see that in general the plot has convey the message successfully. However, we still have something to improve to make the illustration more concise, precise and to the point.
As a result, I would like to make the following redesign considerations:
1. Move the row with <10 company size just under the row of 0 size
2. Change the title so as to include the interpretation of the plot
