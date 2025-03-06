# Color Scheme Documentation

## 🎨 Primary Color Palette

```css
--text: #F1F5F9;      /* Slate white - Clean, crisp text */
--background: #020617; /* Deep slate - Professional dark background */
--primary: #4F46E5;    /* Electric indigo - Modern, tech-focused */
--secondary: #0EA5E9;  /* Sky blue - Trust, reliability */
--accent: #EC4899;     /* Pink - Distinctive CTAs */
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
    background: {
      default: '#020617',
      paper: '#0F172A'
    },
    text: {
      primary: '#F1F5F9',
      secondary: '#CBD5E1'
    },
    error: {
      main: '#EC4899',
      light: '#F472B6',
      dark: '#DB2777'
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
    background: {
      default: '#FFFFFF',
      paper: '#F8FAFC'
    },
    text: {
      primary: '#020617',
      secondary: '#1E293B'
    },
    error: {
      main: '#EC4899',
      light: '#F472B6',
      dark: '#DB2777'
    }
  }
}
```

## 🎯 Color Usage Guidelines

### Navigation & Header
- Background: Deep slate (#020617)
- Text: Slate white (#F1F5F9)
- Logo/Brand: Electric indigo (#4F46E5)
- Active/Hover: Sky blue (#0EA5E9)

### Hero Section
- Background: Deep slate with gradient
- Main Heading: Electric indigo (#4F46E5)
- Subtext: Slate white (#F1F5F9)
- CTA Buttons: Pink (#EC4899)
- Secondary CTAs: Sky blue (#0EA5E9)

### Services Section
- Cards Background: Slightly lighter slate (#0F172A)
- Card Borders: Electric indigo glow
- Icons: Sky blue (#0EA5E9)
- Headings: Electric indigo (#4F46E5)
- Text: Slate white (#F1F5F9)

### Portfolio Projects
- Cards: Paper background (#0F172A)
- Project Titles: Electric indigo (#4F46E5)
- Technologies: Sky blue (#0EA5E9)
- View Project Button: Pink (#EC4899)
- Hover States: Mix of primary and secondary colors

### Contact Section
- Form Background: Slightly lighter slate (#0F172A)
- Input Fields: Borders in Sky blue (#0EA5E9)
- Labels: Slate white (#F1F5F9)
- Submit Button: Pink (#EC4899)
- Social Icons: Electric indigo (#4F46E5)

## 💡 Usage Examples

### Buttons
```css
/* Primary Button */
.button-primary {
  background: #4F46E5;
  color: #F1F5F9;
  &:hover {
    background: #6366F1;
  }
}

/* Secondary Button */
.button-secondary {
  background: #0EA5E9;
  color: #F1F5F9;
  &:hover {
    background: #38BDF8;
  }
}

/* CTA Button */
.button-cta {
  background: #EC4899;
  color: #F1F5F9;
  &:hover {
    background: #F472B6;
  }
}
```

### Cards
```css
.card {
  background: #0F172A;
  color: #F1F5F9;
  border: 1px solid rgba(79, 70, 229, 0.1);
  box-shadow: 0 0 20px rgba(79, 70, 229, 0.05);
}

.card-hover {
  &:hover {
    border-color: #4F46E5;
    box-shadow: 0 0 30px rgba(79, 70, 229, 0.1);
  }
}
```

### Text Styles
```css
.heading-primary {
  color: #4F46E5;
  font-weight: bold;
}

.heading-secondary {
  color: #0EA5E9;
}

.text-body {
  color: #F1F5F9;
}

.text-muted {
  color: #CBD5E1;
}
```