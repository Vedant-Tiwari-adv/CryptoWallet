# README for Web3 Wallet Android App

## Overview
Welcome to the Web3 Wallet Android App tutorial by Morales Blueprint. In this tutorial, you learned how to create a mobile wallet using Flutter and integrate Web3 technologies into your Android app development. The final app allows users to create a new wallet, generate a mnemonic phrase, verify it, and manage wallet functionalities such as checking balance, viewing NFT collections, and sending funds to other wallets.

## Project Details
### Dependencies
The app utilizes the following packages:

- **web3dart:** The core library for connecting to Ethereum nodes, sending transactions, and interacting with smart contracts. The latest version used in this tutorial is 2.6.1.

- **bip39:** A Dart implementation for Bitcoin BIP39, used for generating mnemonic phrases for wallet creation.

- **ed25519_hd:** A library for signing with Ed25519 HD public keys.

- **hex:** A library for encoding and decoding hexadecimal characters, particularly useful for wallet addresses.

- **provider:** A state management package for Flutter.

Make sure these dependencies are added to your `pubspec.yaml` file under the `dependencies` section.

### Project Structure
The project follows the Flutter structure, which is based on widgets. Key directories include:

- **lib:** Contains the Dart code for the app.
  - **main.dart:** The entry point of the app.
  - **screens:** Holds various screens for wallet creation, balance checking, and other functionalities.
  - **utils:** Includes utility functions for handling Web3 operations.
  - **widgets:** Custom Flutter widgets used throughout the app.
https://i.imgur.com/bYesPpx.png
### Screenshots
Here are some screenshots showcasing the app's functionalities:

1. **Wallet Creation Screen**
   - Mnemonic Generation Screen
   - <img src="https://i.imgur.com/bYesPpx.png" width="300">

2. **Balance Checking Screen**
   - Wallet Screen
   - <img src="https://i.imgur.com/SQMkWkx.png" width="300">

3. **NFT Collections Screen**
   - Share Token Screen
   - <img src="https://i.imgur.com/2wK6fBo.png" width="300">

4. **Sending Funds Screen**
   - Varify mnemonic screen
   - <img src="https://i.imgur.com/93CNRva.png" width="300">

5. **Sending Funds Screen**
   - Wallet NFT Screen
   - <img src="https://i.imgur.com/wFUPklg.png" width="300">


6. **Sending Funds Screen**
   - wallet option screen
   - <img src="https://i.imgur.com/YuayaaC.png" width="300">



## Usage
To run the app, ensure your Flutter environment is set up properly. Connect an Android device or start an emulator, and run the app using the following command:
```
flutter run
```

## Conclusion
Congratulations! You've successfully set up a Web3 Wallet Android app using Flutter. Feel free to explore and enhance the app further based on your requirements.

For detailed explanations and additional resources, refer to the [YouTube tutorial](<tutorial-link>).

If you encounter any issues or have suggestions, please open an [issue](<issue-link>) on the GitHub repository.

Happy coding! 🚀
