# gossip-api
A study of feature rich gossip protocols focusing on portability, efficiency and low footprint.

While studying gossip (aka epidemic) protocols, I've come accross a rich variety of implementations, with different remarkable features which I'll aim to standarize across different projects I'll be using as codebase and which will be extended for that purpose.
The API is defined using Swagger, which is language agnostic and guarantees portability across a variety of implementations.
The goal is to define a simple, yet powerful API and to provide fully functional implementations based on:

- GOlang: Smudge: https://github.com/clockworksoul/smudge
- Python: Gossip-Python: https://github.com/thomai/gossip-python
- Java: Apache-Gossip: http://incubator.apache.org/projects/gossip.html
