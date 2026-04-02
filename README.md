# 🌸 Bloomi — Focus Timer

A beautiful soft-pastel Pomodoro timer for students, with background image upload, task management, session history, and sound alerts.

## Features
- ⏱ Pomodoro timer with animated ring progress
- 🎨 Custom background image upload (JPEG, PNG, HEIC)
- ✎ Task list with active task tracking + pomodoro count
- ⚙ Fully customizable durations & session counts
- 📊 Session history & today's stats
- 🔔 Chime sound at session end (Web Audio API)
- 💾 All settings & data persist via localStorage
- 🌸 4 built-in pastel gradient presets

---

## Deploy to Vercel in 3 steps

### Option A — Vercel CLI (fastest)

```bash
npm install -g vercel
cd pomodoro-app
vercel
```

Follow the prompts. Your site will be live at `https://your-app.vercel.app`.

### Option B — GitHub + Vercel Dashboard

1. Push this folder to a GitHub repo:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/bloomi.git
   git push -u origin main
   ```

2. Go to [vercel.com](https://vercel.com) → **New Project** → Import your GitHub repo.

3. Vercel auto-detects static site. Click **Deploy**. Done!

### Option C — Drag & Drop (no CLI needed)

1. Go to [vercel.com/new](https://vercel.com/new)
2. Log in and click **"Deploy without a repository"**
3. Drag the `pomodoro-app` folder onto the page
4. Click **Deploy** — live in ~30 seconds

---

## Custom Domain (optional)

In your Vercel project dashboard → **Settings → Domains** → add your domain.

---

## Tech Stack
- Pure HTML/CSS/JS — zero dependencies, zero build step
- Web Audio API for sound
- localStorage for persistence
- FileReader API for image upload
- `vercel.json` for routing + cache headers
