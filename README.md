# great_expectations
Let us understand how to validate, document, and profile your data to maintain quality and improve communication between teams. It helps us understand what to expect from the data we load and transform, and catch any data issues quickly. With the help of Great Expectations, we can also create data documentation and data quality reports from basically creating unit tests for given data. 
When new data is ingested from any source, it can be transformed as part of the data pipeline and to ensure its correctness, we validate data. This allows us to prevent data quality issues. 

## Expectations
What are Expectations?
Expectations are assertions about your data. And how do you define an assertion. For example, we use assertions to check a particular condition is always true or if any values stray from it. Great Expectations library currently provides over 300 built-in Expectations, and additionally you can write custom Expectations.

## Definitions to understand
[<b>Data Context </b>](https://github.com/vaishali-yasala/great_expectations/tree/main/datacontext) - The primary entry point for a Great Expectations deployment, with configurations and methods for all supporting components.

[<b>Data Source </b>](https://github.com/vaishali-yasala/great_expectations/tree/main/datasource) - It provides a *standard API* for accessing and interacting with data from a wide variety of source systems. 

[<b> Batch Request </b>](https://github.com/vaishali-yasala/great_expectations/tree/main/batchrequest) - A batch request is provided to a Datasource in order to create a Batch. 

[<b> Batch </b>](https://github.com/vaishali-yasala/great_expectations/tree/main/batch) - A Batch is a selection of records from a Data Asset.

[<b> Data Asset </b>](https://github.com/vaishali-yasala/great_expectations/tree/main/dataasset) - A Data Asset is a collection of records within a Datasource which is usually named based on the underlying data system and sliced to correspond to a desired specification.

[<b> Data Connector </b>](https://github.com/vaishali-yasala/great_expectations/tree/main/dataconnector) - A Data Connector provides the configuration details based on the source data system which are needed by a Datasource to define Data Assets.

[<b> Execution Engine </b>](https://github.com/vaishali-yasala/great_expectations/tree/main/executionengine) - An Execution Engine is a system capable of processing data to compute Metrics.

[<b> Metrics </b>](https://github.com/vaishali-yasala/great_expectations/tree/main/metrics) - A Metric is a computed attribute of data such as the mean of a column.

[<b> Validator </b>](https://github.com/vaishali-yasala/great_expectations/tree/main/validator) - A validator is the object responsible for running an Expectation Suite against data. 

[<b> Expectation Suite </b>](https://github.com/vaishali-yasala/great_expectations/tree/main/expectationsuite) - An Expectation Suite is a collection of verifiable assertions about data.

[<b> Validation Result </b>](https://github.com/vaishali-yasala/great_expectations/tree/main/validationresult) - A Validation Result is an object generated when data is validated against an Expectation or Expectation Suite. 

