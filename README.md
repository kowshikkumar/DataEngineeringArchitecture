# DataEngineeringArchitecture

Converting batch to streaming Architecture using Kafka/API. 

Tech stack: Spring boot, Spring batch, Oracle DB, Source file (csv)

In Existing Batch architecture, the File is used as lookup in various stages of batch process. Whereas converting to near real time streaming architecture, Batch look up is converting into Microservice architecture.
Spring batch is used to load file to table since file is source of truth, We are receving from External team.

A service layer with API endpoint's is built top on Oracle table. Necessary service can fetch relevant data using API endpoint exposed. 


NFR:
Latency
Availability

