Observation

we can see that OS distribution in test/control groups are very different. The experiment claim that '66% of the users have seen the old price (39), while a random sample of 33% users a higher price (59).', but users from Linux don't obey such rule, but 53% go to control group, 47% go to test group.

Chi-Square test tells us,

    Price and OS are two main factor which impact converted or not.
    Source and Device don't impact conversion rate that much.


We are going to perform a t-test to test whether the test group's average revenue is higher than control group's average revenue

    H0: test group's average revenue equal to control group's average revenue
    HA: test group's average revenue is higher than control group's average revenue


Pricing Differences

Since the p-value is much smaller than 0.05 threshold, so we reject H0, and accept HA, that is, test group's average revenue is significantly higher than control group's average revenue.
but due to OS distribution aren't the same between test/control groups, price isn't the only difference between test/control groups, so we cannot contribute the increase in average revenue to price.
the experiment design fails, I cannot answer decide whether we can sell software to all users in 59 dollars. I suggest
	1.	find the reason why linux users have different representation ratio than other OS.
	2.	then run the experiment again, make sure price is the only difference between test and control group
	3.	then run t-test again, to see whether the average revenue is significantly improved.
	4.	then I can draw the conclusion.


Actionable Insights

1. friend_referral, Apple user (MAC or iOS), low price are three great positive factors which improve the conversion rate
2. if we want to increase the price, which impacts negatively on conversion rate, we must compensate on the other two factors
	◦	lauch special marketing program targeted to Apple users (MAC or iOS users)
	◦	run some program which rewards user which can invite his/her friend to use our software
3. Linux users don't like our software as much as users on other OS. Development team should find out the reason. For example, is there any incompatibility issue on Linux?

