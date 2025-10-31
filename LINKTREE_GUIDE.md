# Linktree-Style Website Guide

## Overview
This is a simple, modern Linktree-style landing page that displays your profile and important links in one place.

## Features
- ✨ Clean, modern design with gradient background
- 📱 Fully responsive (works on mobile, tablet, and desktop)
- 🎨 Smooth animations and hover effects
- ⚡ Fast loading (single HTML file, no dependencies)
- 🔧 Easy to customize

## How to Customize

All customization is done in the `index.html` file. Look for the `config` object in the `<script>` section:

### 1. Update Profile Information
```javascript
const config = {
    name: "Your Name",
    bio: "Your bio or tagline",
    profileImage: "url-to-your-image.jpg",
    // ...
};
```

### 2. Add/Edit Links
```javascript
links: [
    {
        title: "Link Title",
        url: "https://your-url.com",
        icon: "🔗" // Any emoji works!
    },
    // Add more links...
]
```

### 3. Customize Colors
To change the gradient background, edit the CSS in the `<style>` section:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

You can use any colors you like! Try these gradient generators:
- [uiGradients](https://uigradients.com/)
- [CSS Gradient](https://cssgradient.io/)

## Deployment

### Option 1: Static Hosting
Upload `index.html` to any static hosting service:
- Netlify
- Vercel
- GitHub Pages
- Cloudflare Pages

### Option 2: Use with Hugo
The existing Hugo setup can coexist with this file, or you can integrate it into your Hugo theme.

## Tips

1. **Profile Image**: Use a square image (1:1 ratio) for best results
2. **Icons**: You can use emojis or replace with SVG icons
3. **Links**: Add as many or as few links as you want
4. **Mobile**: The design automatically adapts to smaller screens

## Need Help?

The entire website is contained in a single `index.html` file, making it easy to understand and modify. All the code is commented and organized into clear sections.
