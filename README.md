# HTML Compiler

## 📄 Project Overview

The **HTML Compiler** is a Python/Java-based tool that parses, validates, corrects, and optimizes HTML code. It is designed to help developers write clean, semantically correct, and accessible HTML by analyzing input files, detecting structural and syntactic errors, and offering best-practice suggestions.

---

## 🚀 Features

- 🔍 **Error Detection**
  - Unclosed or unmatched tags
  - Improper tag nesting
  - Duplicate IDs
  - Missing or invalid attributes (e.g., `alt` in `<img>`, `href` in `<a>`)

- 🛠️ **Automatic Correction**
  - Adds missing closing tags
  - Corrects nesting and order of tags
  - Renames duplicate IDs
  - Flags and minimizes inline styles

- 📈 **Optimization & Best Practices**
  - Suggests semantic tags (`<header>`, `<main>`, `<footer>`, etc.)
  - Encourages external stylesheets over inline styles
  - Formats code with proper indentation and spacing

- ♿ **Accessibility Enhancements**
  - Highlights missing ARIA roles or required accessibility attributes
  - Promotes best practices for inclusive design

- 📦 **Output Generation**
  - Corrected HTML file
  - Live Preview Renderer
  - Detailed Diagnostic Report (Errors, Warnings, Fixes)

---

## ⚙️ How It Works

1. **HTML Parsing and Analysis**
   - Tokenizes the HTML structure
   - Validates tag hierarchy and attribute usage

2. **Error Detection and Fixing**
   - Locates unclosed/misplaced tags, duplicate IDs, etc.
   - Automatically corrects minor structural issues

3. **Code Optimization**
   - Suggests semantic and accessible tag alternatives
   - Improves indentation and code readability

4. **Output Generation**
   - Provides:
     - Original and corrected HTML code
     - Live HTML preview (rendered)
     - Diagnostic report of issues and fixes

---


