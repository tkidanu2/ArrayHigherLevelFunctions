# 🧠 Interactive Array Method Explorer

This is a lightweight, interactive educational tool built with HTML, CSS, and JavaScript that helps you **visually experiment with JavaScript array methods** such as `map`, `filter`, `some`, `every`, `find`, `findIndex`, `forEach`, and `flatMap`.

---

## 🚀 Features

- 📦 JSON input pane to simulate datasets (default: employees list)
- 🧠 Dropdown to select any array method dynamically
- 💡 Custom callback editor to apply transformations or filtering
- 📊 Auto-formatted result display in a dynamic HTML table
- ⚠️ Handles errors for invalid JSON or callback expressions

---

## 📁 File Structure




---

## 🖥️ How to Use

1. **Open `arrays.html`** in any modern browser.
2. **Edit JSON** in the left pane, simulating real datasets.
3. **Select an Array Method** from the dropdown in the center.
4. **Write a JavaScript callback function** (e.g., `(e) => e.salary > 70000`).
5. **Click "Run Method"** to see the transformed result in the right-hand pane.

---

## 🧪 Examples

- **Filter Developers:**
  ```js
  (e) => e.position === "Developer"

⚠️ Notes
Uses eval() for interpreting the callback function, which should only be used in safe, local environments for learning/demo purposes.

Validates JSON input and provides descriptive error messages.


🙌 Author
Built by Tawer Kidanu to make learning array methods fun, intuitive, and interactive.

🛠️ Future Enhancements
1- Support for chaining multiple methods

2- Visual representation of callback logic (e.g., diagrams)

3- Export results as CSV or JSON