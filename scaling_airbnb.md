# Scaling Airbnb to 191 countries and millions of hosts

Speakers

- Logan Vander Linden, Payments Partnerships Airbnb
- James Dyett, Head of Strategic Accounts Stripe

Notes

- We are less concerned about the demand rather than the supply
- We have to optimize for the Host experience
  - the importance of the supply side is tantamount at Airbnb
  - they have a chief economist at Airbnb
  - the seller side 
  - payout in 65 currencies
- They could have set up a system where the guest payment is tied to the host payout, but they decided not to.
  - They do hedging for fx trading in order to achieve this; they manage all of this
  - They have a treasury guru who is an expert on this
  - They have a guy who watches the price of oil and how that affects our settlement currencies and our currency position.

At what time do you decide to enter a new market?

- They follow an expand and then optimize pattern.
- They potentially acquire local acquiring partners.
- You cannot copypasta the US model. 
- How long does it take treasury to open that local bank account? Sometimes it will take 12 months to open an account.
- Sometimes it's not clear from a card scheme to an acquirers perspective. You have to validate your information across all parnters.
- If you think you're processing legally because your acquirer said it's ok, you need to ask again.
- They had to rearchitect their platform to support decimales.
- Gateway, acquirer, card scheme are the major stakeholders.
- Airbnb supports cash in Cuba.
- Airbnb teams: Treasury, Legal, Tax, Product, Financial Infrastructure

Complex payments stack

- Airbnb has a lot of countries
- Temporal issue: the time of the charge and the time of the payment, now the treasury guru needs to look at the price of oil.
- What's harder, paying out to guests or paying out to hosts.
- Payouts are a much harder problem, you don't have the same notification/response feedback loop as you have with pay in.
  - Example, they need the host to call them to tell them they haven't recieved their funds.
  - Payin is API based, pay out is batched files (you need to buy a lot of Boba tea lol)
- Payouts are hard. Global is hard. 

Operations

- Airbnb optimizes for operational maintenance. Need to know predictability of cost. 
- Does the partner's portal meet the needs of Airbnb's ops team?
- 10% of our hosts in the US are teachers
- largest segments of hosts in the US are women over the age of 50

Reporting

- The quality of reporting in this industry is varied.
  - Interchange, scheme fees.
  - Money movement on refunds and chargebacks.
  - Sometimes it's just one invoice, good luck trying to reconcile that.
  - If you want to move towards public trading company, you have to be able to predict your revenue and optimize for reporting.

Closing Thoughts

- Two sided marketplaces are tough. Incentivize employees to use your product.
- Build a team of practical thinkers and planners who are really going to manage the project.
- You have to be disciplined. Someone needs to be buttoned up and tight on the details.
- Do your extra due diligence up front.
- Don't spend too much money on marketing.
- The Network effect is what gets you to the Airbnb level. You need people to come back and talk about the product and build community.

Future of Payments

- We've been exchanging value since the beginning of time.
- Real time is now happening.
- Your ability to communicate with the global is going to be facilitated by payments.
- Obstacle to bringing the world closer together is payments.
- It's tied to digital identity.
- We need to mitigate threat of someone's ability to steal payments online.
- Place of innovation: Asia
- Demonitization in India, market penetration in China/India
- Several emerging markets are skipping steps in terms of what they would adopt payment wise.

## Additional Reading

List of Articles, Panels, Talks, and Interviews from Payments Team @ Airbnb

https://gist.github.com/polinadotio/3aaa73df5d15ad00cd3fab5150960c69
