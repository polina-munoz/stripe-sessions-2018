# scaling engineering orgs effectively

Raylene Yung, Head of Payments Engineering at Stripe

### Beginning

- generalist API engineers, based in California
- solidly single threaded
- pairs of engineers would work on features, one at a time
- all engineers had access to all of the payment network info

### Stripe Today

- live in 26 countries
- far beyond payment processing: invoice processing
- millions of sellers paid out using connect
- Stripe Terminal, Stripe Checkout, Stripe Issuing in parallel
- Currently redesigning our core data primitives in order to continue to expand globally

### Infrastructure

- Dusty Burwell, Infrastructure at Stripe
- API spike when Kylie launched a flash lipstick sale on Instagram
- Sequins:
  - open source key value store
- Balancing Stability and Speed

> Engineering principle at Stripe: Make small verifiable changes

Patterns to role out new changes quickly

- Feature Flags
- Scientist, for refactoring critical paths: https://github.com/github/scientist
- Ratchets
  - Static analysis tooling
  - Deprecate APIs and alert engineers using static analysis
  - Allows you to do small incremental changes
  - Nudge behavior of other teams
- Sorbet, optional type checker for Ruby
  - https://medium.com/byteconf/stripe-is-building-a-ruby-typechecker-d6cd7cee6abf
  - https://sorbet.run/
- Unattended deploys
  - Canary deploys / phased deployments with automatic rollbacks
  
### Primitives & People

- Michael Schade, Head of Leverage Engineering at Stripe
- They don't automated support away
- In the early days they hired engineers for their support team
- "the ideal programming language is declarative"
- Ex. building up complex and reusable workflows within Stripe
- "If we can't keep up with all these tools, let's just create the tool builder"

### Training new Engineers

- Tara Teich, Engineering manager
- Stripe used to be called /dev/payments
- How do they teach new Stripes

/dev/start Program

- 4 week program:
  - 4 week project, 3-5 engineers with dedicated mentor
  - full development cycle from design to deploy
  - build a community with your cohort




