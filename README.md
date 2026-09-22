# PayPilot AI — Autonomous AI-Powered Fintech Payments Platform

> **Payments, intelligently automated.**  
> A production-grade, fully responsive fintech dashboard and payment intelligence system built with Next.js 15+, TypeScript, Tailwind CSS, Framer Motion, and Lucide icons.

![PayPilot AI Preview](https://images.unsplash.com/photo-1559526324-4b87b5e36e44?w=1200&auto=format&fit=crop&q=80)

---

## ✨ Features

- ⚡ **Autonomous Dashboard Overview**: 4 high-impact KPI cards, Recharts revenue vs. processing expenses area chart with timeframe filters (7D, 30D, 90D, 1Y), real-time ledger events, and AI Radar insights.
- 🤖 **PayPilot AI Conversational Copilot**: Local simulated intelligence responding to financial prompts (*"Why did payments fail this week?"*, *"Forecast cash flow"*, *"Draft invoice for Acme"*) with interactive data cards, chart visualizers, and direct action triggers.
- 💳 **Payments & Multi-Rail Gateway**: Detailed transaction lists with instant search, status filters (Succeeded, Processing, Failed, Refunded), currency filters, and CSV export.
- 🔍 **Transaction Detail Slide-Over Drawer**: Detailed gross/fee/net breakdowns, PCI tokenized payment method details, AI Risk Score meter (0–100), full event timeline, and instant refund processing.
- 🔗 **Hosted Payment Links Generator**: Generate dynamic payment links with QR code preview, custom expiration, currency selectors, and copy-to-clipboard feedback.
- 📄 **Interactive Invoicing Engine & PDF Preview**: Create professional itemized invoices with live calculation of quantities, unit prices, discounts, tax rates (GST/Sales Tax), payment terms, and printable preview sheets with direct payment links.
- 👥 **Customer Directory & CRM**: Directory of client profiles with lifetime value (LTV), tokenized payment methods, risk classifications, and editable internal notes.
- 📊 **Multi-Dimensional Financial Analytics**: Breakdown charts for payment methods, geographic revenue distribution, decline root-cause diagnostics with AI remediation rules, cohort retention, and exportable AI executive summaries.
- ⚙️ **Settings & Developer Hub**: Team member invites with role-based access, masked API key manager (Live & Test keys), webhook simulator, payout routing (US Bank Wire & Indian UPI VPAs), 2FA controls, and third-party integrations (Slack, QuickBooks, Zapier).
- 🌓 **Dark & Light Mode**: Seamless theme switching with persistent localStorage state.
- 🌐 **Dual Currency Engine**: Real-time switching between USD ($) and INR (₹) across all balances, charts, invoices, and payment links.
- ⌨️ **Command Palette (Cmd/Ctrl + K)**: Global keyboard-accessible search across transactions, customers, invoices, and quick actions.

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 15 (App Router)](https://nextjs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Charts**: [Recharts](https://recharts.org/)
- **Notifications**: [Sonner](https://sonner.emilkowal.ski/)
- **State Management**: React Context & Custom Hooks with local persistence

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18.17+ or higher
- npm or yarn

### Installation

1. Clone or navigate to the repository directory:
   ```bash
   cd "payment app"
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🧭 Application Routes

| Route | Description |
|---|---|
| `/` | Landing page with live AI hero demo, pricing calculator, and features |
| `/login` | Authentication page with one-click Demo Mode logins |
| `/register` | User onboarding and signup flow |
| `/dashboard` | Main dashboard overview, KPI cards, and AI Insights |
| `/payments` | Transaction ledger, payment links, and refund drawer |
| `/invoices` | Invoice management, builder modal, and printable preview |
| `/customers` | Customer directory, profiles, and staff notes |
| `/analytics` | Financial analytics, method breakdown, and AI executive summaries |
| `/assistant` | Interactive conversational AI copilot |
| `/settings` | Business profile, API keys, team members, webhooks, and 2FA |

---

## 📄 License

MIT © 2025 PayPilot AI.
