# Operating Metrics  

## Customers

### AARPC - Average Annual Revenue Per Customer 

Annualized subscription revenue per [customer](#Customer) per year.

### AAPRC New Customers - Average Annual Revenue Per Customer for New Customers

Annualized subscription revenue per [customer](#Customer) per year.

### New Customer 

An organization that becomes a [customer](#customer) through an eligible purchase on a new customer contract. A purchase from a sibling, daughter or parent of an existing customer counts as a new customer if the eligible purchase is made on a new customer contract, but is not counted as a new customer if the purchase is made on an existing contract through an addendum. 

### Customer 
Organization that purchases subscription licenses of at least $1000 USD, other than non-profit or academic licenses.

### Current Customers 
The number of customers with at least one active subscription.

### Non-Business Customer 
Organization that purchases subscription licenses less than $1000, or are purchasing either non-profit or academic licenses. 

### Current Non-Business Customers 
The number of non-business customers with at least one active subscription.

## CAC, fully burdened

All recognized expenses in marketing and sales department P&L for period. 

## Cash 

### USD Cash Balance 

Aggregate USD in cash holdings across all accounts including non-USD holdings whose balance should be calculated based on spot exchange rate to USD on the closing of the day previous to the day the USD Cash Balance is calculated. 

### Monthly Cash Burn

Decrease in [USD Cash Balance](#usd-cash-balance) from the first of the month to the first of the next month, or "0" if cash did not decrease. E.g. Monthly Cash Burn for April is the decrease in cash from April 1 to May 1. 
 
### Operating Months 

[USD Cash Balance](#usd-cash-balance) divided by average of [Monthly Cash Burn](#monthly-cash-burn) in the previous three (3) months. In the case where there was no burn, treat the month as "0" burn, this allows us to project worst case.  

### Pipeline
Pipeline is total opportunity amount stage 1 and greater in a given period defined by AE after first engagement confirming authority, need and committed next step. Opportunity dollar amount is determined by list price times number of users.

### MQL
Marketing Qualified Lead (MQL) is a lead that has reached a lead scoring threshold (100 points). Lead scoring model is based on firmographic, demographic, and behavioral information and can be seen [here](https://docs.google.com/spreadsheets/d/1ZMF7ppWS_Naf-kIFgRymLWwHRVkB09VTqB7wv-AXOnM/edit?usp=sharing). (internal)(doc)

### SQL
Sales Qualified Lead (SQL) is an opportunity created in Stage 1 or greater as either an SAO or Sales created opportunity that meets the pipeline requirements.

### SAO
Sales Accepted Opportunity (SAO) is an opportunity in stage 1 or greater. Created by a sales team member or by an SDR and accepted by a sales team member following an initial qualifying meeting (IQM) or SDR handoff. 

### IQM
Initial Qualifying Meeting (IQM) is a meeting scheduled by an SDR for a sales team member with a qualified lead. 

### SMB 
Companies with up to 499 employees

### Commercial
Companies with 500 to 4,999 employees

### Enterprise
Companies with 5,000 or more employees


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
