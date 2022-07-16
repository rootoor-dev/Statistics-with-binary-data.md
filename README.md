# Statistics-with-binary-data.md
Classical Statistics methods can be used usefully and easily with binary, dummy, fingerprints data. Proof 


# Dummy or binary or fingerprint data

**A dummy variable** ***(x)*** is a variable that holds only one of the two values which are **0** and **1**.

Since all the xi are equal to 0 or 1, summing them all the observations together is the same as counting the number xi that equal to 1. The following formula for the sample mean reveals it is equal to the sample proportion

```
- sum(xi) = count_of_1 = count(xi=1) = total of 1 = N(xi=1) 
- mean(xi) = μ = sum(xi)/n = N/n  = the proportion (p) of a sample that is equal to 1
- variance(xi) = p*q = p(1-p)
- p = proportion(xi=1) = probability(xi=1) = mean in %
- the average value from the population for a binary variable is the proportion of times the binary variable is equal to 1 or the probability that xi=1 ==> mean(%) = proportion

- mode = max(N(x=0),N(x=1)) , if N(xi=0) < N(xi=1) so mo = N(xi=1) else mo = N(xi=0)
- median = proportion_of_1_rounded = round(mean)
- variance = p*q = p(1-p) = mean(1-mean)
- standard-deviation = σ = pow(variance,2) = (variance)²
 
 ** μ mean ; σ sd


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


proportion(person1)= mean(%) = 0.2 ~ 20%
proportion(person2)= mean(%) = 0.2 ~ 20%
proportion(person3)= mean(%) = 0.4 ~ 40%
proportion(person4)= mean(%) = 0.6 ~ 60%
proportion(person5)= mean(%) = 0.8 ~ 80%
proportion(person6)= mean(%) = 1.0 ~ 100%


mode(person1)= max(N(x=0),N(x=1)) = max(4,5) = 5 
mode(person2)= max(N(x=0),N(x=1)) = max(4,5) = 5 
mode(person3)= max(N(x=0),N(x=1)) = max(3,2) = 3
mode(person4)= max(N(x=0),N(x=1)) = max(2,3) = 3
mode(person5)= max(N(x=0),N(x=1)) = max(1,4) = 4
mode(person6)= max(N(x=0),N(x=1)) = max(0,5) = 5

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

```
NB : To estimate a **probability** of an event occurring, one can use standard statistical methods using a binary outcome variable.

# Dummy or binary or fingerprint data

**Dummy variable** x is a variable that holds only one of the two values which are **0** and **1**.

Since all the xi are equal to 0 or 1, summing them all the observations together is the same as counting the number xi that equal to 1. The following formula for the sample mean reveals it is equal to the sample proportion

```
- sum(xi) = count_of_1 = count(xi=1) = total of 1 = N(xi=1) 
- mean(xi) = μ = sum(xi)/n = N/n  = the proportion (p) of a sample that is equal to 1
- variance(xi) = p*q = p(1-p)
- p = proportion(xi=1) = probability(xi=1) = mean in %
- the average value from the population for a binary variable is the proportion of times the binary variable is equal to 1 or the probability that xi=1 ==> mean(%) = proportion

- mode = max(N(x=0),N(x=1)) , if N(xi=0) < N(xi=1) so mo = N(xi=1) else mo = N(xi=0)
- median = proportion_of_1_rounded = round(mean)
- variance = p*q = p(1-p) = mean(1-mean)
- standard-deviation = σ = pow(variance,2) = (variance)²
 
 ** μ mean ; σ sd

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


proportion(person1)= mean(%) = 0.2 ~ 20%
proportion(person2)= mean(%) = 0.2 ~ 20%
proportion(person3)= mean(%) = 0.4 ~ 40%
proportion(person4)= mean(%) = 0.6 ~ 60%
proportion(person5)= mean(%) = 0.8 ~ 80%
proportion(person6)= mean(%) = 1.0 ~ 100%


mode(person1)= max(N(x=0),N(x=1)) = max(4,5) = 5 
mode(person2)= max(N(x=0),N(x=1)) = max(4,5) = 5 
mode(person3)= max(N(x=0),N(x=1)) = max(3,2) = 3
mode(person4)= max(N(x=0),N(x=1)) = max(2,3) = 3
mode(person5)= max(N(x=0),N(x=1)) = max(1,4) = 4
mode(person6)= max(N(x=0),N(x=1)) = max(0,5) = 5

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
NB : To estimate a **probability** of an event occurring, one can use standard statistical methods using a binary outcome variable.

# ENTROPY
**H = - SUM(pi.log(pi))**, where **pi** is the ***probability of a state i of a system***, and **H** is the traditional symbol for **entropy**. 

An example of a system is a set of dummy variables. 

In the special case of one dummy variable: **H = - (p log p + (1-p) log (1-p))**. 






# SOURCES

- [https://murraylax.org/rtutorials/binprop.html](https://murraylax.org/rtutorials/binprop.html)
- [https://stats.oarc.ucla.edu/wp-content/uploads/2016/02/p046.pdf](https://stats.oarc.ucla.edu/wp-content/uploads/2016/02/p046.pdf)


# SOURCES

- [https://murraylax.org/rtutorials/binprop.html](https://murraylax.org/rtutorials/binprop.html)
- [https://stats.oarc.ucla.edu/wp-content/uploads/2016/02/p046.pdf](https://stats.oarc.ucla.edu/wp-content/uploads/2016/02/p046.pdf)
- 


