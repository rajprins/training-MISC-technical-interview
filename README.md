# MuleSoft Training Interview - Technical Project

## Summary
Mule United Airport is undergoing a large legacy modernization initiative. Their primary goal is to expose all their services in a single intuitive REST API.  The current services contain flight data. This flight data represents outbound flights to SFO, CLE, LAX, and PDX from Mule United Airport. The services which expose this data include a SOAP web service, REST web service, and database. Your goal is to create a POC (proof of concept) exposing all these services as a single REST service which can be used to **retrieve** flights. Do your best in this exercise to cover as many of the systems as possible and don't feel limited to only covering the goals outlined in this document. We'd like your solution to be representative of your approach a technical challenge such as this!  

## Goals:

Below are a few goals to help guide you through the development. Remember that we don't require full coverage of every goal; do your best to include as much as possible in your POC. 

- Design and implement a REST service which exposes as many of the above sources of data as possible.

- Return all data in a JSON format.

- Provide something which documents how to interact with the REST service (e.g. RAML or Swagger).

- Anything else you feel beneficial to the solution!

## Systems

Below are the various systems you'll be using in your project. Note you only have read access to these systems.

### American MySQL Database

Server: `training.cpk4jjb2mzwd.us-west-2.rds.amazonaws.com`

Port: `3306`

Username: `ReaderAccount`

Password: `learnmule`

Database: `training`

Table: `flights`

### United REST Service

Retrieve all flights: `http://training.cloudhub.io/essentials/united/flights`

Retrieve flights to a specific destination: `http://training.cloudhub.io/essentials/united/flights/{destination}`

### Delta SOAP Service

WSDL address: `http://training.cloudhub.io/essentials/delta?wsdl`

### Possible destinations

- SFO
- LAX
- CLE
- PDX


## Resources:

While you're not restricted to any specific technology to accomplish this goal, below are some available tools/resources MuleSoft provides.

- MuleSoft documentation: [http://www.mulesoft.org/documentation/display/current/Home](http://www.mulesoft.org/documentation/display/current/Home)

- Anypoint Studio for creating and running Mule Applications: [https://www.mulesoft.com/studio](https://www.mulesoft.com/studio)

- Anypoint Platform Account; sign up for access and a free 30-day trial to most of the available service: [http://anypoint.mulesoft.com](http://anypoint.mulesoft.com)

- RAML.org for modeling REST APIs: [http://raml.org/](http://raml.org/)

- Reach out to josh.rosso@mulesoft.com if you have any questions around project goals.

## Submission:

Submit your final solution including **all** source files to training@mulesoft.com. Ensure the subject reads {Your Name} - Technical Project.
