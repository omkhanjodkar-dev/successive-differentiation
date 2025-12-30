## Successive Differentiation Simulator

This is a small web project that I built to practice working with derivatives and JavaScript.  
The page lets you type a function \(f(x)\), choose an order \(n\), and then it shows all the
successive derivatives up to the \(n\)-th one. It also plots the original function and every
derivative on an interactive graph.

### What the page can do

- **Nth derivative**: computes the symbolic derivative of a function multiple times.
- **Step-by-step list**: shows each order (1st, 2nd, 3rd, …) with a LaTeX-style formula.
- **Graph**: uses an interactive chart so you can see how the function and its derivatives look.
- **Evaluate at a point**: optionally plug in a value of \(x\) into the final derivative.
- **Formula help**: a small “Formulas” window with the most common rules (power, trig, etc.).
- **Background worker**: heavy calculations are done in a Web Worker so the UI does not freeze.

### Main libraries

- `math.js` – for parsing expressions, taking derivatives, and evaluating.
- `Plotly.js` – for the interactive line graph of the function and derivatives.
- `MathJax` – to render the math formulas nicely in the browser.

### How to run it

- Open `simulation.html` in a modern browser (Chrome, Edge, Firefox, etc.).  
- In the **Function f(x)** box, type something like `2*x^3 + sin(x)` (be sure to use `*` for multiplication).  
- Set **Order (n)** to how many times you want to differentiate (for example `3`).  
- (Optional) Type a number in **Evaluate at x** to get the numeric value of the final derivative at that point.  
- Click **Calculate**. The list of derivatives, final expression, and graph should all update.

Some quick examples you can try:

- `x^4 + 3*x^3 + 2` with order `2`
- `sin(x) * cos(x)` with order `2`
- `e^x * x^2` with order `3`

### Notes

- The syntax mostly follows `math.js` (e.g. `sin(x)`, `log(x)`, `exp(x)`, `sqrt(x)`, `pi`, `e`).  
- The goal of the project is educational, not to be a perfect CAS. There might be edge cases or
  expressions that do not simplify as nicely as in a textbook.

---
Last updated: 2025



