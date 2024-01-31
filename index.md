# Nanopub Space

We are currently in the stage of applying for funding for this project.


## Vision

The Nanopub Space is a big step towards the implementation of the vision of a [Knowledge Space](https://w3id.org/knowledge-space/).


## Ecosystem

This project takes the existing nanopublication ecosystem as a starting point:

- [Nanopublications](https://nanopub.net/) are a concept and technology for sharing provenance-aware knowledge graph snippets

- [Nanopub Monitor](https://monitor.knowledgepixels.com/) shows the services in the current nanopublication ecosystem network

This project will make this ecosystem **scalable, trust-aware, and resilient**.


## Software

These pieces of software are to be developed within the project:

- [Nanopub Registry](https://github.com/knowledgepixels/nanopub-registry) (MIT license)
  - design draft available
  - implements the publishing/lookup services of the Knowledge Space vision above
  - once available in a stable version, Nanopub Query (see below) will connect to the Nanopub Registry instances to gather the data on which the Nanopub Query instances can then run more complex queries
- Nanopub<>ActivityPub (MIT license)
  - bidirectional module connecting the knowledge graph contributions in our ecosystem with the plain-text-focussed contributions in ActivityPub world

These pieces of software will be used:

- [Nanopub Query](https://github.com/knowledgepixels/nanopub-query) (AGPL license)
  - implements the query services of the Knowledge Space vision above
- [Nanodash](https://github.com/knowledgepixels/nanodash) (AGPL license)
  - is a graphical user interface to deal with nanopublications
- [nanopub-java](https://github.com/Nanopublication/nanopub-java) (MIT license)
  - a stable Java library to deal with nanopublications
  - includes the generation of hash-based identifiers ([Trusty URIs](https://trustyuri.net/)) and digital signatures

This piece of software will be made obsolete by this project:

- [Nanopub Server](https://github.com/tkuhn/nanopub-server) (MIT license)
  - The publishing/lookup service of the existing nanopublication ecosystem
  - Works but is neither scalable, trust-aware, nor resilient
  - To be gradually replaced by the Nanopub Registry above


## Organization

This project will be performed at [Knowledge Pixels](https://knowledgepixels.com/), a young startup based in Switzerland committed to revolutionize (scientific) knowledge sharing with an open and decentralized ecosystem run on Open Source software.

