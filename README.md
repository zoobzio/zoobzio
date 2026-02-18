# Hi, I'm Alex and I really like Go.

I'm building a framework called zoobzio—a collection of composable libraries for constructing modern applications. The idea is simple: small primitives with clear contracts that snap together without friction. Each library does one thing well and stays out of your way. I find that AI assistants work best when given focused building blocks rather than sprawling abstractions, so everything is designed with explicit types and minimal surface area.

## Foundation

No internal dependencies. The bedrock everything else builds on.

| Project | Version | Description |
|---------|---------|-------------|
| [capitan](https://github.com/zoobzio/capitan) | v1.0.0 | Type-safe event coordination with async processing, backpressure, and zero dependencies |
| [sentinel](https://github.com/zoobzio/sentinel) | v1.0.2 | Zero-dependency struct introspection with cached metadata and type relationship discovery |
| [clockz](https://github.com/zoobzio/clockz) | v1.0.0 | Deterministic clock abstractions for testing time-dependent code |
| [streamz](https://github.com/zoobzio/streamz) | v1.0.6 | Stream processing primitives for channels with batching, windowing, and deterministic testing |
| [dbml](https://github.com/zoobzio/dbml) | v1.0.0 | Programmatic DBML generation for schema-as-code with full type safety |
| [openapi](https://github.com/zoobzio/openapi) | v1.0.1 | OpenAPI 3.1 specification as native Go types for building and manipulating APIs |
| [chisel](https://github.com/zoobzio/chisel) | unreleased | AST-aware code chunking parsing source into semantic units for embeddings |

## Primitives

Small utilities building directly on foundation.

| Project | Version | Description |
|---------|---------|-------------|
| [atom](https://github.com/zoobzio/atom) | v1.0.0 | Type-segregated struct decomposition into typed maps for framework use |
| [check](https://github.com/zoobzio/check) | v0.0.4 | Fluent validation with struct tag verification as visible, testable code |
| [fig](https://github.com/zoobzio/fig) | v0.0.1 | Struct tags to configuration loading from environment, secrets, and defaults |
| [sctx](https://github.com/zoobzio/sctx) | v1.0.1 | Certificate-based security contexts turning mTLS into typed authorization tokens |
| [slush](https://github.com/zoobzio/slush) | v0.0.1 | Type-safe service locator with composable access guards |
| [erd](https://github.com/zoobzio/erd) | v1.0.0 | Entity relationship diagram generation inferring relationships from Go types |

## Data Access

Query infrastructure forming a dependency chain.

| Project | Version | Description |
|---------|---------|-------------|
| [astql](https://github.com/zoobzio/astql) | v1.0.6 | SQL query builder constructing AST with DBML schema validation across multiple databases |
| [soy](https://github.com/zoobzio/soy) | v1.0.5 | Type-safe SQL queries with zero reflection on hot path and schema-validated results |
| [vecna](https://github.com/zoobzio/vecna) | v0.0.2 | Schema-validated filter builder for vector databases with compile-time field checks |
| [lucene](https://github.com/zoobzio/lucene) | unreleased | Query builder for boolean, aggregation, and filtering across search backends |
| [edamame](https://github.com/zoobzio/edamame) | v1.0.1 | Statement-driven query execution without magic strings or runtime reflection |
| [scio](https://github.com/zoobzio/scio) | v0.0.3 | URI-based data catalog routing operations across databases, KV stores, and buckets |

## Storage

Unified abstraction over all storage backends.

| Project | Version | Description |
|---------|---------|-------------|
| [grub](https://github.com/zoobzio/grub) | v0.1.8 | Provider-agnostic storage abstraction unifying key-value, blob, SQL, and vector backends |

## Infrastructure

Operational concerns and service composition.

| Project | Version | Description |
|---------|---------|-------------|
| [cereal](https://github.com/zoobzio/cereal) | v0.1.1 | Boundary-aware serialization transforming data differently as it crosses system edges |
| [rocco](https://github.com/zoobzio/rocco) | v0.1.13 | HTTP framework with automatic OpenAPI generation, validation, and streaming support |
| [flux](https://github.com/zoobzio/flux) | v1.0.1 | Reactive configuration sync watching external sources with validation and automatic rollback |
| [sum](https://github.com/zoobzio/sum) | v0.0.7 | Application framework unifying HTTP, data, configuration, and services with lifecycle management |

## Composition

Workflows, pipelines, and messaging.

| Project | Version | Description |
|---------|---------|-------------|
| [pipz](https://github.com/zoobzio/pipz) | v1.0.4 | Composable data pipelines with rich error context, panic recovery, and signal observability |
| [flume](https://github.com/zoobzio/flume) | v1.0.0 | Dynamic pipeline factory defining pipz pipelines in YAML/JSON with hot-reloading |
| [herald](https://github.com/zoobzio/herald) | v1.0.1 | Bidirectional event distribution publishing capitan events to brokers and back |
| [ago](https://github.com/zoobzio/ago) | v0.0.1 | Event-driven orchestration bridging capitan with pipz for distributed sagas |
| [aperture](https://github.com/zoobzio/aperture) | v1.0.2 | Config-driven bridge from capitan events to OpenTelemetry without instrumentation code |

## Domain

AI, ML, and specialized capabilities.

| Project | Version | Description |
|---------|---------|-------------|
| [zyn](https://github.com/zoobzio/zyn) | v1.0.1 | Type-safe LLM orchestration with typed outputs, session composition, and reliability patterns |
| [cogito](https://github.com/zoobzio/cogito) | v0.0.2 | Reasoning chains with semantic memory for autonomous systems that adapt |
| [vex](https://github.com/zoobzio/vex) | v0.0.1 | Provider-agnostic embedding generation with composable reliability and chunking |
| [ergo](https://github.com/zoobzio/ergo) | unreleased | Event-driven reasoning workflows bridging capitan events with cogito thought execution |
| [rigor](https://github.com/zoobzio/rigor) | unreleased | LLM finetuning pipeline for Go framework docs using LoRA/QLoRA on Qwen models |
| [tendo](https://github.com/zoobzio/tendo) | v0.0.4 | Composable tensor library with optional GPU acceleration for native Go inference |
| [popcorn](https://github.com/zoobzio/popcorn) | unreleased | CUDA elementwise kernels for tensor operations via cgo integration |

## Template

Production-ready starting point with AI-assisted scaffolding.

| Project | Version | Description |
|---------|---------|-------------|
| [sumatra](https://github.com/zoobzio/sumatra) | unreleased | Production-ready Go application template with type-safe registry and OpenAPI |

### Agents

| Agent | Role | Description |
|-------|------|-------------|
| Zidgel | Captain | Requirements extraction and mission orchestration |
| Midgel | First Mate | Entity construction and modification |
| Kevin | Engineer | Testing and verification |
| Fidgel | Science Officer | Complex architecture and documentation |

### Skills

| Skill | Description |
|-------|-------------|
| add-model | Domain model types with validation and lifecycle hooks |
| add-migration | Database schema changes using goose |
| add-contract | Interface definitions bridging handlers and stores |
| add-store | Data store scaffolding (database, bucket, kv, or index) |
| add-wire | Request and response types with boundary processing |
| add-handler | HTTP endpoints with OpenAPI and streaming support |
| add-transformer | Pure functions mapping between models and wire types |
| add-config | Static configuration loaded at startup |
| add-capacitor | Hot-reload runtime configuration via flux |
| add-boundary | Field-level encryption, hashing, and masking |
| add-event | Domain events and operational signals |
| add-pipeline | Composable data processing workflows |
| add-client | External API clients with resilience patterns |
| add-secret-manager | Secret provider configuration for sensitive values |

## Applications

Full implementations built on the stack.

| Project | Version | Description |
|---------|---------|-------------|
| [vicky](https://github.com/zoobzio/vicky) | unreleased | Code intelligence platform with vector indexing and semantic analysis |
| [nestor](https://github.com/zoobzio/nestor) | unreleased | Application template with multiple API surfaces and layered architecture |
| [morpheus](https://github.com/zoobzio/morpheus) | unreleased | Application template demonstrating zoobzio patterns |
| [aegis](https://github.com/zoobzio/aegis) | unreleased | Distributed mesh networking with peer management, topology tracking, and secure gRPC |

## Frontend

| Project | Version | Description |
|---------|---------|-------------|
| [foundation](https://github.com/zoobzio/foundation) | v0.0.1 | Nuxt/Vue monorepo framework for multi-layer applications with shared components |
| [zoobz.io](https://github.com/zoobzio/zoobz.io) | v0.0.1 | Personal website and documentation portal |
