# HTML Authentication System (POC)

## Overview

This project is a simple Proof-of-Concept authentication flow implemented using only HTML.
It demonstrates page navigation between common authentication screens without using CSS, JavaScript, or any backend technology.

The goal of the project is to understand basic web page structure and hyperlink-based navigation.

---

## Pages Included

* **Home (index.html)** – Main navigation page containing links to all modules
* **Login (login.html)** – User login form
* **Register (register.html)** – New user registration form
* **Forgot Password (forgot-password.html)** – Request password reset
* **Reset Password (reset-password.html)** – Create a new password
* **Dashboard (dashboard.html)** – Landing page after login

---

## Navigation Flow

### Login Flow

Home → Login → Dashboard → Logout → Login

### Registration Flow

Home → Register → Login

### Password Recovery Flow

Home → Forgot Password → Reset Password → Login

---

## Technologies Used

* HTML5 only
* Anchor tag navigation
* Form redirection using action attribute

No CSS or JavaScript is used in this project.

---

## How to Run the Project

### Method 1 (Recommended – VS Code Live Server)

1. Open the project folder in VS Code
2. Install the **Live Server** extension
3. Right click `index.html`
4. Click **Open with Live Server**

### Method 2 (Direct Browser)

Open `index.html` directly in any web browser.

---

## Project Purpose

This project is created for academic demonstration of:

* HTML page structure
* Hyperlink navigation
* Form redirection behavior

It does not perform real authentication or data storage.

---

## Author

Student Assignment Submission
