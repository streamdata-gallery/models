---
name: AWS Machine Learning
x-slug: aws-machine-learning
description: Amazon Machine Learning is a service that makes it easy for developers
  of all skill levels to use machine learning technology. Amazon Machine Learning
  provides visualization tools and wizards that guide you through the process of creating
  machine learning (ML) models without having to learn complex ML algorithms and technology.
  Once your models are ready, Amazon Machine Learning makes it easy to obtain predictions
  for your application using simple APIs, without having to implement custom prediction
  generation code, or manage any infrastructure.Amazon Machine Learning is based on
  the same proven, highly scalable, ML technology used for years by Amazon&rsquo;s
  internal data scientist community. The service uses powerful algorithms to create
  ML models by finding patterns in your existing data. Then, Amazon Machine Learning
  uses these models to process new data and generate predictions for your application.Amazon
  Machine Learning is highly scalable and can generate billions of predictions daily,
  and serve those predictions in real-time and at high throughput. With Amazon Machine
  Learning, there is no upfront hardware or software investment, and you pay as you
  go, so you can start small and scale as your application grows.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Models
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Machine Learning API - Create M L Model
  x-api-slug: actioncreatemlmodel-get
  description: |-
    Creates a new MLModel using the DataSource and the recipe as
                information sources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actioncreatemlmodel-get-openapi.md
- name: AWS Machine Learning API - Delete M L Model
  x-api-slug: actiondeletemlmodel-get
  description: Assigns the DELETED status to an MLModel, rendering it unusable.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actiondeletemlmodel-get-openapi.md
- name: AWS Machine Learning API - Describe M L Models
  x-api-slug: actiondescribemlmodels-get
  description: Returns a list of MLModel that match the search criteria in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actiondescribemlmodels-get-openapi.md
- name: AWS Machine Learning API - Get M L Model
  x-api-slug: actiongetmlmodel-get
  description: Returns an MLModel that includes detailed metadata, data source information,
    and the current status of the MLModel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actiongetmlmodel-get-openapi.md
- name: AWS Machine Learning API - Update M L Model
  x-api-slug: actionupdatemlmodel-get
  description: Updates the MLModelName and the ScoreThreshold of an MLModel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actionupdatemlmodel-get-openapi.md
- name: AWS Machine Learning API - Create Evaluation
  x-api-slug: actioncreateevaluation-get
  description: Creates a new Evaluation of an MLModel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actioncreateevaluation-get-openapi.md
- name: AWS Machine Learning API - Create M L Model
  x-api-slug: actioncreatemlmodel-get
  description: |-
    Creates a new MLModel using the DataSource and the recipe as
                information sources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actioncreatemlmodel-get-openapi.md
- name: AWS Machine Learning API - Create Realtime Endpoint
  x-api-slug: actioncreaterealtimeendpoint-get
  description: Creates a real-time endpoint for the MLModel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actioncreaterealtimeendpoint-get-openapi.md
- name: AWS Machine Learning API - Delete M L Model
  x-api-slug: actiondeletemlmodel-get
  description: Assigns the DELETED status to an MLModel, rendering it unusable.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actiondeletemlmodel-get-openapi.md
- name: AWS Machine Learning API - Delete Realtime Endpoint
  x-api-slug: actiondeleterealtimeendpoint-get
  description: Deletes a real time endpoint of an MLModel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actiondeleterealtimeendpoint-get-openapi.md
- name: AWS Machine Learning API - Describe M L Models
  x-api-slug: actiondescribemlmodels-get
  description: Returns a list of MLModel that match the search criteria in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actiondescribemlmodels-get-openapi.md
- name: AWS Machine Learning API - Get M L Model
  x-api-slug: actiongetmlmodel-get
  description: Returns an MLModel that includes detailed metadata, data source information,
    and the current status of the MLModel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actiongetmlmodel-get-openapi.md
- name: AWS Machine Learning API - Predict
  x-api-slug: actionpredict-get
  description: Generates a prediction for the observation using the specified ML Model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actionpredict-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actionpredict-get-openapi.md
- name: AWS Machine Learning API - Update M L Model
  x-api-slug: actionupdatemlmodel-get
  description: Updates the MLModelName and the ScoreThreshold of an MLModel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: Amazon Web Services, Machine Learning, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/aws-machine-learning/actionupdatemlmodel-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.lightsale.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.machine.learning.stack.network
- type: x-command-line-interface
  url: http://aws.amazon.com/cli/
- type: x-console
  url: https://console.aws.amazon.com/machinelearning
- type: x-documentation
  url: http://docs.aws.amazon.com/machine-learning/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/machine-learning/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/machine-learning/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/machine-learning/pricing/
- type: x-tools
  url: http://aws.amazon.com/developertools/
- type: x-website
  url: https://aws.amazon.com/machine-learning/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---