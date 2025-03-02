# Local Aware Wireless (LAW)

Local Aware Wireless (LAW) is an open-source application that provides secure and reliable communication between devices in close proximity by leveraging sound-based communication with locale-aware fingerprinting.

## Features

* **Secure Sound-Based Communication**: Uses environmental fingerprinting to securely transmit data.
* **Locale-Aware Fingerprinting**: Generates unique keys based on the local environment for added security.
* **Adaptive OFDM Modulation**: Ensures robustness against interference and multipath effects.
* **Dynamic Key Generation**: Generates new keys based on changing environmental conditions.
* **Bluetooth Support (Coming Soon)**: Allows for data transmission over Bluetooth when available.
* **Intuitive Interfaces**:
	+ **watchOS App**: Voice interface for hands-free communication.
	+ **iOS Apps**: Text and voice interfaces for flexible communication.

## Requirements

* iOS 12+ or watchOS 5+
* Xcode 11+

## Installation

1. Clone the repository:
```
git clone https://github.com/yourusername/law.git
```

2. Open the project in Xcode.

3. Build and run the app on your iOS or watchOS device.

## Usage

### iOS App

1. Enter a message in the text field.
2. Tap the "Send" button to transmit the message
3. It actively listens to the room for messages addressed back to itself

### WatchOS App

Send a message

1. Tap the "Record" button to start recording your voice message
2. Tap the "Send" button to stop recording and transmit the message
3. It actively listens to the room for a response for a given time

Receive a message

1. Tap the "Listen" button to start listening for a message.
2. The message is displayed or spoken back to you.

## Uses

This *method* allows encryption with an unique, irreplaceable key, never used again or reproducible with common methods.

Its security level depends on the graphity of the room time-spectrum matrix, and the ability of both sides to agree on a codependent gradient matrix mapping. This allows the peers to determine presence, even under Doppler effects.

This allows safe and secure AI integration

Its application goes beyond simple chats. 

Being able to transmit and receive safe, unique, targeted packets could open VL interactions with a locally hosted AI, by using any simple iPhone app. I am making one in Swift. Because Apple

## Contributing

We welcome contributions from anyone interested in improving the LAW! Please see [CONTRIBUTING.md](https://github.com/nightmedia/law/blob/main/CONTRIBUTING.md) for guidelines on how to contribute to the project.

License
This project is licensed under the GPL-3 License.
