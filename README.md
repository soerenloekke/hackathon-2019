# BONSAI 2019 Hackathon

This repo is for the planning and execution of the BONSAI Hackathon in Barcelona from March 25-29, 2019. We are also using a [mailing list](https://bonsai.groups.io/g/hackathon2019) for organization and team communication - you are welcome to join, or browse without subscribing!

## Your contribution

This repository, as well as the broader BONSAI effort, is happy to have your contribution! You are welcome to add your thoughts to existing documents, or create new ones. If you are already a hackathon participant, you can make changes directly to the master branch; otherwise, please [fork the repo and create a pull request](https://guides.github.com/introduction/flow/).

Please note that participation in and contribution to the BONSAI hackathon is subject to the [code of conduct](https://github.com/BONSAMURAIS/hackathon-2019/blob/master/Code-of-conduct.md).

## Motivation

Sustainability assessment, and life cycle assessment (LCA) in particular, is to a large extent built on cathedrals - large background databases, erected by the efforts of many people over a long period of time, but which are now both expensive and exclusive, and whose gatekeepers limit access to both the data and decisions on its management. [BONSAI](https://bonsai.uno/) believes in another model, a [bazaar](https://en.wikipedia.org/wiki/The_Cathedral_and_the_Bazaar) where the entire community can contribute to data generation, validation, and management decisions. We strongly feel that an open database is more transparent and more reproducible, and therefore the only option for the science of life cycle assessment. Such databases are also a prerequisite for LCA studies being used to support democratic decision making.

The BONSAI hackathon will be a first step in turning the ideals and standards developed by the efforts of the BONSAI team over the last five years into an open source toolchain capable of supporting LCA calculations.

## Background

- [RDF](https://en.wikipedia.org/wiki/Resource_Description_Framework) approaches to knowledge management have numerous benefits (such as allowing to link different data sources consistently) and wide application but it's unclear how these can be integrated with 'classic' LCA databases.
- More background on the relationships and open issues with LCA and open data [here](https://chris.mutel.org/next-steps.html#id2) and [here](https://lca-net.com/blog/next-step-open-lca-data/).

## Outputs

In addition to the following, we intend to submit 1-2 scientific publications on the hackathon results after its conclusion.

### Deliverable 1: A comprehensive ontology for industrial ecology and associated relevant data

This is based on the description at https://github.com/BONSAMURAIS/bonsai/wiki/Data-Storage#specify-minimum-core-data-and-metadata-formats - to be formalised as a proper ontology pattern and an RDF schema. 

To cover all aspects of Industrial Ecology, we would have to add "agents" of activities, as in the "[minimal ontology pattern](http://geog.ucsb.edu/~jano/LCA_pattern.pdf)", "assets" of these agents, and "behavioral rules" governing the interaction with their activities. This may be beyond the current hackathon. 

### Deliverable 2: An RDF database and associated tooling incorporating several large LCA data sources

### Deliverable 3: Data exchange standards for interoperable life cycle inventory models

### Deliverable 4: A working model that follows the standards in deliverable 3

This is being developed in the [bentso](https://github.com/BONSAMURAIS/bentso) repository.

### Stretch goal 1: An API specification and running implementation for the produced database

### Stretch goal 2: A set of global and regional independent validation data, and webpage tracking our values with these validation targets

### Stretch goal 3: A simple web-based tool to easily match CSV/Excel tables to the developed ontology using a ML text classifier

### Stretch goal 4: A simple web-based tool to compare directly competing statements present in the database

For example, if we have incorporate muliple EEMRIO databases at some point - or if we import new data that is more recent/disaggregated/otherwise different than existing data.

### Paper 1: Hackathon report to IJLCA

Similar to reports from the LCA discussion forum. Not peer reviewed. All participants as authors.

### Paper 2: From the ground up: A new approach to building LCA databases

Must be open access. Authorship to be determined by contribution to paper writing. All participants acknowledged.

### Paper 3: The world isn't flat: Making computational inventory models usable

Must be open access. Authorship to be determined by contribution to paper writing. All participants acknowledged.

### Paper 4: The BONSAI ontology for industrial ecology 

Must be open access. Authorship to be determined by contribution to paper writing.
