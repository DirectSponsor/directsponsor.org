# DirectSponsor.org Website

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/DirectSponsor/directsponsor.org)

**Live site: [directsponsor.org](https://directsponsor.org/)**

Static website for the Direct Sponsor Society charity organization.

## Current Status (2025-06-23)

✅ **Completed:**
- Hero section with simplified background image (no parallax)
- Mobile-responsive 4-column project grid using floats
- Lightweight CSS with em measurements for accessibility
- Clean, performant design optimized for fast loading
- Successfully deployed to production

## Features
- Mobile-responsive design with float-based layout for compatibility
- Project showcase cards with hover effects and accessibility features
- Hero section with creature image and positioned overlay text
- Lightweight CSS with em measurements
- Clean, minimal structure

## Structure
- `index.html` - Main homepage with hero section and Articles of Association
- `assets/style.css` - Single CSS file with responsive design
- `assets/evolved.jpg` - Hero background image
- `assets/*.png` - Project icon images
- `deploy.sh` - Deployment script for DirectAdmin hosting

## Development URLs
- Local testing: http://satoshihost.ddns.net/warp/projects/directsponsor/org-site/
- Production: https://directsponsor.org/
- Main dev index: http://satoshihost.ddns.net/ (includes link to org-site)

## Recent Changes
- Removed parallax scrolling effect for better performance and image visibility
- Repositioned hero content to upper portion to show creature emerging from water
- Moved "Apologies to creationists" text to bottom overlay, eliminating wasted space
- Simplified CSS structure and removed JavaScript dependencies

## Deployment
Run `./deploy.sh` to deploy to DirectAdmin shared hosting.

## Technical Notes
- Uses `background-attachment: fixed` for stable hero image
- Float-based grid system for maximum browser compatibility
- Semi-transparent hero content overlay for readability
- Em-based measurements throughout for accessibility
- No JavaScript dependencies for lightweight loading

## Next Potential Tasks
- Content updates or additions as needed
- Further mobile optimization if required
- Additional pages using the same clean structure
