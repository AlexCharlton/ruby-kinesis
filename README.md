# Kinesis Streams on Ruby

## Running locally
`Bundle install`

First run `local-setup.sh` to start local Kinesis and DynamoDB

To kick of the sample producer, run `sample_kcl_producer.rb`

To run the sample consumer, run `rake 'kinesis:run[./sample_record_processor]'`

Create new consumers and run them!
