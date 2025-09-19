# Muralla Frontend

Modern React-based admin dashboard for Muralla Cafe management system.

## Features

- 📊 **Dashboard** with real-time metrics
- 🧾 **Invoicing Module** with OpenFactura integration
- 💰 **Finance Management** (Revenue & Expenses)
- 📦 **Inventory Control**
- 👥 **Staff Directory**
- 📅 **Schedule Management**
- 🏗️ **Projects & Tasks**
- 🌙 **Dark Mode Support**
- 🌍 **Multi-language** (Spanish/English)

## Tech Stack

- **Framework**: React 19 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **State Management**: React Context
- **Routing**: React Router v7
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Charts**: Chart.js with react-chartjs-2

## Installation

```bash
npm install
```

## Environment Variables

Create a `.env` file:

```env
VITE_API_BASE_URL=https://api.murallacafe.cl
VITE_WS_URL=https://api.murallacafe.cl
VITE_ENABLE_DEMO=false
VITE_MP_PUBLIC_KEY=your-mercadopago-public-key
```

## Development

```bash
# Start development server
npm run dev

# Build for production
npm run build:prod

# Preview production build
npm run preview

# Run tests
npm test

# Lint code
npm run lint
```

## Project Structure

```
src/
├── components/       # React components
│   ├── common/      # Shared components
│   ├── dashboard/   # Dashboard components
│   └── modules/     # Feature modules
├── contexts/        # React contexts
├── hooks/          # Custom hooks
├── i18n/           # Internationalization
├── services/       # API services
├── types/          # TypeScript types
└── utils/          # Utility functions
```

## Key Modules

### Finance & Invoicing
- Electronic invoicing with OpenFactura
- Revenue and expense tracking
- Financial reports and analytics

### Inventory Management
- Product catalog
- Stock tracking
- Movement history
- Low stock alerts

### Staff Management
- Employee directory
- Schedule management
- Performance tracking

### Projects & Tasks
- Project management
- Task assignment
- Progress tracking
- Team collaboration

## Deployment on Render

### Build Command
```bash
npm ci && npm run build:prod
```

### Publish Directory
```
./dist
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Private - Muralla Cafe © 2025
