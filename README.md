# Prove Your Stake
###### Reputation Sharing Platform // [Global Blockchain Hackathon – NY 2018](http://blockchainhackathon.io/ny/)

## Platform Architecture 
Prove Your Stake (PyS) structurally consists of several modules. Each module is a substantial part of the system.

### Reputation Score Enricher (RSE)
The module consists of a set of connectors to the trusted data providers 
 (such as [Amazon](https://amazon.com), [eBay](https://ebay.com), 
 [Uber](https://uber.com), [Tinder](https://tinder.com), [Airbnb](https://airbnb.com), 
 [Expedia](https://expedia.com), [Yelp](https://yelp.com) and many many others). 
 Each connector enriches our platform with the user's reputation data. 

### Reputation Score Export API (RSEx)
An API allows an easy access to the user's reputation data for third parties.
 The user decides on which information to provide and to whom.

### Reputation Scoring SaaS (RSs)
The service enables third parties to delegate reputation scoring handling to 
 our service and focus on their business model. The user can pick the scoring model
 from our standard library or create his own.

## Security
RSE gets the data over HTTPS which allows to securely ensure the data source. 
 The data enrich process is backed by a decentralized ledger. It ensures
 imported data immutability.

## About
Developed by [Basil Gorin](https://www.linkedin.com/in/gorin/), [Oleksand Shchetynin](https://www.linkedin.com/in/shchetynin/)
 on [Global Blockchain Hackathon](http://blockchainhackathon.io/ny/), July 14 – 15, 2018.
