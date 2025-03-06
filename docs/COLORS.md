# Color Scheme Documentation

## 🎨 Primary Color Palette

```css
--text: #F1F5F9       /* Slate white - clean and crisp */
--background: #020617 /* Deep slate - professional */
--primary: #4F46E5    /* Electric indigo - modern */
--secondary: #0EA5E9  /* Sky blue - trustworthy */
--accent: #EC4899     /* Pink - distinctive */
```

## 🌓 Theme Variations

### Dark Theme (Default)
```javascript
const darkTheme = {
  palette: {
    mode: 'dark',
    primary: {
      main: '#4F46E5',
      light: '#6366F1',
      dark: '#4338CA'
    },
    secondary: {
      main: '#0EA5E9',
      light: '#38BDF8',
      dark: '#0284C7'
    },
    accent: {
      main: '#EC4899',
      light: '#F472B6',
      dark: '#DB2777'
    },
    background: {
      default: '#020617',
      paper: '#0F172A'
    },
    text: {
      primary: '#F1F5F9',
      secondary: '#E2E8F0'
    }
  }
}
```

### Light Theme
```javascript
const lightTheme = {
  palette: {
    mode: 'light',
    primary: {
      main: '#4F46E5',
      light: '#6366F1',
      dark: '#4338CA'
    },
    secondary: {
      main: '#0EA5E9',
      light: '#38BDF8',
      dark: '#0284C7'
    },
    accent: {
      main: '#EC4899',
      light: '#F472B6',
      dark: '#DB2777'
    },
    background: {
      default: '#FFFFFF',
      paper: '#F8FAFC'
    },
    text: {
      primary: '#020617',
      secondary: '#1E293B'
    }
  }
}
```

## 🎯 Color Usage Guidelines

### Navigation & Header
- Background: Glass effect with deep slate base
- Text: Slate white
- Logo/Brand: Electric indigo
- Active Links: Sky blue
- CTA Button: Pink accent

### Hero Section
- Background: Deep slate with subtle gradient
- Main Heading: Slate white
- Subheading: Sky blue
- CTA Buttons: Pink accent
- Decorative Elements: Electric indigo

### Services Section
- Cards Background: Glass effect on deep slate
- Card Icons: Sky blue
- Card Titles: Electric indigo
- Card Text: Slate white
- Hover States: Pink accent

### Portfolio Projects
- Cards: Glass effect background
- Project Titles: Electric indigo
- Technologies: Sky blue
- View Button: Pink accent
- Hover: Gradient mix of primary and secondary

### Contact Section
- Form Background: Glass effect
- Input Fields: Slate white text
- Input Borders: Electric indigo
- Submit Button: Pink accent
- Social Icons: Sky blue

## 💫 Special Effects
- Glass Morphism: rgba(255, 255, 255, 0.1)
- Shadows: rgba(2, 6, 23, 0.1)
- Gradients: Linear mix of primary and secondary
- Hover Effects: Subtle scale and color transitions
- Focus States: Electric indigo glow