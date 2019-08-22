## WIP: Metrics

### Definitions

#### ARR

  - **IARR**: WIP // Incremental Annual Recurring Revenue
  - **New Logo ARR**: ARR from new logos signed, with start dates in the respective period.
  - **Expansion ARR**: ARR from existing customers with a cross-sell/upsell deal, with start dates in the respective period (e.g. increased licensed seat count, upgrading from E10 to E20).
  - **Contraction ARR**: Reduction in ARR from existing customers, but where they are still paying Mattermost.
  - **Churn ARR**: Reduction in ARR from an existing customer where they are no longer paying Mattermost.
  - **Net New ARR**: (New logo ARR + Expansion ARR) - (Contraction ARR + Churn ARR)
  - **Count of New Logos**: Count of new logos signed, with start dates in the respective period.
  - **Count of Churned Logos**: Count of logos lost where an existing customer is no longer paying Mattermost.

#### Magic Number

  - **Magic Number (Gross Margin Adjusted)**: Net New ARR in a period multiplied by Gross Margin in the period, divided by total Sales & Marketing expense in prior period.
  - **Magic Number (No Gross Margin adjustment)**:
  - **Gross Margin**: Net sales revenue minus cost of goods sold

#### Active Users

  - **Total Active Users**: The total number of user accounts created on a single Mattermost server. Excludes deactivated accounts, deleted accounts and bot accounts. This is also the "Total Active Users" measure shown in **System Console > Site Statistics**.
  - **Registered Authorized Users**: Same as **Total Active Users**.
  - **Total Registered Users**: The total number of user accounts created on a single Mattermost server, including deactivated and deleted accounts.
  - **Daily Active Users (DAU)**: The total number of users who viewed the Mattermost site in the last 24 hours. Excludes bot accounts. This is also the "Daily Active Users" measure shown in **System Console > Site Statistics**.
  - **Monthly Active Users (MAU)**: The total number of users who viewed the Mattermost site in the last 30 days. Excludes bot accounts. This is also the "Daily Active Users" measure shown in **System Console > Site Statistics**.
  - **Active User Count**: A measure of the number of active users last 24 hours. **Legacy measure, do not use this for analysis or decision-making.**

#### NPS

  - **Product NPS**: The product net promoter score (Product NPS) measures user satisfaction of the product, calculated based on single question "How likely are you to recommend Mattermost?". The score is based on a -100 to 100 scale, with the [calculation detailed here](https://en.wikipedia.org/wiki/Net_Promoter#How_it_works).
  - **End User Product NPS**: The Product NPS calculated among end users only (ie. not among Team or System Admins).
  - **System Admin Product NPS**: The Product NPS calculated among System Admins only.

#### Support

  - **Support Metrics (E10 and E20)**: Metrics calculated based on Zendesk tickets opened by E10 and E20 customers. Tickets opened by non-subscribed organizations are not counted towards these metrics.
  - **Tickets Created**: Number of net new Zendesk tickets created.
  - **First Response Time [Median, hours]**: The median number of hours from when a ticket was opened in Zendesk to when the first response was sent to the customer.
  - **% First Response >8 Business Hours**: % of newly opened Zendesk tickets whose first response time is greater than 8 business hours as defined in https://mattermost.com/support/.
  - **Resolution Time [Median, hours]**: The median number of hours from when a ticket was opened in Zendesk to when the ticket is resolved.
  - **% Resolution Time >7 days**: % of newly opened Zendesk tickets whose first resolution time is greater than 7 days.
  - **% Resolution Time >14 days**: % of newly opened Zendesk tickets whose first response time is greater than 14 days.
  - **Number of CSAT Responses**: # of new CSAT (Customer Satisfaction) survey responses from customers whose Zendesk ticket was resolved.
  - **Customer Satisfaction Score**: % of newly submitted CSAT survey responses who responded "Yes" to the question <insert CSAT question here>.

For technical analytics definitions not covered here, see the [Analytics Playbook](https://docs.google.com/document/d/1__65LymlUfXLzOiSKD-G56j16Jlx1fRaIu714s3yxDU/edit#heading=h.sowg5wp7n9lk).

### Best Practices

To be added.

