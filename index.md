# Nanopub Space

Funding for this project applied for at [NGI Zero Core](https://nlnet.nl/core/).


## Vision

The Nanopub Space is a first step towards the implementation of the vision of a [Knowledge Space](https://w3id.org/knowledge-space/).


## Software

Software to be developed:

- [Nanopub Registry](https://github.com/knowledgepixels/nanopub-registry) (MIT license)
  - design is available
  - implements the publishing/lookup services of the Knowledge Space vision above
  - once available in a stable version, Nanopub Query (see below) will connect to the Nanopub Registry instances to gather the data on which the Nanopub Query instances can then run more complex queries on
- Nanopub<>ActivityPub (MIT license)
  - bidirectional module connecting the knowledge graph contributions in our ecosystem with the plain-text-focussed contributions in ActivityPub world

Software to be used:

- [Nanopub Query](https://github.com/knowledgepixels/nanopub-query) (AGPL license)
  - implements the query services of the Knowledge Space vision above
- [Nanodash](https://github.com/knowledgepixels/nanodash) (AGPL license)
  - is a graphical user interface to deal with nanopublications
- [nanopub-java](https://github.com/Nanopublication/nanopub-java) (MIT license)
  - a stable Java library to deal with nanopublications
  - includes the generation of hash-based identifiers ([Trusty URIs](https://trustyuri.net/)) and digital signatures


## Organization

This project will be performed at [Knowledge Pixels](https://knowledgepixels.com/), a young startup based in Switzerland committed to revolutionize (scientific) knowledge sharing with an open and decentralized ecosystem run on Open Source software.

