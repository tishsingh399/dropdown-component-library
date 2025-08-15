# Dropdown Component Library

A comprehensive collection of accessible, customizable dropdown components with design token integration.

## 🚀 Free Deployment Options

### Option 1: GitHub Pages (Recommended - 100% Free)
1. **Create a GitHub repository** and push this folder
2. **Go to Settings** → **Pages**
3. **Select source**: "Deploy from a branch"
4. **Choose branch**: `main` or `master`
5. **Your site will be live** at `https://yourusername.github.io/repository-name`

### Option 2: Vercel (Free Tier)
1. **Sign up** at [vercel.com](https://vercel.com)
2. **Import** your GitHub repository
3. **Deploy automatically** - no configuration needed

### Option 3: Surge.sh (Free)
1. **Install Surge**: `npm install -g surge`
2. **Navigate** to this folder
3. **Run**: `surge`
4. **Follow prompts** to deploy

## 📁 Project Structure

```
netlify-deploy/
├── index.html              # Landing page with demo links
├── styles/
│   └── dropdown-tokens.css # Design tokens and component styles
├── demos/
│   ├── annotated-dropdown-demo.html  # Complete interactive demo
│   ├── figma-dropdown-demo.html      # Figma design replica
│   └── simple-dropdown-demo.html     # Basic demo
├── _redirects              # Netlify redirects (if using Netlify)
└── README.md               # This file
```

## 🎯 Demo Pages

### 1. Complete Dropdown Demo (`/demos/annotated-dropdown-demo.html`)
- **All dropdown types**: Standard, Group, Combobox, Multi-Select, Tags, Search
- **Interactive features**: Create new options, theme toggle, filtering
- **Design tokens**: Full light/dark theme support
- **Accessibility**: ARIA attributes, keyboard navigation

### 2. Figma Replica (`/demos/figma-dropdown-demo.html`)
- **Exact visual match**: Pixel-perfect replica of Figma design
- **Annotations**: Shows design notes and specifications
- **Reference**: Perfect for design review and comparison

### 3. Simple Demo (`/demos/simple-dropdown-demo.html`)
- **Basic functionality**: Core dropdown features
- **Clean design**: Minimal, focused demo
- **Quick testing**: Fast loading and simple interactions

## ✨ Features

### 🎨 Design System Integration
- **SDStoken support**: Full integration with your design tokens
- **Theme switching**: Smooth light/dark mode transitions
- **Consistent styling**: All components follow design system guidelines

### ♿ Accessibility
- **ARIA attributes**: Proper roles, labels, and states
- **Keyboard navigation**: Full keyboard support (Tab, Arrow keys, Enter, Escape)
- **Screen reader friendly**: Semantic HTML and proper announcements
- **WCAG compliant**: Follows accessibility guidelines

### 🔧 Component Types
- **Standard Dropdown**: Basic single-selection dropdown
- **Group Dropdown**: Options organized under categories
- **Combobox**: Typeahead with create-new-option functionality
- **Multi-Select**: Checkbox-based multiple selection
- **Tags/Chips**: Visual tag representation with removal
- **Search Dropdown**: Integrated search and filtering

### 📱 Responsive Design
- **Mobile-friendly**: Works on all screen sizes
- **Touch support**: Optimized for touch interactions
- **Flexible layout**: Adapts to different viewport sizes

## 🛠️ Technical Details

### No Dependencies
- **Vanilla JavaScript**: No frameworks or libraries required
- **CSS Custom Properties**: Modern CSS for theming
- **Semantic HTML**: Clean, accessible markup

### Performance
- **Lightweight**: Minimal file sizes
- **Fast loading**: Optimized assets
- **Smooth animations**: CSS transitions and transforms

### Browser Support
- **Modern browsers**: Chrome, Firefox, Safari, Edge
- **Progressive enhancement**: Works without JavaScript
- **Fallbacks**: Graceful degradation for older browsers

## 🧪 Testing

The component library includes comprehensive tests:
- **75+ test cases** covering behavior and accessibility
- **Vitest + Testing Library** for reliable testing
- **User interaction simulation** with `userEvent`
- **Accessibility testing** with ARIA assertions

## 🎨 Customization

### Design Tokens
All styling uses CSS custom properties from your SDStoken system:
- Colors: `--navy-700`, `--gray-400`, `--red-100`, etc.
- Typography: `--font-family-inter`, `--font-size-sm`, etc.
- Spacing: `--spacing-2xs`, `--spacing-xl`, etc.
- Borders: `--border-radius-lg`, `--border-width-xs`, etc.

### Theme Support
- **Light mode**: Default theme with light backgrounds
- **Dark mode**: Dark theme with proper contrast ratios
- **Smooth transitions**: CSS transitions between themes
- **Persistent preference**: Remembers user's theme choice

## 📞 Support

For questions or issues:
1. Check the demo pages for examples
2. Review the design token integration
3. Test accessibility with keyboard navigation
4. Verify responsive behavior on mobile devices

## 🚀 Deployment Notes

### GitHub Pages
- **Free hosting**: No credit card required
- **Custom domain**: Free custom domain support
- **HTTPS**: Automatic SSL certificate
- **Easy setup**: Just push to GitHub and enable Pages

### Vercel
- **Free tier**: Generous limits for personal projects
- **Auto-deploy**: Deploys on every Git push
- **Custom domains**: Free custom domain support
- **Analytics**: Basic analytics included

### Surge.sh
- **Completely free**: No limits for static sites
- **Simple deployment**: One command to deploy
- **Custom domains**: Supported
- **Fast CDN**: Global content delivery

---

**Ready to deploy?** Choose GitHub Pages for the easiest free deployment! 🎉
