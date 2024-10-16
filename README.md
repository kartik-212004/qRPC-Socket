# qRPC-Socket

qRPC-Socket is an open-source project that aims to combine the power of **gRPC's binary procedure calls**, **GraphQL's graph query handling**, and **WebSocket's real-time communication** into a single, flexible communication framework. Built in **Rust**, qRPC-Socket will allow developers to experiment and explore new ways of handling remote procedure calls and graph-based queries over persistent, low-latency connections.

## Current Status

The main focus of this project at the moment is **research** and **exploration**. We are investigating how to:
- Integrate **Protobuf** for efficient data serialization.
- Build custom **socket handshakes** for real-time connections (using WebSockets).
- Evaluate whether to use **GraphQL** or create a custom query language to handle complex data queries.
- Explore and mix technologies to develop a new approach for efficient, real-time communication across multiple platforms.

The ultimate goal is to create an architecture that leverages these technologies to build scalable, real-time systems, but for now, we're in the **exploration phase**. Contributions, suggestions, and discussions are welcome!

## Why qRPC-Socket?

qRPC-Socket offers a fresh take on remote procedure calls by combining the efficiency of binary formats like Protobuf with the flexibility of graph queries and real-time, bidirectional communication over WebSockets. This allows developers to:
- Use real-time data feeds and interactions.
- Execute RPC calls with efficient, binary-level communication.
- Query data in flexible, graph-based formats, supporting complex relationships and interactions.
- Mix and match technologies for specialized use cases.

## License

This project is licensed under the **Apache 2.0 License**. See the [LICENSE](./LICENSE) file for more details.

## Roadmap

### Phase 1: Research and Prototyping
- [x] Initial research on using **Protobuf** for data serialization in Rust.
- [ ] Prototyping custom **socket handshake** using WebSocket.
- [ ] Investigate **GraphQL** integration or custom graph query language design.
- [ ] Develop an initial **proof of concept** for mixing Protobuf, WebSocket, and a query system.
- [ ] Build basic examples to showcase functionality.

### Phase 2: Implementation and Experimentation
- [ ] Implement a prototype for **RPC over WebSocket** using Rust.
- [ ] Create a basic **graph query system** to experiment with data queries and RPC.
- [ ] Test different **socket handshake** mechanisms and optimize for performance.
- [ ] Set up a **benchmarking system** to evaluate performance across different versions.

### Phase 3: Versioning and Community Feedback
- [ ] Develop multiple versions using **Canary** for experimenting with different approaches (e.g., socket handshakes, query mechanisms).
- [ ] Collect community feedback and refine the project based on real-world use cases and developer input.
- [ ] Begin documenting and building **developer-friendly APIs** for qRPC-Socket.

### Phase 4: Stabilization and Release
- [ ] Finalize the core architecture and communication format.
- [ ] Harden the WebSocket, RPC, and query systems for production use.
- [ ] Release the first **stable version** with documentation and examples.
- [ ] Continue to evolve the project based on community feedback and emerging technologies.

## Contributing

We welcome contributions! Whether you're interested in helping with research, prototyping, or just have suggestions for improving the project, feel free to open an issue or a pull request. You can also join the discussion to share ideas or ask questions.

## Contact

If you have any questions or want to get involved, please reach out or join the discussions in our GitHub Issues.

