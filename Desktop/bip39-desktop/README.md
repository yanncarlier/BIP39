# BIP39 Desktop

A BIP39 desktop application built with Electron.

This project is a derivative work, inspired by and built upon the original code from the repository at https://github.com/iancoleman/bip39. 

**Disclaimer: Use at Your Own Risk** This is experimental beta software and may contain bugs or exhibit unexpected behavior. It is provided "as-is" without any warranties. Use of this software is entirely at your own discretion and risk.

Description

This application provides a secure wallet interface for generating and managing BIP39 mnemonic phrases and derived keys for various cryptocurrencies.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd bip39-desktop
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

## Usage

### Development

To start the application in development mode:

```bash
pnpm start

or

env -u ELECTRON_RUN_AS_NODE pnpm start
```

### Packaging

To package the application for all platforms:

```bash
pnpm run package
```

### Building

To build the application for Linux:

```bash
pnpm run build

dist/bip39-desktop-0.5.65.AppImage --no-sandbox
```

## Implementation

The application uses IndexedDB to securely store encrypted mnemonic phrases, salt, and initialization vector (IV).

## Technologies

- Electron
- JavaScript
- IndexedDB for local storage

## Author

Gabriel

## License

[Add license information here]
