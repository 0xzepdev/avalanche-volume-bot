# Avalanche pharaoh volume Bot

A professional volume bot for the Avalanche network that performs automated token swaps with configurable parameters.

https://github.com/user-attachments/assets/06f4e0ee-ce0a-4d20-9ced-4b111b876836
## Mainnet test link
https://snowtrace.io/tx/0xc0244958018942a572e4e740fbbcf119620774a5628b5fa898256263dac96491
https://snowtrace.io/tx/0x9dc9bbb3e231911db9845887f3a7afa81b1c7ed6e10c882b27e926e5954e8983
https://snowtrace.io/tx/0xd0ee6715cff35c3ec4242dae7e675842329416328cb1ee6a74ef6a41cdf50c3a
https://snowtrace.io/tx/0x08827628866570f639410851908e1b1bc84ac20929ad55ccd1d7e04df2b97952
## Built by 0xzepdev
- [Telegram](https://t.me/oxzepdev)
- [Twitter](https://x.com/0xzepdev)

## Features

- Automated token swapping on Pharaoh Dex for Avalanche
- Real-time price monitoring and caching
- Configurable swap amounts and timing
customization
- Transaction tracking and logging
 profit/loss, total daily volume, estimated vs actual output, number of swap daily
- Error handling and recovery
wallet balance check, stopping bot
- Gas price optimization
- Slippage protection

## Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Avalanche wallet with funds

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/avax-bot.git
cd avax-bot
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with the following variables:
```env
PRIVATE_KEY=your_private_key
RPC_URL=your_avalanche_rpc_url
TOKEN_ADDRESS=your_token_address
CONTRACT_ADDRESS=your_dex_contract_address
WETH_ADDRESS=your_weth_address
```

## Usage

1. Configure your swap parameters in `src/config/swap.config.ts`
2. Run the bot:
```bash
npm start
```

## Project Structure

```
src/
├── config/         # Configuration files
├── services/       # Core services
├── types/          # TypeScript types
├── utils/          # Utility functions
├── constants/      # Constants and enums
└── bot.ts          # Main entry point
```

## Development

- `npm run build` - Build the project
- `npm run lint` - Run linter
- `npm run test` - Run tests
- `npm run dev` - Run in development mode

## License

MIT

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request 
