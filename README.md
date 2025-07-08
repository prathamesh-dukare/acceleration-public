# 🚀 Acceleration

> **Save and rediscover what matters, instantly.**

Acceleration is a modern, full-stack productivity tool that helps knowledge workers save, organize, and rediscover their bookmarks and ideas in one beautiful, intuitive space.

## ✨ Features

- **Smart Bookmarking**: Save links with automatic metadata extraction
- **Beautiful Organization**: Organize bookmarks with collections and tags
- **Multiple Ways to Save**: Browser extension, web interface, and context menu
- **Fast Search**: Find what you need instantly with powerful search
- **Cross-Platform**: Works seamlessly across web and browser extension
- **Modern UI**: Beautiful, responsive design built with modern technologies

## 🌐 Live Demo & Links

- **🌐 Website**: [https://getacceleration.com](https://getacceleration.com)
- **🔌 Chrome Extension**: [Install from Chrome Web Store](https://chromewebstore.google.com/detail/acceleration/bhfaaekogleafogfpiahllhgnkbogaoj)
- **📱 Web App**: [https://getacceleration.com/home](https://getacceleration.com/home)

## 🏗️ Architecture

Acceleration is built as a modern full-stack application with three main components:

### 1. Web Application (`/web`)

- **Framework**: Next.js 14 with TypeScript
- **Styling**: Tailwind CSS with shadcn/ui components
- **Authentication**: NextAuth.js with Google OAuth
- **Deployment**: Vercel-ready configuration
- **Features**:
  - Beautiful landing page with gradient design
  - Responsive bookmark management interface
  - Real-time search and filtering
  - Collection and tag organization

### 2. Serverless Backend (`/serverless`)

- **Runtime**: Cloudflare Workers
- **Framework**: Hono.js for API routes
- **Database**: Prisma with Cloudflare D1
- **Authentication**: JWT-based auth system
- **Features**:
  - RESTful API for bookmark management
  - Automatic metadata extraction from URLs
  - User authentication and session management
  - Real-time data synchronization

### 3. Browser Extension (`/extension`)

- **Framework**: React with TypeScript
- **Build Tool**: Vite with CRXJS plugin
- **Styling**: Tailwind CSS
- **Features**:
  - Beautiful new tab replacement
  - Context menu integration
  - Direct bookmark saving
  - Real-time clock and weather
  - Customizable dashboard

## 🛠️ Tech Stack

### Frontend

- **React 18** with TypeScript
- **Next.js 14** for web application
- **Tailwind CSS** for styling
- **shadcn/ui** for component library
- **Framer Motion** for animations
- **Lucide React** for icons

### Backend

- **Cloudflare Workers** for serverless functions
- **Hono.js** for API framework
- **Prisma** for database ORM
- **Cloudflare D1** for database
- **JWT** for authentication

### Development Tools

- **TypeScript** for type safety
- **ESLint** for code linting
- **Vite** for fast development
- **Wrangler** for Cloudflare Workers deployment

## About application
  
#### Bookmark Management

- Automatic metadata extraction from URLs
- Support for collections and tags
- Real-time search and filtering
- Beautiful card-based interface

#### Browser Integration

- New tab replacement with productivity dashboard
- Context menu for quick bookmarking
- Seamless sync between extension and web app

#### User Experience

- Responsive design for all devices
- Dark/light theme support
- Smooth animations and transitions
- Intuitive navigation

## 👨‍💻 Author

**Prathamesh Dukare**

- **GitHub**: [@prathameshdukare](https://github.com/prathameshdukare)
- **LinkedIn**: [Prathamesh Dukare](https://linkedin.com/in/prathameshdukare)
- **Website**: [Website](https://prathame.sh)
- **Peerlist**: [Peerlist.io/prathamesh](https://peerlist.io/prathamesh)
- **Peerlist**: [prathameshTwits](https://x.com/prathameshTwits)

---

**Made with ❤️ in India**


