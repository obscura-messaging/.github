# Obscura

End-to-end encrypted messaging built on the Signal Protocol.

## Repositories

| Repository | Role |
| --- | --- |
| [`obscura-app`](https://github.com/obscura-messaging/obscura-app) | React Native mobile client (Android & iOS) owning application models, authorization, merge, expiry, and UI over ObscuraKit |
| [`obscura-native`](https://github.com/obscura-messaging/obscura-native) | Cross-platform native platform layers (**ObscuraKit** for Kotlin/JVM and Swift) owning Signal encryption, device management, transport, durable inbox, and client-to-client protobuf schemas |
| [`obscura-server`](https://github.com/obscura-messaging/obscura-server) | Minimalist Rust relay server routing opaque encrypted envelopes and managing prekeys, attachments, and WebSocket gateways |
| [`obscura-proto`](https://github.com/obscura-messaging/obscura-proto) | Shared Protocol Buffer wire transport schema pinned by both `obscura-server` and `obscura-native` |
