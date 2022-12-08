# simmulagbas (working name)
simulator, multiverse, agent-based

## proposal

- agent consumes and produces resources from/to one or more other agents
- an agent's environment is the collection of all of its counterparty agents
- resources can be converted to other resources by agents
- conversion rules can be imported into agents from a common library
- agents report internal state on a common channel for visualization
- agents communicate via point-to-point channels
- an agent can act as a pub/sub or other message bus
- each agent is a goroutine
- resource is an interface
- agent is an interface
