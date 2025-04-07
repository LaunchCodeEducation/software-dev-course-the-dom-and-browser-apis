## 🛒 DOM Shopping List App

### 🎯 Objective:
Create a dynamic shopping list application that uses **DOM manipulation** and **event handling** to add, edit, and remove items from the list.

This activity helps students practice:

- Selecting DOM elements using `document.getElementById()` and `document.querySelector()`
- Dynamically updating the DOM by adding, modifying, and removing elements
- Caching DOM elements for cleaner, more efficient code

---

### 🧭 Instructions

---

### 1️⃣ HTML Setup

Create a basic HTML structure that includes:

- An **input field** for entering new items  
- A **button** to add items to the list  
- An **unordered list** to display the shopping list items  

---

### 2️⃣ Core Features

#### ✅ Add Items

When the user enters text in the input field and clicks the **"Add"** button:

- A new list item should be added 
- Each list item should include:
  - The item text
  - A **"Remove"** button to delete the item
  - An **"Edit"** button to modify the item text

#### ❌ Remove Items

- When the **"Remove"** button is clicked:
  - The corresponding list item is removed from the DOM

#### ✏️ Edit Items

- When the **"Edit"** button is clicked:
  - Replace the item text with an input field containing the current value
  - Change the **"Edit"** button to a **"Save"** button

- When **"Save"** is clicked:
  - Update the list item with the new input value
  - Revert the button back to **"Edit"**

---

### 💡 Tips

- Use `addEventListener()` to attach event handlers to your buttons
- Cache selectors for performance and readability (e.g., store input and list elements in variables)
- Consider using `event.target` to identify which button was clicked

