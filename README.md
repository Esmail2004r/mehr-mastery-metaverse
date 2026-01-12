# MEHR Platform Web

> **Global Professional Training Metaverse**

A production-grade EdTech / Metaverse platform foundation built with React, TypeScript, and Vite.

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Run linting
npm run lint
```

## 📁 Project Structure

```
src/
├── assets/           # Static assets (images, logos)
├── components/
│   ├── layout/       # Global layout components (Navbar, Footer, Layout)
│   └── ui/           # Reusable UI components (shadcn/ui based)
├── hooks/            # Custom React hooks
├── lib/              # Utility functions
├── pages/            # Page components (routed views)
│   ├── Index.tsx     # Home page
│   ├── About.tsx     # About page with districts
│   ├── Contact.tsx   # Contact form
│   ├── Events.tsx    # Events placeholder
│   └── NotFound.tsx  # 404 page
└── index.css         # Global styles & design system
```

## 🎨 Design System

The platform uses a dark, futuristic theme with neon cyan accents:

- **Primary**: Neon Cyan (`hsl(187, 100%, 50%)`)
- **Background**: Dark (`hsl(220, 20%, 6%)`)
- **Typography**: Space Grotesk (headings) + Inter (body)
- **Effects**: Glow utilities, smooth transitions

All design tokens are defined in `src/index.css` and `tailwind.config.ts`.

## 📋 Current Phase

**Phase 1: Foundation** ✅

This is the initial technical foundation. No feature development yet.

### Included:
- ✅ Clean folder structure
- ✅ Static pages (Home, About, Contact, Events)
- ✅ Global layout (Navbar, Footer)
- ✅ Design system with theming
- ✅ ESLint & TypeScript configuration
- ✅ Production-ready build setup

### Out of Scope (Future Phases):
- Authentication
- Dashboards
- User roles
- Blockchain/tokens
- Payments
- AI features
- Backend APIs

## 🛠 Tech Stack

- **Framework**: React 18 + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS + CSS Variables
- **UI Components**: shadcn/ui (Radix-based)
- **Routing**: React Router v6
- **State Management**: TanStack Query (ready for future use)

## 🔧 Development Notes

### Assumptions Made:
1. Using React/Vite instead of Next.js (Lovable platform constraint)
2. Events page included as a placeholder per navbar requirements
3. Form submission shows alert (no backend connected)

### Extending the Project:
- Add new pages in `src/pages/`
- Create reusable components in `src/components/`
- Add API services in `src/services/` (create folder when needed)
- Utility functions go in `src/lib/` or `src/utils/`

## 📄 License

Proprietary - MEHR Platform
