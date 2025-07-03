# Authentication System

## 📋 Project Description

This is a **basic Authentication System** built using **HTML**, **CSS**, and **JavaScript** as part of my learning journey in web development. It includes three main pages:

1. **Register Page** (`Register Page.html`) – For creating a new account using email, username, and password.
2. **Login Page** (`Login Page.html`) – For logging into an existing account.
3. **Reset Password Page** (`Reset Password Page.html`) – For resetting a forgotten password.

All validation and logic are handled entirely on the **frontend**, and user data is stored using the browser's `localStorage`. A consistent design is maintained using a CSS stylesheet (`styles.css`) and a background image (`web new.jfif`).

> 🧠 **Note**: As a beginner, I used **ChatGPT (AI)** to help generate and guide parts of the code — especially the **password hashing** logic, which is done on the frontend using the **SHA-256 algorithm** with the Web Crypto API. I’m still learning how hashing and authentication systems work, and this project helped me get started.

---

## ⚙️ Technologies Used

- **HTML** – For building the structure of each page
- **CSS** – For styling the pages and setting a common background image
- **JavaScript** – For handling form input, email/username/password verification, and storing user data

### ✅ What the system currently does:

- Validates email format
- Checks for non-empty username and password
- Verifies login credentials based on stored data
- Hashes passwords using **SHA-256** on the frontend

---

## 🚧 Challenges Faced

- Building everything purely on the frontend without any backend support
- Storing and retrieving data using `localStorage`
- Implementing password hashing as a beginner
- Keeping the logic simple and functional across multiple pages

Although I don’t fully understand everything about password hashing yet, working on this project helped me start exploring those topics with AI assistance.

---

## 🌟 Future Features

- Add backend support (e.g., Firebase or Node.js with a database)
- Use server-side hashing for better security
- Add password strength indicators and form feedback messages
- Implement session/token-based login (e.g., JWT)
- Make the layout responsive for mobile and tablets

---

## 🧪 How to Run the Project

1. **Download the project files**:

   - Go to this GitHub repository in your browser.
   - Click the green **Code** button at the top right.
   - Choose **Download ZIP** from the dropdown.
   - Extract the ZIP file to your computer.

   

2. **Open any of the HTML files in your browser**:

   - `Register Page.html`
   - `Login Page.html`
   - `Reset Password Page.html`

3. Make sure these files are in the same folder:

   - `styles.css`
   - `web new.jfif`

Once everything is in place, open the HTML files in a browser like Chrome or Firefox, and you’re good to go!

---

> ⚠️ **Disclaimer**: This is a beginner-level project created for learning purposes only. It does not include secure authentication and should not be used for real applications.
