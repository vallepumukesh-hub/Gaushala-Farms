# 🐄 Gaushala Farms — React + Vite

A dairy farm website built with React 18 and Vite.
Student project demonstrating CO1, CO2, CO3 concepts.

## 🚀 Getting Started

### 1. Create the project (run this once)
```bash
npm create vite@latest Gaushala_farms -- --template react
cd Gaushala_farms
```

### 2. Replace the src folder with the files in this project

### 3. Install dependencies
```bash
npm install
```

### 4. Start the dev server
```bash
npm run dev
```

Open http://localhost:5173 in your browser.

## 📁 Project Structure

```
Gaushala_farms/
├── index.html               ← HTML entry point
├── vite.config.js           ← Vite configuration
├── package.json             ← Dependencies
└── src/
    ├── main.jsx             ← React entry point
    ├── App.jsx              ← Root component (holds all state)
    ├── index.css            ← Global styles
    ├── data/
    │   └── products.js      ← Product data (CO2: immutable)
    ├── utils/
    │   └── formatPrice.js   ← Pure helper function (CO2)
    └── components/
        ├── Navbar.jsx       ← Top navigation bar
        ├── Hero.jsx         ← Green banner section
        ├── ProductList.jsx  ← Filter tabs + product grid
        ├── ProductCard.jsx  ← Single product card
        ├── Cart.jsx         ← Slide-out cart sidebar
        ├── About.jsx        ← Why choose us section
        └── Footer.jsx       ← Bottom bar
```

## 📚 Concepts Covered

| Course Outcome | Concept | Where |
|---|---|---|
| CO1 | Declarative UI | All JSX components |
| CO1 | Unidirectional data flow | App.jsx → props down, callbacks up |
| CO1 | Component-driven architecture | 7 separate components |
| CO2 | Immutable data | data/products.js with const |
| CO2 | Pure functions | utils/formatPrice.js |
| CO2 | ES6+ (arrow fns, spread, destructuring) | Throughout |
| CO3 | useState hook | App.jsx, ProductList.jsx, ProductCard.jsx |
| CO3 | useEffect hook | App.jsx (updates tab title) |
| CO3 | Props as contracts | Every component |
| CO3 | Controlled UI | Cart qty controlled by App state |
