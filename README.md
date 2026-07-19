# Alexandra Grace — Personal Pilates, London

A single-page lead-generation site. Everything is in `index.html` (no build step, no dependencies).

## Put it live with GitHub Pages

### Option A — no terminal (easiest)
1. Go to the repo on github.com → **Add file → Upload files**.
2. Drag in `index.html` (must be named exactly that, in the repo root).
3. **Commit changes** to the `main` branch.
4. Go to **Settings → Pages** → under *Build and deployment*, set **Source: Deploy from a branch**, **Branch: main / (root)** → **Save**.
5. Wait ~1 minute. Your site is live at `https://joejeffery4.github.io/AlexandraGrace/`.

### Option B — terminal
```bash
git clone https://github.com/joejeffery4/AlexandraGrace.git
cd AlexandraGrace
# copy index.html into this folder, then:
git add index.html
git commit -m "Add Pilates landing page"
git push origin main
```
Then enable Pages as in step 4 above.

## The enquiry form
- By default, pressing **Send enquiry** opens the visitor's email app, pre-addressed to `aglivermore@hotmail.co.uk`.
- For a tidier inbox (no email pop-up), create a free form endpoint at [web3forms.com](https://web3forms.com) or [formspree.io](https://formspree.io) and paste it into `FORM_ENDPOINT` near the bottom of `index.html`.

## Still to add
- Three client testimonials (search the file for `[Add a`).
- A portrait photo of Alexandra (two spots marked in the file: the hero panel and the About section).

## Custom domain (optional)
In **Settings → Pages → Custom domain**, add a domain you own (e.g. `alexandragrace.co.uk`) and follow the DNS steps GitHub shows.
