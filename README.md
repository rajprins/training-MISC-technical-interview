# MuleSoft Training Interview - Technical Project

## Summary
Mule United Airport is undergoing a large legacy modernization initiative. Their primary goal is to expose some of their services in a single intuitive REST API.  The current services contain flight data. This flight data represents outbound flights to SFO, CLE, LAX, and PDX from Mule United Airport. The goal of this exercise is to take either their database or SOAP service and expose it as a REST API. We estimate this project to take around 3-4 hours to complete. 

## Goals:

Below are a few goals to help guide you through the development. 

- Design and implement a REST service which exposes the database or SOAP service as a REST API.

- Return all data in a JSON format.

- Package the project as a Mule deployable.

## Cool ideas

Got some cool ideas not included in the goals above? No worries! Feel free to get creative with your solution, below are some cool ideas you could try out.

- Writing a specification that defines the interaction with your API.

- Routing to more than one service in your solution.

  - We've even included an extra REST service, if you'd like to test it out!

- Implementing error handling within the API.

- Deploying the app to a Mule server.

## Systems

Below are details on the various systems which can be used in this project.

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

Below are some available tools/resources we think you'll find helpful! 

- MuleSoft documentation: [http://www.mulesoft.org/documentation/display/current/Home](http://www.mulesoft.org/documentation/display/current/Home)

- Anypoint Studio for creating and running Mule Applications: [https://www.mulesoft.com/studio](https://www.mulesoft.com/studio)

- Anypoint Platform Account; sign up for access and a free 30-day trial to most of the available service: [http://anypoint.mulesoft.com](http://anypoint.mulesoft.com)

- RAML.org for modeling REST APIs: [http://raml.org/](http://raml.org/)

- Reach out to josh.rosso@mulesoft.com if you have any questions around project goals.

## Submission:

Submit your final solution including **all** source files to training@mulesoft.com. Ensure the subject reads {Your Name} - Technical Project.
