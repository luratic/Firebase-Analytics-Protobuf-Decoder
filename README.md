# Firebase Analytics Protobuf Decoder

This repository contains a compiled **Protocol Buffer descriptor** (`.desc` file) that allows you to decode and analyze **Firebase Analytics (GA4)** network requests sent from mobile apps (Android/iOS).


## 📦 Contents

- `firebase_analytics_proto_by_luratic.desc`  
  A compiled protobuf descriptor for decoding Firebase Analytics payloads.  
  This file can be used to interpret binary-encoded messages sent via **gRPC**, **protobuf**, or **POST payloads** in Firebase Analytics requests.

## 🔍 Purpose

Google Analytics 4 (GA4) on mobile apps (via Firebase SDK) sends data in a binary **protobuf** format rather than plain JSON as in web measurement.  
This descriptor helps researchers, developers, and analysts **inspect and reverse-engineer** those network payloads to better understand how GA4 events are structured and transmitted.

It can be used for:
- Decoding mobile analytics payloads captured with tools like **Charles**, **Proxyman**, or **mitmproxy**  
- Debugging analytics implementations in **Firebase SDKs**  
