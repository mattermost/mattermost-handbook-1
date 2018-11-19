# Operating Metrics  


## AARPC - Average Annual Revenue Per Customer 

Annualized subscription revenue per [customer](#Customer) per year.

## Customer 
Organization that purchases subscription licenses of at least 10 seats, other than non-profit or academic licenses.

## Current Customers 
The number of customers with at least one active subscription.

## Non-Business Customer 
Organization that purchases subscription licenses fewer than 10 seats or are purchasing either non-profit or academic licenses. 

## Current Non-Business Customers 
The number of non-business customers with at least one active subscription.


```
# BC  	
Current number of business customers with a valid subscription


# BC Churn
Number of business customer subscriptions that either opted-out of a renewal or did not opt-in to renewal after subscription expired during time period


# New BC
Number of new business customers (logos) added during time period


Net New BC
Net New BC = # BC (+) # New BC (-) # BC Churn


Total Contract Value (TCV)
Customer or partner commitment to spend money with Mattermost, Inc. as measured by the total amount of sales orders agreed in a signed contract that are not subject to opt-out (termination for convenience) or opt-in (renewal). This can be fully executed purchase order or sales order, or a click-sign agreement from customers to a licensing agreement executed online.


First Year Annual Contract Value  (FYACV)
Value of the first 12 months of bookings in a contract.


Average Annual Contract Value (AACV)
Average TCV over 12 months. Specifically TCV divided by number of months in term multiplied by 12. For multiple year deals with contracted ramps, the ACV will be the average annual booking per year.


Average Contract Term
Average contract term length in years (i.e. 1.5 years)


Average Revenue Per Account for New Customers (ARPA New Customers)
ARR / Total # BC


Average Revenue Per Account Total (ARPA Total)
ARR / Total # BC
		
Monthly Recurring Revenue (MRR)
Recurring revenue recognized in current month.


Annual Recurring Revenue Starting (ARR Starting)	
Dollar value of total ARR at the beginning of a time period. The sum of Monthly Recurring Revenue plus True-ups divided by twelve multiplied by 12. =((MRR+True-ups/12)*12)


Annual Recurring Revenue Ending (ARR Ending)	
Dollar value of total ARR at the end of a time period. The sum of Monthly Recurring Revenue plus True-ups divided by twelve multiplied by 12. =((MRR+True-ups/12)*12)


ARR New
Dollar value of subscriptions from brand new BC accounts (i.e. new logos) added during time period normalized to a one year period. Excludes non-recurring components

ARR Renewal	
Dollar value of ARR from an existing BC account that renews existing licenses. In the spreadsheet, this will have previously been represented as New ARR (if first renewal).


ARR Expansion
Positive change in ARR in existing accounts during time period as measured in dollars. Includes True-Ups.


ARR Reduction
Negative change in ARR in existing accounts during time period as measured in dollars. 

ARR Churn 	
Dollar value of subscriptions with business customers that either opted-out of a renewal or did not opt-in to renewal after subscription expired during time period.


ARR Upgrade	
Existing E10 BC customer changes to E20 license.


ARR Add-ons
Existing BC customer adds extra features.


True Up	
When customer adds more licenses during contract term and then notifies MM at the time of renewal. Included as ARR Expansion applied to the original contract (not the renewal).


Co-term
When existing customer purchases additional licenses on a short term contract to match the contract term of the original licenses. Shown as expansion in License spreadsheet.


Net New ARR		
"""Net New ARR"" = ""ARR New"" (+) ""ARR Expansion"" (-) ""ARR Reduction"" (-) ""ARR Churned"" 
or 
""ARR Ending (-) ""ARR Starting"""
		
Magic Number
Incremental MRR for trailing three months / Sales & Marketing Spend over trailing months -6 to months -4 (one quarter lag).

Lifetime Value of a Customer (LTV)*
Life-Time Value = Average Revenue per Year x Gross Margin% x 1/(1-K) + GxK/(1-K)^2; K = (1-Net Churn) x (1-Discount Rate). Assumes a 10% cost of capital based on current cash usage and borrowing costs.

Customer Acquisition Cost (CAC)*
Total Sales & Marketing Expense/Number of New Customers Acquired


LTV/CAC Ratio*
The customer Life-Time Value to Customer Acquisition Cost ratio (LTV:CAC) measures the relationship between the lifetime value of a customer and the cost of acquiring that customer. A good LTV to CAC ratio is considered to be > 3.0.

Months to Recover CAC
# months to recover acquisition costs. Based on GM% and ARPU	
		
Gross Billings
Gross amount invoiced during period excluding any discounts applied after the billing, such as discounts for early payment

Net Billings
Net amount invoiced during period including any discounts applied after the billing, such as discounts for early payment

Net Subscription Billings
Net amount invoiced for subscription offerings during period including any discounts applied after the billing, such as discounts for early payment


GAAP Revenue
Revenue earned as we provide a service to the customer over time. Determined based on GAAP reporting standards. Example: Three months after selling a subscription for $120/year we have $30 of GAAP Revenue, as we have earned 3/12 of the annual subscription for the three months past. 


Deferred Revenue
Revenue that is yet to be earned after the execution of an agreement. Example: Three months after selling a subscription for $120/year we have $30 of GAAP Revenue, as we have earned 3/12 of the annual subscription for the three months past and we have $90 of Deferred Revenue as we have 9/12 of the subscription yet to earn. 
*GitLab definition

```
