# Valentine's Day 2026 Plan 💕

A simple, beautiful single-page website to display our Valentine's Day itinerary.

## Features

- Clean, romantic design with gradient backgrounds
- Responsive layout that works on all devices
- Easy to update activities by editing `index.html`
- No backend or database required
- Ready to deploy to Vercel

## Local Development

Simply open `index.html` in your browser to see the site.

## Deployment to Vercel

### Option 1: Using Vercel CLI

```bash
# Install Vercel CLI (if not already installed)
npm i -g vercel

# Deploy
vercel
```

### Option 2: Using Vercel Website

1. Go to [vercel.com](https://vercel.com)
2. Click "Add New Project"
3. Import this Git repository
4. Click "Deploy"

## Customizing Your Plan

Edit the activities in `index.html`. Each activity follows this structure:

```html
<li class="activity">
    <div class="activity-time">TIME HERE</div>
    <div class="activity-title">ACTIVITY NAME</div>
    <div class="activity-description">
        Description of what you'll do.
    </div>
</li>
```

You can add, remove, or modify activities as needed.
