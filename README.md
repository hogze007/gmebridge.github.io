
# GME Bridge — Static Site (GitHub Pages)

## Quick Deploy (no monthly hosting fees)
1) Create a GitHub account and a public repo named **gmebridge.github.io** (or your-username.github.io).
2) Upload all files from this folder to the repo root (drag & drop in GitHub web).
3) Go to **Settings → Pages** and ensure the branch is **main / root**.
4) Your site will be live at https://gmebridge.github.io (replace with your username).

## Custom Domain (Cloudflare DNS)
- Add your domain (e.g., gmebridge.com) to Cloudflare (Free plan).
- DNS records:
  - **A** @ → 185.199.108.153
  - **A** @ → 185.199.109.153
  - **A** @ → 185.199.110.153
  - **A** @ → 185.199.111.153
  - **CNAME** www → gmebridge.github.io
- In GitHub repo, create a file named **CNAME** with a single line: `gmebridge.com`

## Email Forwarding (free)
- In Cloudflare, use **Email Routing** to forward **mhegazi@gmebridge.com** to your existing mailbox.
- Or use your registrar's free email forwarding.

## Edit Content
- Edit the HTML pages with any text editor. CSS at `assets/css/style.css`.
- Replace phone/email/location in `footer` and contact page.

---
Made for a fast, clean launch. No backend, no cookies.
