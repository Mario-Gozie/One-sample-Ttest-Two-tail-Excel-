## INTRODUCTION

This is a one sample test to compare mean peformance of Men and Womenfor an indoor gardening task through hypothesis testing.

### RELEVANCE OF HYPOTHESIS TESTING IN A BUSISNESS SETTING

Hypothesis testing is very important in business analytics for decision making.lets takefor example that an Ecommerce business want to change their delivery company for a faster one, they need to run a hypothesis test with samples and compare if there is a difference between the time it takes to make delivery between the old and the new company. This will help stake-holders to make decision whether to continue with the old company or switch to the new one. 

## THE TASK

We read the story of _**Martha Stewart correctional Quarterly**_ which tells us that the average score of women on a test of indoor gardening is 73. but there is no standard deviation. we want to know how men will score on this test.We sample random selection of n = 40 men, and compare their sample mean (M= 65.13) to the population mean of women. The sample of is assumed to be pulled from a population of men who have the same mean as women (U = 73).

![Alt_Text](https://github.com/Mario-Gozie/One-sample-Ttest-Two-tail-Excel-/blob/master/Images/The%20Task.png)

## THE DATASET

This is a sample of 40 men score for indoor gardening.

![Alt_Text](https://github.com/Mario-Gozie/One-sample-Ttest-Two-tail-Excel-/blob/master/Images/Dataset.png)


## A GLANCE AT THE TASK

Looking at this question, the average score of the female population is known and that of the men is not known. 
Now the tricky part is that the question is asking that I assume that the men and women have the same average score which is 73. in other words the hypothesized mean for Men is 73.

## DECIDING ON STATISTICAL TEST TO USE

In deciding the statistical test to use for comparing means, I need to consider if the population mean andpopulation standard deviation is 
given or not. Here, the question gave the population mean and stated it clearly that the population standard deviation is absent. so I have no optionthan to use a **_T-test_** and it has to be **_Two-Tailed_** because I am asked to check if the two mean scores are the same not if one is higher or lower. if otherwise (I am given mean and standard deviation of the population, I would have gone for a **_Two-Tailed Z-test_**

## POINT OF VIEW AND GOAl
In summary, all I need to do is to do hypothesis testing and take a decision. if Men's Mean score for indoor gardening is  73 (same as women) or not. and to also determine what could be the mean range based on sample.

![Alt_Text](https://github.com/Mario-Gozie/One-sample-Ttest-Two-tail-Excel-/blob/master/Images/Point%20of%20View.png)




## HYPOTHESIS

* **My Null  Hypothesis** simply says that the mean score of men is same as women (Hypothesised mean = 73)
*  **My Alternate hypothesis** says the two means are not the same.

![Alt_Text](https://github.com/Mario-Gozie/One-sample-Ttest-Two-tail-Excel-/blob/master/Images/Hypothesis.png)



## DETERMINING SIGNIFICANT FIGURE
For this task, I will take my significant figure to be **0.05**

![Alt_Text](https://github.com/Mario-Gozie/One-sample-Ttest-Two-tail-Excel-/blob/master/Images/significant%20figure.png)


## CALCULATION OF SAMPLE STATISTICS AND CALCULATION OF TEST STATISTICS.

![Alt_Text](https://github.com/Mario-Gozie/One-sample-Ttest-Two-tail-Excel-/blob/master/Images/Data%20collection.png)

## DECISION MAKING


### CALCULATION OF P-VALUE AND CHECKING FOR THE REJECTION RULE 

![Alt_Text](https://github.com/Mario-Gozie/One-sample-Ttest-Two-tail-Excel-/blob/master/Images/Pvalue.png)

### CALCULATION OF CRITICAL VALUE AND CHECKING FOR THE REJECTION RULE

![Alt_Text](https://github.com/Mario-Gozie/One-sample-Ttest-Two-tail-Excel-/blob/master/Images/Critical%20values.png)

## DECISION
Looking at the section for calculating sample statistics and Test statistic, There seems to be difference between the hypothesized mean (73) and the sample mean (6.125). **_A difference of 7.875_**. After hypothesis testing, I got a P-value(3.9921E-08) less than the significant figure which shows that the difference in mean I saw was significant. hence, **I reject the null Hypothesis that the Average mean of mean score is same as women.** 

Alternatively, I calculated the critical value for a T-test distribution. which is -2.02269092 on  the left and 202269092 on the left and  my T-statistic(-6.803004533) does not fall in-between these values so **I have to reject the null hypothesis.**

![Alt_Text](https://github.com/Mario-Gozie/One-sample-Ttest-Two-tail-Excel-/blob/master/Images/Decision.png)

## CONFIDENCE INTERVAL

since the average score of Men and Women are not the same, I need to know a range for the average score of men, in order to know this, I have to do a confidence interval calculation.

![Alt_Text](https://github.com/Mario-Gozie/One-sample-Ttest-Two-tail-Excel-/blob/master/Images/Confidence%20Interval.png)

so from the sample so far, I can say that I am 95% confident that the mean of score of Men will be between 62.78 and 67.47

## Thank You

![Alt_Text](https://github.com/Mario-Gozie/Ecommerce-Data-Visualization/blob/main/Images/thanks.jpg)
