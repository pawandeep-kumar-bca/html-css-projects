# 💬 CSS Tooltip (Hover Effect)

A simple and elegant **CSS-only Tooltip** built using **HTML & CSS**.
This project demonstrates how to show additional information when hovering over an element without using JavaScript.

---

## ✨ Features

* 🖱️ Tooltip appears on hover
* ⚡ Pure CSS (no JavaScript needed)
* 🎯 Smooth fade-in effect using opacity
* 🎨 Clean and minimal UI
* 📱 Easy to integrate into any project

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3 (Hover, Positioning, Transition)**

---

## 📂 Project Structure

```
10-css-tooltip/
│
├── index.html
├── style.css (or style.scss)
└── README.md
```

---

## ⚙️ How It Works

* Tooltip text (`<p>`) is positioned **absolute**
* Initially hidden using:

  * `visibility: hidden`
  * `opacity: 0`
* On hover:

  * Visibility becomes visible
  * Opacity transitions to `1`

```css
.tooltip:hover p {
  visibility: visible;
  opacity: 1;
}
```

---

## 💡 Use Cases

* Buttons with extra info
* Icons with labels
* Form hints
* Navigation tooltips

---

## 🙋‍♂️ Author

**Pawandeep Kumar**

* 💼 Aspiring Full Stack Developer
* 🚀 Building UI components daily

---

## ⭐ Support

If you like this project:

* Give it a ⭐ on GitHub
* Share with others

---

## 💡 Future Improvements

* Add arrow pointer to tooltip
* Add multiple tooltip positions (top, bottom, left, right)
* Add animation variations
* Make reusable component

---

🔥 *Small component, big UI impact!*
