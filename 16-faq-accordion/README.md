# ❓ FAQ Accordion (CSS Only)

A modern and interactive **FAQ Accordion UI** built using **HTML & CSS only (no JavaScript)**.
This project uses hover effects to expand and collapse answers smoothly.

---

## ✨ Features

* 📂 Accordion-style FAQ layout
* ⚡ Pure CSS (no JavaScript required)
* 🎯 Smooth expand/collapse animation
* ➕ Toggle icons (plus/minus)
* 🎨 Gradient background design
* 📱 Clean and centered layout

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3 / SCSS**
* **Flexbox**
* **Remix Icons**

---

## 📂 Project Structure

```id="faq91x"
16-faq-accordion/
│
├── index.html
├── style.css
├── style.scss
└── README.md
```

---

## 📑 Sections Included

* 🧾 **Header**

  * Title: FAQ's

* 📋 **FAQ Items**

  * Question
  * Answer
  * Toggle icons (+ / −)

---

## ⚙️ How It Works

* Answers are hidden using:

  * `max-height: 0`
  * `opacity: 0`

* On hover:

  * Content expands using `max-height`
  * Opacity changes to `1`
  * Icons toggle (plus → minus)

```css
.faq_1:hover p {
  max-height: 300px;
  opacity: 1;
}
```

---

## 🎨 Customization

You can easily change:

* 🎨 Background gradient:

```css
background: linear-gradient(to right bottom, #fe542e, #f1961a);
```

* 📋 Questions & answers text
* 🎯 Animation speed:

```css
transition: max-height 0.5s ease;
```

---

## 💡 Highlights

* Pure CSS interaction (no JS)
* Beginner-friendly project
* Reusable FAQ component
* Smooth UI animations

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

* Add click-based accordion (JavaScript)
* Allow only one open at a time
* Add keyboard accessibility
* Make fully responsive

---

🔥 *Great UI component for websites & SaaS dashboards!*
