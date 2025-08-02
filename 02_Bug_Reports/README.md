# 🐞 Bug Report: Login Form - No Error Message When Fields Are Empty

| Field            | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **ID**           | BUG-LOGIN-001                                                               |
| **Title**        | Missing validation message when submitting empty login form                 |
| **Reported By**  | Adrio Welly Rolando                                                         |
| **Environment**  | Web Banking                                                                 |
| **Severity**     | Medium                                                                      |
| **Priority**     | High                                                                        |
| **Status**       | Open                                                                        |
| **Date Reported**| 2025-08-02                                                                  |

## ✅ Pre-Condition:
User is on the login page of the Web Banking application.

## 🧪 Steps to Reproduce:
1. Open the login page.
2. Leave both the **username** and **password** fields empty.
3. Click on the **"Login"** button.

## 🎯 Expected Result:
System should display an inline validation message such as:
- “Username is required”
- “Password is required”

## ❌ Actual Result:
No validation message appears. The form looks inactive with no user feedback, leading to confusion.

## 📸 Screenshots:
📷 Screenshot not available as this is a dummy scenario for portfolio purposes.

## 📌 Suggested Fix:
Implement required field validation with user-friendly error messages for better UX.
