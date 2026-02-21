# The Witness Missions — Welcome Home Page

A beautiful landing page for new believers, built for The Witness Missions ministry.

## Files
- `index.html` — The full website
- `logo.png` — The Witness Missions logo

## Deploying to Netlify from GitHub

1. Push both files to your GitHub repository
2. Go to [app.netlify.com](https://app.netlify.com)
3. Click **"Add new project"** → **"Import from Git"**
4. Select your GitHub repo
5. Click **Deploy** — your site will be live at `yourname.netlify.app`

## Features
- ✝ Welcome page for new believers
- 📖 Scripture, next steps, FAQ & morning prayer
- 📬 Contact form (powered by Netlify Forms)
- 💬 AI-powered faith chat assistant
- 📱 Fully mobile responsive

## Setting Up the AI Chat
The chat widget calls the Anthropic API directly. To enable it:
1. Get a free API key at [console.anthropic.com](https://console.anthropic.com)
2. Open `index.html` and find the fetch call to `api.anthropic.com`
3. Add your API key to the headers: `'x-api-key': 'YOUR_KEY_HERE'`

## Setting Up Form Notifications
1. Deploy to Netlify
2. Go to **Site Settings → Forms**
3. Click **Add notification → Email notification**
4. Enter your email to receive form submissions
