# Uncommon CSS `calc()` Pitfalls

This repository demonstrates some unexpected behaviors that can arise when using the CSS `calc()` function.  The `bug.css` file showcases examples of issues related to unit mixing, nested expressions, and potential browser compatibility problems.  `bugSolution.css` provides solutions and best practices to avoid these pitfalls.

**Key Issues:**

* **Unit Inconsistency:** Mixing different units (e.g., `px`, `%`, `em`) within a single `calc()` expression can lead to unpredictable results as the browser tries to resolve them.
* **Nested Complexity:** Deeply nested `calc()` functions reduce readability and increase the chance of errors.
* **Browser Compatibility:**  While widely supported, older browsers might have limited or inconsistent support for the `calc()` function.

**Solutions:**

* **Consistent Units:** Use a single unit type (e.g., `px`, `%`, `em`) throughout your `calc()` expression whenever possible.
* **Simplify Expressions:** Break down complex `calc()` expressions into smaller, more manageable parts.
* **Testing:** Thoroughly test your CSS across different browsers to identify and resolve any compatibility issues.
* **Alternatives:** Consider using CSS variables or preprocessors to simplify calculations and improve code maintainability.