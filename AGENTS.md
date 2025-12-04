# Developer Portfolio

A modern, responsive portfolio template for developers and freelancers built with Next.js 16, React 19, and Tailwind CSS 4.

## Tech Stack

- **Framework**: Next.js 16 (App Router)
- **UI Library**: React 19
- **Styling**: Tailwind CSS 4, SASS
- **Animations**: Lottie React
- **Package Manager**: npm
- **Build Output**: `.next`
- **Dev Port**: 3000

## Available Skills

| Skill | Description |
|-------|-------------|
| `build-and-deploy` | Build and deploy to Vercel or Netlify |

## Project Structure

```
├── app/              # Next.js App Router pages
├── components/       # React components
├── utils/data/       # Portfolio content configuration
│   ├── personal-data.js
│   ├── experience.js
│   ├── projects-data.js
│   ├── skills.js
│   └── educations.js
├── public/           # Static assets
└── .claude/skills/   # AI agent skills
```

## Quick Commands

```bash
# Install dependencies
npm install

# Development
npm run dev

# Build
npm run build

# Start production
npm start
```

## Customization

Edit files in `utils/data/` to customize your portfolio content:

1. **personal-data.js** - Name, bio, contact info, social links
2. **experience.js** - Work history
3. **projects-data.js** - Portfolio projects
4. **skills.js** - Technical skills
5. **educations.js** - Education background

## Features

- Fully responsive design
- SEO optimized with Next.js Metadata API
- Contact form with Email/Telegram notifications
- Blog integration from dev.to
- Dark gradient theme with Lottie animations
- Docker support
