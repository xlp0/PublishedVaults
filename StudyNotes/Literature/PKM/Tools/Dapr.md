---
Aliases: Dapr, Distributed Application Runtime
---
[Dapr](https://dapr.io/), which stands for "Distributed Application Runtime," is an open-source runtime that simplifies the process of building microservices-based applications. It provides a set of building blocks and abstractions to help developers write resilient, scalable, and portable applications without being tied to specific programming languages or frameworks. Dapr aims to address common challenges in building distributed systems, such as service-to-service communication, state management, and event-driven architecture.

Key features and concepts of Dapr include:

1. **Service Invocation:** Dapr allows microservices to invoke each other using a consistent API, regardless of the underlying communication protocol or technology. This simplifies the process of making cross-service calls.

2. **State Management:** Dapr provides a state management building block that enables applications to store and retrieve state in a consistent manner. It supports different state stores, like Redis, Cosmos DB, and more.

3. **Pub/Sub Messaging:** Dapr facilitates event-driven architecture by providing a publish-subscribe messaging pattern. Services can publish events, and other services can subscribe to those events to react accordingly.

4. **Event-Driven Architecture:** Dapr encourages building applications using events as the primary means of communication between services. This promotes loose coupling and scalability.

5. **Binding:** Dapr introduces the concept of "bindings" that connect application components to external resources, such as databases, message queues, and more. This simplifies integration tasks.

6. **Secret Management:** Dapr helps manage secrets securely by providing a way to retrieve secrets from external stores and inject them into applications at runtime.

7. **Middleware:** Dapr can act as middleware, providing features like retries, timeouts, and circuit breakers to enhance the resilience of microservices.

8. **Sidecars:** Dapr can be integrated into your application as a sidecar, which means it runs alongside your microservices and provides the necessary runtime capabilities without altering your application's code.

Dapr is designed to be language-agnostic, meaning you can use it with various programming languages, and it's cloud-agnostic, allowing you to deploy your applications to different cloud providers or on-premises environments. It's also highly extensible, allowing the community to develop new building blocks and integrations.

Developers can interact with Dapr through HTTP or gRPC APIs. It provides SDKs for different programming languages, making it easier to integrate Dapr into your applications.

Dapr was created to simplify the challenges of building distributed systems and to provide developers with a consistent way to handle common distributed system tasks. It's widely used in cloud-native and microservices-based application development to enhance agility and scalability.