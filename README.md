# 🌶️ Chilly - Decentralized Order Tracking DApp

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Next.js](https://img.shields.io/badge/Next.js-16.0-black)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/)

**Chilly** is an open-source decentralized application (dApp) built on Next.js that helps businesses and individuals keep track of orders on the blockchain. Built with modern Web3 technologies for transparency, immutability, and trustless order management.

## ✨ Features

- 🔗 **Web3 Integration** - Connect with MetaMask, WalletConnect, and other popular wallets
- 📦 **Order Tracking** - Create, update, and monitor orders on the blockchain
- 🔐 **Decentralized Storage** - Immutable order records stored on-chain
- 📊 **Dashboard** - Real-time order status and analytics
- 🌐 **Cross-chain Support** - Built with compatibility for multiple blockchain networks
- 🎨 **Modern UI** - Beautiful, responsive interface built with Tailwind CSS

## 🚀 Getting Started

### Prerequisites

- Node.js 18.x or higher
- npm, yarn, or pnpm
- A Web3 wallet (MetaMask recommended)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/HyperSafeD/chilly.git
cd chilly
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env.local` file in the root directory:
```env
NEXT_PUBLIC_CHAIN_ID=1
NEXT_PUBLIC_RPC_URL=https://mainnet.infura.io/v3/YOUR_PROJECT_ID
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🛠️ Tech Stack

- **Framework**: [Next.js 16](https://nextjs.org/) - React framework with App Router
- **Language**: [TypeScript](https://www.typescriptlang.org/) - Type-safe JavaScript
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- **Web3**: 
  - [wagmi](https://wagmi.sh/) - React Hooks for Ethereum
  - [viem](https://viem.sh/) - TypeScript Ethereum library
  - [RainbowKit](https://www.rainbowkit.com/) - Wallet connection UI
  - [@tanstack/react-query](https://tanstack.com/query) - Data fetching and caching

## 📁 Project Structure

```
chilly/
├── app/                # Next.js App Router pages
│   ├── layout.tsx      # Root layout
│   └── page.tsx        # Home page
├── components/         # React components
├── hooks/             # Custom React hooks
├── lib/               # Utilities and configurations
├── public/            # Static assets
└── contracts/         # Smart contracts (if applicable)
```

## 🤝 Contributing

We welcome contributions! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **GitHub**: [https://github.com/HyperSafeD/chilly](https://github.com/HyperSafeD/chilly)
- **Issues**: [https://github.com/HyperSafeD/chilly/issues](https://github.com/HyperSafeD/chilly/issues)

## 👥 Maintainers

- [HyperSafeD](https://github.com/HyperSafeD)

## 🙏 Acknowledgments

- Built with ❤️ by the open-source community
- Special thanks to all contributors

---

**Made with Next.js and Web3** 🌶️
