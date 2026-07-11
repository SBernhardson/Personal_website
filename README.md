# Shane Bernhardson — Sports Science Website

Built with Hugo + Netlify CMS. Deploy to Netlify for free hosting with a blog editor at `/admin`.

---

## 🚀 Setup (one-time, ~15 minutes)

### Step 1 — Push to GitHub
1. Go to [github.com](https://github.com) and click **New repository**
2. Name it `shane-site` (or anything you like), keep it **Public**
3. Don't initialize with README (you already have one)
4. Upload all these files: drag the folder contents into the GitHub UI, or use GitHub Desktop

### Step 2 — Deploy on Netlify
1. Go to [netlify.com](https://netlify.com) and sign up (free)
2. Click **Add new site → Import an existing project**
3. Choose **GitHub** and select your `shane-site` repo
4. Build settings will auto-detect from `netlify.toml` — just click **Deploy**
5. Your site goes live at a URL like `https://random-name-123.netlify.app`

### Step 3 — Enable the Blog CMS
1. In Netlify dashboard → **Site settings → Identity → Enable Identity**
2. Scroll to **Registration** → set to **Invite only**
3. Go to **Services → Git Gateway → Enable Git Gateway**
4. Go to **Identity tab → Invite users** → enter your email
5. Check your email, accept the invite, set a password

That's it. Your blog editor is now live at `yoursite.netlify.app/admin`

---

## ✍️ Writing a Blog Post

1. Go to `yoursite.netlify.app/admin`
2. Log in with your email and password
3. Click **Blog Posts → New Blog Post**
4. Fill in: Title, Date, Category, Excerpt, Emoji Icon, and Body
5. Click **Publish** — the site rebuilds automatically in ~30 seconds

---

## ✏️ Editing Site Content

To change your name, role, university, email, or other details:
- Open `hugo.toml` in GitHub
- Edit the values under `[params]`
- Commit the change — Netlify rebuilds automatically

---

## 📁 Project Structure

```
shane-site/
├── hugo.toml              # Site config (name, role, email, etc.)
├── netlify.toml           # Build settings for Netlify
├── content/
│   ├── about.md           # About page
│   ├── contact.md         # Contact page
│   └── posts/             # Blog posts live here
│       ├── 2026-05-08-rethinking-vo2-max.md
│       └── ...
├── layouts/               # HTML templates
├── static/
│   ├── css/main.css       # All site styles
│   └── admin/             # Netlify CMS files
└── README.md
```

---

## 🎨 Customizing the Design

All colors, fonts, and spacing are in `static/css/main.css`.
The accent color is `--accent: #4169e1` (royal blue) — change that one variable to retheme the whole site.
