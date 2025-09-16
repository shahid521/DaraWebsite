# Dara - Media & Entertainment Hub

## Overview

Dara is a modern web application that replicates the طرب (Tarab) app interface, serving as a unified media and entertainment hub. The application allows users to search, discover, and access content from multiple platforms in one place. It features a dark-themed, mobile-first design with Arabic/English support and provides functionality for URL processing, media content management, and platform integration.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript using Vite as the build tool
- **UI Components**: shadcn/ui component library with Radix UI primitives
- **Styling**: Tailwind CSS with custom design system following the Tarab app's visual identity
- **State Management**: TanStack Query (React Query) for server state management
- **Routing**: Wouter for lightweight client-side routing
- **Form Handling**: React Hook Form with Zod validation

### Backend Architecture
- **Runtime**: Node.js with Express.js server
- **API Design**: RESTful API with JSON responses
- **Data Validation**: Zod schemas for type-safe validation
- **Storage Layer**: Abstracted storage interface supporting both memory storage and PostgreSQL

### Design System
- **Color Scheme**: Dark navy theme (220 15% 12%) with bright blue accents (210 100% 60%)
- **Layout**: Mobile-first responsive design with consistent spacing using Tailwind units
- **Typography**: System font stack optimized for Arabic/English compatibility
- **Components**: Reference-based design exactly replicating the Tarab app interface

### Core Features
- **Search & URL Processing**: Intelligent search that can process URLs (especially YouTube) and general search queries
- **Platform Integration**: Support for multiple media platforms (YouTube, Instagram, TikTok, etc.)
- **Media Management**: CRUD operations for media content with metadata storage
- **Navigation**: Tab-based bottom navigation (Sources, Files, Playlists, More)

### Data Layer
- **ORM**: Drizzle ORM for type-safe database interactions
- **Schema**: Well-defined schemas for users, media content, and playlists
- **Migrations**: Database migration support through Drizzle Kit

## External Dependencies

### Database
- **PostgreSQL**: Primary database using Neon serverless PostgreSQL
- **Connection**: @neondatabase/serverless for database connectivity
- **Schema Management**: Drizzle ORM with migration support

### UI Libraries
- **Radix UI**: Comprehensive set of unstyled, accessible UI primitives
- **Lucide React**: Icon library for consistent iconography
- **React Icons**: Additional icons including platform-specific icons (YouTube, Instagram, etc.)
- **Embla Carousel**: Carousel/slider functionality

### Development Tools
- **TypeScript**: Full type safety across the application
- **ESBuild**: Fast bundling for production builds
- **PostCSS**: CSS processing with Tailwind CSS
- **Replit Integration**: Development environment optimizations for Replit

### Potential Integrations
- **YouTube API**: For fetching video metadata and thumbnails
- **Platform APIs**: Future integration with Instagram, TikTok, and other media platforms
- **Authentication**: Prepared user schema for future authentication implementation