# Introducing Stripe Terminal
[stripe.com/terminal](stripe.com/terminal)

## User Stories

### Ventrata

* They power Tour operators (Big bus tours, paramount, universal, star line)
* Speed of transaction is important
* Online requires servers and in-store requires more people
* Problems arise in managing hardware distribution and monitoring
* Current termial landspace is old and clunky
* Stripe is developer friendly
* Stripe onbooarding 3 hours vs 3 weeks of traditional POS onboarding (time to first sale)
* Ease of deploying new hardware across stores without new mechant codes/credentials/configuration
* Transactions are **Very fast**
* Works well in spotty connection situations
* Removes complexity in discovering devices

### Glossier

* Pop-up showrooms
* Brick & Mortar Locations
* Custom In-Store Portals with Stripe Integrations
* Tie online & in-store transactions

### Blackthorn.io Salesforce Integration

* Custom Mobile Pay apps
* Launch Mobile Payment App from Salesforce

### Universe

* Social ticketing online
* Food/Music/Film Festivals
* Acquired by LiveNation
* Mobile ticket sales for walk-ups

## Goals

* Meet Customers where they are
* Have unified view
* across geographies

* Today's POS landscape is complicated
* US is late in adopting EMV

* The problem to solve is In-Person payments
* Simplify Payment Stack across channels
* Reduce security & compliance burden
* Enable global expansion from a single platform

* **Custom EMV kernel for lightning fast transactions**

## Technical Building Blocks

### Terminal iOS/JS SDKs
* Integrate quickly to drive payments
* Reduces PCI scope

#### Registration
* POS on the Web
* Connect Reader via simply entering the reader device pairing code displayed on the web app. The reader is now paired.
* Pairing via cookies so connection saved on reloads

#### Transactions
* Ring up sale on Web-based POS
* POS triggers prompts on reader
* Customer enters card on reader (swipe/chip/contactless) and auths via stripe
* Stripe confirms to reader and POS
* Reader & POS never hold card data

#### iOS SDK
* Initial launch with only Mobile Reader
* Android SDK in the works (accepting Beta partners)

### Pre-certified EMV readers
* All devices are pre-certified (PCI/DSS Level 1, EMVCo Level 1,2,3)

### Web-based Fleet Management Tools
* Keep tabs on terminals & reader devices
* Devices periodically phone home with health
* Send/schedule configuration updates and software updates to devices
  * splash screen updates

## Offline to Online Subscriptions

* Visibility into where the customers are engaging. Offers Cross-channel Visibility.
  * Buy something online -> card on file -> reusable tokens can be used for in-store purchases

## Roadmap

* iOS/JS SDK (available now)
* Android SDK (Q1 2019)
* Additonal Hardware Form factors
* FLobal Expansion (Currently only US private beta)
  * Australia/GB/Singapore/HongKong
