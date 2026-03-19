#  Kabuya Secure Secrets - Full-Stack Authentication App

##  Project Overview
This is a modern Full-Stack web application developed to demonstrate secure user authentication practices. It allows users to register, log in, and securely store a personal secret.

##  Technical Stack
* **Backend:** Node.js, Express.js
* **Database:** PostgreSQL (pg)
* **Authentication:** Passport.js (Local Strategy), Express-session
* **Security:** Bcrypt (Password Hashing), Dotenv (Environment Variables)
* **Frontend:** EJS (Embedded JavaScript), CSS3 (Modern Glassmorphism UI)

##  Key Features & Security Implementation
1.  **Password Hashing:** Implemented `Bcrypt` to hash passwords with a salt factor of 10, ensuring user data remains unreadable even if the database is compromised.
2.  **Session Management:** Integrated `Express-session` and `Passport.js` to manage persistent user logins via secure cookies.
3.  **Data Privacy:** Used `Dotenv` to hide sensitive database credentials (User, Host, Password) from the public source code.
4.  **Modern UI:** Designed a responsive "Glassmorphism" interface with a blurred background effect and professional typography (Poppins).

