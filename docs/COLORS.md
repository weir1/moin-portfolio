# Color Scheme Documentation

## 🎨 Primary Color Palette

```css
--text: #fbf4d2;      /* Light cream text */
--background: #0c0901; /* Dark brown/black background */
--primary: #f2e074;    /* Golden yellow */
--secondary: #64a00f;  /* Forest green */
--accent: #77ec35;     /* Bright lime */
```

## 🌓 Theme Variations

### Dark Theme
```javascript
const darkTheme = {
  palette: {
    mode: 'dark',
    primary: {
      main: '#f2e074',
      light: '#f7e9a0',
      dark: '#d9c85a'
    },
    secondary: {
      main: '#64a00f',
      light: '#7ac412',
      dark: '#4c7a0b'
    },
    background: {
      default: '#0c0901',
      paper: '#1a1a1a'
    },
    text: {
      primary: '#fbf4d2',
      secondary: '#e0d9b7'
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
      main: '#64a00f',
      light: '#7ac412',
      dark: '#4c7a0b'
    },
    secondary: {
      main: '#f2e074',
      light: '#f7e9a0',
      dark: '#d9c85a'
    },
    background: {
      default: '#ffffff',
      paper: '#f5f5f5'
    },
    text: {
      primary: '#0c0901',
      secondary: '#2a2a2a'
    }
  }
}
```

## 🎯 Color Usage Guidelines

### Navigation & Header
- Background: Dark theme background
- Text: Light cream text
- Logo/Brand: Primary golden yellow

### Hero Section
- Background: Dark background with gradient
- Headings: Primary color
- Subtext: Text color
- CTA Buttons: Secondary color

### Services Section
- Cards: Slightly lighter background
- Icons: Secondary color
- Headings: Primary color
- Text: Main text color

### Portfolio Projects
- Cards: Paper background
- Project Titles: Primary color
- Technologies: Text color
- Buttons: Secondary color

### Contact Section
- Form Background: Paper background
- Input Fields: Text color with primary color focus
- Submit Button: Secondary color
- Icons: Primary color