# ArcticDEX

<p align="center">
  <strong>A Sci-Fi Terminal Interface for Decentralized Exchanges.</strong>
</p>

ArcticDEX is a fullscreen, cross-platform terminal emulator and system monitor that has been upgraded to serve as a hub for Web3 trading and Decentralized Exchange (DEX) interactions.

It is a fork of the archived [eDEX-UI](https://github.com/GitSquared/edex-ui) project, bringing its futuristic "sci-fi computer" aesthetics into the decentralized finance ecosystem.

## Vision

While the original project focused on system monitoring and traditional terminal usage, **ArcticDEX** aims to integrate:
- Real-time crypto price tracking
- On-chain DEX interactions (Swaps, Liquidity)
- Wallet connections directly from the terminal
- A brand new "Arctic" aesthetic (Cool blues, whites, and icy grays)

## Development Instructions

To build and run ArcticDEX from source:

### Prerequisites
- Node.js
- npm
- Git

### Running from source

**On *nix systems:**
```bash
# Clone the repository
git clone https://github.com/frozen/arcticdex.git
cd arcticdex

# Install dependencies and rebuild native modules
npm run install-linux

# Start the application
npm start
```

**On Windows:**
*Run your shell as Administrator.*
```cmd
# Clone the repository
git clone https://github.com/frozen/arcticdex.git
cd arcticdex

# Install dependencies and rebuild native modules
npm run install-windows

# Start the application
npm start
```

## Credits

- Originally forked from [eDEX-UI by Squared](https://github.com/GitSquared/edex-ui)
- Upgraded and maintained by frozen for ArcticDEX

## Licensing

Licensed under the GPLv3.0.
