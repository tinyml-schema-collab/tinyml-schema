# Welcome to tinyml-schema

The Internet of Things (IoT) is revolutionizing industry. Powered by pervasive embedded devices, the Industrial IoT (IIoT) provides a unique solution for retrieving and analyzing data near the source in real-time. Distributed computing presents management challenges, as IoT devices are diverse and constrained, and their number is growing exponentially. The situation is even more challenging when various on-device applications (so-called artifacts) are deployed across decentralized IoT networks. Questions to be addressed include how to discover an appropriate function, whether that function can be executed on a certain device, and how to orchestrate a cross-platform service. To tackle these challenges, we propose an approach for the scalable management of on-device applications among distributed IoT devices. By leveraging the W3C Web of Things (WoT), the capabilities of each IoT device, or more precisely, its physical patterns, can be semantically expressed in a Thing Description (TD). In addition, we introduce semantic modeling of on-device applications to supplement a TD with additional information regarding applications on the device. By hosting the enriched semantic knowledge of the entire IoT system in a Knowledge Graph (KG), we can discover and interoperate diverse knowledge across the network in a unified way. This reduces fragmentation and increases the reusability of IoT components. 

This is the tinyml-schema project repository. It contains all the schemas, examples, and related software.

The goal of tinyml-schema is not to invent new semantic models for IoT. Instead we integrate and reuse existing schemas, ontologies and vocabularies. The approach is open, organic and community based. 

## Citation
If our work has been useful for your research and you would like to cite it in an scientific publication, please cite our paper [Towards Semantic Management of On-Device Applications in Industrial IoT](https://github.com/tinyml-schema-collab/tinyml-schema) as follows:
```
To be added
```

## Project Structure
* [SPARQLQueries](https://github.com/tinyml-schema-collab/tinyml-schema/tree/main/SPARQLQueries): We prove the concept by providing SPARQL queries to answer a set of compentency questions
* [otherSchemas](https://github.com/tinyml-schema-collab/tinyml-schema/tree/main/otherSchemas): other dependency schemas, such as SSN, SOSA, schemaorg, etc,.
* [semanticExample](https://github.com/tinyml-schema-collab/tinyml-schema/tree/main/semanticExample): semantic instances for demonstration purposes including semantic descriptions of IoT devices and on-device artifacts (Neural Network, CEP Rules, and IoT devices)
* CEPRuleSchema: The ontology for CEP rules
* NeuralNetworkSchema: The ontology for neural network model

## To do
```
To be added
```

## Contributing to the project

We welcome contributions. Please contact us by email to get started!



