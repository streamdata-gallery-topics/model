---
name: AWS API Gateway
x-slug: aws-api-gateway
description: Amazon API Gateway is a fully managed service that makes it easy for
  developers to create, publish, maintain, monitor, and secure APIs at any scale.
  With a few clicks in the AWS Management Console, you can create an API that acts
  as a front door for applications to access data, business logic, or functionality
  from your back-end services, such as workloads running on Amazon Elastic Compute
  Cloud, code running on AWS Lambda, or any Web application. Amazon API Gateway handles
  all the tasks involved in accepting and processing up to hundreds of thousands of
  concurrent API calls, including traffic management, authorization and access control,
  monitoring, and API version management. Amazon API Gateway has no minimum fees or
  startup costs. You pay only for the API calls you receive and the amount of data
  transferred out.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Model
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/model/master/_listings/aws-api-gateway/apis.md
specificationVersion: "0.14"
apis:
- name: AWS API Gateway API Model Create
  x-api-slug: aws-api-gateway-api
  description: Creates a new Model for this API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/models
  tags: Models
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/model/master/_listings/aws-api-gateway/restapisuojnr9hd57models-post-openapi.md
- name: AWS API Gateway API Model Delete
  x-api-slug: aws-api-gateway-api
  description: Deletes a model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/models/CalcOutput
  tags: Model
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/model/master/_listings/aws-api-gateway/restapisuojnr9hd57modelscalcoutput-delete-openapi.md
- name: AWS API Gateway API Model Generatetemplate
  x-api-slug: aws-api-gateway-api
  description: Generates a sample mapping template that can be used to transform a
    payload into the structure of a model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/models/output/default_template
  tags: Model, Templates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/model/master/_listings/aws-api-gateway/restapisuojnr9hd57modelsoutputdefault-template-get-openapi.md
- name: AWS API Gateway API Model Byname
  x-api-slug: aws-api-gateway-api
  description: Gets information about the Model of a specified name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/models/output
  tags: Model, Byname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/model/master/_listings/aws-api-gateway/restapisuojnr9hd57modelsoutput-get-openapi.md
- name: AWS API Gateway API Restapi Models
  x-api-slug: aws-api-gateway-api
  description: Gets an API&#39;s model collection represented by a Models instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/l9kujxkzq2/models
  tags: Models
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/model/master/_listings/aws-api-gateway/restapisl9kujxkzq2models-get-openapi.md
- name: AWS API Gateway API
  x-api-slug: aws-api-gateway-api
  description: Amazon API Gateway is a fully managed service that makes it easy for
    developers to create, publish, maintain, monitor, and secure APIs at any scale.
    With a few clicks in the AWS Management Console, you can create an API that acts
    as a front door for applications to access data, business logic, or functionality
    from your back-end services, such as workloads running on Amazon Elastic Compute
    Cloud, code running on AWS Lambda, or any Web application. Amazon API Gateway
    handles all the tasks involved in accepting and processing up to hundreds of thousands
    of concurrent API calls, including traffic management, authorization and access
    control, monitoring, and API version management. Amazon API Gateway has no minimum
    fees or startup costs. You pay only for the API calls you receive and the amount
    of data transferred out.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: :///
  tags: Model
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/model/master/_listings/aws-api-gateway/openapi.md
x-common:
- type: x-documentation
  url: https://docs.aws.amazon.com/apigateway/api-reference/
- type: x-faq
  url: https://aws.amazon.com/api-gateway/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/api-gateway/getting-started/
- type: x-partners
  url: https://aws.amazon.com/api-gateway/partners/
- type: x-pricing
  url: https://aws.amazon.com/api-gateway/pricing/
- type: x-website
  url: https://aws.amazon.com/api-gateway/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---