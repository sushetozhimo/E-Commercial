# Commercial - Next.js Application

## Overview
A Next.js application with React 19, Tailwind CSS 4, and modern web development setup.

## Project Structure
- `app/` - Next.js App Router pages and layouts
  - `page.js` - Main page component
  - `layout.js` - Root layout component
  - `globals.css` - Global styles with Tailwind
- `public/` - Static assets (images, icons)
- `next.config.mjs` - Next.js configuration
- `postcss.config.mjs` - PostCSS configuration for Tailwind

## Development
- **Dev Server**: Runs on port 5000 with `npm run dev -- -p 5000 -H 0.0.0.0`
- **Build**: `npm run build`
- **Production Start**: `npm run start`

## Tech Stack
- Next.js 16.1.1
- React 19.2.3
- Tailwind CSS 4
- ESLint 9

## Configuration
- `allowedDevOrigins: ['*']` configured in next.config.mjs for Replit proxy compatibility
