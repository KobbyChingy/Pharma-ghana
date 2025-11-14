# 💊 PharmaCare Ghana

A comprehensive **Pharmacy Management System** built with Electron for Windows desktop.

## 🌟 Features

### For All Users
- 📦 **Inventory Management** - Track medicines with cost, selling price, and expiry dates
- 👥 **Patient Management** - Register and manage patient records
- 📋 **Prescription Management** - Create and track prescriptions
- 🛒 **Point of Sale (POS)** - Fast checkout with receipt printing
- 🔔 **Smart Alerts** - Low stock, expiring items, and profit/loss warnings

### Admin-Only Features
- 📊 **Sales Reports** - Daily, weekly, and monthly analysis
- 💰 **Profit/Loss Tracking** - Real-time profitability monitoring
- 📈 **Visual Analytics** - Charts and trends
- 🏆 **Best-Sellers Analysis** - Top-selling and most profitable items
- 👥 **User Management** - Manage admin and pharmacist accounts

## 🚀 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm (comes with Node.js)

### Setup

1. **Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/pharmacare-ghana.git
cd pharmacare-ghana
```

2. **Install dependencies**
```bash
npm install
```

3. **Run the application**
```bash
npm start
```

## 📦 Building for Distribution

### Build Windows Installer
```bash
npm run build-win
```

The installer will be created in the `dist/` folder.

### Build Portable Version
```bash
npm run build-win-portable
```

## 🔐 Default Login

Create your admin account on first launch by clicking "Sign Up" and selecting "Administrator" role.

## 📖 User Guide

### For Pharmacists:
- Access inventory, patients, prescriptions, and POS
- Process sales and print receipts
- View alerts for low stock and expiring items

### For Administrators:
- All pharmacist features PLUS:
- View detailed sales reports with profit analysis
- Track best-selling and most profitable items
- Manage user accounts
- Monitor business performance

## 🛠️ Technology Stack

- **Electron** - Desktop application framework
- **React** - UI library
- **Tailwind CSS** - Styling
- **LocalStorage** - Data persistence

## 📝 License

MIT License - See LICENSE file for details

## 👨‍💻 Author

Kingsford Oppong and The OmniWeave Softwares Team

## 📧 Support

For issues and questions, please open an issue on GitHub.

---

**Built with ❤️ for Ghanaian Pharmacies**
