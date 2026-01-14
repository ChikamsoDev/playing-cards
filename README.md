🂡 Playing Cards Layout (HTML & CSS)

A simple playing cards layout built with **semantic HTML** and **modern CSS (Flexbox)**.
This project focuses on **layout structure, alignment, and visual symmetry**, without using JavaScript.

## 📌 Overview

This project displays three playing cards:

* **Ace of Spades**
* **King of Hearts**
* **Queen of Diamonds**

Each card is structured into **three sections** (left, middle, right) to mimic the layout of real playing cards, including rotated bottom values and suit-based coloring.

## 🎯 Learning Goals

This project was built to practice:

* **Flexbox layout techniques**
* **Intentional CSS rules (no random styling)**
* **Component-based thinking using reusable classes**
* **Visual balance and symmetry**
* **Transformations (`rotate`) for realistic UI effects**

## 🧱 Structure

### HTML

* Semantic structure using `<main>`
* Each card is a reusable `.card` component
* Cards are divided into:

  * `.left` → top-left rank & suit
  * `.middle` → center suit symbols
  * `.right` → bottom-right rank & suit (rotated 180°)

### CSS

* Flexbox used for:

  * Card container layout
  * Internal card alignment
* Reusable utility classes:

  * `.red` for Hearts & Diamonds
  * `.black` for Spades
* `transform: rotate(180deg)` used for authentic card orientation
* Shadows and border-radius for depth and realism

## 🎨 Design Choices

* **Green background** to resemble a card table
* **White cards** with rounded corners for realism
* **Georgia serif font** to match traditional playing cards
* **Consistent spacing** using padding and `gap`

## 📂 Files

```
.
├── index.html
├── styles.css
└── README.md
```

## 🚀 How to Run

1. Clone or download the repository
2. Open `index.html` in your browser
3. No build tools or dependencies required

## 🔮 Possible Improvements

* Add more card ranks and suits
* Generate cards dynamically with JavaScript
* Add hover or flip animations
* Make the layout responsive for smaller screens
* Create a full deck using CSS Grid or JS

## 🧠 What This Project Demonstrates

This project shows an understanding of **layout fundamentals**, **CSS intent**, and **UI structure**, making it a strong foundation for more advanced front-end work.
