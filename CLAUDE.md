# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A static single-page Valentine's Day itinerary website. No backend, no build process, no dependencies - just pure HTML/CSS.

## Architecture

- **index.html**: Single-file website containing all HTML, CSS (inline), and content
- **vercel.json**: Minimal Vercel configuration for deployment
- All styling is embedded in the HTML file using a `<style>` tag
- Activities are hardcoded in the HTML as list items

## Editing Activities

Activities are stored in the `<ul class="activities">` section of index.html. Each activity uses this structure:

```html
<li class="activity">
    <div class="activity-time">TIME</div>
    <div class="activity-title">TITLE</div>
    <div class="activity-description">DESCRIPTION</div>
</li>
```

To modify the itinerary, edit these list items directly in index.html.

## Deployment

Deploy to Vercel using:
```bash
vercel
```

Or connect the Git repository through the Vercel web dashboard.

## Design Notes

- Pink/rose color scheme with gradients
- Responsive design works on mobile and desktop
- Hover animations on activity cards
- No JavaScript required - pure HTML/CSS
