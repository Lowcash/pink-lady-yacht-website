# Project Architecture

## Overview
This project is a single-page React application built with Vite, serving as a professional brochure site for yachting services. It emphasizes visual hierarchy, responsiveness, and clear calls-to-action.

## Directory Structure

```
src/
├── assets/          # Static assets (images, logos)
├── components/      # React components
│   ├── ui/          # Base UI elements
│   └── [Feature].tsx # Feature-specific components (Hero, Services, etc.)
├── lib/             # Utilities and constants
├── styles/          # Global styles
├── App.tsx          # Main application component
└── main.tsx         # Entry point
```

## Key Systems

### 1. Service Showcase
- **Implementation**: `Services.tsx`
- **Data**: Defined in `src/lib/constants.ts` for easy updates.
- **Layout**: Responsive grid system adapting to mobile/tablet/desktop.

### 2. Navigation
- **Implementation**: `Navigation.tsx`
- **Behavior**: Sticky header with smooth scroll to anchor links.
- **Mobile**: Hamburger menu with slide-out drawer.

### 3. Contact Integration
- **Implementation**: `Contact.tsx`
- **Features**: Direct WhatsApp links and email form integration.

## Tech Stack Decisions
- **Vite**: Fast build times and modern development experience.
- **React**: Component-based architecture for maintainability.
- **Tailwind CSS**: Rapid styling with built-in responsive modifiers.
- **Lucide React**: Consistent, lightweight icon set.
