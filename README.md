# NutriLens 🥗

AI-powered meal calorie analyzer built with Claude Vision API.

## Features
- Upload or photograph a meal
- AI analyzes calories, macros, and ingredients
- Health score (1–10) with personalized tips
- Daily calorie log with goal tracker

## Deploy to Vercel (Free)

### Step 1 — Push this folder to GitHub
Upload all 3 files to a new GitHub repo:
- `index.html`
- `api/proxy.js`
- `vercel.json`

### Step 2 — Connect to Vercel
1. Go to [vercel.com](https://vercel.com) and sign up with your GitHub account
2. Click **Add New Project** → Import your GitHub repo
3. Click **Deploy** (no build settings needed)

### Step 3 — Add your API Key
1. In Vercel dashboard → your project → **Settings → Environment Variables**
2. Add:
   - **Name:** `ANTHROPIC_API_KEY`
   - **Value:** your key from [console.anthropic.com](https://console.anthropic.com)
3. Click **Save** then go to **Deployments → Redeploy**

Your app will be live at `https://your-project.vercel.app` 🎉

## Get an Anthropic API Key
1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Sign up / log in
3. Go to **API Keys** → **Create Key**
4. Copy and paste into Vercel environment variables
