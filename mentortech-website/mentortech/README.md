# MentorTech A.C. — Website

**Empowering Talents, Transforming Futures**  
Ciudad Juárez, Chihuahua · México · mentortech.org

---

## Structure

```
mentortech/
├── index.html                  ← Home
├── css/style.css               ← All styles
├── js/main.js                  ← Scroll reveal, nav, interactions
├── pages/
│   ├── mision.html             ← Mission & Vision
│   ├── nosotros.html           ← About Us
│   ├── contacto.html           ← Get in Touch
│   ├── noticias.html           ← News
│   └── oportunidades.html      ← Current Opportunities
└── .github/workflows/deploy.yml ← Auto-deploy to GitHub Pages
```

---

## Hosting Options (Free)

### 1. GitHub Pages ⭐ Recommended
- Free, reliable, supports custom domains (mentortech.org)
- Auto-deploys on every push via included GitHub Action

**Steps:**
1. Create a GitHub account at github.com
2. Create a new **public** repository named `mentortech` (or `mentortech-website`)
3. Upload all files (drag & drop in browser, or use Git)
4. Go to **Settings → Pages → Source → GitHub Actions**
5. Push to `main` branch → auto-deploys
6. URL: `https://yourusername.github.io/mentortech/`

**Custom domain (mentortech.org):**
1. Add a file named `CNAME` with content: `mentortech.org`
2. In your domain registrar, add a CNAME record pointing to `yourusername.github.io`

---

### 2. Netlify (Alternative free option)
- Drag & drop the folder at netlify.com/drop
- Instant URL, supports custom domains
- No account needed for quick test

### 3. Vercel
- Import GitHub repo at vercel.com
- Automatic HTTPS, fast CDN
- Free for personal/nonprofit use

### 4. Cloudflare Pages
- Free, very fast CDN
- Connect GitHub repo at pages.cloudflare.com
- Good if you use Cloudflare for DNS already

---

## Contact Form Setup

The contact form in `pages/contacto.html` uses Formspree.
1. Create a free account at formspree.io
2. Create a new form → copy the form ID
3. In `contacto.html`, replace `your-form-id` in the action URL:
   ```html
   action="https://formspree.io/f/YOUR-FORM-ID"
   ```
Free tier: 50 submissions/month. More than enough for MentorTech.

---

## Fonts Used
- **Syne** (headings) — Google Fonts
- **DM Sans** (body) — Google Fonts

Both load via CDN, no installation needed.

---

*Para uso interno del equipo · mentortech.org*
