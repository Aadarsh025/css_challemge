# CSS Layout & Animation Challenge

A practical CSS mini-project focused on building responsive layouts and smooth, professional animations using **Flexbox, CSS Grid, CSS transitions, transforms, and keyframes**.

## 📌 Project Overview

This project was created as part of a CSS challenge designed to improve practical layout and animation skills through focused mini-exercises.

The project contains three main challenges:

1. **Flexbox Layout**
2. **CSS Grid Layout**
3. **CSS Animation**

Each challenge is built with responsive design in mind so that the layouts work across desktop, tablet, and mobile screen sizes.

---

## 🧩 1. Flexbox Layout Challenge

The Flexbox section demonstrates how to create a responsive row of feature cards.

### Requirements Covered

- Three cards displayed in a row on desktop.
- Cards stack vertically on smaller screens.
- Uses:
  - `display: flex`
  - `justify-content`
  - `align-items`
  - `gap`
  - Flexible widths with `flex: 1`
- Includes hover effects for interaction feedback.
- Uses a responsive media query for mobile devices.

### Desktop Layout

```text
┌─────────────────────────────────────────────┐
│                                             │
│   ┌─────────┐  ┌─────────┐  ┌─────────┐   │
│   │  Card 1 │  │  Card 2 │  │  Card 3 │   │
│   └─────────┘  └─────────┘  └─────────┘   │
│                                             │
└─────────────────────────────────────────────┘
```

### Mobile Layout

```text
┌───────────────┐
│    Card 1     │
├───────────────┤
│    Card 2     │
├───────────────┤
│    Card 3     │
└───────────────┘
```

### Files

- `flexbox.html`
- `flex.css`

---

## 🧱 2. CSS Grid Layout Challenge

The Grid section demonstrates a two-dimensional responsive layout using CSS Grid.

### Requirements Covered

- Contains at least 6 grid items.
- Uses `display: grid`.
- Uses `repeat()` for responsive column definitions.
- Uses equal spacing with `gap`.
- Maintains consistent card styling and alignment.
- Rearranges the layout at smaller breakpoints.

### Responsive Behavior

**Desktop:** 3 columns

```text
┌─────────┬─────────┬─────────┐
│ Item 1  │ Item 2  │ Item 3  │
├─────────┼─────────┼─────────┤
│ Item 4  │ Item 5  │ Item 6  │
└─────────┴─────────┴─────────┘
```

**Tablet:** 2 columns

```text
┌─────────┬─────────┐
│ Item 1  │ Item 2  │
├─────────┼─────────┤
│ Item 3  │ Item 4  │
├─────────┼─────────┤
│ Item 5  │ Item 6  │
└─────────┴─────────┘
```

**Mobile:** 1 column

```text
┌─────────────┐
│   Item 1    │
├─────────────┤
│   Item 2    │
├─────────────┤
│   Item 3    │
├─────────────┤
│   Item 4    │
├─────────────┤
│   Item 5    │
├─────────────┤
│   Item 6    │
└─────────────┘
```

### Files

- `grid.html`
- `grid.css`

---

## ✨ 3. CSS Animation Challenge

The Animation section demonstrates different types of CSS animation using separate UI elements.

### Animation Examples

#### 1. Button Hover Animation

Uses:

- `transition`
- `transform`
- `box-shadow`

The button smoothly changes its appearance and moves slightly upward when hovered.

#### 2. Loading Spinner

Uses:

- `@keyframes`
- `transform: rotate()`
- `animation`

The spinner continuously rotates to create a loading effect.

#### 3. Fade-In Content

Uses:

- `@keyframes`
- `opacity`
- `transform: translateY()`

Content smoothly appears when the page loads.

#### 4. Card Lift Effect

Uses:

- `transition`
- `transform: translateY()`
- `box-shadow`

The card moves upward smoothly when hovered.

#### 5. Animated Navigation Underline

Uses:

- `::after`
- `transition`
- Dynamic `width`

The underline expands smoothly when hovering over navigation links.

#### 6. Pulse Animation

Uses:

- `@keyframes`
- `transform: scale()`
- `opacity`

The circle continuously grows and shrinks subtly.

### Files

- `animation.html`
- `animation.css`

---

## 📱 Responsive Design

All three challenges are designed to respond to different screen sizes.

### Breakpoints Used

| Screen Size | Behavior |
|---|---|
| Desktop | Full multi-column layouts |
| Below 800px | Layouts reduce their number of columns |
| Below 600px | Layouts switch to mobile-friendly single-column layouts |

The project avoids unnecessary absolute positioning and uses Flexbox, Grid, flexible sizing, spacing, and media queries to maintain alignment.

---

## 📂 Project Structure

```text
CSS-Challenge/
│
├── flexbox.html
├── flex.css
│
├── grid.html
├── grid.css
│
├── animation.html
├── animation.css
│
└── README.md
```

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- Flexbox
- CSS Grid
- CSS Transitions
- CSS Transforms
- CSS Keyframes
- Responsive Media Queries

No JavaScript or external CSS framework is required for these challenges.

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone <your-repository-url>
```

2. Open the project folder.

3. Open any of the following files in a browser:

```text
flexbox.html
grid.html
animation.html
```

4. Use the browser's Developer Tools to test different screen sizes and verify the responsive behavior.

---

## 📸 Screenshot Guide

The challenge requires screenshots demonstrating the completed work.

Recommended screenshots:

### Flexbox
- Desktop view showing all 3 cards in a row.
- Mobile view showing cards stacked vertically.

### Grid
- Desktop/tablet view showing the responsive grid with 6 items.

### Animation
- Animation page showing the different animation components.
- Capture the button/card hover state or another visible animation state when appropriate.

---

## ✅ Best Practices Demonstrated

- Logical separation of challenge components.
- Clear class naming.
- Responsive layouts.
- Consistent spacing.
- Flexible sizing.
- Minimal use of absolute positioning.
- Smooth and subtle animations.
- Responsive debugging with browser Developer Tools.
- Separate HTML and CSS files for each challenge.

---

## 🎯 Learning Objectives

Through this project, the following CSS concepts are practiced:

- Building layouts with Flexbox.
- Understanding horizontal and vertical alignment.
- Creating two-dimensional layouts with CSS Grid.
- Making layouts responsive.
- Using media queries effectively.
- Creating interactive hover states.
- Understanding `transition` and `transform`.
- Creating animations with `@keyframes`.
- Combining animation techniques to improve UI interaction without excessive motion.

---

## 👨‍💻 Author

**Aadarsh Tripathi**

Computer Science (Data Science) Undergraduate

Skills and interests include:

- Python
- Data Structures & Algorithms
- Web Development
- Machine Learning
- Data Science

---

⭐ If you find this project useful, consider giving the repository a star!
