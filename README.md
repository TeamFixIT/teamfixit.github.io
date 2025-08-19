# 🌐 TeamFixIT Website

This repository contains the source code for the **TeamFixIT organisation website**, built by Murdoch University IT students.\
The website serves as a professional showcase for our team and projects, and is hosted using **GitHub Pages** at:

🔗 [https://teamfixit.github.io](https://teamfixit.github.io)

---

## 🛠️ Tech Stack

- **HTML5** → Page structure
- **Tailwind CSS** → Styling and layout
- **Vanilla JavaScript** → Small interactivity
- **GitHub Pages** → Deployment (no backend required)

---

## 📂 Repository Structure

```
teamfixit.github.io/
│── index.html       # Home Page
│── project.html     # Project Overview
│── team.html        # Team Profiles
│── contact.html     # Contact Page
│
├── css/
│   └── styles.css   # Custom CSS (optional, Tailwind handles most styling)
├── js/
│   └── script.js    # JavaScript for future interactions
└── README.md        # Repo documentation
```

---

## 💻 Development

### 1. Clone the repo

```bash
git clone https://github.com/teamfixit/teamfixit.github.io.git
cd teamfixit.github.io
```

### 2. Open locally

Since this is a static site, you can just open `index.html` in your browser.\
For a smoother dev workflow, you can use a local web server (e.g. with VSCode Live Server extension or Python):

```bash
python3 -m http.server
```

Then visit: `http://localhost:8000`

### 3. Edit

- **HTML** → Update content in pages
- **Tailwind** → Utility classes directly in HTML
- **Custom CSS** → Add overrides in `css/styles.css`
- **JS** → Add interactions in `js/script.js`

---

## 🌍 Deployment (GitHub Pages)

This repo is configured for deployment at the **org root domain**:

🔗 [https://teamfixit.github.io](https://teamfixit.github.io)

Deployment is automatic:

1. Push changes to the `main` branch.
2. GitHub Pages will rebuild and update the live site.

---

## 👥 Contributing

1. Create a new branch:
   ```bash
   git checkout -b feature/my-change
   ```
2. Make edits and commit:
   ```bash
   git commit -m "Added new section to Team page"
   ```
3. Push branch:
   ```bash
   git push origin feature/my-change
   ```
4. Open a Pull Request in GitHub.

---

## ✅ Future Improvements

- Add placeholder profile photos for team members.
- Add mobile-friendly navbar (hamburger menu).
- Enhance accessibility (ARIA labels, alt text).
- Improve interactivity with small JS features.

---

© 2025 TeamFixIT | Murdoch University Students

