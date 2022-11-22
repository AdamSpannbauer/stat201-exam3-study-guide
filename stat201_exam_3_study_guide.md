# Exam 3 study guide - Fall 2022

[Download copy of this as a Word doc](https://github.com/AdamSpannbauer/stat201-exam3-study-guide/raw/master/stat201_exam_3_study_guide.docx)

## Question break down (40 Questions total)

* 13 CI questions (Ch 13 & 14) (1 of them interpretation)
* 12 Chapter 15&16 Qs (1 of them interpretation)
* 6 Chapter 17 Qs (1 of them interpretation)
* 7 Chapter 19 Qs (1 of them interpretation)
* 2 "Choose the right tool" Qs

## 13 CI questions (Ch 13 & 14) (1 of them interpretation)

* Margin of Error
  * Formulas
    * Proportion: $z*SE(\hat{p})$
      * $SE(\hat{p}) = \sqrt{\frac{\hat{p}\hat{q}}{n}}$
    * Mean: $t_{n-1}*SE(\bar{y})$
      * $SE(\bar{y}) = \frac{s}{\sqrt{n}}$
  * What factors affect the size of ME?
    * How does sample size affect ME? Larger sample size leads to (larger/smaller) ME?
    * How does the confidence and *critical value* affect ME? Larger confidence leads to (larger/smaller) ME? Larger critical value leads to (larger/smaller) ME?
  * How does ME affect a CI? Larger ME leads to (larger/smaller) CI?
  * Given a confidence interval, how could you find the ME?
* Confidence Intervals
  * CIs talk about capturing the ***population*** parameter based on our sample. We use CIs when we do NOT know info about the population
  * Inperpretation
    * We are \_\_\_% confident that the true population \_\_\_\_\_\_\_\_ (mean/proportion) is captured in the range \_\_\_ to \_\_\_
    * ^general form, make sure to give some context (ie "the true proportion of manufacturing defects")
  * Know CI conditions!! (mean and proportion)
    * Shared conditions
      * \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
      * \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
    * 3rd condition for proportion CIs: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
    * 3rd condition for mean CIs: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
  * Formulas
    * Proportion: $\hat{p} \pm z*SE(\hat{p})$
      * Aka $\hat{p} \pm Margin\,\,of\,\,Error$
      * $SE(\hat{p}) = \sqrt{\frac{\hat{p}\hat{q}}{n}}$
    * Mean: $\bar{y} \pm t_{n-1}*SE(\bar{y})$
      * Aka $\bar{y} \pm Margin\,\,of\,\,Error$
      * $SE(\bar{y}) = \frac{s}{\sqrt{n}}$
  * Bigger confidence bigger interval
  * "Critical values" ($z$ & $t_{n-1}$) are looked up based on level of confidence
    * We just need the level of confidence to look up $z$
    * We need "degress of freedom" and level of confidence to look up $t_{n-1}$
      * $t_{n-1}$ comes from the $t$-distribution. This has fatter tails and leads to wider, more realistic confidence intervals for smaller sample sizes.
* Estimate of the SD of a sampling dist is the SE

## 11 Chapter 15&16 Qs (1 of them interpretation)

* UNLESS YOU DESIGNED AN EXPERIMENT AND COLLECTED THE DATA YOU CAN'T SAY ANYTHING ABOUT CAUSATION
* Hypothesis testing steps
  * Hypotheses - State null ($H_0$) and alternative hypotheses ($H_a$)
    * Null hypotheses examples: $\mu = 10$  & $p = 0.2$
    * Alternative hypotheses examples: $\mu \ne 10$ & $p < 0.2$ & $\mu > 20$
  * Model - Check assumptions of test (same as CIs)
  * Mechanics - Calculate test statistic and convert to a p-value
  * Conclusion - Interpret p-value and state conclusions of test
    * When interpreting include: statement about $H_0$, level of significance, & p-value
    * p > $\alpha$ - **Fail to reject the null hypothesis**, there is not evidence to support the alternative hyothesis
    * p < $\alpha$ - **Reject null hypothesis**, there is evidence to support the alternative hypothesis
    * $\alpha$ - aka "alpha" or "level of significance"- very common to use 0.05
      * Relates to confidence levels in CIs.  A test with $\alpha = 0.05$ and a CI at 95% confidence will agree
* p-values
  *  p - probability
  * "Assuming the null hypothesis to be true, what's the probability we'd see the data in our sample"
  * Examples:
    * Assuming heads should come up 50% of the time, what's the probability we'd see 20 heads in a row?  This would be very unusual data to observe and have a low p-value. It might lead us to reject the assumption that it is a fair coin.
    * Assuming the average weight of a french bull dog is 24.3 pounds, what's the probability we'd see a french bull dog that weighs 40 pounds? This would be very unusual data to observe and have a low p-value. It might lead us to reject the assumption that the dog is a frenchie.
* Confidence intervals and hypothesis tests
  * If a 95% confidence includes the null hypothesized mean/proportion then a hypothesis test will result in p > 0.05 (ie fail to reject $H_0$).
    * Example: A 95% confidence interval of a population mean is [10, 15].
      * If we ran a hypothesis test with $H_0: \mu = 12$, we'd see a p-value greater than 0.05 and fail to reject the null hypothesis
      * If we ran a hypothesis test with $H_0: \mu = 19$, we'd see a p-value less than 0.05 and reject the null hypothesis
* Hypothesis testing errors
  * Type I error - [False Positive](https://i.imgur.com/AxubVWu.jpg) - rejecting the null hypothesis when it's true
    * The probability of making a Type I is denoted as $\alpha$ (alpha)
    * We base p-values and our conclusions on how unusual events are. There's always a chance of just seeing some unsual things ([eg](https://content.time.com/time/nation/article/0,8599,1901663,00.html)). We often say if there's <5% chance of observing this data assuming the null then reject the null.  We'd still see that happen ~5% of the time when the null is true.
  * Type II error - [False Negative](https://i.imgur.com/n0FOqJZ.jpg) - failing to reject the null hypothesis when it's false
  * If you decrease chance of making a Type I error you increase chances of Type II error
  * If you decrease chance of making a Type II error you increase chances of Type I error

## 6 Chapter 17 Qs (1 of them interpretation)

## 7 Chapter 19 Qs (1 of them interpretation)

## 2 "Choose the right tool" Qs