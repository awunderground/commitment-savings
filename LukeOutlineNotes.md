# Luke's Outline Notes

A collection of random thoughts on the Seedpaper and how we might use it.



We find that women who exhibit hyperbolic preferences were
more likely to take up our offer to open a commitment savings
product. We find a similar, but insignificant, effect for men. (pg 2)

* I wonder if this will hold up to a more powerful (nonparametric  test)


We conjecture that the amount-based goal is a stronger
device, since there is an incentive to continue depositing after the
initial deposit (otherwise the money already deposited can never
be accessed), whereas with the date-based goal there is no explicit
incentive to continue depositing (pg. 6)

* Possible to set up a paired trial here?
* Compare savings at the begining of the study versus the end for the accounts
* We could use this comparison to do a censored data test. Investigating the difference in savings taking into account people who dropped out early



Table 6 (pg. 25) is an obvious candidate for for non parametric techniques. They had issues with outliers. Rank Based regression solves for issues with outliers.



I'm hesitant to use table 7 for a few reasons
* It seems like like a combination of regression and distribution estimation. "Table VII shows regressions for deciles of the distribution" That is not something we have really addressed. LOESS is close, but not quite the same.
* We can only use one test from chapter 10 to count towards our 4 required tests, and a nonparametric regression on Table 6 will be much more straight forward.


Doing a k-sample test on the three treatments (SEED account, savings marketing, control) will be easy and straightforward.
* I think a rank based test on the difference in savings would be appropriate as that will help control for people's potentially significant disparities in income and wealth.

