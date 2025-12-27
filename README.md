# Calyn Landing Page

A modern, animated landing page for Calyn - AI Social Content Engine.

## Features

- Modern React + TypeScript + Vite setup
- Framer Motion animations
- Tailwind CSS styling
- Responsive design
- Smooth scroll navigation
- Interactive components

## Getting Started

### Install Dependencies

```bash
npm install
```

### Run Development Server

```bash
npm run dev
```

The app will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
src/
├── components/
│   ├── landing/       # Landing page sections
│   │   ├── Navbar.tsx
│   │   ├── Hero.tsx
│   │   ├── FeatureCards.tsx
│   │   ├── FeaturesGrid.tsx
│   │   ├── HowItWorks.tsx
│   │   ├── Pricing.tsx
│   │   ├── Testimonials.tsx
│   │   ├── FAQ.tsx
│   │   ├── Footer.tsx
│   │   └── InfiniteCarousel.tsx
│   └── ui/            # Reusable UI components
│       ├── text-flip.tsx
│       └── grid-background.tsx
├── lib/
│   └── utils.ts       # Utility functions
├── App.tsx            # Main app component
├── main.tsx           # Entry point
└── index.css          # Global styles
```

## Technologies Used

- React 19
- TypeScript
- Vite
- Tailwind CSS
- Framer Motion
- Lucide React (icons)
- React Intersection Observer
