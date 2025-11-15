# HyperGlueX

A modern dashboard for HyperLiquid trading and analytics.

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

## License

MIT
