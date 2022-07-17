# STATISTICS AND COMPUTATION

## Measures of trend
Estimate where a distribution falls. To which value a distribution is tending.


## Measures of variability
***Variability*** is simply the differences among items, which could be
differences in eye color, hair color, height, weight, sex, intelligence,
etc

*Variability* measures the **dispersion** or **similarity** among scores and tell us about the variety of the scores in a distribution.

Several measures of variability such as
- tidy
- sum of squares: SUM(Xi-mean)
- variance
- standard deviation.

## Measures of dependency
Measure of the dependence (linkage) between two or more variables.

Obtained through:

- Correlation
- mutual information
- entropy
- conditional entropy

# Definitions

##Mean
• the arithmetic average of the values in a dataset
• can be affected by extreme values since it uses the exact value of each data
• more accurate measure of central tendency as it takes the individual scores into account
• defined as the mathematical center of a distribution.(i.e., differences between scores and the mean).
• Perfect balancing point because The sum of such different IS zero for any distribution
• xbar of sample is the best unbiased estimator of the population mean (µ).
• can be influenced by extremely large or extremely small values (outliers)
• Specifically, extremely small values pull the mean down and extremely large values pull the mean up
• it is good to use the median as a measure of central tendency in skewed distribution

## Variance
• arithmetic mean of the squared deviations from the observed arithmetic mean
• the average of the squared differences from the "mean". This is also called measure of variability.
• measure of variability that takes into account both the variation of the scores and number of scores in a
distribution
• useful for comparing two (or more) means
• Measures the average variability among scores in a distribution.
• if small, data are close to the mean and spread out if big.
• for population (observed variance), use ***n*** and for sample (corrected variance, unbiased variance) use ***n-1*** in the formula

## Standard-deviation
• measure of how spread out numbers of the series(s) are. This is also called measure of variability.
• same meaning as variance
• useful to know the difference between values in a set or between two (or more) series of numbers.
• useful for comparing two (or more) means.
• if small, data are close to the mean and spread out if big.
• for population, use ***n*** and for sample use ***n*** in the formula

## Median
• the middle number or value of an ordered (sorted) array of numbers (sorted from the smallest to the biggest).
• If there are an odd number of data points, the median will be the number in the absolute middle.
• If there is an even number of data points, the median is the mean of the two center data
points, meaning the two center values should be added together and divided by 2.
• does not take into account the actual values of the scores in a set of data
• Better measure of central tendency than the mode since it balances perfectly distribution.
• Better measure of central tendency when data sets are incomplete or data are severely skewed.


## Fashion
• the most frequently occurring score. Sometimes there is no mode, two modes, or more than 2 modes
• Sometimes there is no mode, two modes, or more than 2 modes
• used to know the most common value in a distribution.

## Tidy
• The highest value or data point minus the lowest value
• provides information about the area a distribution covers, BUT does not say anything about individual values.
• A phenomenon is said to have “strong dynamics” when the extent (or dispersion) is large.

## Extreme values or outliers
Smallest and largest values.
Extremely small or extremely large values in a distribution.

## p% trimmed mean
- arithmetic mean of the remaining observations after having deleted the smallest p% and the largest p%.
- observations must be ordered from smallest to largest.
Note: If p% of n (observations) is not an integer, several (computer) algorithms exist for interpolating at each end of the distribution and for determining xtr(p).

## Absolute Deviation
• We compare all of the values to some sort of measure of central tendency (usually the mean). So we can see how the data as a whole differs or deviates from the mean.

## Sum of squares
• sum of the squares of the deviations from the mean
• squared of sum of Xi minus mean [SUM(Xi-mean)]²
• measures the total variation among scores in a distribution;
• does not measure average variability
• could be equal to zero if there is no variability and all the scores are equal
• Can't be negative (mathematically impossible)

## Skewness
• to know how data are skewed
• indicates the presence or the absence of extreme values (outliers) in a dataset
• ***negatively skewed*** = presence of some small extremes.
• ***positively skewed*** = present
this of some large extremes.

## z-score
Given by the formula: **z = (x − µ)/σ**

## Quantiles

- generalization of the notion of median (division into 2 equal parts of an ordered distribution in ascending order)
- quartiles (division by 4)
- deciles (division by 10)
- percentiles (division by 100), also called percentiles)
- The divisions give parts of the same manpower.

We will thus speak of the “90 percentile” to indicate the value separating the first 90% of the population from the remaining 10%. Thus, in a population of young children, a child whose height is above the 90 percentile, or below the 10 percentile, may be the subject of special monitoring.

## Quartiles
Q1 (called the lower quartile)
Q2 (called the median)
Q3 (called the upper quartile)

These Q divide the distribution into three equal parts.

## Percentiles
For a whole number **P**, where **1 ≤ P ≤ 99**, the **Pth percentile** of a distribution is a value such that *P % of the data fall at or below it*. Thus, *there are 99 percentiles*.
**The percentile locations** are found using the formula: LP = (n + 1)P/100

- Q1 = 25% percentile
- Q2 = 50% percentile
- Q3 = 75% percentile

## interquartile range
the distance between Q1 and Q3
It tells us the spread of the middle half of the data

## Confidence interval (CIα)
The central limit theorem (TCL) guarantees that the estimated mean *xbar* is at a smaller distance than *d* from the theoretical mean E(X) with a probability close to P(|Y|.σ/√(n) )<d where Y follows a standard Gaussian distribution. This also means that *Qα* is the quantile corresponding to *α* for a Gaussian such that:

- **P(E(X) ε [*Xbar-(Qα.σ/√n); Xbar-(Qα.σ/√n)*]) = 1-α**

**ICα** is used to establish the **margin of error** between data from a survey (sample) and data from the total population: **ICα=x̅ ± Za/2*σ/√( not)***
- margin of error = Zα/2 x σ/√(n)
- Zα/2 is the confidence coefficient
- α = degree of confidence
- σ = standard deviation
- n = sample size

## Coefficient of variation
Relative dispersion measurement

# Study of a single variable or univariate descriptive statistics
All measures of central tendencies and variability (dispersion/similarity) serve for better analysis.

# Study of two or more variables (bivariate / multivariate statistics)
The principle is the same as for a single variable, except that all the characteristics (mean, mode, standard deviation, etc.) are bivariate (vectors).

On the other hand, there is an additional feature: the **correlation**. It is a linear measure of the dependence between the different components of the multivariate variable.

There are other **dependency measures** between two variables, such as **mutual information** (or **conditional entropy**).



# Normal Distribution

To better understand how standard deviations are used as measures of dispersion, we next consider normal distributions. The graph of a normal distribution is called a normal curve or a bell-shaped curve. The curve has
the following properties:
1. The curve is bell-shaped with the highest point over the mean µ.
2. It is symmetrical about the line through µ.
3. The curve approaches the horizontal axis but never touches or crosses it.
4. The points where the curve changes concavity occur at µ+σ and µ−σ.
5. The total area under the curve is assumed to be 1.(0.5 to the left of the mean and 0.5 to the right).

The data for a normal distribution are spread according to the following rules:

• About 68 percent of the data values will lie within one standard deviation of the mean.
• About 95 percent of the data values will lie within two standard deviations of the mean.
• About 99.7 percent of the data values will lie within three standard deviations of the mean.

This result is sometimes referred to as the emperical rule, because the given percentages are observed in practice.

```markdown
# For Quantitative (discrete) Variables
use MEAN , MEDIAN or MODE

# interval or ratio scale
use MEAN

# For Ordinal Variables
use MEDIAN or MODE

# For Nominal Variables
use only MODE

# SKEWNESS
if the skewness is BETWEEN -2 and +2, there are NOT extremes in the data. If the
skewness is less than -2 or greater than +2, there ARE extremes in the data.
**When there are extremes in the data, the mean is a worse measure of trend. So don't use it!**

```

# Formulas for quantitative data


### fashion



Grouped data

Mo ≈ L + (c dL)/(dL + dH)

- L = lower boundary of the modal class
- c =
- dL= difference in frequencies between the modal class and the class immediately below
- dH= difference in frequencies between the modal class and the class immediately above



















# Formulas for binary data

```
- n denotes the size of the set of data
- sum(xi) = count_of_1 = count(xi=1) = total of 1 = N(xi=1)
- mean(xi) = μ = sum(xi)/n = N/n = the proportion (p) of a sample that is equal to 1
- variance(xi) = p*q = p(1-p)
- p = ratio(xi=1) = probability(xi=1) = mean in %
- the average value from the population for a binary variable is the proportion of times the binary variable is equal to 1 or the probability that xi=1 ==> mean(%) = proportion

- mode = max(N(x=0),N(x=1)) , if N(xi=0) < N(xi=1) so mo = N(xi=1) else mo = N(xi= 0)
- median = proportion_of_1_rounded = round(mean)
- variance = p*q = p(1-p) = mean(1-mean)
- standard-deviation = σ = pow(variance,2) = (variance)²
 
 ** μmean; sd

EXAMPLE:

Given this data:

person1, 1 0 0 0 0
person2, 1 0 0 0 0
person3, 1 1 0 0 0
person4, 1 1 1 0 0
person5, 1 1 1 1 0
person6, 1 1 1 1 1

----------- calculus ------------
sum(person1)= N(x=1) = 1+0+0+0+0 = 1
sum(person2)= N(x=1) = 1+0+0+0+0 = 1
sum(person3)= N(x=1) = 1+1+0+0+0 = 2
sum(person4)= N(x=1) = 1+1+1+0+0 = 3
sum(person5)= N(x=1) = 1+1+1+1+0 = 4
sum(person6)= N(x=1) = 1+1+1+1+1 = 5


mean(person1)= N(x=1)/n = (1+0+0+0+0)/n = 1/5 ~ 0.2
mean(person2)= N(x=1)/n = (1+0+0+0+0)/n = 1/5 ~ 0.2
mean(person3)= N(x=1)/n = (1+1+0+0+0)/n = 2/5 ~ 0.4
mean(person4)= N(x=1)/n = (1+1+1+0+0)/n = 3/5 ~ 0.6
mean(person5)= N(x=1)/n = (1+1+1+1+0)/n = 4/5 ~ 0.8
mean(person6)= N(x=1)/n = (1+1+1+1+1)/n = 5/5 ~ 1.0


proportion(person1)=mean(%)=0.2~20%
proportion(person2)=mean(%)=0.2~20%
proportion(person3)=mean(%)=0.4~40%
proportion(person4)=mean(%)=0.6~60%
proportion(person5)=mean(%)=0.8~80%
proportion(person6)= mean(%) = 1.0 ~ 100%


mode(person1)= max(N(x=0),N(x=1)) = max(4.5) = 5
mode(person2)= max(N(x=0),N(x=1)) = max(4.5) = 5
mode(person3)= max(N(x=0),N(x=1)) = max(3,2) = 3
mode(person4)= max(N(x=0),N(x=1)) = max(2,3) = 3
mode(person5)= max(N(x=0),N(x=1)) = max(1,4) = 4
mode(person6)= max(N(x=0),N(x=1)) = max(0.5) = 5

median(person1)= proportion = round(0.2) ~ 0
median(person2)= proportion = round(0.2) ~ 0
median(person3)= proportion = round(0.4) ~ 0
median(person4)= proportion = round(0.6) ~ 1
median(person5)= proportion = round(0.8) ~ 1
median(person6)= proportion = round(1.0) ~ 1

variance(person1)= p*q = 0.2*(1-0.2) ~ 0.16
variance(person2)= p*q = 0.2*(1-0.2) ~ 0.16
variance(person3)= p*q = 0.4*(1-0.4) ~ 0.24
variance(person4)= p*q = 0.6*(1-0.6) ~ 0.24
variance(person5)= p*q = 0.8*(1-0.8) ~ 0.16
variance(person6)= p*q = 1.0*(1-1.0) ~ 0

standard_deviation(person1)= pow(variance,2) = 0.16² = 0.256
standard_deviation(person2)= pow(variance,2) = 0.16² = 0.256
standard_deviation(person3)= pow(variance,2) = 0.24² = 0.0576
standard_deviation(person4)= pow(variance,2) = 0.24² = 0.0576
standard_deviation(person5)= pow(variance,2) = 0.16² = 0.256
standard_deviation(person6)= pow(variance,2) = 0² = 0



sum


```
NB: To estimate a **probability** of an event occurring, one can use standard statistical methods using a binary outcome variable.

#ENTROPY
**H = - SUM(pi.log(pi))**, where **pi** is the ***probability of a state i of a system***, and **H** is the traditional symbol for **entropy**.

An example of a system is a set of dummy variables.

In the special case of one dummy variable: **H = - (p log p + (1-p) log (1-p))**.





#ALGORITHMS

### variance

```
Let n ← 0, Sum ← 0, SumSq ← 0
For each datum x:
n ← n + 1
Sum ← Sum + x
SumSq ← SumSq + x × x
Var = (SumSq − (Sum × Sum) / n) / (n − 1)

This algorithm can easily be adapted to compute the variance of a finite population: simply divide by n instead of n − 1 on the last line.

```





















# SOURCES

- [https://blog.u-bourgogne.fr/licence-geographie/wp-content/uploads/sites/23/2015/06/seance_4.pdf](https://blog.u-bourgogne.fr/licence -geography/wp-content/uploads/sites/23/2015/06/seance_4.pdf)
- [https://murraylax.org/rtutorials/binprop.html](https://murraylax.org/rtutorials/binprop.html)
- [https://stats.oarc.ucla.edu/wp-content/uploads/2016/02/p046.pdf](https://stats.oarc.ucla.edu/wp-content/uploads/2016/02 /p046.pdf)
- [https://mylittleneuron.com/2021/01/12/processing-of-data-incomplete-or-imputation/](https://mylittleneuron.com/2021/01/12/processing-of-data- incomplete-or-imputation/)
