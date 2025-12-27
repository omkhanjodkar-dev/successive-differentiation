# Successive Differentiation Simulator

An advanced, single-file web application for calculating, visualizing, and exploring the Nth derivative of mathematical functions. Designed for educational use in college laboratories.

## Features

- **Symbolic Differentiation:** Uses `math.js` to accurately calculate Nth-order derivatives of complex functions.
- **Real-Time Graphing:** Visualizes the original function ($f(x)$) and its derivatives ($f'(x)$, $f''(x)$, etc.) simultaneously using `Plotly.js`.
- **LaTeX Rendering:** Displays clean, textbook-quality mathematical equations using `MathJax`.
- **Numerical Evaluation:** Evaluate the final derivative at a specific point ($x=a$).
- **Web Worker Engine:** Performs heavy calculations in a background thread, keeping the UI responsive.
- **Formula Reference:** Built-in modal with standard derivatives and rules (Product, Quotient, Chain).
- **Single-File Deployment:** Entire application contained in `simulation.html` for easy distribution and offline use.

## Technologies Used

- **HTML5 & CSS3:** Modern, responsive UI.
- **JavaScript (ES6+):** Core logic and Web Worker implementation.
- **[Math.js](https://mathjs.org/):** Symbolic differentiation engine.
- **[Plotly.js](https://plotly.com/javascript/):** Interactive graphing library.
- **[MathJax](https://www.mathjax.org/):** LaTeX display engine.

## How to Use

1. Open `simulation.html` in any modern web browser (Chrome, Edge, Firefox, Safari).
2. **Input:**
   - Enter your function in the **Function f(x)** field (e.g., `sin(x) * x^2`).
   - Enter the desired **Order (n)** (e.g., `3` for the 3rd derivative).
   - (Optional) Enter a value for **x** to evaluate the result numerically.
3. **Calculate:** Click the **Calculate** button.
4. **Analyze:**
   - View step-by-step symbolic results in the output section.
   - Interact with the graph to zoom, pan, and inspect values.
5. **Tools:** Use the **Formulas** button for help or **Quick Examples** to load preset functions.

## Project Structure

- `simulation.html`: The complete application (UI, styles, logic, and graphing).
- `README.md`: This documentation.
