# Robert Mao - Personal Portal

A modern, responsive about.me style personal portal showcasing your profile, skills, experience, and contact information.

## Features

- **Hero Section** - Eye-catching introduction with animated background
- **About Section** - Tell your story with stats showcase
- **Skills Section** - Display your expertise with icon cards
- **Experience Timeline** - Professional journey in an elegant timeline
- **Contact Section** - Social links and contact information
- **Fully Responsive** - Perfect on mobile, tablet, and desktop
- **Smooth Animations** - Engaging user experience
- **Single File** - Everything in one HTML file for easy deployment

## Quick Start

1. Open `index.html` in a text editor
2. Find the `config` object (around line 450)
3. Update your personal information
4. Save and open in a browser

## Customization Guide

### Hero Section
```javascript
hero: {
    name: "Your Name",
    profilePhoto: "path/to/your/photo.jpg",
    tagline: "Your Professional Title",
    description: "Your introduction text"
}
```

### About Section
```javascript
about: {
    text1: "First paragraph about you",
    text2: "Second paragraph about you",
    stats: [
        { number: "10+", label: "Years Experience" },
        { number: "50+", label: "Projects Completed" },
        // Add more stats...
    ]
}
```

### Skills
```javascript
skills: [
    { icon: "💻", name: "Web Development" },
    { icon: "📱", name: "Mobile Apps" },
    // Add your skills with emoji icons
]
```

### Experience
```javascript
experience: [
    {
        date: "2020 - Present",
        title: "Job Title",
        company: "Company Name",
        description: "What you did in this role"
    },
    // Add more positions...
]
```

### Social Links
```javascript
social: [
    { icon: "💼", url: "https://linkedin.com/in/yourusername" },
    { icon: "💻", url: "https://github.com/yourusername" },
    // Add your social profiles
]
```

### Contact Information
```javascript
contact: {
    email: "your.email@example.com",
    location: "Your City, Country"
}
```

## Color Customization

To change the color scheme, edit the CSS gradient in the `<style>` section:

```css
/* Main gradient (Hero & Contact sections) */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

Try these color combinations:
- Sunset: `#f83600 0%, #f9d423 100%`
- Ocean: `#2E3192 0%, #1BFFFF 100%`
- Forest: `#134E5E 0%, #71B280 100%`
- Midnight: `#232526 0%, #414345 100%`

## Sections

### Hero
- Profile photo with floating animation
- Name and tagline
- Description
- Call-to-action buttons
- Animated background pattern

### About
- Two-column layout (text + stats)
- Customizable stat cards with numbers and labels
- Responsive design

### Skills
- Grid layout with icon cards
- Hover effects
- Fully customizable icons and names

### Experience
- Vertical timeline design
- Alternating left/right layout (desktop)
- Single column on mobile
- Dot indicators and connecting line

### Contact
- Social media icon links
- Email and location
- Gradient background matching hero

## Deployment

### Netlify
1. Drag and drop `index.html` to Netlify
2. Your site is live!

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts

### GitHub Pages
1. Commit `index.html` to your repo
2. Go to Settings > Pages
3. Select your branch and save
4. Your site will be live at `username.github.io/repo-name`

## Tips

1. **Profile Photo**: Use a square image (1:1 ratio) for best results
2. **Icons**: Use emojis or replace with SVG icons
3. **Content**: Keep descriptions concise and impactful
4. **Stats**: Update with your real numbers for credibility
5. **Links**: Make sure all URLs are correct and working

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

Free to use and modify for personal or commercial projects.

---

Built with ❤️ - No frameworks, no dependencies, just pure HTML, CSS, and JavaScript.
