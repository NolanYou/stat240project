# IMPORTANT:

These are the remaining peer reviews that I have not yet made changes for. PLEASE use these to see what to edit and delete the sentence once you have completed them. Also make sure you download the recent file... there are many changes!!!


Peer reviews:
Graphs: 
It also seems that some of your graphs are extraneous, for you offer both a scatter plot and a box plot each time when these seem to each carry the same information and you only really need to choose one to include.

Analysis: 
Also when discussing hypothesis testing you talk about testing to see if the means for the 2 categories are equal or if they are not equal. I’m not sure if hypothesis testing gives you grounds to conclude they are not equal, I think it just gives evidence against them being equal. Also, for your race hypothesis tests you only test black and asian when it seems white has a mean heavily differing from the population at large by looking at your graphs. Lastly, it does not seem like you used a statistical model to analyze the second research question and only included graphical displays. I think you should try to answer this question using a statistical model. 

Interpretation: 
The conclusions that are drawn for the first research question are mainly supported by your statistical evidence. The interpretations are also being made in clear language for the most part. I notice how you say “there is not evidence to conclude that the mean mortality rate from stroke is different between men and women”. Again, I do not think finding a low p-value allows you to conclude that the means are different, rather it just provides strong evidence against the null hypothesis. Same goes for when you state “there is a difference between the groups, and we can see that by its low p value…” . I also think you should mention other possible statistical models that could be used for the data in your discussion section, such as logistic regression (since you are using categorical variables), etc.

Hailey's reviews:

Intro: you're not doing any 'causal' inference here, so be careful when you say you're looking at the causes of heart disease and stroke. It may be better to state that you're looking at demographic information to find associations between those variables and occurence of heart disease / stroke

Intro: Make sure you include a thesis statement / explicitly state your RQs in the intro. A thesis could be "Americans over the age of 65 are more likely to experience a stroke or heart disease than those under 65" (doesn't have to be this, just an example)

I'm not sure your boxplots of race influence on heart disease / stroke support the claim that CHD is statistically more likely than stroke. You could definitely claim there is more variability in heart disease, though.

Make sure your graph states in the title the age range of the data.

Are you assuming the data is normal? If so, don't you want to put X_1 ~ N(mu, sigma^2)?

You know how to see whether or not data is normally distributed (histograms, residual plots, etc.). I'd suggest running some of these tests / plotting the data to show this, just because you're relying heavily on this assumption. If it's violated you don't necessarily have to change your analysis, but definitely bring it up in your limitations.

RQ1: You performed a 2-sided test, so you can only say they're not equal. I know it's pretty obvious that one is larger than the other, but just in technical terms you've only tested whether or not they're equal.

When you're reporting t.test results, use the format (t-stat = X on Y df, p = Z)

Race RQ: which race are you testing? Your parameter says 'black', but your description says Asians/Pacific Islanders. Also, be careful in reporting your results because you performed a one-sided test but said you performed a two-sided test.

Stroke RQ: same issue with difference between params and description

Make sure you differentiate that you tested CHD for the analysis of the black population and Stroke for the Asian population.

I think a table is a great idea, but not in this format. There are ways you can build a table writing in Latex that doesn't require you just print an R output. If you don't have time to make this table, I'd suggest just scrapping it altogether since you've thoroughly reported your results above.

Generally, you don't have to worry about rounding as a limitation

References: Make sure your output is not just print out errors



Data set link: https://catalog.data.gov/dataset/rates-and-trends-in-heart-disease-and-stroke-mortality-among-us-adults-35-by-county-a-2000
