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

### Total Contract Value (TCV)

Customer or partner commitment to spend money with Mattermost, Inc. as measured by the total amount of sales orders agreed in a signed contract that are not subject to opt-out (termination for convenience) or opt-in (renewal). This can be fully executed purchase order or sales order, or a click-sign agreement from customers to a licensing agreement executed online.

### First Year Annual Contract Value  (FYACV)

Value of the first 12 months of bookings in a contract.

### Average Annual Contract Value (AACV)
Average TCV over 12 months. Specifically TCV divided by number of months in term multiplied by 12. For multiple year deals with contracted ramps, the ACV will be the average annual booking per year.

### Average Contract Term
Average contract term length in years (i.e. 1.5 years)

### True Up	
When customer adds more licenses during contract term and then notifies MM at the time of renewal. Included as ARR Expansion applied to the original contract (not the renewal).

### Co-term
When existing customer purchases additional licenses on a short term contract to match the contract term of the original licenses. Shown as expansion in License spreadsheet.

### Magic Number

Incremental MRR for trailing three months / Sales & Marketing Spend over trailing months -6 to months -4 (one quarter lag).

### Lifetime Value of a Customer (LTV)*

Life-Time Value = Average Revenue per Year x Gross Margin% x 1/(1-K) + GxK/(1-K)^2; K = (1-Net Churn) x (1-Discount Rate). Assumes a 10% cost of capital based on current cash usage and borrowing costs.

### Customer Acquisition Cost (CAC)*

Total Sales & Marketing Expense/Number of New Customers Acquired

### LTV/CAC Ratio*

The customer Life-Time Value to Customer Acquisition Cost ratio (LTV:CAC) measures the relationship between the lifetime value of a customer and the cost of acquiring that customer. A good LTV to CAC ratio is considered to be > 3.0.

### Months to Recover CAC

Number months to recover acquisition costs. Based on GM% and ARPU	
		
### Gross Billings

Gross amount invoiced during period excluding any discounts applied after the billing, such as discounts for early payment

### Net Billings

Net amount invoiced during period including any discounts applied after the billing, such as discounts for early payment

### Net Subscription Billings

Net amount invoiced for subscription offerings during period including any discounts applied after the billing, such as discounts for early payment

### GAAP Revenue

Revenue earned as we provide a service to the customer over time. Determined based on GAAP reporting standards. Example: Three months after selling a subscription for $120/year we have $30 of GAAP Revenue, as we have earned 3/12 of the annual subscription for the three months past. 

### Deferred Revenue

Revenue that is yet to be earned after the execution of an agreement. Example: Three months after selling a subscription for $120/year we have $30 of GAAP Revenue, as we have earned 3/12 of the annual subscription for the three months past and we have $90 of Deferred Revenue as we have 9/12 of the subscription yet to earn. 


## ARR - Definitions, Subtypes, and Calculations

### Monthly Recurring Revenue (MRR) 
is defined as recognized revenue for subscriptions active from the starting day to the final day of a calendar month calculated as the sum of subscription services in signed contracts, net of discounts, credits, taxes and fees (including reseller and coseller fees), divided by the number of days for which each subscription is effective (inclusive of start and end dates) multiplied by an average of 30.4166667 days per calendar month and measured in USD, with foreign currencies converting to USD based on the spot price exchange rate on the first day of the month in the month of the latest customer contract signed.

### Bookings

Bookings are closed won sales (minus taxes and fees) reported in USD.  Total bookings would include all sales for mattermost whether recurring or not.   Subscription bookings refers to the sum of all sales for our subscriptions ( does not include PS or one time sales).   Bookings will be reported on for a given time period based on the close date of the deal.  This differs from MRR/ARR which uses the license start/end date.   

### Annual Recurring Revenue (ARR) is defined as Monthly Recurring Revenue multiplied by twelve (12). 
Basic Calculation:
The sum of Monthly Recurring Revenue received in the month divided by twelve multiplied by 12. =((MRR+True-ups/12)*12). Based on contract license dates.

**ARR Calculation Rules:**

* For multiple year deals with contracted ramps, the ARR will be the average annual TCV per year.
* ARR will not include Professional Service, One time Fees, Partner fees, or any discounts.  
* ARR Calculation will be calculated based on the appropriate license start and end date.  No ARR will be active outside the start and end date.  We will not use close date in ARR.  
* Any deal less than 12 months in length will count towards ARR at the MRR (TCV/Length in months) rate * 12 mo.  However the ACV of these will be exact value of the deal.  
* ARR will be the total amount of active subscriptions sold through Partners, Sales, Customer Success, and Online Means.  
* ARR will be based on and reported in USD.  We will convert foreign currencies into USD.  We will used a fixed conversion rate that will adjust once quarterly (set at the exchange rate of the 1st day of quarter) or per year (TBD).   We will limit the sale of MM in local currencies to a handful of currencies ( Euros and GBP for now).     
* Replacement deals will have the original deals license end date moved up, and the full ARR rolled into a single deal. 
* Early Termination, early terminations on pre-paid deals will not be eligible for a refund.  Customer paying on monthly or payment terms and early terminate will be handled on a case by case basis.  The ARR will end when the license date ends (either the original or an updated license date).  

Note:  Further definitions here:  https://docs.google.com/document/d/1aKJrJ7VBf6lGzYNe2xpsTaAfUjw_3Pv1TBRw5XhRCs0/edit#

## ARR Sub Variants or Types:

We will track and report on these variations of ARR

### Net New ARR

Value of new ARR from new and existing customers that will result in recurring revenue over the next 12 months less any credits, lost renewals, reductions or any other decrease to annual recurring revenue. Excluded from Net New ARR are bookings that are non-recurring such as training and non-recurring engineering fees. Also equals ARR less renewals. 

### New Customer ARR

ARR from New Logos.  These are customers who have either never had a subscription with Mattermost or have not had an active subscription with us for more than 12 months.  

### New Business Customer ARR

ARR from New Logos whose total ARR is > $1K or have more then 1K employees.  These are customers who have either never had a subscription with Mattermost or have not had an active subscription with us for more than 12 months.  

### Partner ARR

ARR for all contracts that originated from partners.   

### Sales ARR

ARR for all contracts that originated from the Mattermost Sales Team.  

### Online ARR

ARR for contracts that are from our online store or from the Mattermost Cloud.  

### Sales Driven Expansion ARR

This is the amount of expansion driven by sales activities.  This is currently defined as any expansion (Contract or Account) within the first 12 months or up to the first renewal ( whichever comes first )  as well as any Account Expansion (see definition above).   

### Customer Success Driven Expansion ARR

This is the amount of expansion driven by customer success activities.  This is currently defined as any contract expansion (See definition above) after the first 12 months or up to the first renewal ( whichever comes first ).  

### Contract Expansion ARR

ARR of contracts that increased during the subscription term (e.g. increased seats) or at the time of subscription renewal. Examples of this generally occur part of organic expansion.  Occurs on existing subscription contracts.

### Account Expansion ARR

ARR of contracts from new groups and operating budgets within existing customers that will result in recurring revenue over the next 12 months.  Account expansion has one of three identifiers :  1.)  it comes from a new operating unit within a customer ( with its own budget and approval chain ).  2.)  A brand new contract and license is required for a seperate team internally ( with the exception of a second contract for ease of use or eventual consolidation), 3.)  There is a separate executive sign off on this contract over existing contracts.  

### Renewal ARR

Dollar value of subscriptions with business customers that either opted-out of a renewal or did not opt-in to renewal after subscription expired during time period.

### Total Expansion ARR

Contract Expansion + Account Expansion.  

### Winback ARR

Total ARR of churned customers that we have been able to win back as paying subscribers within the first 12 months after a churn event.  

### Reduction ARR

The total ARR of the subscription base that shrunk but was not lost during the period measured.   

### Churn ARR

The total ARR of the subscription base that was lost during the period measured.   

### Per Product ARR
Product 

## Data/Fields Required for ARR Metrics:

### Original Amount

Amount of Deal Closed (TCV) in Local Currency

### Original Currency

The Currency of Original Amount

### Amount

Amount of Deal Closed (TCV) in USD

### Length

Length of the Deal Closed

### Partner Fee

Amount of the total deal owed to partner

### ACV

The total Average ACV of the deal

### ARR

The ARR for this deal ( Average for multi-year)

### Partner

The name of the partner if one was used

### License Start Date

### License End Date

### Type 
* New
* Renewal
* Account Expansion
* Contract Expansion
* Winback
* Downgrade/Reduction
* Closed Lost

### Sales Source
* Partner
* Sales
* Online

### Products/line items

The products on this deal

### Expansion Credit

Sales or CS driven Expansion

### Previous Opportunity

Opportunities to link together

### Previous Amount

Previous or linked opp amount

### Previous ARR

Previous or linked opp arr

### Previous Length

Previous or linked opp length

### Previous End Date

Previous or linked opp end date

### Delta ARR

The difference between the current arr and the previous linked arr

### Delta Amount

The difference between the current amount and the previous linked amount

### Next Amount

The Upcoming renewal amount if needed

### Next ARR

The Upcoming renewal arr if needed

### Next Renewal Length

The Upcoming renewal legnth if needed

### Account Summary ARR

The total ARR of the account 

Note:  SFDC Opp Walk through here:  https://docs.google.com/document/d/15ZAiQTSstMApM0kEYjEvDZH9RocW1ZxBZ0949aCzias/edit

## Revenue Workflow:

### Partner Driven Deals:

There are three types of partners we will work with.  

1. The first is a a pure “Referral Partner”, they will get 15% of the initial tcv (less taxes and currency conversions).  They connect us with business or refer us to deals.  Once they pass through a deal we manage the sale, relationship, expansion, and renewal.  All deals handled this way follow our rules and processes.  
* The fees on this type of a deal are limited to the initial sale.  
* Commission should be paid on the ARR ( which is defined as less fees )

2. The second is a “Enablement Partner”, they are eligible for 15% of the initial tcv (less taxes and currency conversions).  They enable us to enter a market we would not normally be able to enter.  Many companies for instance cannot process government contracts.  These partners will assist us and will handle the legal end of contracts and final paperwork.  We will still have a direct relationship with the customer and co-work with the partner on renewals.   
* The fees on this type of a deal will be recurring
* Commission should be paid on the ARR ( which is defined as less fees )
  
3. The third is a true “Strategic Partner”.  They are eligible for 15-30% of the initial TCV depending on their partner tier and if they will do tier 1 support ( 5% ).   These partners should be prepared to handle the sales and renewals functions.  We will provide customer enablement and partner material.  We may assign CS at our discretion to help keep these accounts active, but at higher partner tiers we expect the Partner to maintain this relationship.   
* The fees on this type of a deal will be recurring	
* No Commission should be paid on the ARR ( which is defined as less fees ), Unless we assign a CS person at our discretion.   

### Sales Driven Deals:

The majority of sales driven deals fall into two types of customer use cases.  #1 New Logos (  customers who have not had an active subscription for more than 12 months ) or #2 Expansion that is from Account Expansion ( Expansion from new units within a customer ) or any additional expansion within the first year of a deals. In the case of expansion deals sales and cs will work together on these to ensure they close properly.   

### CS Driven Deals:

Customer success is primarily involved in owning and closing two types of deals.  #1 Renewals and #2 Contract Expansion ( or a better way to say this maybe organic expansion within and account outside the first year).  They will assist and help sales close account expansions and both be goaled and metriced on these as well.  Customer success will start working with the customer immediately after the sale and work towards full ownership at the renewal or end of 12 months.  

### Online Deals:
Deals sold online for either our enterprise software or for the Mattermost cloud will be automatically calculated and managed in the system.  These should be assigned a CSM to begin working with them just like any other deal.   
