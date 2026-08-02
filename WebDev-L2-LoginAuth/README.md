# Login & Signup Authentication System

**Oasis Infobyte SIP — Web Development & Designing Track — Level 2, Task 4**

## Objective
A client-side login and signup system with form validation, duplicate-account prevention, and a simulated authenticated state — built without a backend, using localStorage to persist accounts.

## Tech Stack
- HTML5
- CSS3
- JavaScript (Vanilla)

## Features
- Toggle between Login and Sign Up views
- Signup form validation: required name, valid email format, minimum password length (6+ characters), password confirmation match
- Duplicate email detection on signup
- Login form validation: valid email format, required password, incorrect credentials handling
- Simulated authenticated "dashboard" view showing the logged-in user's name and email
- Log out returns to the login screen
- Accounts persist across page reloads using localStorage
- Dark, modern-tech themed design consistent with the rest of the portfolio site
- Fully responsive layout

## How to Run
Open `index.html` in any modern browser — no build steps or dependencies required.

## File Structure
WebDev-L2-LoginAuth/
├── index.html
├── style.css
└── README.md