# Service Description

A list of all Open Source repositories can be found on the GitHub organization page: [https://github.com/nimble-platform](https://github.com/nimble-platform)

Each repository holds a README file in its root folder with basic deployment instructions and usage options.

Launch Workshop Video: [https://www.youtube.com/watch?v=3ET5VGF2gVA](https://www.youtube.com/watch?v=3ET5VGF2gVA)

#### The following repositories are essential for running the NIMBLE core:

- **business-process-service**: Enables the execution of business processes
- **catalog-service**: Stores products and (logistic) services
- **common**: Common data models and utilities that can be accessed by other services
- **frontend-service**: The user interface
- **identity-service**: Manages user and company identities
- **indexing-service**: Provides search capabilities with Apache SOLR
- **trust-scoring-service**: Enables the configuration and calculation of trust scores

#### The following repositories are required for platform analytics:

- **docker-elk**: Provides the Elasticsearch, Logstash and Kibana stack
- **data-aggregation**: Aggregates data from other services

#### The following repositories support optional/additional services:

- **agent-service**: Enables agent-based business processes
- **chatbot-service**: Configurations for running Rocket.Chat
- **collaboration-tools**: Enables the collaboration feature
- **data-channel-service**: Enables the data channel feature
- **dcf_service**: Enables filtering of Kafka streams for the data channel feature
- **delegate-service**: Enables platform federation
- **epcis**: Enables EPC code support for the Tracking and Tracing feature
- **tracking-analysis-service**: Enables analytics for the Tracking and Tracing feature
- **tracking-iot-blockchain-service**: Enables IoT and Blockchain integration for the Tracking and Tracing feature
- **tracking-service**: Enables the Tracking and Tracing feature

#### The following repositories are helpful for deployment:

- **cloud-config**: Infrastructure configuration for cloud deployment
- **docker_setup**: Setup for local deployment