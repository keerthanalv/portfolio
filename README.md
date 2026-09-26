# Keerthana L. – Personal Portfolio Website

A modern, minimal, elegant, and professional personal portfolio website designed for **Keerthana L.**, Computer Science and Engineering student at S J C Institute of Technology (SJCIT).

---

## 🎨 Design & Aesthetic Highlights

- **Soft Pastel Palette**:
  - **Off-white (`#FAFAFA`)**: Main clean background.
  - **Soft peach (`#F5BDAA`)**: Subtle highlights, indicators, and gentle tag accents.
  - **Muted pink (`#E990A5`)**: Elegant accents, section kickers, pulse indicators, and active nav highlights.
  - **Dusty lavender (`#806F94`)**: Secondary elements, metadata, icons, and borders.
  - **Deep purple (`#5B496D`)**: Headings, primary buttons, and prominent details with high-contrast readability (>8:1).
- **Typography**: Paired editorial heading serif (*Newsreader*) with a clean, highly legible modern geometric body font (*Plus Jakarta Sans*).
- **Subtle Scroll Animations**: Sections and cards gently fade in and move slightly upward as they enter the viewport with smooth, staggered delays. Fully respects the user's `prefers-reduced-motion` settings.
- **Clean Focus**: Profile photo/avatar removed to keep the direct spotlight on your name, academic foundation, and authentic achievements.
- **Authenticity First**: Accurately showcases educational background, current technical interests, verified course certifications, published article, and genuine student leadership & event coordination roles.
- **Zero Distractions**: No fake statistics, no percentage-based skill meters, no generic AI stock illustrations, and no bloated frameworks.
- **100% Pure Web Standards**: Pure semantic HTML5, modern responsive CSS3, and lightweight vanilla JavaScript. Zero build steps, loads instantly.

---

## 📁 File Structure

```text
Portfolio/
├── index.html              # Main HTML structure with all sections & clear comments
├── css/
│   └── style.css           # Custom styling, color tokens, responsive layout, scroll animations
├── js/
│   └── main.js             # Mobile menu, scroll spy, smooth scroll, scroll animations, email copy toast
├── assets/
│   └── favicon.svg         # Monogram brand icon matching the deep purple & pastel theme
└── README.md               # Documentation & customization guide
```

---

## 🚀 How to Run Locally

You don't need any server, Node.js, or complex tools to view the website:

1. Open the project folder: `c:\Users\HP\Documents\Portfolio`
2. **Double-click `index.html`** to open it immediately in your favorite browser (Chrome, Edge, Firefox, Brave, Safari).
3. Alternatively, if you use VS Code, right-click `index.html` and choose **"Open with Live Server"**.

---

## ✏️ How to Customize & Update Your Information

Clear, intuitive HTML comments are included in `index.html` showing exactly where to update links and information:

### 1. Linking Your Published Article
In `index.html`, locate the **Published Article** section (`id="article"`):
```html
<!-- Replace href="#" with your actual published article URL -->
<a href="https://your-article-link-here" class="btn btn-primary" target="_blank" rel="noopener noreferrer">
  <span>Read Article</span>
</a>
```

### 2. Adding Your LinkedIn Profile
In `index.html`, navigate to the **Contact** section (`id="contact"`):
- Update `href="#"` for LinkedIn with: `https://linkedin.com/in/your-profile`

### 3. Adding Certificate Credential Links
In the **Certifications & Learning** section (`id="certifications"`):
- Each card has a `cert-link-placeholder`. You can wrap it with an `<a>` tag or replace the placeholder text with your verification link or credential ID:
```html
<a href="https://your-credential-link.com" target="_blank" class="cert-link-placeholder">
  <span>Verify Credential ↗</span>
</a>
```

### 4. Updating Graduation Year & CGPA (When Ready)
In the **Education** section:
- Look for `<span class="education-editable-note">Status: In Progress</span>`.
- You can add your expected graduation year or academic standing whenever you wish (e.g., `Expected Graduation: 2027 • CGPA: 9.X`).

---

## 🌐 How to Host Your Website for Free

### Option A: GitHub Pages (Recommended)
1. Initialize a git repository and push this folder to your GitHub account:
   ```bash
   git add .
   git commit -m "Update portfolio with soft pastel palette and scroll animations"
   git branch -M main
   git remote add origin https://github.com/<your-username>/portfolio.git
   git push -u origin main
   ```
2. Go to your repository on GitHub → **Settings** → **Pages**.
3. Under **Branch**, select `main` and root `/`, then click **Save**.
4. Your portfolio will be live at `https://<your-username>.github.io/portfolio/` in 1–2 minutes!

### Option B: Vercel or Netlify
1. Drag and drop the `Portfolio` folder directly onto [Netlify Drop](https://app.netlify.com/drop) or import from GitHub on [Vercel](https://vercel.com).
2. It will deploy automatically with an instant HTTPS link.

---

## 📄 License & Credits
Designed and developed for **Keerthana L.**
Feel free to update, expand, and share with recruiters, mentors, and peers!
