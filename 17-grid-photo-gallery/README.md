# 🖼️ Grid Photo Gallery

A modern and responsive **Photo Gallery Layout** built using **HTML & CSS Grid**.
This project showcases images in a dynamic grid layout with custom spanning items.

---

## ✨ Features

* 🧩 CSS Grid-based layout
* 🖼️ Multiple images arranged in grid
* 🎯 Custom grid spanning (featured images)
* ⚡ Lightweight (no JavaScript required)
* 🎨 Clean and minimal design
* 📱 Easily extendable for responsiveness

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3 (Grid Layout)**
* **Flexbox (optional use)**

---

## 📂 Project Structure

```id="gridp12"
17-grid-gallery/
│
├── index.html
├── style.css
├── style.scss
└── README.md
```

---

## 📑 Sections Included

* 🧾 **Header**

  * Title: Grid Photo Gallery

* 🖼️ **Gallery Section**

  * Image grid layout
  * Featured large images
  * Regular grid items

---

## ⚙️ How It Works

* Gallery uses **CSS Grid**:

```css
grid-template-columns: repeat(5, 1fr);
grid-template-rows: repeat(6, 1fr);
```

* Some images span multiple rows/columns:

```css
&:nth-child(1) {
  grid-row: 1/3;
  grid-column: 1/3;
}
```

---

## 🎨 Customization

You can easily modify:

* 🖼️ Image sources (Unsplash links)
* 🧩 Grid layout:

```css
grid-template-columns: repeat(5, 1fr);
```

* 📏 Gap between images:

```css
gap: 2rem;
```

---

## 💡 Highlights

* Real-world gallery layout
* Advanced CSS Grid usage
* Clean and scalable design
* Great for portfolio projects

---

## 🙋‍♂️ Author

**Pawandeep Kumar**

* 💼 Aspiring Full Stack Developer
* 🚀 Building UI projects daily

---

## ⭐ Support

If you like this project:

* Give it a ⭐ on GitHub
* Share with others

---

## 💡 Future Improvements

* Add hover effects (zoom / overlay)
* Add lightbox (image preview popup)
* Make fully responsive
* Add filtering (categories)

---

🔥 *Perfect project to master CSS Grid & layouts!*
