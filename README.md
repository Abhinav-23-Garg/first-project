# 🚑 Health System - Login & Dashboard

This project is a simple **HTML & CSS based system** with separate login/registration pages for **Users** and **Doctors**.  
It is designed as a lightweight prototype (no JavaScript or backend required).

---

## 📂 Project Structure


├── index.html # Main landing page (choose User or Doctor)
├── user_registration.html # User registration page (Phone + DOB)
├── user_login.html # User login/dashboard page
├── doctor_registration.html # Doctor login page (Doctor ID + Password)
├── doctor_login.html # Doctor dashboard (Attend Call, Queue, Logout)
├── README.md # Project documentation



---

## ✨ Features
### 🔹 User Side
- Register using **Phone Number** and **Date of Birth**.
- Redirected to **User Login page** after registration.

### 🔹 Doctor Side
- Login with **Doctor ID (10 digits)** and **Password (6 digits only numbers)**.
- Redirected to **Doctor Dashboard**.
- Dashboard includes:
  - 📞 **Attend Call** button
  - 👥 **View Patient Queue** button
  - 🚪 **Logout** button

### 🔹 Styling
- Clean **modern UI** using only **HTML + CSS**.
- Centered, responsive design with animations and gradients.
- No JavaScript or backend is required (purely static prototype).

---

## 🚀 How to Run
1. Download or clone this repository.
2. Open `index.html` in your browser.
3. Navigate between pages:
   - **User →** Register and go to `user_login.html`.
   - **Doctor →** Login and go to `doctor_login.html`.

---

## 🛠️ Tech Stack
- **HTML5**
- **CSS3 (with Flexbox & Animations)**
- **No JavaScript**
- **No Backend**

---

## 📌 Next Steps (Future Enhancements)
- Add backend (Node.js/Express or Django) to handle authentication.
- Connect Doctor’s **Attend Call** button to a **video/audio system** (WebRTC).
- Store patient queue dynamically in a database.
- Enhance security with hashed password storage.

---

👨‍⚕️ Designed for **Smart India Hackathon Prototype**  
