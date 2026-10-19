# Rahel Seyum: portfolio site

## Put it online with GitHub Pages (about 15 minutes)

1. Create a free account at github.com.
2. Click **New repository**. Name it exactly `YOUR-USERNAME.github.io` and set it to **Public**.
3. Click **uploading an existing file** and drag in `index.html`, `resume.pdf` and `rahel-seyum.jpg`. Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Branch", pick `main` and `/ (root)`, then **Save**.
5. After 1–2 minutes your site is live at `https://YOUR-USERNAME.github.io`.

## Use your own domain (optional, about $10–20 a year)

1. Buy a domain, for example `rahelseyum.com`, from Cloudflare, Porkbun or Namecheap.
2. In your domain's DNS settings, add:
   - Four **A** records for `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - One **CNAME** record for `www` pointing to `YOUR-USERNAME.github.io`
3. In GitHub, go to **Settings → Pages → Custom domain**, type your domain and save.
4. When it becomes available, tick **Enforce HTTPS**.

## Edit the site

- **Add LinkedIn:** in `index.html`, search for `Add your LinkedIn`, remove the `<!--` and `-->` around that line, and put in your profile address.
- **Link a finished audit:** upload the report PDF, then in the matching case study change the status to "Read the report" and add a link such as `<a href="citylights-audit.pdf">Read the CityLights audit (PDF)</a>`.
- **Update your résumé:** upload a new file with the same name, `resume.pdf`.

## Before you share it

Test it yourself and keep the evidence for interviews:
- Run axe DevTools and WAVE (an automated axe scan already passes with no WCAG 2.1 A/AA issues).
- Tab through the whole page with the keyboard only.
- Read it with NVDA, and zoom to 200%.
