# Pendota Mani - Portfolio Website

Single-file portfolio ready for deployment to Vercel or any static host.

## Files
- `index.html`: Complete website with embedded HTML, CSS, and JS (no external frameworks or dependencies).
- `package.json`: Project manifest for Vercel/Node environment.
- `vercel.json`: Clean URL routing configuration for Vercel.

## Placeholders to update in `index.html`:
1. **Google Form iframe**: Search for `<!-- PLACEHOLDER: Paste your Google Form embed iframe here -->` and insert your Google Form embed snippet into the `#form-container` div.
2. **Workflow Videos**: Place `LeadFlow.mp4` and `InstantAlert.mp4` in the project root, or update the `<source src="...">` tags with direct links.
3. **Email**: Replace `your-email@domain.com` in the Contact section with your real email.

## Deploying to Vercel:
### Option 1: Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option 2: GitHub + Vercel Dashboard
1. Push this folder to a GitHub repository.
2. Go to [vercel.com](https://vercel.com) -> **Add New Project** -> Import your GitHub repository.
3. Click **Deploy**.
