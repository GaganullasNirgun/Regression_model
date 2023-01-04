Problem Statement :

X Education sells online courses to industry professionals.The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos.When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not.The typical lead conversion rate at X education is around 30%.

Goal :

X Education needs help in selecting the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company needs a model wherein you a lead score is assigned to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

Assignment questions and conclusions : 

1. Which are the top three variables in your model which contribute most towards the probability of a lead getting 
converted?
Solution -> Top Three variables that contribute more towards the probability of lead getting converted are:
Tags_Closed by Horizzon
Tags_Lost to EINS
Tags_Will revert after reading the email

2. What are the top 3 categorical/dummy variables in the model which should be focused the most on to increase the 
probability of lead conversion?
Solution -> Top 3 categorical/dummy variables:
Tags_Closed by Horizzon
Tags_Lost to EINS
Tags_Will revert after reading the email

3. X Education has a period of 2 months every year during which they hire some interns. The sales team, in particular, 
has around 10 interns allotted to them. So during this phase, they wish to take the lead conversion more aggressively. 
So they want almost all of the potential leads (i.e. the customers who have been predicted as 1 by the model) to be 
converted and hence, want to make phone calls to as many of such people as possible. Suggest a good strategy they 
should employ at this stage.
Solution -> A good strategy would be to employ at this stage should be to go for a low threshold value of the model because 
we get high Sensitivity which means there will be a high percentage of the Total No. of conversions for that 2 months 
duration. Also, we can focus on other variables such as:
Tags_Closed by Horizon 
Tags_Lost to EINS 
Tags_Will revert after reading the email 
Lead Source_Welingak Website 
Last Activity_SMS Sent 

4. Similarly, at times, the company reaches its target for a quarter before the deadline. During this time, the company 
wants the sales team to focus on some new work as well. So during this time, the company’s aim is to not make 
phone calls unless it’s extremely necessary, i.e. they want to minimize the rate of useless phone calls. Suggest a 
strategy they should employ at this stage.
Solution -> To minimize the rate of useless phone calls the company can opt for a strategy in which we have a high threshold 
value of the model which means that there will be high specificity which means that we will be focusing on leads 
that are not likely to convert that means we could lose some leads to other competitions but there is a fair amount of 
chance also that by not making too many phone calls to these leads we could close them

