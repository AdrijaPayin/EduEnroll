# 🎓 EduEnroll: Student Application Form

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)

EduEnroll is a responsive, web-based Student Application Form featuring real-time client-side validation. Designed with a clean and intuitive user interface, it secures user data entry pipelines before submission—ensuring school databases receive perfectly formatted information every time.

🌐 **[Live Demo Interface](https://adrijapayin.github.io/student-application-form/)**

---

## ✨ Key Highlights & Features

* 👤 **Comprehensive Profiling:** Structured inputs capture essential student personal details smoothly.
* 🔘 **Mutually Exclusive Class Choice:** Implements native radio button constraints allowing selection of only one grade level at a time.
* 📊 **Smart Academic Matrix Table:** Built-in tabular fields for entering subject marks, featuring automated boundary validation strictly enforcing scores between `0` and `100`.
* 🛡️ **Regex Validation Guards:** * 📞 **Phone Field:** Rejects any input that isn't exactly a 10-digit sequence.
  * 📍 **PIN Code Field:** Enforces standard geographical 6-digit numeric configurations.
* 🔒 **Submission Gatekeeper:** The submit trigger button remains dynamically disabled until all inputs are valid and the **Terms & Conditions** checkbox is checked.

---

## 📂 Project Architecture

```text
├── index.html          # Structural document layout and input elements
├── css/
│   └── style.css       # Custom styles, responsive grid layout, and form themes
└── js/
    └── validation.js   # Client-side validation engines and dynamic DOM mutations
