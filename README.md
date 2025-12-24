# Successive Differentiation Simulator

An advanced web-based tool for calculating the Nth derivative of mathematical functions symbolically.

## Features

- **Symbolic Differentiation:** Uses `math.js` to accurately calculate derivatives of complex functions.
- **Beautiful Mathematical Output:** Integrates `MathJax` to render the final result in high-quality LaTeX format.
- **Step-by-Step Progress:** Displays intermediate derivatives for every order leading up to the target.
- **Modern Responsive UI:** A clean, professional interface built with CSS variables and flexbox/grid for all screen sizes.
- **Asynchronous Processing:** Long-running calculations are handled asynchronously to keep the user interface responsive.
- **Stop Control:** Allows users to cancel ongoing high-order calculations instantly.

## Technologies Used

- **HTML5 & CSS3:** For structure and modern styling.
- **JavaScript (ES6+):** For calculation logic and UI interaction.
- **[Math.js](https://mathjs.org/):** An extensive math library for symbolic differentiation and simplification.
- **[MathJax](https://www.mathjax.org/):** A JavaScript display engine for mathematics that works in all browsers.

## How to Use

1. Open `simulation.html` in any modern web browser.
2. Enter your function in the **Function f(x)** field (e.g., `sin(x) * x^2`).
3. Enter the desired **Order (n)** of the derivative.
4. Click **Calculate**.
5. View the intermediate steps in the results section and the formatted final answer at the bottom.

## Project Structure

- `simulation.html`: The main application file containing the UI and calculation logic.
- `simulation 1.html`: An experimental version including graphing capabilities.
- `README.md`: Project documentation.