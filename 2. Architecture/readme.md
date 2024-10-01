# Architecture
Next Gen EA platform will need a technical platform that is flexible, independent as well equipped with latest tech innovations like Gen AI etc. For this reason SAP BTP is the PaaS choice where this platform will be developed. 
The following diagram will show the high level Tech Architecture of Next Gen EA Platform.
![HighlevelArchitecture](https://github.com/I304296/nextgenea/blob/main/images/highlevel-architecture.png)

As the Diagram shows above, we'd use the following:
* BTP Workzone for the fornt end UX delivery channel where we'd deploy the contents i.e. various apps fulfilling different functionalities.
* UX can be developed using UI5 or Build Apps
* The back end services will be built on CAP/HANA Cloud.
* HANA Cloud will be used for storing structured data, metadata.
* CAP will be used for building the back bone service that will help interlinking various apps.
* For Business AI services like RAG Enterprise we may need a separate BTP Account (to leverage Internal innovations via Canary)
* Main services to leverage SAP Buisness AI will be built using Langchain either via Python/CAP and this service layer will be main service to help ingesting SAP Business AI services.
