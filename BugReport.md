# 🐞 Bug Report – Internshala Login Page

This document lists the bugs found during manual testing of the Internshala login page.

---

| Bug ID | Description                              | Steps to Reproduce                                                                 | Expected Result                                      | Actual Result                                       | Severity | Status |
|--------|------------------------------------------|-------------------------------------------------------------------------------------|------------------------------------------------------|----------------------------------------------------|----------|--------|
| BUG01  | Password visibility icon not working     | 1. Go to login page  <br> 2. Enter password <br> 3. Click eye icon                 | Password should toggle between visible and hidden    | Nothing happens                                     | Medium   | Open   |
| BUG02  | No validation message for empty email    | 1. Go to login page <br> 2. Leave email blank <br> 3. Click login                 | Show “Email is required” message                     | No message is shown                                | High     | Open   |
| BUG03  | Typo in password field placeholder       | 1. Visit login page <br> 2. Check password field placeholder text                  | Should say “Enter password”                          | Shows “Enter pasword” (spelling mistake)           | Low      | Open   |
| BUG04  | Login button enabled with empty fields   | 1. Open login page <br> 2. Leave email and password blank <br> 3. Observe button   | Login button should remain disabled                  | Login button is clickable even with empty fields   | High     | Open   |
| BUG05  | Incorrect login redirects with no error  | 1. Enter wrong credentials <br> 2. Click login                                     | Show “Invalid login” message                         | Redirects with no error shown                      | High     | Open   |

---



