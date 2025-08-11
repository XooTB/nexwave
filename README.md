# NexWave SaaS Website

A modern, professional SaaS website built with Astro and TailwindCSS. NexWave is an AI-powered business automation platform designed to streamline operations and boost productivity.

## 🚀 Features

- **Modern Design**: Clean, professional UI with a cohesive brand identity
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Pages Included**:
  - Home (hero, features, testimonials, pricing preview)
  - Features (detailed feature breakdown)
  - Pricing (tiered pricing plans with billing toggle)
  - About Us (company mission, team, timeline)
  - Contact (contact form with company information)
  - Sign Up / Sign In (authentication UI mockups)
- **Interactive Elements**: Smooth animations, hover effects, and form interactions
- **Brand Identity**: Consistent color palette, typography, and design system
- **Performance**: Built with Astro for optimal loading speeds

## 🎨 Design System

### Colors
- **Primary**: Blue gradient (#3b82f6 to #1d4ed8)
- **Secondary**: Neutral grays (#f8fafc to #020617)
- **Accent**: Purple gradient (#d946ef to #a21caf)

### Typography
- **Display Font**: Space Grotesk (headings)
- **Body Font**: Inter (body text)

## 🛠️ Tech Stack

- **Framework**: Astro 5.0
- **Styling**: TailwindCSS 3.4
- **Language**: TypeScript
- **Forms**: TailwindCSS Forms
- **Typography**: TailwindCSS Typography

## 📦 Installation

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

4. Preview production build:
```bash
npm run preview
```

## 📁 Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Button.astro
│   │   ├── FeatureCard.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   └── TestimonialCard.astro
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── pages/
│   │   ├── index.astro (Home)
│   │   ├── features.astro
│   │   ├── pricing.astro
│   │   ├── about.astro
│   │   ├── contact.astro
│   │   ├── signup.astro
│   │   └── signin.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── tailwind.config.mjs
├── tsconfig.json
└── package.json
```

## ✨ Key Features

### Interactive Elements
- Smooth scroll animations with Intersection Observer
- Mobile-responsive navigation with hamburger menu
- Interactive pricing toggle (monthly/annual)
- Form validation and submission handling
- Password visibility toggles
- Hover effects and transitions

### Professional Content
- Realistic company information and testimonials
- Comprehensive feature descriptions
- Tiered pricing with clear value propositions
- Team profiles with social links
- Company timeline and milestones

### Accessibility
- Semantic HTML structure
- Proper ARIA labels
- Keyboard navigation support
- Focus management
- Color contrast compliance

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📱 Responsive Breakpoints

- Mobile: 640px and below
- Tablet: 641px to 1024px
- Desktop: 1025px and above

## 🚀 Deployment

This project is ready for deployment to any static hosting service:

- **Vercel**: Connect your repository and deploy automatically
- **Netlify**: Drag and drop the `dist` folder
- **GitHub Pages**: Enable Pages in repository settings
- **Cloudflare Pages**: Connect repository for automatic deployments

## 📄 License

This project is for demonstration purposes. Feel free to use it as a template for your own SaaS websites.

---

Built with ❤️ using Astro and TailwindCSS