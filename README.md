festival-greeting/
├── public/ # optional static assets (favicon, images)
├── src/
│ ├── App.js # Main React component (greeting, countdown, confetti)
│ ├── index.css # Global styles (diyas, animations, layout)
│ └── main.jsx # Vite entry point (or index.js for CRA)
├── index.html
├── package.json
├── vite.config.js # (if using Vite)
└── README.md


If you used Create React App the production output will be in `build/` instead of `dist/`.

---

## 📦 Installation & Setup (Vite)

Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/festival-greeting.git
cd festival-greeting


Install dependencies:

npm install


Run development server:

npm run dev


Open http://localhost:5173 (or the URL shown in terminal).

Build for production:

npm run build


Preview production build locally:

npm run preview

🔁 If you used Create React App (CRA)

Install dependencies:

npm install


Run dev server:

npm start


Open http://localhost:3000.

Build for production:

npm run build


CRA produces a build/ folder (use build as the publish/output folder in deployment settings).

📦 Dependencies

This app is intentionally lightweight. Typical deps (already in package.json):

react

react-dom

vite (if using Vite)

No heavy libraries required. If you want to add more features, you can install:

npm install react-router-dom react-icons

☁️ Deployment
Deploy on Vercel (recommended)

Push your code to GitHub.

Go to Vercel
 → Sign in with GitHub → Import Project.

Select your repository festival-greeting.

Vercel auto-detects Vite or CRA:

For Vite: Build command npm run build, Output directory dist

For CRA: Build command npm run build, Output directory build

Click Deploy. Vercel will give you a live URL.

Deploy on Netlify

Push your repo to GitHub.

Go to Netlify
 → New site → Import from Git → choose your repo.

Set:

Build command: npm run build

Publish directory: dist (Vite) or build (CRA)

Click Deploy site. Netlify will provide a live URL.

✅ What to submit for Practical 3

GitHub repository link: https://github.com/YOUR_USERNAME/festival-greeting

Live URL (Vercel or Netlify)

Screenshot of GitHub repo showing latest commit

Screenshot of Vercel/Netlify showing successful production deploy

Short command log (the terminal commands you ran)

✍️ How to change festival name & date

Open src/App.js (top of file) and edit:

const FESTIVAL_NAME = 'Diwali';
const FESTIVAL_DATE = new Date(2025, 10, 1, 0, 0, 0); // months are 0-indexed: 10 == November


Save, commit, and push — the deployed site will auto-update.
