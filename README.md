# DataEngineeringArchitecture

Converting batch to streaming Architecture using Kafka/API. 
Tech stack: Spring boot, Spring batch, Oracle DB, Source file (csv)

In Existing Batch architecture, the File is used as lookup in various stages of batch process. Whereas converting to near real time streaming architecture, Batch look up is converting into Microservice architecture.
Spring batch loads External Source file to table and service layer is built on top of the table.

NFR:
Scalability
Latency
Availability

