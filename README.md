# Product Preview Card Component

A responsive product preview card built as part of a Frontend Mentor challenge.  
The component is implemented using **mobile-first CSS**, **Flexbox**, and modern layout techniques with a focus on clean structure, maintainability, and design fidelity.

## 🔗 Live Demo

👉 [View Live Site](https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/)

---

## 📸 Screenshot

<img src="./images/screenshot.png" alt="Product preview card component" width="400" />

---

## 🛠️ Built With

- Semantic HTML5
- CSS custom properties (variables)
- Flexbox (mobile-first layout)
- Responsive images using `<picture>`
- BEM methodology for class naming
- Google Fonts (Fraunces & Montserrat)

---

## ✨ Features

- Mobile-first responsive layout
- Single content-driven breakpoint for tablet and desktop
- Equal split layout on larger screens using Flexbox
- Responsive image swapping for mobile and desktop
- Clean spacing using `gap` and padding instead of margins
- Button built with `inline-flex` for precise icon/text alignment

---

## 🧠 What I Learned

- How to structure CSS into **layout, box styling, and typography layers**
- Why using **one breakpoint** for structural layout changes improves maintainability
- How `flex: 1` distributes space evenly between flex items
- The difference between **content images** (`<picture>`) and **decorative images** (`background-image`)
- How `object-fit: cover` helps images fill flexible containers correctly
- Why controlling line length with `ch` units improves readability
- How padding affects visual balance even when flex items are equal width

---

## 🎯 Design Decisions

- **Mobile-first approach:** all base styles target mobile, with enhancements for larger screens
- **One structural breakpoint (`48rem`):** the layout changes from column to row only when content requires it
- **Width containment:** a `max-width` is used on larger screens to maintain readable typography and visual balance
- **Spacing with `gap`:** avoids margin-collapse issues and keeps layout intent clear
- **Inner content wrapper:** separates layout sizing from padding for better visual symmetry

---

## 🚀 Continued Improvements

- Add keyboard focus states for improved accessibility
- Improve button hover and active states
- Extract common spacing and typography tokens for reuse across components

---

## 👤 Author

- GitHub – [@YOUR_GITHUB_USERNAME](https://github.com/dayu420)
- Frontend Mentor – [Dayu420](https://www.frontendmentor.io/profile/dayu420)

---

## 🙏 Acknowledgments

- Design provided by [Frontend Mentor](https://www.frontendmentor.io)
