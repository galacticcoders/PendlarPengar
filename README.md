# Pendlar Pengar

**Pendlar Pengar** is an open-source iOS app designed to empower Swedish train commuters by simplifying the process of claiming refunds for train delays and cancellations. The app automatically tracks delays, cross-checks them with train schedules, and notifies users when they’re eligible for a refund—all while prioritizing privacy and security.

## 📋 Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Privacy and Security](#privacy-and-security)
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)

## 🚀 Features
- **Automated Delay Tracking**: Tracks delays and cancellations in real time using on-device location data.
- **Refund Notification**: Notifies users when they’re eligible to claim a refund, with a single-tap option to submit.
- **Privacy First**: All data collection is kept on-device, ensuring user privacy. Only data explicitly approved by the user is sent out.
- **Transparency**: The app is open-source to allow anyone to verify the code for privacy and security.

## 🚧 Getting Started

1. **Prerequisites**:
   - macOS and Xcode for iOS development
   - An Apple Developer account (for testing on a physical device)

2. **Installation**:
   - Clone this repository:
     ```bash
     git clone https://github.com/galacticcoders/pendlar-pengar.git
     ```
   - Open the project in Xcode:
     ```bash
     cd pendlar-pengar
     open PendlarPengar.xcodeproj
     ```
   - Install any dependencies (e.g., via CocoaPods if you’re using dependencies in the project):
     ```bash
     pod install
     ```

3. **Running the App**:
   - Build and run the app on the iOS simulator or a connected device from Xcode.

## 🔒 Privacy and Security

Pendlar Pengar is committed to protecting user privacy. Here’s how we do it:
- **On-Device Processing**: Location tracking and data processing happen entirely on-device. No personal data is stored or sent to external servers.
- **User Control**: The app only prompts users when a delay or cancellation is detected, and users have full control over submitting claims.
- **Transparent Codebase**: The code is open-source to allow anyone to inspect and verify privacy measures. We welcome feedback and improvements to ensure the highest standards of security and privacy.

## 🤝 Contribution Guidelines

Contributions are welcome and greatly appreciated! Here’s how you can help:
1. **Fork the Repository**: Create your own fork and clone it locally.
2. **Create a Feature Branch**: Make changes or add new features.
3. **Submit a Pull Request**: Ensure your code is well-documented and tested. Describe the changes made and any additional information needed.

If you’re new to open-source, check out the [good first issues](https://github.com/galacticcoders/pendlar-pengar/issues) to get started!

## 📜 License

This project is licensed under the [MIT License](LICENSE), which allows anyone to use, modify, and distribute the code freely.

---

**Thank you for your interest in Pendlar Pengar!** This project is built with the community in mind, and your feedback and contributions help make it stronger. Together, let’s make commuting a bit easier and hold train operators accountable.
