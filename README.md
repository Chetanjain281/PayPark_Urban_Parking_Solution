# PayPark - Smart Urban Parking Solution

## Overview
PayPark is a smart parking management system designed to address urban traffic congestion and parking inefficiencies. By integrating RFID technology, IoT hardware, Firebase real-time database, and a cross-platform mobile app, PayPark delivers a seamless parking experience, including space reservation, UPI payments, and real-time availability updates.

## Key Features
- **RFID-based Check-in/Check-out**: Users are assigned RFID tags for secure vehicle identification.
- **IoT Integration**: Sensors track parking space availability in real-time.
- **Mobile Application**: Cross-platform app developed in Flutter (Android/iOS).
- **Real-Time Database**: Powered by Firebase and Firestore for efficient data storage.
- **UPI Payments**: Secure transactions via Razorpay.

## System Architecture
### Hardware:
- **RFID Readers**: Used for user verification and vehicle check-in/out.
- **Microcontrollers**: Arduino and NodeMCU manage sensors and data communication.

### Software:
- **Mobile App**: Developed using Flutter for a consistent user experience on both Android and iOS.
- **Backend**: Firebase for real-time database management, Firestore for structured data, and Azure Cloud Functions for advanced processing.
- **Authentication**: Secure user access through Firebase Authentication.
- **Payments**: UPI payment integration using Razorpay.

## How It Works
1. **User Registration**: Register through the PayPark mobile app and activate your account by adding a wallet balance.
2. **Parking Reservation**: Reserve available parking spaces using the mobile app.
3. **Check-in/Check-out**: Scan your RFID tag upon entry and exit; the system automatically records the time.
4. **Payment**: The app calculates the parking time, and users can pay directly via UPI.

## Future Scope
- Integration of biometric or facial recognition for enhanced security.
- Expansion to include Vehicle-to-Infrastructure (V2I) communication.
- Advanced machine learning for predictive parking optimization.
- Integration with public transport and Electric Vehicle (EV) charging stations.

## Tech Stack
- **Mobile Development**: Flutter (Dart)
- **Backend**: Firebase, Firestore, Azure Cloud Functions
- **Payments**: Razorpay UPI Integration
- **Hardware**: Arduino, NodeMCU, RFID Readers

## See the demo
[![Watch the video](https://img.youtube.com/vi/r1jezVhJUbQ/0.jpg)](https://youtu.be/r1jezVhJUbQ)

## Contributors
- **Chetan Jain** - Department of Electronics and Telecommunication Engineering, VIT Pune
- **Sanskruti Chopade** - Department of Electronics and Telecommunication Engineering, VIT Pune
- **Ameya Date** - Department of Electronics and Telecommunication Engineering, VIT Pune

## Project Guide
- **Prof. Mrunal Shidore** - Assistant Professor, Department of Electronics and Telecommunication Engineering, VIT Pune

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
