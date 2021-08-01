# Data-Science
 Introduction to Data Science
 
 Populations and Samples:
 
 A parameter is a characteristic of a population  e. g. , the average height of all Americans. \ 
 A statistics is a characteristic of a sample e. g. , the average height of a sample of Americans.
 
 Data based on types and measurement level, Data type is categorical and numerical.  Categorical data has categories or groups. Numerical data present numbers.  They show discrete or continuous.
 
 Data visualisation for categorical data : frequency distribution tables, bar charts, pareto diagram. 
 Data visualisation for Numerical  data :  Histogram: Depicts information from a frequency table or a grouped frequency table as a bar graph
 
 
![image](https://slidetodoc.com/presentation_image_h/014b1c614da506e65bda7ccf07b992e9/image-14.jpg)


 
 Cross table : shows data  
 
 Descriptive and inferential statistics are two broad categories in the field of statistics.
 ## Descriptive statistic
 Use descriptive statistics to summarize and graph the data for a group that you choose. This process allows you to understand that specific set of observations. Descriptive statistics describe a sample. 
Descriptive statistics frequently use the following statistical measures to describe groups:  Central tendency, Dispersion, Skewness.
 
 Measure of central tendency :
 
 ![image](https://slidetodoc.com/presentation_image_h/014b1c614da506e65bda7ccf07b992e9/image-30.jpg)
 ![image](https://slidetodoc.com/presentation_image_h/014b1c614da506e65bda7ccf07b992e9/image-31.jpg)
 
 mean :  simple average : <img src="https://latex.codecogs.com/gif.latex?\mu" title="\mu" /> for population and  <img src="https://latex.codecogs.com/gif.latex?\bar{x}" title="\bar{x}" /> for sample. It is easily affected by outliers.  
 
 Median  :  is the middle number in an ordered dataset.
 
 Mode:  value that occurs more often.
 
 Measure of symmetry: skewness indicates whether the data is concentrated on one side. 
 
 ![image](https://slidetodoc.com/presentation_image_h/014b1c614da506e65bda7ccf07b992e9/image-32.jpg) 
  
 ![image](https://slidetodoc.com/presentation_image_h/014b1c614da506e65bda7ccf07b992e9/image-15.jpg)
 ![image](https://slidetodoc.com/presentation_image_h/014b1c614da506e65bda7ccf07b992e9/image-16.jpg)
 
 ## Variability :
 
 
 ![image](https://slidetodoc.com/presentation_image_h/014b1c614da506e65bda7ccf07b992e9/image-35.jpg)
 ![image](https://slidetodoc.com/presentation_image_h/014b1c614da506e65bda7ccf07b992e9/image-36.jpg)
 ![image](https://slidetodoc.com/presentation_image_h/014b1c614da506e65bda7ccf07b992e9/image-37.jpg)
 ![image](https://slidetodoc.com/presentation_image_h/014b1c614da506e65bda7ccf07b992e9/image-38.jpg)
 
 variance :
 
 Standard Deviation and Coefficient of Variation
 
 ![image](https://user-images.githubusercontent.com/64529936/127644393-8bb742ec-be78-401c-8eb6-ca51a45e9693.png)
 ![image](https://user-images.githubusercontent.com/64529936/127644524-b6f3fdc6-503d-47cd-bc51-65f31fa513db.png)
 ![image](https://user-images.githubusercontent.com/64529936/127640602-83a72abe-93af-474b-8dcf-c1641650c07f.png)
  ![image](https://user-images.githubusercontent.com/64529936/127645246-164a9135-22db-4296-8dde-799addcde31e.png)
  
  correlation is symmetrical with respect to both variables. This is very important for causality.  Correlation does not imply causation. 
  
  ## Inferential statistics
  
  Inferential statistics takes data from a sample and makes inferences about the larger population from which the sample was drawn. Using a random sample, we can generalize from the sample to the broader population. The difference between the sample statistic and the population value is the sampling error. Inferential statistics incorporate estimates of this error into the statistical results. 
  The most common methodologies in inferential statistics are hypothesis tests, confidence intervals, and regression analysis.
  what is distribution ?  point estimates and confidence intervals ?  
  A distribution is a function that shows the possible values for a variable and how often they occur. Uniform distribution , normal distributions and exponential distribution.
  
  standardization (mean, std) =(0,1) . the standardazied variable called z-score 
  ![image](https://user-images.githubusercontent.com/64529936/127658753-04e7b499-ebad-4c48-aec2-ed02c16996eb.png)
  ![image](https://user-images.githubusercontent.com/64529936/127649926-c3eff461-68ea-4328-b0fb-706ac308a638.png)
  
  Central limit theorem: 
  
  no matter underlying distribution, sampling distribution  of mean is normal distribution. even population distribution is nor normal. 
  the standard deviation of the distribution formed by sample means
 
 Estimator and estimation:

Point Estimates
An estimate for a parameter that is one numerical value. An example of a point estimate is the sample mean or the sample proportion. 
 point estimate is stand exactly in the confidence interval estimates.
 Such intervals are built around point estimates which is why understanding point estimates is important to understanding interval estimates.
 the standard error of the mean is <img src="https://latex.codecogs.com/gif.latex?\frac{\sigma&space;}{\sqrt{n}}" title="\frac{\sigma }{\sqrt{n}}" />

confidence interval is the range within which you expect the population parameter to be.  sample mean is point estimate and population variance is known.
![image](https://user-images.githubusercontent.com/64529936/127655789-88be8be1-ff27-471b-b2b9-b695943b0140.png)

## t-statistics :
 It is looking like normal distribution but has fatter tails . There is more uncertainty . Z-statistics is more related to normal distribution. t-statistics is related to student t distribution.
 confidence interval-population variance is unknown.  The exact shape of the Student’s t-distribution depends on the degrees of freedom. As the degrees of freedom increases, the graph of Student’s t-distribution becomes more like the graph of the standard normal distribution.
  Sample size is small we use student t distribution. we have sample mean and sample standard deviation and standard error. 
  ![image](https://user-images.githubusercontent.com/64529936/127659744-bd5b61a0-dcc1-45f5-bf4f-d75a6461aba1.png)

Dependent samples.  like linear regression, and 
Independent samples :  two samples are truly independent
 
<img src ="https://user-images.githubusercontent.com/64529936/127662564-733203c9-dea3-41bc-b944-7c4886eb6e9e.png" width = "400" height = "250" />
<img src ="https://user-images.githubusercontent.com/64529936/127662601-4ebbf79a-6041-4670-a6c2-d0583e91c56f.png" width = "400" height = "250" />

 ## Hypothesis test
 
 Hypothesis tests use sample data answer questions like the following:

Is the population mean greater than or less than a particular value?
Are the means of two or more populations different from each other?
 
 1- Formulate a hypothesis, 2- find the right test, 3- execute the test, 4-make dicision
 
 null hypothesis: it is the statement we are trying to reject. the null hypothesis is always the accepted fact. 
 H0 = mean grade of population = 70 <img src="https://latex.codecogs.com/gif.latex?%" title="%" />.   so H1 is population mean grade is not 70 <img src="https://latex.codecogs.com/gif.latex?%" title="%" /> , first calculate mean of sample then scale z-score so check if z is in the rejection region 
 State the alpha level. If you aren’t given an alpha level, use 5<img src="https://latex.codecogs.com/gif.latex?%" title="%" /> (0.05).
 
  type one error = false positive , type two error= false negative
  
  We call this significant level (alpha). We first transform our sample.we choose Standard Normal Distribution ( mean =0 and std =1 ). It is just we can simply transform our data from any normal distribution to Standard normal distribution.
  
  P-value :  
  This rejection of null hypothesis and accepting the alternate hypothesis is done using the P value 
  ![image](https://user-images.githubusercontent.com/64529936/127738748-bcb11388-3847-4e9b-b790-5b05786b6ff5.png)
  
  accepted if p-value > alpha and rejected if p-value < alpha
  
 ## Linear regression   analysis
  
 ##What is <img src="https://latex.codecogs.com/gif.latex?R^2" title="R^2" /> ? 

 <a href="https://www.codecogs.com/eqnedit.php?latex=R^2&space;=&space;\frac{variebility&space;explained&space;by&space;the&space;regression&space;}{total&space;variability&space;of&space;the&space;dataset}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?R^2&space;=&space;\frac{variebility&space;explained&space;by&space;the&space;regression&space;}{total&space;variability&space;of&space;the&space;dataset}" title="R^2 = \frac{text{variebility explained by the regression} }{text{total variability of the dataset}}" /></a>
 
 It is measure goodness of our fit 
 The R-squared shows how much of the total variability of the dataset is explained by your regression model. This may be expressed as: how well your model fits your data. It is incorrect to say your regression line fits the data, as the line is the geometrical representation of the regression equation. It also incorrect to say the data fits the model or the regression line, as you are trying to explain the data with a model, not vice versa.
 
  <img src="https://365datascience.com/resources/blog/2018-11-image8-5-1024x495.jpg" width="800" height="400"/>
  
  The sum of squares total, denoted SST, is the squared differences between the observed dependent variable and its mean. 
  The second term is the sum of squares due to regression, or SSR. It is the sum of the differences between the predicted value and the mean of the dependent variable.
  the sum of squares error, or SSE. The error is the difference between the observed value and the predicted value.
  
  ![image](https://user-images.githubusercontent.com/64529936/127621853-ccfc2112-20be-404a-bf8a-d7138ffa978b.png)
  
  Like the R-squared, the adjusted R-squared measures how well your model fits the data. However, it penalizes the use of variables that are meaningless for the regression.
  Almost always, the adjusted R-squared is smaller than the R-squared. The statement is not true only in the extreme occasions of small sample sizes and a high number of independent variables.

  
 ##  What is ANOVA (analysis of variance)?
 
 Analysts use the ANOVA test to determine the influence that independent variables have on the dependent variable in a regression study.
  ## What is F-statistics?
  
It follows f distribution. null hypothesis : all the betas are zero , alternative hypothesis : at least one beta is not zero . the lower the f-statistics the closer to a non-significant model.

## OLS estimate 
Ordinary Least Squares (OLS) is the most common estimation method for linear models.
As long as your model satisfies the OLS assumptions for linear regression, you can rest easy knowing that you’re getting the best possible estimates.
In regression analysis, the coefficients in the regression equation are estimates of the actual population parameters. We want these coefficient estimates to be the best possible estimates!

 ##  Linearity:
 The linear regression is the simplest non-trivial relationship.  
 In statistics, a regression model is linear when all terms in the model are either the constant or a parameter multiplied by an independent variable.
 if assumption is violated we can use transformation. Linear models can model curvature by including nonlinear variables such as polynomials and transforming exponential functions.
 
 ## No Endogeneity
 
 error between predicted value and real value is correlated with independent variable. this is problem called omitted variable bias.Omitted variable bias occurs when you forget to include a variable. This is reflected in the error term as the factor you forgot about is included in the error. In this way, the error is not random but includes a systematic part (the omitted variable). 
 ## Normality and homoscedasticity
 
 The variance of the errors should be consistent for all observations. In other words, the variance does not change for each observation or for a range of observations. This preferred condition is known as homoscedasticity (same scatter). If the variance changes, we refer to that as heteroscedasticity (different scatter). 
  
 ## Autocorrelation
 Autocorrelation is not observed in cross-sectional data. You usually spot it at time series data, which is a subset of panel data. we can recognise  autocorrelation by plotting all residuals in a graph and look for patterns. alternative model is autoregressive. 
 
 Residuals = Observed value – the fitted value
 
 ## Multicollinearity
 We observe multicollinearity when two or more variable  have a high correlation. This impose a big problem to our regression model as the coefficient will be wrongly estimated.  We can fix it by drop one of two variables or transform them into one  (average ).
 
 
 
  
 
 
  
  
  
  
  