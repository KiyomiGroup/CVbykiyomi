# CVbykiyomi — Sprint 1

> Tailor your CV to any job, instantly.

A simple, clean web app that generates a professional CV and cover letter tailored to a specific job description. No login. No backend. No cost.

---

## 🚀 Live Demo (GitHub Pages)

Once deployed: `https://<your-username>.github.io/cvbykiyomi/`

---

## 📁 File Structure

```
/
├── index.html          → Home page
├── form.html           → Multi-step form (4 steps)
├── cv-preview.html     → CV preview + print
├── cover-letter.html   → Cover letter preview + print
└── README.md
```

---

## ✨ Features (Sprint 1)

- ✅ Multi-step form with progress indicator
- ✅ Personal info, work experience, skills, job description
- ✅ CV generated from a clean professional template
- ✅ Cover letter auto-generated and tailored to the job description
- ✅ Print / Download via browser print
- ✅ No backend, no login, no database — pure HTML/CSS/JS
- ✅ Data stored in `sessionStorage` between pages

---

## 🛠 How to Deploy on GitHub Pages

1. **Create a new GitHub repository** (e.g. `cvbykiyomi`)
2. **Upload all 4 files** (`index.html`, `form.html`, `cv-preview.html`, `cover-letter.html`) to the root of the repo
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch and `/ (root)` folder
5. Click **Save**
6. Your site will be live at: `https://<your-username>.github.io/cvbykiyomi/`

---

## 🧑‍💻 Local Development

Just open `index.html` in your browser — no build step required.

```bash
# Or use a simple local server
npx serve .
```

---

## 🗺 Roadmap

| Sprint | Features |
|--------|----------|
| ✅ Sprint 1 | Core form, CV + cover letter templates, print |
| Sprint 2 | AI-powered tailoring via Claude API |
| Sprint 3 | User accounts, saved CVs |
| Sprint 4 | Multiple CV templates, premium features |

---

Built with ❤️ by Kiyomi
