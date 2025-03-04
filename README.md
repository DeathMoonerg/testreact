# Aidil Saputra Kirsan - Portfolio Website

A modern, responsive portfolio website built with React, Tailwind CSS, and Framer Motion animations.

## 🚀 Features

- **Responsive Design**: Fully responsive across all device sizes
- **Dark/Light Mode**: Toggle between light and dark themes
- **Interactive Animations**: Smooth animations and transitions using Framer Motion
- **Particle Background**: Interactive particle system in the header
- **Optimized Performance**: Code splitting and lazy loading for better performance
- **Accessibility**: ARIA compliant and keyboard navigable
- **PWA Support**: Can be installed as a Progressive Web App
- **Like Button**: Interactive feature with backend connection

## 🛠️ Tech Stack

- **Frontend**:
  - React 18
  - Tailwind CSS for styling
  - Framer Motion for animations
  - Lucide React for icons
  - React Scroll for smooth scrolling
  - Typed.js for typing animations
  - TSParticles for animated background

- **Backend**:
  - Express.js for API endpoints
  - Vercel Serverless Functions

## 🏗️ Project Structure

```
/
├── public/             # Static assets
├── src/
│   ├── components/     # React components
│   │   ├── layout/     # Layout components
│   │   ├── sections/   # Page section components
│   │   └── ui/         # Reusable UI components
│   ├── context/        # React context providers
│   ├── styles/         # CSS and style-related files
│   ├── App.jsx         # Main App component
│   ├── index.css       # Global styles
│   └── main.jsx        # Entry point
├── .eslintrc.cjs       # ESLint configuration
├── package.json        # Dependencies and scripts
├── tailwind.config.js  # Tailwind CSS configuration
└── vite.config.js      # Vite configuration
```

## 📝 Getting Started

### Prerequisites

- Node.js 18+ and npm/yarn

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/aidilsaputrakirsan/portfolio.git
   cd portfolio
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm run dev
   ```

4. Open your browser and visit:
   ```
   http://localhost:5173
   ```

## 🚢 Deployment

1. Build the project:
   ```
   npm run build
   ```

2. Preview the production build:
   ```
   npm run preview
   ```

3. Deploy to your hosting platform of choice (GitHub Pages, Vercel, Netlify, etc.)

## 🧩 Components

- **Header**: Navigation and hero section with particle background
- **About**: Personal information and professional overview
- **Skills**: Technical skills with interactive filtering
- **Experience**: Career, education, and achievements timeline
- **Projects**: Portfolio showcasing various projects
- **Contact**: Contact form and information
- **Footer**: Site navigation and social links

## 📱 Responsive Design

The site is fully responsive with breakpoints for:
- Mobile devices
- Tablets
- Laptops/Desktops
- Large screens

## 🌙 Dark/Light Theme

The site supports both dark and light themes with:
- System preference detection
- Manual toggle
- Persistent preference saving

## 📄 License

MIT

## 👤 Author

Aidil Saputra Kirsan

---

Made with ❤️ and React + Tailwind CSS