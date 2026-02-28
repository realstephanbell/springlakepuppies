# SpringLakePuppies.com — Setup Guide

## File Structure
```
springlakepuppies/
├── index.html
├── style.css
├── README.md
└── articles/
    └── best-grooming-tools-cockapoos.html
```

---

## Step 1 — Connect Netlify

1. Go to [netlify.com](https://netlify.com) and create a free account
2. Click **Add new site → Import an existing project → GitHub**
3. Authorize Netlify and select the `springlakepuppies` repository
4. Leave all build settings blank (no build command needed — plain HTML)
5. Click **Deploy site**
6. Your site will be live at a Netlify URL in ~30 seconds

---

## Step 2 — Connect Your Domain (Squarespace → Netlify)

### In Netlify:
1. Go to **Site settings → Domain management → Add custom domain**
2. Type: `springlakepuppies.com`
3. Copy the A record and CNAME values Netlify gives you

### In Squarespace:
1. Go to **Domains** in your Squarespace account
2. Click `springlakepuppies.com` → **DNS Settings**
3. Delete existing A records pointing to Squarespace
4. Add the A record and CNAME from Netlify
5. Save — DNS updates within 1–2 hours (up to 48 max)

After this, cancel your Squarespace website plan. Keep the domain registration only (~$20/year).

---

## Step 3 — Add Amazon Affiliate Links

Replace `YOUR_AFFILIATE_LINK_HERE` in any article file with your real Amazon Associates link.

Get affiliate links from the SiteStripe bar at the top of any Amazon product page while logged into Associates.

---

## Step 4 — Adding New Articles

1. Copy `articles/best-grooming-tools-cockapoos.html`
2. Rename and update the content
3. Add a card to `index.html` pointing to the new article
4. Commit to GitHub — Netlify auto-deploys in ~30 seconds

---

## Suggested Next Articles
1. best-toys-cockapoos.html
2. cocker-spaniel-ear-care.html
3. best-dog-food-cockapoos.html
4. cockapoo-puppy-essentials-checklist.html
5. best-harnesses-poodles.html
