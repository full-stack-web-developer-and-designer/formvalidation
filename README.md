# JavaScript Client-side Form Validation

A lightweight and user-friendly JavaScript form validation script that provides real-time input feedback to ensure form data is accurate, complete, and ready for submission.  

---

## 📌 About the Project

FormValidation.js is a simple, custom-built validation solution designed to enhance any HTML form with instant input checks.  
It highlights errors, validates different field types, and improves user experience with clean, interactive feedback — all without requiring external libraries.

---

## ✨ Features

- Real-time form validation  
- Highlights valid and invalid inputs  
- Custom validation messages  
- Email, text, and password validation  
- Minimal, readable JavaScript code  
- No dependencies — **pure JavaScript**  
- Easy to integrate into any project

---

## 🛠️ Built With

- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6)**

---

## 🚀 Live Demo

Try the live project here:  
👉 https://full-stack-web-developer-and-designer.github.io/formvalidation/

---

### 📷 Screenshot

[![Mockup of project "JavaScript Form validation" by professional web developer and designer Mirnes Glamočić](/screenshot.png)]( https://full-stack-web-developer-and-designer.github.io/formvalidation/)

---

## 📂 Project Structure

```graphql
jQuery-datepicker/
│── index.html          # Main page containing JavaScript form validation
|
│── LICENSE             # MIT LICENSE
|
│── README.md           # This documentation file
|
│── screenshot.png      # screenshot
|
│── style.css           # Styles for form and layout
|
└── validation.js       # JavaScript form validation
```

---


---

## 🔧 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/full-stack-web-developer-and-designer/formvalidation.git
```

### 2. Open the project

Open the index.html file in a browser:

```diff
index.html
```

---

## 📦 Usage

Include the script inside your HTML:

```html
<script src="validation.js"></script>
```

Add form fields with IDs or classes that match your JavaScript selectors:

```html
<input type="text" id="name" placeholder="Enter your name">
<input type="email" id="email" placeholder="Enter your email">
<input type="password" id="password" placeholder="Enter your password">
<button type="submit">Submit</button>
```

The JavaScript automatically validates on input or submit (depending on your implementation).

---

## 🧪 Example JavaScript Validation

```javascript
const nameInput = document.getElementById("name");

nameInput.addEventListener("input", () => {
  if (nameInput.value.length < 3) {
    nameInput.classList.add("invalid");
  } else {
    nameInput.classList.remove("invalid");
    nameInput.classList.add("valid");
  }
});
```
---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create a new branch

3. Commit your changes

4. Push your branch

5. Submit a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

### 👤 Author

#### Mirnes Glamočić
🌐 https://mirnesglamocic.com

📧 Contact available on the website

---

### ⭐ Acknowledgments

Thank you for trying JavaScript form validation!

Feel free to send suggestions or improvements.

---

### ⭐ If you find this project helpful, please give it a star!
