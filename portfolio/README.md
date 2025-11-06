# Vishal — Portfolio Website

Clean, personal portfolio built with HTML5, CSS3, and vanilla JavaScript. Includes smooth animations, dark/light theme, projects grid, and a working contact form via Formspree.

---

## Preview
![Preview](./assets/ele/preview.png)

## Features
- Responsive layout (mobile-first)
- Dark/Light theme toggle (persisted)
- Animated sections and project cards
- Contact form powered by Formspree
- Simple, no-build static site

## Project Structure
```
portfolio/
├── index.html
├── thank-you.html
├── error.html
├── assets/
│   ├── css/
│   ├── js/
│   ├── ele/
│   ├── fonts/
│   ├── projects/
│   └── config/
└── README.md
```

## Run Locally
```bash
# From repo root
cd portfolio

# Option 1: Python
python -m http.server 5173 --bind 127.0.0.1
# open http://127.0.0.1:5173

# Option 2: Node
npx http-server -p 5173 -a 127.0.0.1
```

## Deploy
- GitHub Pages: enable Pages from the `main` branch root
- Any static host (Netlify, Vercel, etc.): import this repo and deploy

## Contact Form (Formspree)
```html
<form id="contactForm" action="https://formspree.io/f/xovpglzd" method="POST">
  <input type="text" name="name" required>
  <input type="email" name="email" required>
  <input type="text" name="subject" required>
  <textarea name="message" required></textarea>
  <input type="hidden" name="_redirect" value="/thank-you.html">
  <button type="submit">Send</button>
</form>
```
Notes:
- After deployment, add your domain in Formspree → Allowed domains

## Author
- Email: vp312600@gmail.com
- LinkedIn: https://www.linkedin.com/in/vishal-patel26/
- GitHub: https://github.com/Vp3126
