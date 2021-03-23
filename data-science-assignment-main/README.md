## Streamlabs Data Science Take Home Assignment

Thank for you for your interest in joining the data team at Streamlabs! We appreciate you investing the time in this assignment and in this process with us. This assignment gives you an opportunity to showcase your skills in a low-stress environment that is closer to how you would normally work. In exchange for your investment, we commit to spending time reviewing your assignment at a deep level and giving it the attention it deserves. Thank you.

We believe it is important that our assessment of your skills matches the technical challenges you will face as an engineer at Streamlabs. In this assignment you will be provided with a data set, and will be tasked with building a predictive classifier that can be run on similar data to predict churn.

## The Problem

Imagine that Streamlabs has acquired a telecom company that provides cell phone service. However, Streamlabs Telecom has one major problem: our customers are leaving our service for competitors at an alarming rate. We believe that if we could identify users who are about to leave our service, we could convince them to stay by giving them a great deal on their next month's bill. As our new Data Scientist, we've enlisted your help with building a model that we can use to identify these customers going forward. To assist you in building your model, we have provided you with a data set containing histortical customer activity, as well as information about their account.

Please familiarize yourself with the data contained in `cell_customer_data.csv` and use it to train a churn prediction model we can use to identify likely to churn customers.

## The Data Set

Here you can find a description of the data set to help you in building your model.

### Overview
- The dataset has 56,837 observations of customer usage activity and demographic data
- Each observation is for one customer only

### Target Variable

- `churn` - `0` = customer did not churn, `1` = customer did churn

### Numerical Features

- `customer_id` - an identifier unique to this customer
- `revenue` - Average monthly revenue
- `mou` - Average monthly minutes of use
- `recurring_charge` -  Total recurring charge, aka the basic monthly rate for the customer’s voice plan
- `director_assist` - Number of director assisted calls
- `overage` - Overage minutes used. Overage represents calls or minutes over the number of minutes allowed in the customer’s voice plan
- `roaming` - Number of roaming calls
- `minutes_delta` - % change in minutes of use
- `revenue_delta` - % change in revenues
- `dropped_calls` - Average number of dropped voice calls
- `blocked_calls` - Average number of blocked voice calls
- `unanswered` - Average number of unanswered voice calls
- `customer_care` - Average number of calls to customer support
- `conference` - Average number of dropped conference calls (three-way calls)
- `mou_received` - Minutes of voice calls received
- `outcalls` - Average number of outbound calls
- `incalls` - Average number of inbound calls
- `peaks` - Average number of calls during peak hours
- `off_peaks` - Average number of calls during off-peak hours
- `call_forwarding` - Average number of call forwarding calls
- `call_waiting` - Average number of call waiting calls
- `months` - Months in service
- `uniq_subs` - Number of individuals listed in the account
- `active_subs` - Number of individuals listed in the account who actively use the service
- `phones` - Number of phones issued
- `models` - Number of unique phone models issued
- `eqp_days` - Number of days of current phone
- `age1` - Age of first household member
- `age2` - Age of second household member
- `accept_offer` - Number of previous retention offers accepted
- `referrals` - Number of referrals made by subscriber
- `income` - Income (0=>missing)
- `handset_price` - Handset price (0=>missing)

### Categorical Features

For all of these columns, `0` = no (customer is not in category), `1` = yes (customer is in category)

- `children` - Are there children in the household 
- `credit_a` - Highest credit rating is A 
- `credit_aa` - Highest credit rating is AA 
- `rural` - Customer is in a rural area 
- `suburban` - Customer is in a suburban area 
- `town` - Customer is in an urban area 
- `refurbished` - Phone is refurbished 
- `web_capable` - Phone has web capabilities 
- `truck` - Customer owns a truck 
- `rv` - Customer owns an RV 
- `motorcycle` - Customer owns a motorcycle
- `job_prof` - Occupation is professional
- `job_clerical` - Occupation is clerical
- `job_crafts` - Occupation - crafts
- `job_student` - Occupation - student
- `job_homemaker` - Occupation - homemaker
- `job_retired` - Occupation - retired
- `job_self` - Occupation - self-employed
- `travel` - Has traveled overseas
- `pcown` - Owns a personal computer
- `credit_card` - Has at least one credit card
- `new_user` - New cell phone user
- `existing_user` - Existing cell phone user

## Your Submission

Please submit your work in a Jupyter notebook (preferred) or similar.

## What we are looking for

You will be evaluated on your ability in exploratory analysis, feature engineering, model selection and training. We will be evaluating your model against an expanded data set to see how it performs.

## Documentation & Thought Process

- Please try to comment your code as much as you think is needed.

- Please include a `README.md` file containing any instructions/details/context we should know when reviewing your submission. Please also include answers to the following questions.

```
- Briefly describe your predictive churn model. How did you select the variables to be included in the model?

- What are the key factors that predict customer churn, based on your findings? Do these factors make sense? What is their relative importance?

- What would you do to improve your work/get greater results?

- How long did it take you to complete this assignment?

- What about this assignment did you find most challenging?

- What about this assignment did you find unclear?

- Do you feel like this assignment was an appropriate level of difficulty?
```

## Questions

Please email us if you have any questions along the way. We will try our best to help guide you through any confusions. Feel free to make assumptions and document them as you go as well.

## Submission

Please submit your completed assignment via email to the recruiter who sent it to you. You can submit your assignment as a zip file attachment, or you can push it to a GitHub repository and include a link to the respository. We want to thank you again for your time and for your interest in joing the data team at Streamlabs!
