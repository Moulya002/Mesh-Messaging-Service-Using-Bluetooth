**📡 Mesh Messaging Service Using Bluetooth**

An alternate way of communication using Bluetooth technology
**🚀 Overview**

This project implements a Bluetooth-based peer-to-peer communication system that enables messaging without internet or cellular networks.
It is designed for use in situations where traditional connectivity is unavailable — such as crowded areas, remote locations, or emergency scenarios.

The system establishes a mesh-like communication network using Bluetooth proximity, allowing nearby devices to discover each other, exchange messages, and maintain communication with minimal hardware requirements.

**🧠 Technical Summary (Deep Dive)**
**🔹 Purpose & Motivation**

Provide an alternative communication channel without relying on Wi-Fi, mobile data, or telecom infrastructure.

**Ensure connectivity in situations like:**

Natural disasters

Network outages

Low-coverage areas

Security-focused offline communication

**🔹 System Architecture**

Based on the report content, the system includes the following components:

Device Discovery Module

Identifies nearby Bluetooth-enabled devices.

Uses proximity scanning to maintain active peer lists.

Message Exchange Layer

Manages sending and receiving of chat messages.

Ensures delivery within the Bluetooth range limit.

Secure Communication

Implements encrypted message transmission (AES/secure pairing).

Protects data from unauthorized access.

User Interface (UI)

Simple interface for sending/receiving messages.

Displays nearby available peers.

**🔹 Key Features**

📶 Works fully offline

🔍 Automatic Bluetooth device discovery

🔁 Peer-to-peer messaging

🔐 Encrypted message transmission

🧭 Lightweight and battery-efficient

📱 Designed for mobile devices (Android assumed based on report structure)

**🔹 Advantages**

No internet or SIM card required

Works in emergencies

Secure and private

Low cost and easy to deploy

**⚙️ Technologies & Tools**

Based on the report references:

Bluetooth Classic / BLE

Android SDK (if implemented on Android)

Java / Kotlin

Encryption libraries (AES / Android Security APIs)

Messaging and service-binding frameworks

**📈 Results & Observations**

From the report excerpts:

Successful short-range communication achieved using Bluetooth

Stable messaging within the Bluetooth range (10–100 meters depending on device)

Demonstrated practical offline communication in real environments

Sufficient for emergency or basic peer-to-peer messaging

**🧪 How to Use**

Enable Bluetooth on the device

Install and open the app

Allow necessary permissions (Bluetooth, location)

Discover nearby peers

Start messaging

**🔗 Contact**

Author: Moulya R. B.

📧 Email: moulyarb02@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/moulyarb/

🌐 GitHub Profile: https://github.com/Moulya002
