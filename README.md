# 📱 Responsive Website with CSS Media Queries

## 📝 Task 4: Make a Website Mobile-Friendly Using CSS Media Queries

### 🎯 Objective
Convert an existing desktop-only webpage into a mobile-friendly, responsive layout using CSS media queries.

---

## 🛠️ Tools Used

- [Visual Studio Code](https://code.visualstudio.com/)
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
- HTML5 & CSS3

---

## 📂 Project Structure

responsive-website/
│
├── index.html # Main HTML file
├── style.css # CSS file with media queries
└── README.md # Project documentation

---

## 🚀 Features Implemented

- ✅ Responsive layout for devices with max-width 768px
- ✅ Navigation bar stacks vertically on mobile
- ✅ Content columns stack vertically on smaller screens
- ✅ Images scale within their containers
- ✅ Overflow and scrolling issues fixed
- ✅ Font sizes adjusted for better mobile readability

---

## 📱 Media Query Example

```css
@media (max-width: 768px) {
  .content {
    flex-direction: column;
    padding: 1rem;
  }

  nav ul {
    flex-direction: column;
    text-align: center;
  }

  .left, .right {
    width: 100%;
    margin-bottom: 1rem;
  }
}
