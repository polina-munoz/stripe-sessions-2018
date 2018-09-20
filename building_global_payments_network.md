# building a global payments network

David Singleton

- Discussing phone growth from 2005 onwards
- Developer experience for mobile was fragmented
- It was time consuming, error prone, costly -- barrier to innovation
- We are on the cusp of a similar paradigm shift for commerce globally (similar to mobile paradigm shift with android and ios)
- Payment leadership considerations: conversion, product launches, uptime, fraud & risk, costs
- Global expansion:
  - Finance and reconcile everything at the end of the month with new regulations and standards
  - KYC in SF is straight forward (social)
  - KYC in India is long and hard and fragmented
  - country level implementation is a huge drain on the engineering team
  - "double width" numerals that Japanese computers produce
  - Polish tourists expect to pay in p24, sign a contract in Polish. Establish a euro denominated bank account.
  - Reconcile p24 payments with the rest of our finances
  - Stripe has added significant headcount to its euro team for understanding regulatory changes
  - Allow for faster/instant payouts to remain competitive

Optimizing the pay in experience

- leaders are usually focused on optimizing experiences for pay in
- we are now trying to optimize pay out
  - how will this work across national borders?
  - greatest area of complexity: period where money is held in treasury balances
    - how you manage exchange rates
    - created dependendies on regional entities, reconciliation
    - trying to balance how money is held
    - there is a virtual fence around how we handle money
    - how do you free the movement of money?
 - three problem areas:
   - how you pay money in (funding)
   - how you pay money out (disbursment)
   - how you move money (balances)
- how do you connect these three components in the best way?
  - how do you move money and manage your treasury?
  - this is a source of risk

Optimizing how you accept money

- dynamically formatting postal codes for CA buyers maximizes acceptance rates
- Stripe is one of the very few direct acquirers of VISA and mastercard
- local acquiring for global challenges
- "fx" conversion = "foreign currency conversion"
- Stripe attempts to get ahead of this problem: currently presents 7 settlement currencies in Europe

Optimizing Costs

- Speaker: Kalyani Iyer, Global Acquiring Lead https://www.linkedin.com/in/kalyaniiyer/
- Instant funding of virtual wallets with account funding transactions (AFTs)
  - There is a lot of opportunity here
  - A way to store value on your platform
  - You can top up your wallet with a debit card: charging a debit card can get expensive pretty fast
  - Bank debits are cheaper but users want to use debit cards
  - Stripe turned on VISA's AFT product to enable quick and easy top ups for virtual wallets
  - How do you optimize for auth rate?
    - Ex. AFTs
      - all sorts of decline codes, "do not honor"
      - complimented with "issuer outreach"
      - how we ensure that the user experience is still optimal?
      - there are a handful of issuers that do not support AFTs: Stripe has blacklisted them (lol)
      - being "close to the bare metal"

Back to the Global Payments Network:

- goal is to think of a small number of basic operations 
- benefit is a high performing treasury network
- reduce time to report, reconcile, and fund managment
- the three basic operations are pay in, pay out, and treasury movement

Better Payouts

- product and user experience
- operational excellence
- you can do this with top-ups and instant payouts
- "conventional rails" <-- he keeps saying this, need to figure out what this means



  
