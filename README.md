# AWS CWL-Lambda-ElasticSearch

Lambda function ships JSON formatted logs to Elasticsearch

Basically the lambda receives base64 encoded logs directly from Cloudwatch or Kinesis, decodes and post bulk to ES.

Most implementation is taken from AWS doc.

<img src="https://travis-ci.org/joykabir/aws-lambda-elasticsearch.svg?branch=master" alt="Build Status" />
