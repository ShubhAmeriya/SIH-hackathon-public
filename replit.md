# Career & Education Advisor Platform

## Overview

This is a comprehensive career and education guidance platform specifically designed for students in Jammu and Kashmir. The application serves as a one-stop solution for personalized career recommendations, college exploration, job database access, entrance exam information, and educational resources. Built with a modern full-stack architecture, it features a React frontend with TypeScript, Express.js backend, and PostgreSQL database with Drizzle ORM.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript for type safety and modern development
- **Routing**: Wouter for lightweight client-side routing
- **State Management**: TanStack Query (React Query) for server state management and caching
- **UI Framework**: Radix UI components with shadcn/ui design system
- **Styling**: Tailwind CSS with custom design tokens and dark mode support
- **Build Tool**: Vite for fast development and optimized production builds

### Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **API Design**: RESTful API with organized route handlers
- **Database Integration**: Drizzle ORM for type-safe database operations
- **Development**: Hot reloading with tsx for development server
- **Production**: esbuild for optimized server bundling

### Database Design
- **Database**: PostgreSQL with Neon serverless hosting
- **ORM**: Drizzle ORM with TypeScript schema definitions
- **Schema Structure**:
  - Users table with comprehensive profile data including academic background, interests, and career preferences
  - Career paths with detailed information about requirements, salaries, and skills
  - Colleges with location, courses, and institutional details
  - Jobs database with categorization and filtering capabilities
  - Entrance exams with schedules and requirements
  - Resources including e-books, courses, and scholarships
  - User saved items for bookmarking functionality

### User Experience Features
- **Onboarding Flow**: Multi-step guided setup collecting academic background, interests, and career goals
- **Personalization**: AI-driven recommendations based on user profile and preferences
- **Responsive Design**: Mobile-first approach with adaptive layouts
- **Interactive Components**: Rich data visualizations using Recharts
- **Search and Filtering**: Advanced filtering across all content types

### Key Modules
1. **Career Path Finder**: Personalized career recommendations with detailed breakdowns
2. **College Explorer**: Comprehensive database of educational institutions with filtering
3. **Jobs Database**: Curated job listings with category-based organization
4. **Entrance Exams**: Centralized exam information with schedules and requirements
5. **Resource Library**: Educational materials including e-books, courses, and scholarships
6. **Dashboard**: Personalized user hub with recommendations and saved items

## External Dependencies

### Core Technologies
- **Neon Database**: Serverless PostgreSQL hosting for scalable data storage
- **Radix UI**: Headless UI components for accessible interface elements
- **TanStack Query**: Server state synchronization and caching layer
- **Recharts**: Data visualization library for career analytics and trends

### Development Tools
- **Vite**: Modern build tool with hot module replacement
- **Drizzle Kit**: Database migration and schema management
- **ESBuild**: Fast JavaScript bundler for production builds
- **TypeScript**: Static type checking for enhanced code quality

### UI and Styling
- **Tailwind CSS**: Utility-first CSS framework with custom design system
- **Lucide React**: Icon library for consistent visual elements
- **Class Variance Authority**: Component variant management
- **Date-fns**: Date manipulation utilities

### Form Management
- **React Hook Form**: Performant form handling with validation
- **Zod**: Runtime type validation and schema parsing
- **Hookform Resolvers**: Integration between React Hook Form and Zod

The architecture prioritizes scalability, type safety, and user experience while maintaining clean separation of concerns between frontend presentation, backend logic, and data persistence layers.