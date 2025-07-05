# Ahmed Aadhil - Data Science Portfolio

A modern, responsive portfolio website showcasing my data science projects, skills, and experience.

## 🚀 Live Demo

Visit the live portfolio: [ahmed-aadhil.github.io](https://ahmed-aadhil.github.io)

## 📋 About

I'm Ahmed Aadhil, a second-year Data Science student at Sri Lanka Technological Campus (SLTC). This portfolio showcases my journey in data science, featuring projects in machine learning, data visualization, and web development.

## ✨ Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Project Showcase**: Interactive project cards with filtering by category
- **Skills Display**: Visual representation of technical skills and tools
- **Contact Form**: Functional contact form with form validation
- **SEO Optimized**: Proper meta tags and Open Graph support

## 🛠️ Tech Stack

### Frontend
- **React 18** with TypeScript
- **Vite** for fast development and building
- **Tailwind CSS** for styling
- **shadcn/ui** component library
- **React Hook Form** with Zod validation
- **TanStack Query** for data fetching
- **Framer Motion** for animations

### Backend
- **Express.js** with TypeScript
- **PostgreSQL** database with Drizzle ORM
- **Zod** for data validation
- **Neon** serverless PostgreSQL

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/AadhilAslam88/portfolio.git
cd portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
cp .env.example .env
# Add your database URL and other environment variables
```

4. Set up the database:
```bash
npm run db:push
```

5. Start the development server:
```bash
npm run dev
```

The app will be available at `http://localhost:5000`

## 📁 Project Structure

```
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page components
│   │   ├── hooks/          # Custom React hooks
│   │   └── lib/            # Utility functions
│   └── public/             # Static assets
├── server/                 # Backend Express application
│   ├── routes.ts           # API routes
│   ├── db.ts              # Database connection
│   └── storage.ts         # Data access layer
├── shared/                 # Shared types and schemas
│   └── schema.ts          # Database schemas and types
└── package.json
```

## 🎯 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run db:push` - Push database schema changes
- `npm run db:studio` - Open Drizzle Studio

## 🌐 Deployment

### GitHub Pages (Static)
For a static version without backend functionality:

1. Build the project:
```bash
npm run build
```

2. Deploy the `dist/public` folder to GitHub Pages

### Full Stack Deployment
For full functionality including the contact form:

- **Vercel**: Deploy with serverless functions
- **Netlify**: Deploy with edge functions
- **Railway/Render**: Deploy with PostgreSQL database

## 📞 Contact

- **Email**: aslamaadhil99@gmail.com
- **Phone**: +94 71 283 3936
- **LinkedIn**: [ahmed-aadhil](https://www.linkedin.com/in/ahmed-aadhil)
- **GitHub**: [AadhilAslam88](https://github.com/AadhilAslam88)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ If you found this portfolio helpful, please give it a star!
