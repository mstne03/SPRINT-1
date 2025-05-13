# Web Design Replication Using CSS, Sass, and Bootstrap

This project demonstrates three different implementations of the same web page design using various styling technologies. Each approach is isolated in its own Git branch to allow clear comparison and modular development.

---

## 🔧 Technologies Used

- HTML5
- CSS3 (Vanilla)
- Sass (SCSS)
- Bootstrap 5

---

## 🌿 Branch Structure

The repository is organized into branches derived from a common development branch:

main
└── develop
├── vanilla-css
├── sass
└── bootstrap


- **`main`**: the stable, production-ready branch.
- **`develop`**: the working branch where feature branches are merged.
- **`vanilla-css`**: implementation using only HTML and pure CSS.
- **`sass`**: implementation using Sass for modular and scalable styles.
- **`bootstrap`**: implementation using the Bootstrap 5 framework for rapid development.

---

## 📂 General File Structure

The directory structure may vary slightly between branches, but generally follows this pattern:

├── index.html
├── styles/
│ └── css/
│   └── style.css 
│ └── sass/ # only in the sass branch
│   └── main.scss
├── / # only if custom assets are needed