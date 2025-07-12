# MentorConnect

A modern mentoring platform built with React, TypeScript, and Tailwind CSS. Optimized for deployment on Vercel.

## 🚀 Features

- **Dashboard**: Analytics and session management
- **Booking System**: Complete mentoring session booking workflow
- **Profile Management**: User profiles and settings
- **Wallet & Earnings**: Financial tracking and management
- **Content Management**: Educational content organization
- **Team Collaboration**: Team features and management
- **Community**: Community engagement features
- **Notifications**: Real-time notification system
- **Dark/Light Theme**: Toggle between themes with persistence

## 🛠 Tech Stack

- **Frontend**: React 19, TypeScript
- **Styling**: Tailwind CSS
- **Routing**: React Router DOM v7
- **Animations**: Framer Motion
- **Icons**: Lucide React, React Icons
- **Build Tool**: Vite 6
- **Deployment**: Vercel (optimized)

## 📦 Getting Started

### Prerequisites

- Node.js 18+
- npm (recommended for Vercel deployment)

### Local Development

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd mentorconnect
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:5173](http://localhost:5173)

## 🚀 Deployment to Vercel

This project is fully optimized for Vercel deployment:

### Option 1: Deploy via Vercel CLI

1. **Install Vercel CLI**
   ```bash
   npm i -g vercel
   ```

2. **Deploy**
   ```bash
   vercel
   ```

### Option 2: Deploy via Vercel Dashboard

1. **Connect your repository** to Vercel
2. **Import your project** - Vercel will auto-detect the framework
3. **Deploy** - No additional configuration needed!

### Option 3: Deploy via Git Integration

1. **Push to GitHub/GitLab/Bitbucket**
2. **Connect repository** in Vercel dashboard
3. **Auto-deploy** on every push to main branch

## 📋 Available Scripts

- `npm run dev` - Start development server (port 5173)
- `npm run build` - Build for production with TypeScript checking
- `npm run preview` - Preview production build (port 4173)
- `npm run lint` - Run ESLint
- `npm run type-check` - Run TypeScript type checking

## 🏗 Project Structure

```
mentorconnect/
├── src/
│   ├── components/          # Reusable UI components
│   │   ├── Layout/         # Layout components (Header, Sidebar, etc.)
│   │   └── UI/             # UI components (Charts, Cards, etc.)
│   ├── pages/              # Page components
│   ├── App.tsx             # Main app component with routing
│   ├── main.tsx            # App entry point
│   └── index.css           # Global styles with Tailwind
├── public/                 # Static assets
├── dist/                   # Production build output
├── vercel.json            # Vercel configuration
├── .vercelignore          # Files to ignore during deployment
├── vite.config.ts         # Vite configuration (production optimized)
└── package.json           # Dependencies and scripts
```

## ⚡ Performance Optimizations

- **Code Splitting**: Automatic chunking for vendor, router, and UI libraries
- **Asset Optimization**: Minified CSS/JS with Terser
- **Caching**: Optimized cache headers for static assets
- **Bundle Analysis**: Separated chunks for better loading performance

## 🔧 Configuration Files

- **`vercel.json`**: Vercel deployment configuration with SPA routing
- **`vite.config.ts`**: Production-optimized Vite configuration
- **`.vercelignore`**: Excludes unnecessary files from deployment
- **`tsconfig.json`**: TypeScript configuration

## 🌐 Environment Variables

This is a frontend-only application with no backend dependencies. No environment variables are required for basic functionality.

## 🎨 Theming

The application supports dark/light theme switching with:
- System preference detection
- Local storage persistence
- Smooth transitions

## 📱 Responsive Design

Fully responsive design optimized for:
- Desktop (1024px+)
- Tablet (768px - 1023px)
- Mobile (320px - 767px)

## 🔒 Security Headers

Production deployment includes security headers:
- `X-Content-Type-Options: nosniff`
- `X-Frame-Options: DENY`
- `X-XSS-Protection: 1; mode=block`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support

If you encounter any issues during deployment:

1. **Check build logs** in Vercel dashboard
2. **Verify Node.js version** (18+ required)
3. **Ensure all dependencies** are properly installed
4. **Check TypeScript errors** with `npm run type-check`

For additional support, please open an issue in the repository.
