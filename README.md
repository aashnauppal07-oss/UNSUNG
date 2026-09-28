# Unsung – Invisible Work Tracker

## Run in VS Code
1. Unzip and open the `unsung` folder in VS Code (File > Open Folder).
2. Install the recommended **Live Server** extension.
3. Right-click `index.html` > **Open with Live Server** (http://127.0.0.1:5500).
   Alternative: run `npm start` in the terminal.

## Files
- `index.html` – all screens (login, profile, splash, app)
- `css/style.css` – pastel theme
- `js/app.js` – logic (auth, alarms, calendar, trackers, chatbots, SOS)

## Deploy (free)
- **Netlify Drop**: drag the folder to https://app.netlify.com/drop
- **GitHub Pages**: push to a repo > Settings > Pages > deploy from `main`.
- **Vercel**: `npx vercel` in the folder.

Notes: data is stored in the browser (localStorage). Voice SOS needs Chrome + HTTPS/localhost + mic permission.
