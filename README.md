# [EventStore](http://eventstore.com/) resources collection
Information I found in the internet about [EventStore](http://eventstore.com/), that hopefully will become and awesome list.

This is a list to help people understand [EventStore](http://eventstore.com/) as a database tool, I did not include theory concepts around EventStore (like Event Sourcing, CQRS, Event Versioning, etc).

🏚 - Seems abandoned

🧓 - Older than 2019

⚡️ - Active

## EventStore
 - ⚡️ [Official Website](http://eventstore.com/)
 - ⚡️ [Official Github](https://github.com/EventStore/EventStore)

## Community
### Google Groups
- ⚡️ [Official Google Group List](https://groups.google.com/forum/#!forum/event-store)
### Twitter
- ⚡️ [Official Twitter](https://twitter.com/eventstore)
### Stack Overflow
- ⚡️ [Stack Overflow tag](https://stackoverflow.com/questions/tagged/get-event-store) - note: play with filters, there're many more than the ones showed by that link.

## Content
### Blog articles
 - 🧓 [EventStore for Orleans Grain Persistence](https://codeopinion.com/eventstore-for-orleans-grain-persistence/)
 - 🧓 [Explaining Greg's Event Store](https://blog.arkency.com/2015/03/explaining-gregs-event-store/)
 - 🧓 [Event Sourcing - Step by step in F#](https://medium.com/@dzoukr/event-sourcing-step-by-step-in-f-be808aa0ca18)
### Slides
- 🧓 [How to write your database: the story about Event Store](https://www.slideshare.net/vhaydin/it-weekendukraine2013event-store)
### Videos
- 🧓 [A deep look into the Event Store](https://vimeo.com/53153270)
### Books
### Blogs
### YouTube channels
### Online Courses

## Examples by language
### C#
- ⚡️ [Official .NET examples](https://github.com/EventStore/EventStore.Samples.Dotnet) - Samples with the dotnetapi

### F#
- ⚡️ [Equinox Examples](https://github.com/jet/equinox/tree/master/samples) - Examples using Equinox Framework.

## Clients by language
### Python
### .NET
#### C#
- ⚡️ [Official EventStore client](https://www.nuget.org/packages/EventStore.Client/) - The client API for Event Store
#### F#
- 🏚 [EventStore Client](https://github.com/haf/EventStore.Client.FSharp) - Wrapper Around EventStore.Client (.NET)
- ⚡️ [Equinox Project](https://github.com/jet/equinox) -  A unified programming model for event-sourced processing against stream-based stores including snapshots, caching and other state management/retrieval optimizations.
   - ⚡️ [EventStore Client for Equinox](https://www.nuget.org/packages/Equinox.EventStore) - Production-strength EventStore Adapter instrumented to the degree necessitated by Jet's production monitoring requirements.

- ⚡️ [Propulsion Project](https://github.com/jet/propulsion) - .NET event stream projection and scheduling platform with EventStore, CosmosDb, Equinox and Kafka integrations
  - ⚡️ [EventStore Client for Propulsion](https://www.nuget.org/packages/Propulsion.EventStore/) - Provides bindings to EventStore
### JVM
#### Scala
- ⚡️ [Official EventStore client](https://github.com/EventStore/EventStore.JVM) - Event Store JVM Client 
#### Java
-  ⚡️ [EventStore Java Client](https://github.com/msemys/esjc) - This is EventStore driver for Java, that uses Netty for network communication and GSON for object serialization/deserialization to JSON

### Erlang
- 🏚 [EventStore Client](https://github.com/exponentially/extreme) - Elixir Adapter for EventStore
- ⚡️ [Commanded](https://github.com/commanded/commanded) - Use Commanded to build Elixir CQRS/ES applications
  - 🏚 [EventStore Client for Commanded](https://github.com/commanded/commanded-extreme-adapter) - Use Event Store with Commanded via the Extreme Elixir TCP client.

### Rust
 - ⚡️ [EventStore Client in Rust](https://github.com/YoEight/eventstore-rs)

### Haskell
 - ⚡️ [EventStore Client](https://hackage.haskell.org/package/eventstore)

### JavaScript
 - ⚡ [Official Nodejs EventStore Client](https://github.com/EventStore/EventStore-Client-NodeJS) - not sure if this is in npm
 - ⚡️ [Nodejs EventStore Client by Nicolas Dextraze](https://github.com/nicdex/node-eventstore-client)
 - ⚡️ [Nodejs EventStore Client by Carey Bishop](https://github.com/x-cubed/event-store-client)
## Tools
## Visualization
 - ⚡️ [EventStore Exporter](https://github.com/marcinbudny/eventstore_exporter) - metrics Prometheus exporter
 ![EventStore Grafana dashboard](https://github.com/marcinbudny/eventstore_exporter/blob/0.7.0/dashboard.png?raw=true)

## Docker 
 - ⚡️ [Official Docker Image](https://hub.docker.com/r/eventstore/eventstore)

## Places I think EventStore should be included

- ⚡️ [Awesome master list, Databases section](https://github.com/sindresorhus/awesome/blob/master/readme.md#databases)
- 🏚 [Awesome Databases, dot-net section](https://github.com/numetriclabz/awesome-db#dot-net)

## Places where EventStore is included
- 🏚 [Awesome cqrs-event-sourcing, tools section](https://github.com/leandrocp/awesome-cqrs-event-sourcing#tools)
