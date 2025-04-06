# 🔐 Password Strength Indicator

A simple and effective Python script to check the strength of a password using regular expressions. It guides users to create more secure passwords by providing real-time feedback based on strength criteria.

## 🧰 Features

- Validates if a password:
  - Is at least 8 characters long
  - Contains at least one uppercase letter
  - Contains at least one lowercase letter
  - Includes at least one number
  - Has at least one special character (e.g. `@#$%^&*`)
- Provides specific suggestions to improve weak passwords
- Easy to customize and extend

## 📦 Requirements

- Python 3.x

Uses only built-in libraries:
```python
import re
