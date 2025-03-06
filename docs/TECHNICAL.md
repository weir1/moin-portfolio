# Technical Documentation

## 🛠 Tech Stack

### Core Technologies
- **Next.js 14** - React framework for production
- **TypeScript** - For type safety and better developer experience
- **Material UI (MUI)** - Component library with built-in dark/light theme support

### Styling & Design
- **Material UI Theming** - Custom theme with dark/light mode
- **Emotion** - CSS-in-JS solution (comes with MUI)
- **Framer Motion** - For smooth animations

### State Management & Data
- **React Context** - For theme and global state management
- **Local Storage** - For persisting user preferences

### Development Tools
- **ESLint** - Code linting
- **Prettier** - Code formatting
- **Husky** - Git hooks
- **Jest** - Unit testing
- **Cypress** - E2E testing

### Deployment & Hosting
- **Vercel** - Hosting and deployment
- **GitHub Actions** - CI/CD pipeline

## 📁 Project Structure
```
src/
├── components/     # Reusable UI components
├── theme/         # MUI theme configuration
├── pages/         # Next.js pages
├── styles/        # Global styles
├── utils/         # Utility functions
├── hooks/         # Custom React hooks
├── types/         # TypeScript types
└── context/       # React Context providers
```

## 🔄 State Management
- Theme preferences stored in local storage
- React Context for global state
- MUI's theme provider for styling

## 📱 Responsive Design
- Mobile-first approach
- Breakpoints following MUI's standard sizes
- Flexible grid system for layouts