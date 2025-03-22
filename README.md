# Stream and parse Pump.Fun AMM transaction instructions via gRPC

This project provides a Node.js service to fetch and parse transactions from Pump.Fun AMM using gRPC.

## Features
- Uses Solana gRPC API for efficient transaction retrieval.
- Parses transactions using `@shyft-to/solana-transaction-parser`.
- Supports `.env` configuration for easy authentication.

## Installation
```sh
git clone https://github.com/your-repo/get-parsed-transaction-of-pump-fun-amm-from-grpc.git
cd get-parsed-transaction-of-pump-fun-amm-from-grpc
npm install
```

## Configuration
Create a `.env` file in the root directory based on `.env.example`:
```
ENDPOINT=https://grpc.ams.shyft.to
X_TOKEN=YOUR_AUTH_TOKEN
```

## Usage
### Development
```sh
npm run watch
```

### Build
```sh
npm run build
```

### Run
```sh
npm start
```

## Dependencies
- `@solana/web3.js` for interacting with Solana blockchain.
- `@triton-one/yellowstone-grpc` for gRPC communication.
- `@shyft-to/solana-transaction-parser` for transaction parsing.

## License
This project is licensed under the ISC License.

## Author
[impin2rex](https://impin2rex.github.io)
