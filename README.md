# Successive Differentiation Simulator

An advanced, single-file web application for calculating, visualizing, and exploring the Nth derivative of mathematical functions. Designed for educational use in college laboratories.

## 🚀 Key Features

- **Symbolic Differentiation:** Powered by `math.js`, providing accurate Nth-order derivatives for polynomial, trigonometric, exponential, and logarithmic functions.
- **Dynamic Visualization:** Interactive graphing of the original function and all successive derivatives (up to the requested order) using `Plotly.js`.
- **LaTeX Mathematical Output:** Renders textbook-quality equations via `MathJax`, with custom formatting to ensure clean, readable results (removing artifacts like `\cdot`).
- **Numerical Evaluation:** Instantly evaluate the Nth derivative at any given value of $x$.
- **Non-Blocking Performance:** Leverages **Web Workers** to handle complex symbolic computations and point generation in the background, ensuring a smooth, lag-free UI.
- **Comprehensive Formula Reference:** An expanded, built-in reference modal covering:
    - Basic Rules (Power, Constant, etc.)
    - Trigonometric Derivatives
    - Exponential and Logarithmic Rules
    - Product, Quotient, and Chain Rules
- **Modern Responsive Design:** A clean, professional interface built with CSS variables, optimized for both desktop and mobile viewing.

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3 (Modern Flexbox/Grid), JavaScript (ES6+).
- **Mathematics Engine:** [Math.js](https://mathjs.org/) for symbolic parsing and calculation.
- **Graphing Library:** [Plotly.js](https://plotly.com/javascript/) for interactive SVG/Canvas plots.
- **Math Rendering:** [MathJax v3](https://www.mathjax.org/) for LaTeX display.

## 📖 How to Use

1. **Launch:** Open `simulation.html` in any modern web browser.
2. **Input:**
   - **Function f(x):** Enter your expression (e.g., `2*x^3 + sin(x)`). Use `*` for multiplication.
   - **Order (n):** Specify how many times you wish to differentiate.
   - **Evaluate at x:** (Optional) Provide a value to calculate the final numerical result.
3. **Calculate:** Hit the **Calculate** button to start the engine.
4. **Interact:**
   - Scroll through the **Order-by-Order** symbolic steps.
   - Use the **Graph** to toggle specific derivatives on/off or zoom into points of interest.
   - Use **Copy** on the final answer to save it to your clipboard.
5. **Learn:** Click the **Formulas** button at any time to verify differentiation rules.

## 📝 Syntax Tips

The simulator uses `math.js` syntax:
- Powers: `x^2`
- Multiplication: `2*x` or `x*y`
- Functions: `sin(x)`, `cos(x)`, `log(x)`, `exp(x)`, `sqrt(x)`
- Constants: `e`, `pi`

---
*Created for the Successive Differentiation Project - 2025*