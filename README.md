# 🛡️ Spam Filter using Regular Expressions

A JavaScript project that filters spammy or unwanted content from user input using **regular expressions**.  
Built as part of the **freeCodeCamp JavaScript Algorithms and Data Structures Certification**.

## 💡 Features
- Built using HTML, CSS, and JavaScript
- Detects spam phrases using RegEx patterns
- Learn concepts like:
  - Capture groups
  - Character classes
  - Pattern chaining
- Real-time spam detection on user input

## 📘 Overview
Regular expressions (RegEx) are patterns used to match character combinations in strings.  
This project helps you understand and practice:
- Validating text input using chained regex checks
- Matching phrases using flags like `i` (case-insensitive)
- Using `.some()` to check messages against a deny list of expressions

### 🔍 Spam examples that will be flagged by the current logic:

- `Please help me recover my account.`  
- `You will receive 1000 dollars if you act now!`  
- `Dear friend, I need your urgent response.`

These phrases match patterns like `/please help/i`, `/[0-9]+\s*(hundred|thousand)?\s+dollars/i`, and `/dear friend/i`.


## 🔗 View Demo  
[Live Demo](https://abhishekdevelops.github.io/Spam-Filter-Regex)

## 🏆 Part of FreeCodeCamp Project  
This project is part of the **JavaScript Algorithms and Data Structures Certification** by [freeCodeCamp](https://www.freecodecamp.org/).

---
