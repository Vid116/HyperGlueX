# HyperGlueX

A modern analytics and monitoring dashboard for HyperLiquid DEX. Track your portfolio, analyze market data, monitor liquidity pools, and gain insights into your trading performance.

## Project Status

This project is in active development. See the [Progress Tracker](#progress-tracker) below for current status.

## Progress Tracker

### Frontend (UI/UX)
- ✅ Next.js project setup with TypeScript
- ✅ Tailwind CSS configuration with dark theme
- ✅ Responsive dashboard layout (Header + Sidebar)
- ✅ Basic UI components (Card, Button)
- ⬜ Charts and visualization components
- ⬜ Portfolio view UI
- ⬜ Pools monitoring UI
- ⬜ Analytics dashboard UI
- ⬜ Mobile optimization

### Backend
- ⬜ API route structure
- ⬜ Data fetching and caching layer
- ⬜ WebSocket integration for real-time data
- ⬜ Database setup (if needed)
- ⬜ Server-side data processing

### HyperLiquid Integration
- ⬜ HyperLiquid API client setup
- ⬜ Wallet connection integration
- ⬜ Real-time market data streaming
- ⬜ Account/position data fetching
- ⬜ Pool data integration
- ⬜ Transaction history

### Analytics Dashboard
- ⬜ Performance metrics calculation
- ⬜ PnL tracking and visualization
- ⬜ Trade history analysis
- ⬜ Market trend indicators
- ⬜ Custom analytics widgets

### Portfolio Tracking
- ⬜ Current positions display
- ⬜ Balance overview
- ⬜ Asset allocation charts
- ⬜ Position performance tracking
- ⬜ Historical portfolio value

### Pools Checking
- ⬜ Liquidity pools list
- ⬜ Pool metrics and stats
- ⬜ APY/APR calculations
- ⬜ Pool composition visualization
- ⬜ User pool positions

### Deployment & DevOps
- ⬜ Environment configuration
- ⬜ Build optimization
- ⬜ Hosting setup (Vercel/other)
- ⬜ CI/CD pipeline
- ⬜ Monitoring and error tracking

## Tech Stack

- **Next.js 15** - React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **Recharts** - Data visualization
- **Lucide React** - Icon library

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure

```
src/
├── app/              # Next.js app directory
│   ├── layout.tsx   # Root layout
│   ├── page.tsx     # Home page
│   └── globals.css  # Global styles
├── components/
│   ├── layout/      # Layout components
│   │   ├── Header.tsx
│   │   ├── Sidebar.tsx
│   │   └── DashboardLayout.tsx
│   └── ui/          # Reusable UI components
│       ├── Card.tsx
│       └── Button.tsx
├── lib/             # Utility functions
└── types/           # TypeScript types
```

## Features

- Responsive dashboard layout
- Dark theme optimized for trading
- Portfolio tracking
- Market data visualization
- Trading interface

## Development

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Roadmap

### Immediate Priorities (Next Sprint)
1. Set up HyperLiquid API integration
2. Build chart components for data visualization
3. Create portfolio tracking UI
4. Implement real-time data updates

### Future Enhancements
- Advanced analytics and custom indicators
- Multi-wallet support
- Historical data analysis
- Export reports (PDF, CSV)
- Price alerts and notifications
- Mobile app (React Native)

## Contributing

This is a personal project, but suggestions and feedback are welcome! Feel free to open issues for bugs or feature requests.

## License

MIT
