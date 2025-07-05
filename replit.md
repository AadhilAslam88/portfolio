# Ahmed Aadhil - Data Science Portfolio

## Overview

This is a full-stack web application for Ahmed Aadhil's data science portfolio. The application showcases projects, skills, and experience in data science, featuring a modern, responsive design built with React and TypeScript. It includes a contact form with backend submission handling and uses shadcn/ui components for a polished user interface.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript
- **Build Tool**: Vite for fast development and optimized production builds
- **Routing**: Wouter for lightweight client-side routing
- **State Management**: React hooks with TanStack Query for server state management
- **Styling**: Tailwind CSS with shadcn/ui component library
- **Form Handling**: React Hook Form with Zod validation

### Backend Architecture
- **Framework**: Express.js with TypeScript
- **Runtime**: Node.js with ESM modules
- **API Structure**: RESTful API with `/api` prefix
- **Middleware**: Custom logging and error handling
- **Development**: Hot reloading with Vite integration in development mode

## Key Components

### User Interface Components
- **Navigation**: Fixed navigation with smooth scrolling and active section highlighting
- **Hero Section**: Animated landing area with professional headshot and call-to-action
- **About Section**: Personal story, education details, and resume download
- **Projects Section**: Filterable project showcase with modal details
- **Skills Section**: Technical skills with animated progress bars and tool icons
- **Contact Section**: Form with validation and submission handling
- **Footer**: Social media links and contact information

### Backend Components
- **Routes**: Contact form submission and message retrieval endpoints
- **Storage**: PostgreSQL database storage with Drizzle ORM
- **Validation**: Zod schema validation for form inputs
- **Error Handling**: Centralized error handling with proper HTTP status codes

## Data Flow

1. **Client-Side Rendering**: React components render the portfolio interface
2. **Form Submission**: Contact form data is validated client-side with Zod
3. **API Communication**: Form data is sent to Express backend via fetch
4. **Server Validation**: Backend validates data using shared Zod schemas
5. **Storage**: Contact messages are stored in PostgreSQL database
6. **Response Handling**: Success/error responses are displayed to users via toast notifications

## External Dependencies

### Frontend Dependencies
- **UI Components**: @radix-ui components for accessible UI primitives
- **Form Management**: @hookform/resolvers for form validation integration
- **HTTP Client**: TanStack Query for data fetching and caching
- **Styling**: Tailwind CSS for utility-first styling
- **Icons**: Font Awesome for social media and UI icons
- **Fonts**: Google Fonts (Inter and Fira Code)

### Backend Dependencies
- **Database ORM**: Drizzle ORM configured for PostgreSQL
- **Database Driver**: @neondatabase/serverless for Neon PostgreSQL
- **Session Management**: connect-pg-simple for PostgreSQL session store
- **Validation**: Zod for runtime type checking and validation
- **Development**: tsx for TypeScript execution in development

### Development Tools
- **Build System**: Vite with React plugin and runtime error overlay
- **Code Quality**: TypeScript for type safety
- **Database Migrations**: Drizzle Kit for schema management
- **Asset Optimization**: Automatic image optimization and code splitting

## Deployment Strategy

### Build Process
1. **Frontend Build**: Vite compiles React application to static assets
2. **Backend Build**: esbuild bundles Express server for production
3. **Asset Generation**: Static assets are generated in `dist/public`
4. **Database Setup**: Drizzle migrations can be applied with `npm run db:push`

### Production Configuration
- **Static Serving**: Express serves built React application
- **Database**: PostgreSQL via Neon serverless driver
- **Environment Variables**: `DATABASE_URL` required for database connection
- **Session Storage**: PostgreSQL-backed session storage for scalability

### Development Environment
- **Hot Reloading**: Vite dev server with Express API proxy
- **Type Safety**: Shared types between frontend and backend
- **Database**: Local PostgreSQL or Neon development database
- **Error Handling**: Development-specific error overlays and logging

## Changelog

```
Changelog:
- July 05, 2025. Initial setup with Alex Perera placeholder content
- July 05, 2025. Updated profile to Ahmed Aadhil with personal information:
  - Name: Ahmed Aadhil  
  - Email: aslamaadhil99@gmail.com
  - Phone: +94 71 283 3936
  - Study period: 2023-2027 (second-year student)
  - GitHub: https://github.com/AadhilAslam88
  - LinkedIn: https://www.linkedin.com/in/ahmed-aadhil
  - Added professional profile photo
- July 05, 2025. Added PostgreSQL database integration:
  - Created database connection with Drizzle ORM
  - Replaced in-memory storage with database storage
  - Contact messages now persist in PostgreSQL database
  - Applied database schema with contact_messages table
```

## User Prefere

```
Preferred communication style: Simple, everyday language.
```
