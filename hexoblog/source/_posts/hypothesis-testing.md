---
title: Hypothesis Testing
date: 2022-06-17 08:35:07
tags: [Statistics, Math]
categories: Nerdy Mathy stuff
---

I originally learned about hypothesis testing in STA2004F, where it was touted as a "boring" section in the course. It turns out to be a useful way to look at problems and try to get some order out of chaos.

<!-- more -->

## Hypothesis Testing introduction
**Statistics** is the discipline that concerns the collection, organization, analysis, interpretation, and presentation of data.

A **statistical hypothesis test** is a method of statistical inference used to decide whether the data at hand sufficiently support a particular hypothesis. 

**Standard deviation** is how much a distribution differs from the mean.

**Variance** is the squared deviation.

### Why we test
In fields like physics, scientists have found principles that hold in the microscopic and macroscopic realms; this is because behavior in nature is somewhat predictable and consistent; however, in daily life economics, psychology, and business seem completely random. We humans, wanting to understand what confuses us, try to form formulas and principles that put randomness in a box we could understand.

This is why we have statistics, we try to take complete randomness and draw insightful and useful conclusions from them.

{% asset_img statsandpsych.jpg How fields like psychology are built on statistics %}

### What we test
This depends largely on what we hypothesise, but it comes down to testing if a **critical value** is in the **rejection region** or not.

In science we NEVER accept something as true, we either REJECT it or we DON'T REJECT IT since there is no significant evidence. For example, if someone has better evidence that the Earth is flat than the evidence that it is round, most good scientists will change their views.

### How we test

{% asset_img simpleCompositeTests.jpeg Simple and Composite tests of the mean %}

We make a **simple** or **composite** hypothesis. Simple being "equal" and composite being "not equal" or "more/less than." We've got the **null hypothesis** which is our calculated guess and an **alternative hypothesis** which goes against our guess but could also be true.

We do tests like these with any parameters that have significance to our hypothesis and use many types of tests and use different measurements, all to do the same: Prove **our hypothesis is false or is not false** and draw conclusions.

{% asset_img typesOfTests.png Types of tests %}
{% asset_img NullAndAlternateHypothesis.png Null and Alternate hypothesis in the rejection region %}


## Story time!
My friends and I loved this course, but it is notoriously a very difficult course to pass in UCT; in fact, our class had a rewrite of test 1 after the pass rate was 16%.

I attended every lecture and found every piece of this course useful to think and solve problems with random data. I hope we get to explore these ideas more in the upcoming machine learning modules.


## References
- Wikipedia, Statistics, [ONLINE] Available at: https://en.wikipedia.org/wiki/Statistics [Accessed 17 June 2022]
- Wikipedia, Statistical hypothesis testing, [ONLINE] Available at: https://en.wikipedia.org/wiki/Statistical_hypothesis_testing [Accessed 17 June 2022]
