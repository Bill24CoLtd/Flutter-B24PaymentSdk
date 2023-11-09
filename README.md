
# b24_payment_sdk

**b24_payment_sdk** is a Flutter package that simplifies the integration of payment methods for merchants who want to offer a range of payment options, including bank app payments, bank checkout, and KHQR payments. This package is written in Dart and supports both Android and iOS platforms.


## Features

- **Bank App Payment**: Allow your users to make payments through their bank's mobile app, providing a seamless and familiar payment experience.

- **Bank Checkout**: Offer a convenient checkout process where users can pay directly through their bank, ensuring a secure and efficient transaction.

- **KHQR Payment**: Enable users to make payments using the KHQR (Quick Response Code) method, offering a versatile and widely accepted payment option.

## Getting started

To use the **payment_sdk** package in your Flutter project, follow these steps:


### 1. Add the dependency
Add the following dependency to your `pubspec.yaml` file:
```yaml
dependencies:
  b24_payment_sdk: ^1.0.0

## Usage


import 'package:b24_payment_sdk/b24_payment_sdk.dart';


void main() { 
B24PaymentSdk.intSdk(
controller: context,
tranId: "4614B5964908",
refererKey: "123X",
language: "km",
darkMode: false,
isProduction: false,
);}
  




