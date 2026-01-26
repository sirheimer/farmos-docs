# Juice Platform Documentation

Customer-facing documentation for the Juice automated organic distribution platform.

## Overview

This documentation is built with [Mintlify](https://mintlify.com/) and covers all aspects of using Juice for TikTok content creation, account management, and organic growth.

## Documentation Structure

```
juice-docs/
├── introduction.mdx              
├── quickstart.mdx                
├── essentials/                   
├── brand-hub/                    
├── templates/                    
├── content-creation/             
├── accounts/                     
├── posting/                      
├── assets/                       
├── analytics/                    
└── faq.mdx                       
```

**Total: 42 documentation pages**

## Key Documentation Sections

### 🎯 Most Important

1. **content-creation/** - 9 pages covering the AI content generator (most complex feature)
2. **accounts/** - 5 pages explaining account types, warmup, and lifecycle
3. **essentials/** - 3 pages on strategy and how Juice works

### 📚 Supporting

- **brand-hub/** - Brand Kit setup and management
- **templates/** - Template selection and customization
- **posting/** - How automated posting works
- **assets/** - Media library management
- **analytics/** - Performance tracking

## Local Development

### Setup

```bash
# Install Mintlify CLI
npm install -g mintlify

# Navigate to docs directory
cd juice-docs

# Start local dev server
mintlify dev
```

**Opens at:** http://localhost:3000

### Preview Changes

Any changes to `.mdx` files hot-reload automatically in the browser.

## Deployment

### To Mintlify Hosting

```bash
# From juice-docs directory
mintlify deploy
```

**Live URL:** https://docs.juice.co (or your configured domain)

### To Custom Hosting

Mintlify can export static files:

```bash
mintlify build
```

Outputs to `_site/` directory for hosting on:
- Vercel
- Netlify
- AWS S3
- Any static host

## Configuration

**mint.json** contains:
- Site navigation structure
- Brand colors (#4EEC5D primary green)
- Logo/favicon paths
- Top bar links
- Footer socials

**To modify navigation:** Edit `mint.json` → `navigation` array

## Content Guidelines

**Tone:** Conversational, helpful, non-technical  
**Audience:** Marketing managers, not developers  
**Format:** Short paragraphs, bullets, visual examples  
**Goal:** Help users succeed with Juice, not just list features  

## Adding New Pages

1. Create `.mdx` file in appropriate folder
2. Add frontmatter (title, description)
3. Write content using Mintlify components
4. Add to `mint.json` navigation
5. Test locally with `mintlify dev`

## Mintlify Components Used

- `<Steps>` - Step-by-step instructions
- `<Accordion>` - Collapsible FAQ items
- `<Card>` - Linked cards
- `<CardGroup>` - Card grid layouts
- `<Tabs>` - Tabbed content
- `<Tip>`, `<Warning>`, `<Info>` - Callouts

## Maintenance

**Update schedule:**
- Monthly: Review analytics section for new features
- Quarterly: Update screenshots and examples
- As needed: Add pages for new features

## Assets Needed

**Before deploying, add:**
- `/logo/light.svg` - Juice logo (light mode)
- `/logo/dark.svg` - Juice logo (dark mode)
- `/favicon.svg` - Favicon
- Screenshots for each page (add to `/images/` folder)

## Questions?

Contact: docs@juice.co

## License

© 2026 Juice. All rights reserved.
