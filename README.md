# 👋 Hey! I'm Alex.

I try to write code that is simple to reason about, easy to maintain, and more powerful than the sum of it's parts.

I am currently working on [zoobz-io](https://github.com/zoobz-io), a collection of composable libraries in Go designed for constructing modern agentic applications.

The idea is simple: small primitives with clear, generic contracts that snap together without friction. Each library does one thing well and stays out of your way.

### Configuration

| Package                                  | Description                                   |
| ---------------------------------------- | --------------------------------------------- |
| [fig](https://github.com/zoobz-io/fig)   | Struct tags in, configuration out             |
| [flux](https://github.com/zoobz-io/flux) | Reactive configuration synchronization for Go |

### Events

| Package                                          | Description                                                       |
| ------------------------------------------------ | ----------------------------------------------------------------- |
| [capitan](https://github.com/zoobz-io/capitan)   | Type-safe event coordination for Go with zero dependencies        |
| [herald](https://github.com/zoobz-io/herald)     | Bidirectional bindings between capitan events and message brokers |
| [aperture](https://github.com/zoobz-io/aperture) | Config-driven bridge from capitan events to OpenTelemetry signals |

### Data & Storage

| Package                                        | Description                                                    |
| ---------------------------------------------- | -------------------------------------------------------------- |
| [dbml](https://github.com/zoobz-io/dbml)       | A Go package for building and generating DBML programmatically |
| [astql](https://github.com/zoobz-io/astql)     | Type-safe SQL query builder with DBML schema validation        |
| [lucene](https://github.com/zoobz-io/lucene)   | Type-safe search queries for Elasticsearch and OpenSearch      |
| [vecna](https://github.com/zoobz-io/vecna)     | Schema-validated filter builder for vector databases           |
| [soy](https://github.com/zoobz-io/soy)         | Type-safe SQL query builder for Go with schema validation      |
| [edamame](https://github.com/zoobz-io/edamame) | Statement-driven query exec for Go                             |
| [grub](https://github.com/zoobz-io/grub)       | Provider-agnostic storage for Go                               |

### Pipelines

| Package                                    | Description                                                         |
| ------------------------------------------ | ------------------------------------------------------------------- |
| [pipz](https://github.com/zoobz-io/pipz)   | Type-safe, composable data pipelines for Go                         |
| [flume](https://github.com/zoobz-io/flume) | A dynamic pipeline factory for pipz with hot-reloading capabilities |

### HTTP

| Package                                        | Description                                                       |
| ---------------------------------------------- | ----------------------------------------------------------------- |
| [openapi](https://github.com/zoobz-io/openapi) | OpenAPI 3.1 specification as native Go types                      |
| [rocco](https://github.com/zoobz-io/rocco)     | Type-safe HTTP framework for Go with automatic OpenAPI generation |
| [sctx](https://github.com/zoobz-io/sctx)       | Certificate-based security contexts for Go                        |

### AI

| Package                                      | Description                                                    |
| -------------------------------------------- | -------------------------------------------------------------- |
| [zyn](https://github.com/zoobz-io/zyn)       | Type-safe LLM orchestration for Go                             |
| [cogito](https://github.com/zoobz-io/cogito) | LLM-powered reasoning chains with semantic memory for Go       |
| [chit](https://github.com/zoobz-io/chit)     | Conversation lifecycle controller for LLM-powered applications |
| [vex](https://github.com/zoobz-io/vex)       | Type-safe embedding vector generation for Go                   |

### Tools

| Package                                          | Description                                                |
| ------------------------------------------------ | ---------------------------------------------------------- |
| [sentinel](https://github.com/zoobz-io/sentinel) | Zero-dependency struct introspection for Go                |
| [clockz](https://github.com/zoobz-io/clockz)     | Type-safe clock abstractions for Go with zero dependencies |
| [slush](https://github.com/zoobz-io/slush)       | Type-safe guarded service locator for Go                   |
| [cereal](https://github.com/zoobz-io/cereal)     | Boundary-aware serialization for Go                        |
| [check](https://github.com/zoobz-io/check)       | Fluent validation for Go with struct tag verification      |
