# Indexing_data_in_ES_from_dynamodb_table
This lambda function is invoked whenever any data is inserted, updated or deleted in dynamodb table through dynamodb stream and once the lambda is invoked it indexes the data in AWS Elasticsearch by reading it from dynamodb table.
Developer should add the respective dynamodb table in trigger of this lambda function.
