# Anti-Cancer-Drug-Analysis

In this challenge I took on the role of a data analyst working a pharmaceutical company which was testing their anti-cancer drug regimen, Capomulin, vs other drug regimens. I did this analysis in a Jupyter notebook and utilized Python, numpy, pandas, and matplotlib. I loaded in 2 .csvs to merge together and then cleaned the data so I could do effective calculations and visualizations. In order to get a handle on the situation, the first thing I did was do a summary of the tumor volumes by drug regimen.

![reg_sum](/Images/regimen_summary.png)

The first question to answer was how many mice stayed alive throughout the study. The better drug regimens would have more mice alive and there would be less of a drop off over time. I used pandas to create a plot of this data and the bar plot is below. 

![mice_over_time](/Images/no_mice_over_time.png)

The next piece of information was to find out the distribution of males and female mice. This visualization works as a pie chart and I used pyplot to display it. 

![pie_chart](/Images/pie_chart.png)

The next piece of analysis was to determine which drug treatments are in the top four. I used tumor volume at the last timepoint to be the most important factor. According to this standard, the best four treatments are Ramicane, Capomulin, Ceftamin, and Infubinol. I used a box and whisker plot to visualize each of the treatments and looked for outliers. There were no outliers. As you can see Ramicane and Capomulin had the smallest tumor volumes compared to the next 2 best regimens.

![boxplot](/Images/boxplots.png)

Since Capomulin was the pharmaceutical's drug, I decided to pick a mouse at random and do a line graph to demonstrate how the drug regimen affected tumor volume. This is to illustrate the drug's effectiveness. 

![lineplot](/Images/lineplot.png)

The next piece of visualization involved Capomulin and mouse weight. I made a scatter plot that involved mice weight in grams on the x axis and the average tumor volume on the y. Below is that scatter plot. As you can see there seems to be a correlation, therefore I added a linear regression line. 

<img src="/Images/scatter.png" width="400"> <img src="/Images/lin_regress.png" width="400">

All of these calculations and visualizations were done in a Jupyter Notebook. 
