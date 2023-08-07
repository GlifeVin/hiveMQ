# HiveMQ - Railway Template

This example deploys a self-hosted version of [HiveMQ](https://www.hivemq.com/). 

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/ELAarG?referralCode=HT4TtK)

## What is HiveMQ?
HiveMQ is a high-performance, enterprise-grade MQTT (Message Queuing Telemetry Transport) broker that enables seamless communication between devices and applications using the MQTT protocol. MQTT is widely used for real-time data exchange and communication in IoT (Internet of Things) applications, where low bandwidth and reliable messaging are crucial. HiveMQ provides various features and options for deploying it in high availability and clustered configurations. 

## Features
1. MQTT 5.0 Support: HiveMQ supports the MQTT 5.0 specification, providing advanced features such as shared subscriptions, enhanced security, message properties, and more.
2. High Performance: HiveMQ is designed for high performance and low latency, making it suitable for applications that require real-time communication.
3. Scalability: HiveMQ can be easily scaled horizontally to handle a large number of concurrent connections and messages.
4. Reliability: It ensures message delivery even in unreliable network conditions. Persistent sessions and durable message storage mechanisms prevent message loss.
5. Security: HiveMQ offers comprehensive security features, including TLS/SSL encryption, client authentication, access control, and integration with external authentication mechanisms.
6. Websockets: HiveMQ supports MQTT over WebSockets, allowing devices and applications to communicate over HTTP/HTTPS ports.
7. Advanced Clustering: HiveMQ supports clustering, enabling you to set up multiple instances that work together to provide high availability and fault tolerance.
8. Session Management: It provides flexible session management options, including session expiration, resumption, and storage.
9. Retained Messages: HiveMQ allows the broker to store the last known state of a topic, ensuring that new subscribers immediately receive the latest data.
10. QoS (Quality of Service): HiveMQ supports MQTT's QoS levels, ensuring that messages are delivered as required by the application's quality-of-service requirements.

## ✨ Services

- HiveMQ

## 💁‍♀️ How to use

- Click the Railway button 👆
- Add the required environment variables
- Deploy

## 📝 Notes

- Source repo: https://github.com/hivemq/hivemq-community-edition
- Docs: https://docs.hivemq.com/hivemq/