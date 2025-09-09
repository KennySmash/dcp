# Decentralized Chat Protocol (DCP)

**A modern, secure, and truly decentralized communication protocol designed for the web**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Protocol Version](https://img.shields.io/badge/Protocol-v1.0-blue.svg)](./specification/)
[![Status](https://img.shields.io/badge/Status-Draft-orange.svg)]()

## Overview

DCP is a spiritual successor to IRC that brings modern security, usability, and extensibility to decentralized chat. Built for the web-first era, it combines the openness of traditional protocols with contemporary features like end-to-end encryption, rich media sharing, and programmable extensions.

### Key Features

- 🔒 **End-to-end encryption** by default with forward secrecy
- 🌐 **Web-native** - runs in any modern browser, no apps required
- 🏠 **Self-sovereign identity** - you own your data and keys
- 🚀 **Programmable** - extensible with functions and bots
- 🌍 **Network adaptive** - works from fiber to satellite to mesh networks
- 📧 **Email compatible** - seamless bridge for gradual migration
- 🔗 **Federated** - decentralized network of independent nodes

## Architecture

```
[Web Client] ←→ [Home Node] ←→ [Federation Network]
                    ↓
              [Media Service]
                    ↓
             [Function Runtime]
                    ↓
               [Bot Engine]
                    ↓
            [Function Database]
```

### Core Components

- **Identity Files**: Portable cryptographic identities with user preferences
- **Home Nodes**: Your personal server for authentication and message routing
- **Function System**: JavaScript/WebAssembly extensions for custom functionality
- **Bot Framework**: Automated agents for moderation, integration, and services
- **Trust Chains**: Distributed moderation and reputation networks

## Getting Started

### For Users

1. **Join a community**: Visit any DCP-enabled website (like `https://chat.example.com`)
2. **Create identity**: Generate your cryptographic identity automatically
3. **Save your key**: Download your identity file - this is your "passport" to the network
4. **Start chatting**: Join channels, send messages, share files

### For Developers

1. **Read the specification**: Start with the [full protocol specification](./specification.md)
2. **Try the examples**: Check out reference implementations and examples
3. **Build clients**: Create web, mobile, or desktop clients using the open protocol
4. **Write functions**: Extend the protocol with custom JavaScript/WASM functions
5. **Deploy nodes**: Run your own home node for ultimate control

### For Communities

1. **Deploy a home node**: Set up your community's communication hub
2. **Migrate gradually**: Use email bridge for seamless transition from existing systems
3. **Customize experience**: Install functions and bots tailored to your needs
4. **Federate**: Connect with other communities while maintaining autonomy

## Use Cases

### 🏢 **Enterprise Communication**
- Replace email + Slack with unified, self-hosted platform
- Seamless external communication via email bridge
- Advanced compliance and audit capabilities
- Custom integrations and workflows

### 🎮 **Gaming Communities** 
- Voice chat with spatial audio
- Rich media sharing and streaming
- Custom bots for game integration
- Persistent community across games

### 📰 **Journalism & Privacy**
- Anonymous communication channels
- Source protection with cryptographic guarantees
- Censorship-resistant mesh networking
- Dead-drop systems for maximum security

### 🌐 **Disaster Response**
- Works over satellite, mesh, and radio networks
- Offline message queuing and sync
- Emergency contact systems
- Bandwidth-adaptive features

### 🏫 **Education & Research**
- Collaborative documents and whiteboards
- Academic discussion channels
- Integration with research tools
- Privacy-preserving analytics

## Network Adaptation

DCP automatically adapts to your network conditions:

| Connection Type | Features Available |
|---|---|
| **Fiber/Broadband** | Full features: HD video, real-time collab, unlimited media |
| **Mobile Data** | Optimized: compressed media, data-saver mode, quality controls |
| **Satellite** | Essential: text + documents, voice messages, manual downloads |
| **Mesh/Radio** | Minimal: text only, store-and-forward, emergency protocols |

## Security & Privacy

- **Identity**: Ed25519 keys with PBKDF2 protection
- **Messages**: ChaCha20-Poly1305 encryption with Double Ratchet forward secrecy  
- **Transport**: TLS 1.3 with certificate pinning
- **Metadata**: Minimized data collection with user control
- **Functions**: Sandboxed WebAssembly/V8 execution
- **Federation**: Cryptographically signed cross-node communication

## Contributing

We welcome contributions from developers, security researchers, and community members!

### Areas We Need Help

- 🔧 **Protocol Implementation**: Reference clients and servers
- 🔒 **Security Auditing**: Cryptographic review and penetration testing  
- 📚 **Documentation**: Tutorials, guides, and API documentation
- 🧪 **Testing**: Compliance tests and interoperability validation
- 🎨 **UI/UX**: Client interfaces and user experience design
- 🤖 **Extensions**: Functions, bots, and integrations

### Development Process

1. **Fork** this repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Code of Conduct

This project follows a contributor covenant. Be respectful, inclusive, and collaborative. We're building this together! 🤝

## Community


### Support

- **Specification Issues**: [GitHub Issues](https://github.com/KennySmash/dcp/issues)

## License

This project is licensed under multiple licenses:

- **Protocol Specification**: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) - freely implementable
- **Reference Implementation**: [MIT License](./LICENSE-MIT) - use in any project
- **Documentation**: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) - share and adapt

## Frequently Asked Questions

### Why not just use Matrix/XMPP/IRC?

Each has strengths, but DCP combines the best aspects:
- **vs Matrix**: Simpler protocol, better performance, web-native design
- **vs XMPP**: Modern crypto, built-in media handling, function extensibility  
- **vs IRC**: Security by default, rich features, network adaptation
- **vs Discord/Slack**: Decentralized, open protocol, data ownership

### How is this different from blockchain chat apps?

DCP is **not** a blockchain protocol:
- ✅ **Fast**: No mining or consensus delays
- ✅ **Cheap**: No transaction fees or token requirements
- ✅ **Scalable**: No global state synchronization
- ✅ **Private**: No public transaction ledger
- ✅ **Practical**: Works with existing internet infrastructure

### Can I migrate from Discord/Slack/Teams?

Yes! DCP includes migration tools and bridges:
- **Email bridge**: Maintains external communication during transition
- **Import tools**: Migrate channels, users, and message history
- **Gradual adoption**: Users can switch at their own pace
- **Feature parity**: All modern chat features supported

### What about mobile support?

DCP is designed mobile-first:
- **Progressive Web App**: Install from browser, works offline
- **Native apps**: Reference implementations for iOS/Android
- **Battery optimized**: Efficient protocols and smart caching
- **Data sensitive**: Adapts to mobile data limitations

### Is this production ready?

DCP is currently in **draft specification** phase:
- ✅ **Design**: Complete protocol design
- 🔄 **Implementation**: Reference implementation in progress  
- ⏳ **Testing**: Security audits and compliance testing needed
- ⏳ **Production**: Target late 2025 for initial production deployments

---

**Built with ❤️ by the open source community**

*"Communication should be open, secure, and under your control"*
