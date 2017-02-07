# AWS CWL-Lambda-ElasticSearch

## Lambda function that ships plain json logs to elasticsearch

Basically the lambda receives base64 encoded logs directly from Cloudwatch or Kinesis, decodes and post bulk to ES.

Most implementation is taken from AWS doc.

Travis Build: https://travis-ci.org/joykabir/aws-lambda-elasticsearch.svg?branch=master
