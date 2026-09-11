# Bharat AI Summit 2026 — Invitation Website

Single-file website — sirf `index.html`. Koi login, koi backend, koi build-step nahi chahiye.

## VS Code me kholna
1. Is folder ko VS Code me open karein.
2. `index.html` par right-click → **Open with Live Server** (agar extension installed hai), ya seedha browser me double-click karke file open kar lein.

## Deploy karne ke options (sabse aasan)

### Option 1 — Netlify Drop (sabse fast, free)
1. https://app.netlify.com/drop kholein.
2. Is folder ko drag-and-drop karein.
3. Turant ek live URL mil jayega, jise aap apne domain (bharatcxo.com ya subdomain) se connect kar sakte hain.

### Option 2 — Vercel
1. `npm i -g vercel` (ek baar)
2. Folder ke andar terminal me: `vercel`
3. Prompts follow karein — free hosting mil jayega.

### Option 3 — GitHub Pages
1. Is folder ko GitHub repo me push karein.
2. Repo → Settings → Pages → Branch select karke Save karein.
3. `https://<username>.github.io/<repo>/` par live ho jayega.

## Customize karna ho to
- Sab kuch ek hi file `index.html` me hai (HTML + CSS + JS).
- Colors `:root { }` block ke top me CSS variables se control hote hain (`--maroon`, `--gold`, `--parchment`).
- "Add to calendar" button ek `.ics` file download karta hai — event date/time already 30 Sept 2026, 1:30–5:00 PM IST set hai.
- Footer me `bharatcxo.com` link already add hai.

Mobile-first design hai — chhoti screen se lekar desktop tak test kiya hua hai.
