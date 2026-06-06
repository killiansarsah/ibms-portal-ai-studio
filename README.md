# IBMS Ghana - Insurance Broker Management System

1. Professional insurance broker management system tailored for the Ghanaian insurance market, compliant with NIC regulations.

## 🏗️ Project Structure

```
ibms-ghana/
├── apps/
│   ├── frontend/          # React + TypeScript + Vite frontend
│   └── backend/           # Node.js API (coming soon)
├── packages/              # Shared packages
├── database/              # Database schemas and seeds
├── docs/                  # Documentation
└── scripts/               # Utility scripts
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm
- Git

### Installation

```bash
# Install dependencies
cd apps/frontend
npm install

# Start development server
npm run dev
```

The application will open at `http://localhost:3000`

## 📦 Features

- **Dashboard** - Real-time KPIs and analytics
- **Policies** - Motor and non-motor portfolio management
- **Claims** - Complete claims workflow with loss ratio tracking
- **Clients** - CRM with client segmentation (Bronze/Silver/Gold/Platinum)
- **Renewals** - Pipeline management with 30/60/90-day tracking
- **Commissions** - Automated calculations with NIC levy (1%) and WHT (5%)
- **Compliance** - NIC requirements tracking
- **Reports** - 10 standard insurance reports

## 🇬🇭 Ghana-Specific Features

- Ghana Cedi (GH₵) currency formatting
- NIC levy calculations (1%)
- Withholding tax (5%)
- Local insurers (GLICO, Enterprise, Hollard, Star, SIC)
- Compliance with Insurance Act 2021
- Premium trust account tracking

## 🛠️ Tech Stack

**Frontend:**

- React 18
- TypeScript
- Vite
- Tailwind CSS
- Recharts
- React Router

**Backend (Coming Soon):**

- Node.js
- Express
- Prisma
- PostgreSQL

## 📝 Scripts

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run preview  # Preview production build
```

## 🗂️ Frontend Structure

```
apps/frontend/src/
├── pages/              # Feature-based page organization
│   ├── auth/
│   ├── dashboard/
│   ├── policies/
│   ├── claims/
│   ├── clients/
│   ├── renewals/
│   ├── commissions/
│   ├── compliance/
│   └── reports/
├── components/         # Reusable components
│   ├── layout/
│   ├── ui/
│   └── calendar/
├── services/           # API services
├── context/            # React contexts
├── types/              # TypeScript types
└── styles/             # Global styles
```

## 📄 License

Proprietary - All rights reserved

## 👥 Authors

IBMS Ghana Development Team

---

**Built with ❤️ for the Ghanaian insurance industry**
