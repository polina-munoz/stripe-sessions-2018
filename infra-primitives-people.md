# Infra, primitives, and people: The three pillars of scaling engineering orgs effectively

Host: Raylene Yung, Head of Payments

### Culture
  * Engineers spend time getting feedback from customers and partners
  * Developer and User focus. Teams personally engage with tickets and visit customer offices for feedback
  * Feature development in parallel

## Infrastructure

Speaker: Dusty Burwell, Software Engineer

* Sequins: OSS Key-Value Store
  * auto-scaling
  * life-cycle management
  * focus on stability
  * replace system quickly and safely
* Stability || Speed
  * choose between stability vs velocity
  * Why not both

### Tools

* Feature Flags
  * quick rollouts
  * A/B tests
  * try out new things with minimal impact on users
* Scientist
  * introduce new code paths in the system simutaneously.
  * reports around performance characteristics of two code paths
* Ratchets
  * use static analysis tooling to squeeze old patterns out
  * deprecating old methods by catching old calls by static code analysis
* Sorbet
  * Optional typing system on top of ruby
  * additional type safety to cripple part of the system during CI (not production)
  * http://sorbet.run
  * not OSS yet
* Unattended Deploy
  * Stripe deploys over 400 times a day
  * Canary Deploy
    * deploy to small number of servers first
    * deploy to rest of the fleet after metrics are stable
    * roll back automatically on issues

## Scale User Support

Speaker: Michael Shade, Head of Leverage Engineering

* Support is learning what to build next
* Dedicated tooling team
  * creates tools for support and other teams
* internal tools are hard to keep up with
* didn't have data around efficiency of tools
* Make everyone a tool builder
  * Scripting environment for business workflows
  * build workflows for support environment
* This has become a learning engine at stripe
  * incorporates insights, feedback, reusable automations, checklists
  * doesn't become stale as it represents day-to-day workflows

## Recruiting

Speaker: Tara Teich, Engineering Manager, Mobile

### New Hire Education

* Initially, new engineers paired with a mentor
* /dev/start principles
  * consistent experience
  * ramp up on tech stack and best practices
  * learn culture from established engineers
* 4 week program
  * 3-5 engineers with dedicated mentor
  * full development cycle (design to deploy)
  * build community with your cohort
* Mentors have oppurtunities to learn
  * leading
  * project managing
* Proved to be un-scalable
  * mentors need to be established leaders
  * new hires increase faster than pool of mentors
  * different projects were not consistent in knowledge / difficulty
* How to scale?

## What's Next

* Innovate and expand
* new countries
* new solutions for markets
* richer versions of checkout & fraud
* multi-region development
  * radar built in seattle
  * local payment methods for europe developed in seattle 
