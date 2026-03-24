# CSS-Only Modal 🔥

A simple modal (popup) built using only HTML and CSS — no JavaScript required!

This project demonstrates how to use the `:target` pseudo-class to create a functional modal.

---

## 🚀 Features

- Pure HTML + CSS (No JavaScript)
- Uses `:target` pseudo-class
- Smooth open/close transition
- Responsive design
- Clean UI

---

## 📂 Project Structure
```
04-css-model/
│
├── index.html
├── style.scss
└── style.css
└── README.md
```



---

## 🧠 How It Works

- The modal is triggered using an anchor link (`href="#openModal"`).
- When clicked, the URL hash changes.
- The CSS `:target` selector detects the active ID and displays the modal.

---

## 📸 Demo Flow

1. Click on **Open Modal**
2. Modal appears using `:target`
3. Click **× (close)** to close it

---

## 🧾 HTML Snippet

```html
<a href="#openModal">Open Modal</a>

<div id="openModal" class="modal">
  <div class="modal-content">
    <a href="#" class="close">&times;</a>
    <h3>Modal Title</h3>
    <p>This is a CSS-only modal using :target.</p>
  </div>
</div>