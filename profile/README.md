# 🚀 Commerce-Kick

**Kick-start your Salesforce Commerce projects with production-ready starter kits**

Welcome to Commerce-Kick! We provide battle-tested starter templates and boilerplates for Salesforce Commerce Cloud development. Skip the tedious setup and jump straight into building amazing commerce experiences.

## 🛒 What We Offer

### Web Starter Kit
- **React Commerce Starter** - Modern React-based storefront with TanStack Router, Query, and Vite
  - Server-side rendering
  - Type-safe routing and data fetching
  - Comprehensive Salesforce Commerce Cloud integration
  - Built with React 19, TypeScript, and Tailwind CSS

### Mobile Starter Kit
- **Expo Commerce App** - Cross-platform mobile commerce solution
  - Same commerce features as web kit
  - Native mobile experience with Expo
  - Shared Salesforce Commerce Cloud integration
  - Optimized for iOS and Android

## ✨ Features

All our starter kits come pre-configured with:

- 🔐 **SLAS Authentication** - Shopper Login and API Service integration
- 🛍️ **Cart & Checkout** - Complete shopping cart functionality
- 🔍 **Product Search** - Einstein Search and category browsing
- 👤 **Account Management** - User profiles and order history
- 📱 **Responsive Design** - Mobile-first, accessible UI components
- ⚡ **Performance Optimized** - Best practices for speed and UX
- 🎨 **Modern UI** - Tailwind CSS with Radix UI components
- 🔄 **State Management** - TanStack Query for data fetching and caching
- 📚 **TypeScript** - Full type safety throughout the application
- 🚀 **Production Ready** - Includes deployment configurations

## 🚀 Quick Start

Choose your preferred method to get started:

### Option 1: CLI Tool (Recommended)
Use our interactive CLI to scaffold your project:

```bash
# Create a new project with interactive prompts
npx @commerce-kick/create my-commerce-project

# Or specify template directly
npx @commerce-kick/create my-project --template web
npx @commerce-kick/create my-project --template mobile
```

### Option 2: Clone Templates Directly
```bash
# Web starter kit
git clone https://github.com/commerce-kick/start-kick.git
cd start-kick
npm install

# Configure your .env file with Salesforce Commerce Cloud credentials
cp .env.example .env
# Edit .env with your SFCC credentials

npm run dev

# Mobile starter kit  
git clone https://github.com/commerce-kick/mobile-kick.git
cd mobile-kick
npm install

# Configure your .env file (same SFCC credentials as web)
cp .env.example .env
# Edit .env with your SFCC credentials

npx expo start
```

## 📋 Prerequisites

**For Web Starter Kit:**
- Node.js 18+ and npm/yarn
- Salesforce Commerce Cloud B2C instance with API credentials
- Basic knowledge of React and TypeScript

**For Mobile Starter Kit:**
- Node.js 18+ and npm/yarn
- Expo
- Salesforce Commerce Cloud B2C instance (same as web)
- iOS Simulator (Mac) or Android Emulator for testing

## 🏗️ Our Repositories

| Repository | Type | Platform | Framework | Tech Stack | Status |
|------------|------|----------|-----------|------------|--------|
| [create](https://github.com/commerce-kick/create) | CLI Tool | - | Node.js | TypeScript, Commander.js | ✅ Active |
| [start-kick](https://github.com/commerce-kick/start-kick) | Web Template | Web | React + TanStack | Vite, TypeScript, Tailwind | ✅ Active |
| [mobile-kick](https://github.com/commerce-kick/mobile-kick) | Mobile Template | Mobile | Expo | React Native, TypeScript | ✅ Active |

## 🛠️ CLI Tool

We've built a powerful CLI tool to make getting started even easier. The `@commerce-kick/create` package provides:

- 🎯 **Interactive project setup** - Choose your template and configuration
- 📦 **Automatic dependency installation** - No manual setup required
- 🔧 **Git repository initialization** - Ready to commit from day one
- 🎨 **Beautiful terminal output** - Clean, informative progress indicators

### CLI Features

```bash
# Interactive mode - guided setup
npx @commerce-kick/create

# Quick project creation
npx @commerce-kick/create my-awesome-store

# Advanced options
npx @commerce-kick/create my-project --template web --no-git
```

Available CLI options:
- `--template <web|mobile>` - Choose your starter template
- `--no-install` - Skip automatic dependency installation
- `--no-git` - Skip git repository initialization

Learn more in the [CLI documentation](https://github.com/commerce-kick/create).

**Web Starter Kit:**
- **TanStack Router** - File-based routing with automatic code splitting
- **TanStack Query** - Powerful data fetching and caching
- **Vite** - fast development
- **commerce-sdk-isomorphic** - Salesforce Commerce Cloud SDK integration
- **Radix UI + Tailwind CSS** - Accessible, customizable components

**Mobile Starter Kit:**
- **Expo Router** - File-based navigation for React Native
- **Same Commerce Logic** - Shared Salesforce integration patterns
- **Native Components** - Platform-optimized UI components
- **Universal TypeScript** - Consistent types across platforms

## 🤝 Contributing

We welcome contributions from the community! Whether you're:

- 🐛 **Reporting bugs** or requesting features
- 💡 **Suggesting improvements** to existing kits
- 🔧 **Contributing code** or documentation

## 💬 Community & Support

- 🐛 **Issues** - Report bugs or request features in individual repositories

## 🙏 Acknowledgments

Special thanks to:
- Salesforce Commerce Cloud team for excellent APIs and documentation
- The open-source community for inspiration and contributions
- All developers who have tested and improved our starter kits

---

**Ready to kick-start your next commerce project?** 

Browse our starter kits above to begin building amazing commerce experiences today!

⭐ **Don't forget to star the repositories you find useful!**
