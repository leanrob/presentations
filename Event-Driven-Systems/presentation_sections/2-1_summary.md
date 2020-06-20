# Overview
## Event Sourcing / C.Q.R.S / D.D.D.


## D.D.D. - Domain Driven Design

Domain Driven Design is the idea that a software system should match the real-world domain that it is being built for.

- Context
- Domain
- Model
- Ubiquitous Language

Note:

Domain driven design is the idea that a software system should match the real-world domain it is being build for.
Or at least as closly as possible.

To acheive this, DDD, has 3 major concepts to consider.

Context is not a software idea, but rather the context in which word and statements live.

Domain refers to a sphere of knowledge and activity. Our domain is Amazon.

The model used is an abstraction of real-world aspects of the domain that are used to solve problems in the domain
> Ex. We have the idea of a listing in Amazon, that is part of the model


## C.Q.R.S. - Command Query Responsibility Separation

C.Q.R.S. is the concept that the command that a user sends to perform should be separated from the events that change the system.

- Keeping an audit log
- Extendable and flexable systems
- Scalability


## Event Sourcing

Instead of keeping a record of only the current state of the data within a system, Event Sourcing keeps a record of the full series of actions taken on thats data

- Append-only systems
- Events are understandable for Domain Experts and Developers
- Event Stores
- More...