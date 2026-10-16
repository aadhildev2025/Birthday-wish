# Happy Birthday Goundoos - Tribute Website 🎂💖

A responsive, romantic birthday tribute web page built with HTML, Tailwind CSS, Canvas Confetti, and Web Audio API synthesizer.

## 🚀 How to Upload to GitHub & Deploy to Vercel

### Step 1: Initialize Git and Push to GitHub

1. Open your terminal in this project directory:
   ```bash
   cd "C:\Users\peace\.gemini\antigravity-ide\scratch\goundoos-birthday"
   ```

2. Go to [github.com/new](https://github.com/new) in your browser and create a new repository (for example: `goundoos-birthday`).
   - Leave it **Public** (or **Private**).
   - Do **NOT** check "Add a README file" (we already have one).

3. Copy the repository URL and run the following commands:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/goundoos-birthday.git
   git branch -M main
   git push -u origin main
   ```

---

### Step 2: Deploy to Vercel

You have two easy ways to deploy to Vercel:

#### Method A: Via Vercel Web Dashboard (Recommended & Automatic)
1. Go to [vercel.com](https://vercel.com) and log in (sign in with your GitHub account).
2. Click **"Add New..."** &rarr; **"Project"**.
3. Under "Import Git Repository", find your **`goundoos-birthday`** repository and click **Import**.
4. Leave all settings at their default (Framework Preset: **Other** / Static).
5. Click **Deploy**.
6. Within ~10-20 seconds, your site is live with a free SSL URL (e.g., `https://goundoos-birthday.vercel.app`)!
*(Every time you push new changes to GitHub, Vercel will automatically redeploy).*

#### Method B: Direct Command Line Deployment
If you want to deploy directly from your terminal:
```bash
npx vercel
```
- Follow the on-screen prompts (login, link project).
- When asked if you want to deploy to production, run:
```bash
npx vercel --prod
```
