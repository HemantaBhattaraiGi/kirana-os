# 🏪 Kirana OS — The Digital Operating System for Modern Retail

**Kirana OS** is a high-fidelity, full-stack enterprise solution designed to digitize the traditional retail ecosystem. It bridges the gap between local merchants (Shopkeepers) and their customers through a seamless, automated, and AI-enhanced platform.

---

## 🔗 Live System
- **Frontend (Vercel)**: [https://kirana-os-frontend.vercel.app/](https://kirana-os-frontend.vercel.app/)
- **Backend (Render API)**: [https://kiranaosbackend.onrender.com/api](https://kiranaosbackend.onrender.com/api)

---

## 🔐 Distribution Disclaimer
> [!IMPORTANT]
> **Private Infrastructure**: This project is **not open source**. It is developed as a proprietary business solution. Unauthorized copying, distribution, or use of the source code is strictly prohibited.

---

## ✨ Core Modules

### 👨‍💼 Merchant Infrastructure (Shopkeeper)
- **POS Terminal**: A "terminal-aesthetic" point-of-sale system for rapid transaction processing.
- **Inventory Ledger**: Real-time product management with search, filtering, and stock tracking.
- **Customer Debt Tracking**: Automated ledger for managing credit (Udhaar) and digital settlements.
- **Financial Reporting**: One-click generation of PDF bills and full ledger history for accounting.
- **Smart Analytics**: Dashboard stats for revenue, pending debts, and customer growth.

### 🛍️ Customer Experience (High-Fidelity Portal)
- **Marketplace Browsing**: Discover local shops and browse real-time inventories.
- **Shopping Pipeline**: Add items to cart, place orders, and track them via a vertical timeline.
- **Receipt Vault**: Instant access to digital receipts and historical orders.
- **Loyalty & Rewards**: Integrated point system and tiered membership rewards.
- **AI Shopping Assistant**: A dedicated chat interface powered by GPT for product discovery and support.

---

## 🛠️ Technical Architecture

### Frontend (Next.js 15)
- **Framework**: React / Next.js with App Router.
- **Styling**: Tailwind CSS with custom high-fidelity components (inter, outfit typography).
- **Icons**: Lucide React for consistent, high-fidelity iconography.
- **Utilities**: `jspdf` for document generation, `qrcode` for payments, and `xlsx` for data export.

### Backend (Node.js & Express)
- **Engine**: Node.js with Express.js for the RESTful API.
- **ORM**: Prisma for type-safe database interactions.
- **Database**: PostgreSQL (Hosted on Render).
- **Security**: JWT-based stateless authentication and password hashing (bcrypt).
- **Email Pipeline**: Custom Flask-based Gmail API for reliable delivery with file attachments.

---

## 🚀 Deployment Strategy
- **Frontend**: CI/CD via Vercel for instant builds and global edge distribution.
- **Backend**: Managed hosting on Render with automated environment synchronization.
- **Database**: Dedicated PostgreSQL cluster for reliable data persistence.

---

## 🛡️ License
Proprietary — All Rights Reserved. Created by [Hemanta Bhattarai](https://github.com/HemantaBhattarai5i).
