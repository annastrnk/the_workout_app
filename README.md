# Next.js Auth Project (Learning Project)

This project was built while I was learning **Next.js** and modern authentication practices.  
It demonstrates how to implement a simple authentication system using **Lucia Auth** and **SQLite**.

---

## ✨ Features

- **User signup** – register new users  
-  **Store users in SQLite database**  
-  **Password hashing** – secure storage of passwords  
-  **Email duplication check** – prevent duplicate accounts  
-  **Lucia Auth integration** – manage sessions and authentication  
-  **Session & session cookie configuration**  
-  **Create and store auth sessions** after login/signup  
-  **Verify active auth sessions** to identify logged-in users  
-  **Protect routes** from unauthorized access  
-  **Switch auth modes with query parameters** (login ↔ signup)  
-  **User login via Server Actions**  
-  **Auth-only layout** – pages only accessible when logged in  
-  **User logout** – clear session and remove cookie  

---

## 🛠️ Tech Stack

- [Next.js 15+ (App Router)](https://nextjs.org/)  
- [Lucia Auth](https://lucia-auth.com/)  
- [SQLite](https://www.sqlite.org/) with `better-sqlite3` adapter  
- Server Actions (for authentication flow) 