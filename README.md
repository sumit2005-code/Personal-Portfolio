Here is the full README text — just copy and paste it into your `README.md` file:

```markdown
# 🌐 Sumit Sharma — Personal Portfolio

A personal portfolio website built with **HTML, CSS, JavaScript**, and **jQuery** to showcase my skills, services, projects, and contact information.

---

## 🔗 Live Demo
<a href="https://sumitfolio-eight.vercel.app/"> Live </a>
> Deploy this project on GitHub Pages or Netlify to get a live URL.

---

## 📁 Project Structure

```
sumitfolio/
├── HTML/
│   ├── index.html
│   ├── assets/
│   │   ├── css/
│   │   │   ├── main.css
│   │   │   └── responsive.css
│   │   ├── js/
│   │   │   ├── script.js
│   │   │   ├── scroll-spy.js
│   │   │   ├── counter-up.js
│   │   │   ├── portfolio.js
│   │   │   ├── testi-slider.js
│   │   │   └── blog-slider.js
│   │   ├── images/
│   │   │   ├── Home/
│   │   │   ├── About/
│   │   │   ├── Portfolio/
│   │   │   ├── Testimonials/
│   │   │   └── Blogs/
│   │   └── vendors/
│   │       ├── font-awesome/
│   │       ├── swiper/
│   │       ├── magnific-popup/
│   │       ├── jquery/
│   │       └── typed/
```

---

## ✨ Features

- **Responsive Design** — works on all screen sizes (mobile, tablet, desktop)
- **Typing Animation** — powered by Typed.js
- **Skill Progress Bars** — animated on scroll
- **Counter Animation** — experience, projects, clients, awards
- **Portfolio Filter** — filter projects by category
- **Testimonials Slider** — powered by Swiper.js
- **Blog Slider** — powered by Swiper.js
- **Lightbox Gallery** — powered by Magnific Popup
- **Scroll Spy Navigation** — active nav link highlights on scroll
- **Contact Form** — mailto-based (no server/PHP required)
- **Smooth Scroll** — smooth anchor navigation

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling and layout |
| JavaScript | Interactivity |
| jQuery 3.6.0 | DOM manipulation |
| Typed.js | Typing text animation |
| Swiper.js | Sliders (testimonials & blogs) |
| Magnific Popup | Lightbox for portfolio images |
| Font Awesome | Icons |

---

## 📬 Contact Form

The contact form uses a simple `mailto:` approach — no PHP or backend server needed. When the user clicks **Send Message**, their default email client (Gmail, Outlook, etc.) opens with the form data pre-filled.

```html
<form action="mailto:sharmashumit568@gmail.com"
      method="post"
      enctype="text/plain">
```

---

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/sumit2005-code/Personal-Portfolio.git
   ```

2. **Navigate into the project folder**
   ```bash
   cd Personal-Portfolio/HTML
   ```

3. **Open in browser**
   - Simply open `index.html` in any browser
   - Or use VS Code **Live Server** extension for hot reload

---

## 📦 How to Deploy on GitHub Pages

1. Push your code to GitHub
2. Go to your repository → **Settings** → **Pages**
3. Under **Source**, select `main` branch and `/HTML` folder (or root)
4. Click **Save** — your site will be live at:
   ```
   https://sumit2005-code.github.io/Personal-Portfolio/
   ```

---

## 👤 Author

**Sumit Sharma**
- 📧 Email: [Sharmashumit568@gmail.com](mailto:Sharmashumit568@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/shumit-sharma-766381327](https://www.linkedin.com/in/shumit-sharma-766381327)
- 🐙 GitHub: [github.com/sumit2005-code](https://github.com/sumit2005-code)
- 📞 Phone: +91 8429308573

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Made with ❤️ by Sumit Sharma
```

Copy everything above, open your `README.md` file in VS Code, paste it, and save. Then push it to GitHub with:

```bash
git add README.md
git commit -m "Add README"
git push origin main
```