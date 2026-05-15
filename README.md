# SQL-NoSQL
This project is mainly targeted to improve collaboration of SQL and NoSQL databases without any actually modelling.

The aim of this project is to help automotive companies or any other organisation, whose data lies in both document store databases (NoSQL) and relational tables (SQL). Our platform acts as a bridge to connect the two types of data and allows it to be reasoned and queried together.

Our ML models along with our AI tools encourages users to ask their queries in natural language. Which will be later used to convert into structured queries to retrieve the relevant information.

Data from the organisation will not be sent to the AI models, only a dummy test data will be used to make the model understand the structure of the dataset in order for it to generate meaningful and syntactically correct queries, which can later be executed on the databases. After which, the retrieved information will be processed via our engine to be sent back to the user as a natural language output.

The prototype of the platform includes data similar to the sales and finance data of automotive manufacturer.

The SQL tables include:
Sales Header
Product
Material Master
Purchase Order
Finance
Production Inventory
Billing Header
Billing Line Item


The NoSQL tables include:
Engine Specifications
Part Specifications
Model Specifications
Fuel Specifications
Testing Specifications
Tyre Specifications
Performance Specifications