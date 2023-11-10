# Dr.ma_serveless_insertapplication
Serverless application with insert property and update the property

•	Downloaded the zip files from the blackboard
•	Imported the files and folders onto Cloud9.
Invoking add_property function:
•	Created a lambda function named add_property.
•	Written the code for add_property which adds the given property details onto the database i.e. DynamoDB.
•	Created an Event JSON named add_property and gave the values to be added into the database.
•	Created a REST API gateway and named it property_add and Added API trigger as REST API gateway in lambda function.
•	Created a stage called “development” to deploy all the changes.
•	Invoking the add_property function in lambda created a column in the Dynamodb table with the given details.
•	Gone through Cloudwatch logs to debug the errors.
Invoking update_property function:
•	Created a lambda function named update_property.
•	Created a REST API gateway and named it property_add and Added API trigger as REST API gateway in lambda function.
•	Created a stage called “development” to deploy all the changes.
•	Written the code for update_property which updates the given property details in the database i.e. DynamoDB based on the PID given.
•	Execution results state that it successfully updated the table.
•	Created an Event JSON named update_property and have given the values that are to be updated in the database.
•	Invoking the update_property function in lambda updated a column in the Dynamodb table with the given details.
•	Gone through Cloudwatch logs to debug the errors.
•	Previewed and ran the application “add_property.html” from Cloud9.
