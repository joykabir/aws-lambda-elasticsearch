# aws-lambda-elasticsearch
*Lambda function that ships plain json logs to elasticsearch

Basically this lambda takes base64 encoded logs from Cloudwatch or Kinesis stream, decodes and post to ES.

Most implementation is takesn from AWS help.
