# ARTIFACT — Website

## Structure
```
artifact-site/
├── public/
│   ├── index.html        ← Main landing page
│   └── assets/           ← Drop images/logos here
└── vercel.json           ← Vercel config
```

## Deploying to Vercel

### First time
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in this folder
3. Follow the prompts — done

### Or drag & drop
1. Zip this entire folder
2. Go to vercel.com/new
3. Drag the zip onto the page

## Adding your product image
Replace the placeholder in the hero section:
- Open `public/index.html`
- Find `[ Product Image — Replace ]`
- Add your image to `public/assets/`
- Replace the placeholder div with: `<img src="/assets/your-image.png" ...>`

## Updating content
All copy is in `public/index.html` — search for the
text you want to change and edit directly.

## Adding pages (future)
- `public/work.html`     ← Portfolio / case studies
- `public/about.html`    ← Extended about page
- `public/contact.html`  ← Standalone contact
