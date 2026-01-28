# School System Login and Registration

## 📌 Project Overview
This project is a simple **School System web interface** created using **HTML and CSS only**.  
It demonstrates a basic **Login → Dashboard → Logout flow** and includes a **User Registration page**.  
The system is for **front-end practice only** and does not use a database or backend logic.

---

## 🧩 Features
- Login Page with username and password fields
- Registration Page for new users
- Student Dashboard with a sample data table
- Navigation using anchor tags (`<a>`)
- Consistent UI design using a single CSS file
- Logout functionality that redirects back to the login page

---

## 📁 Project Structure
├── login.html
├── register.html
├── dashboard.html
├── style.css
└── README.md


---

## 🖥️ Pages Description

### 🔐 Login Page (`login.html`)
**Purpose:**  
Allows users to access the system.

**Components:**
- Username input field
- Password input field
- Login button
- Link to the Register page

**How it works:**
1. User enters a username and password
2. Clicking **Login** redirects the user to `dashboard.html`
3. Clicking **Register here** opens the registration page

---

### 📝 Register Page (`register.html`)
**Purpose:**  
Allows new users to create an account.

**Components:**
- Full Name
- Username
- Email
- Password
- Confirm Password
- Register button
- Link back to Login page

**How it works:**
1. User fills out the registration form
2. Clicking **Register** redirects the user to `login.html`
3. Clicking **Login here** also returns to the Login page

⚠️ *Note:* This page does not store user data. It is for UI demonstration only.

---

### 📊 Dashboard Page (`dashboard.html`)
**Purpose:**  
Displays a sample student dashboard after login.

**Components:**
- Welcome message
- Table showing sample student data (ID, Name, Email, Course)
- Logout link

**How it works:**
1. User is redirected here after logging in
2. The dashboard displays static sample data
3. Clicking **Logout** redirects the user back to `login.html`

---

## 🎨 Styling (`style.css`)
- Uses a clean and modern layout
- Same color scheme across all pages
- Responsive form containers
- Styled table for dashboard data
- Hover effects for buttons and links

---

## ⚙️ Technologies Used
- HTML5
- CSS3

No JavaScript, backend, or database is used in this project.

---

## 🚀 How to Run the Project
1. Download or clone the repository
2. Open `login.html` in any modern web browser
3. Navigate through the system using the provided buttons and links

---

## 📚 Educational Purpose
This project was created to practice:
- HTML forms
- Page navigation using anchor tags
- CSS layout and styling
- Basic front-end application flow
- GitHub repository submission

---

## 👤 Author
**Vincent Torrejas**

---

## 📄 License
This project is for educational purposes only.
