# Nathalie Nicole — Portfolio (Vite + React + Tailwind)

This is a ready-to-deploy portfolio project built with Vite, React and TailwindCSS.
It is modeled to look and feel like a LinkBuilder-style website and includes:
- Hero, Approach, Case Studies, Pricing, Contact CTA
- Contact form (mailto fallback + Formspree placeholder)
- Meta tags and Open Graph tags
- Instructions to deploy on Vercel / Netlify

## Quick start
1. Install dependencies: `npm install`
2. Run dev server: `npm run dev`
3. Build: `npm run build`
4. Preview production build: `npm run preview`

## Deploying
- **Vercel**: Connect the repository or upload this project. Vercel detects Vite automatically.
- **Netlify**: Drag & drop the `dist/` folder after running `npm run build`, or connect repo. Build command: `npm run build`, Publish directory: `dist`

## Contact form (Formspree)
The contact form in the project uses a mailto fallback. To enable Formspree replace the `FORM_ENDPOINT` in `src/components/ContactForm.jsx` with your Formspree endpoint.

## Domain / URL
Recommended domain: nathalienicole-seo.com

To use `nathalienicole-seo.com` with Vercel or Netlify, see the DNS notes at the bottom of this file.

-- Generated for: Nathalie Nicole (nathalienicole.seo@gmail.com)


## DNS / Domain steps for nathalienicole-seo.com

1. Buy the domain `nathalienicole-seo.com` via a registrar (Namecheap, GoDaddy, etc.).
2. In Vercel, go to Domains -> Add `nathalienicole-seo.com` and follow the steps. Add the DNS records Vercel gives.
3. Or in Netlify, add the domain under Site settings -> Domain management and follow their steps.
4. Wait for DNS propagation; SSL will be issued automatically by the hosting platform.
