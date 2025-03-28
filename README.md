# 🎨 CSS 3D Circle Animation Tutorial

Welcome to my interactive CSS animation project! This web application showcases a visually intriguing 3D hover animation using pure HTML and CSS. I created this to help fellow IT students understand how powerful and creative CSS can be — even without JavaScript.

## 🚀 Project Demo

👉 [Live Demo Link](#) *(Replace this with your actual GitHub Pages or Netlify link)*

---

## 📁 Project Structure

/project-folder
│
├── index.html
├── assets/
│ └── style.css
└── README.md

---

## 🔧 How to Run This Project

### 1. Clone or Download the Repository

```bash
git clone https://github.com/yourusername/css-animation-tutorial.git

Or just download the ZIP file and extract it.

2. Open index.html in Your Browser
No installation is needed. This project runs entirely in the browser. Just double-click index.html or open with VS Code and use Live Server.

💡 What This Project Teaches
How to use CSS transitions and transforms
Creating 3D-like effects with rotate3d and translate3d
Structuring reusable circle layers using the :nth-child() selector
Adding hover interactions without JavaScript
🧠 Key Code Snippets
📍Snippet 1: HTML Structure of the Animated Card

<div class="card">
    <div class="circle"></div>
    <div class="circle"></div>
    <div class="circle"></div>
    <div class="circle"></div>
    <div class="circle"></div>
</div>
Explanation:
This creates five nested .circle elements inside a parent .card. Each circle will be animated on hover to create a 3D layered effect.

📍Snippet 2: CSS Hover Animation Using translate3d()

.card:hover .circle:nth-child(1) {
    transform: translate3d(0, 0, 30px); 
}

.card:hover .circle:nth-child(2) {
    transform: translate3d(0, 0, 60px); 
}

.card:hover .circle:nth-child(3) {
    transform: translate3d(0, 0, 90px); 
}

.card:hover .circle:nth-child(4) {
    transform: translate3d(0, 0, 120px); 
}

.card:hover .circle:nth-child(5) {
    transform: translate3d(0, 0, 150px); 
}
Explanation:
Each circle moves further along the Z-axis, creating a stunning depth illusion. This is enhanced by transition-delay, which staggers the animation for a smoother visual effect.

✨ Features
✅ Pure HTML + CSS only
✅ Interactive hover effect
✅ 3D layered animation
✅ Responsive and centered layout
✅ Great for visual learners
🧼 Coding Best Practices
Semantic HTML with proper use of <div> elements
Clean, readable CSS with comments
Separated files for HTML and CSS
Uses transition, transform, and :hover efficiently
👩‍💻 Author
Sarah Mitchell
IT Student & Front-End Enthusiast

