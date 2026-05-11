# 🌵 Desert Sky Events — Official Website

> Party rentals for the High Desert · Victorville, CA  
> Live site: [desertskyevents.github.io](https://desertskyevents.github.io)

---

## 📋 About

This is the official website for **Desert Sky Events**, a party rental company serving Victorville, Apple Valley, Hesperia, and the surrounding High Desert area of California.

Services offered:
- 🏰 Jumpers & Bounce Houses
- ⛺ Tents & Canopies (20×20, 20×30, 20×40)
- 🪑 Tables & Chairs
- ⚡ Add-Ons (Generator, Table Cloths, Chafing Dishes, Posters)
- 📷 Event Photography
- 📦 Packages & Bundles

---

## 🗂️ File Structure

```
desertskyevents.github.io/
│
├── index.html          ← The entire website (one file)
├── README.md           ← You're reading this
│
└── images/             ← All your photos go here
    ├── dse-logo.png
    ├── 8J2A6797.JPEG
    ├── 8J2A6813.JPEG
    ├── 8J2A6814.JPEG
    ├── 8J2A6815.JPEG
    ├── 8J2A6818.JPEG
    ├── Desert_Sky_Events.jpg
    ├── Desert_Sky_Events_Jumper_7.jpg
    ├── Desert_Sky_Events__1_.jpg
    ├── IMG_5965.jpg
    ├── IMG_5971.jpg
    ├── IMG_5973.jpg
    ├── IMG_5981.jpg
    ├── IMG_5984.jpg
    ├── IMG_5997.jpg
    ├── IMG_6000.jpg
    ├── IMG_6003.jpg
    └── IMG_6009.jpg
```

---

## 🚀 How to Deploy (GitHub Pages)

### Step 1 — Create the Repository
1. Go to [github.com](https://github.com) and sign in
2. Click the **+** icon → **New repository**
3. Name it exactly: `desertskyevents.github.io`
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload Your Files
1. Inside the repo, click **Add file → Upload files**
2. Upload `index.html` and `README.md` to the root
3. Create an `images/` folder and upload all photos inside it
   - To create the folder: drag a photo and type `images/` before the filename

### Step 3 — Turn on GitHub Pages
1. Go to your repo → **Settings** (top tab)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **main** branch → **/ (root)**
4. Click **Save**
5. Wait ~60 seconds → your site is live at:

```
https://desertskyevents.github.io
```

---

## 📬 Setting Up the Quote Form (Formspree)

The contact form uses [Formspree](https://formspree.io) — free, no backend needed.

1. Go to [formspree.io](https://formspree.io) and create a free account
2. Click **+ New Form** → name it "DSE Quote Requests"
3. Copy your **Form ID** (looks like: `xbjvkpqr`)
4. Open `index.html` and find this line:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
5. Replace `YOUR_FORM_ID` with your real ID:
   ```html
   <form action="https://formspree.io/f/xbjvkpqr" method="POST">
   ```
6. Save and re-upload `index.html` to GitHub
7. Quote form submissions will now go straight to your email ✅

> Free tier allows **50 submissions/month** — plenty to start.

---

## 🌐 Adding a Custom Domain (Optional)

When you're ready for `desertskyevents.com` (~$12/year):

1. Buy the domain from [Google Domains](https://domains.google) or [Namecheap](https://namecheap.com)
2. In your domain provider's DNS settings, add:
   ```
   Type: CNAME
   Name: www
   Value: desertskyevents.github.io
   ```
3. In GitHub → Settings → Pages → enter your domain under **Custom domain**
4. Check **Enforce HTTPS** — GitHub gives you a free SSL certificate

---

## ✏️ How to Make Changes

Everything is in `index.html`. To update content:

| What to change | Where to find it |
|---|---|
| Phone number | Search `(760) 258-7380` — appears in nav, footer, hero |
| Prices | Search the dollar amount e.g. `$150` |
| Package contents | Search the package name e.g. `Kids Party` |
| Photos | Replace files in the `images/` folder with same filename |
| Social links | Search `instagram.com` or `tiktok.com` |
| Service area cities | Search `Victorville` |
| Colors | Search `:root {` at top of CSS — all colors are variables |

After any change:
1. Edit the file
2. Re-upload to GitHub (drag and drop over the old file)
3. Site updates automatically in ~30 seconds

---

## 📱 Contact & Socials

| Platform | Handle |
|---|---|
| 📞 Phone | (760) 258-7380 |
| ✉️ Email | desertskyevents@gmail.com |
| 📸 Instagram | [@desert_sky._event](https://www.instagram.com/desert_sky._event) |
| 🎵 TikTok | [@desert_sky_events](https://www.tiktok.com/@desert_sky_events) |
| 👍 Facebook | Desert Sky Event |

---

## 🗺️ Service Area

Victorville · Apple Valley · Hesperia · Adelanto · High Desert, CA

---

*Built with HTML, CSS & JavaScript · Hosted on GitHub Pages · © 2025 Desert Sky Events*
