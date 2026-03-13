<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0533,50:2d1b69,100:11998e&height=220&section=header&text=🏨%20Hotel%20Room%20Booking&fontSize=46&fontColor=ffffff&fontAlignY=42&desc=Management%20System%20%7C%20CodeIgniter%20%7C%20PHP%20%7C%20MySQL&descSize=15&descAlignY=62&descColor=ffffffcc&animation=fadeIn" width="100%" />

<br/>

[![HTML](https://img.shields.io/badge/HTML-34.2%25-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/karthikbm33/Hotel-Room-Booking-Management-System)&nbsp;
[![JavaScript](https://img.shields.io/badge/JavaScript-30.4%25-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/karthikbm33/Hotel-Room-Booking-Management-System)&nbsp;
[![PHP](https://img.shields.io/badge/PHP-29.6%25-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://github.com/karthikbm33/Hotel-Room-Booking-Management-System)&nbsp;
[![CSS](https://img.shields.io/badge/CSS-5.8%25-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://github.com/karthikbm33/Hotel-Room-Booking-Management-System)

[![License](https://img.shields.io/badge/License-GPL--3.0-11998e?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](./LICENSE)&nbsp;
[![Status](https://img.shields.io/badge/Status-Under%20Development-orange?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karthikbm33/Hotel-Room-Booking-Management-System)&nbsp;
[![Stars](https://img.shields.io/github/stars/karthikbm33/Hotel-Room-Booking-Management-System?style=for-the-badge&logo=apachespark&color=2d1b69&logoColor=white)](https://github.com/karthikbm33/Hotel-Room-Booking-Management-System/stargazers)

</div>

---

## 📖 About

**Hotel Room Booking Management System** is a full-stack web application that allows hotels to manage room bookings, guests, and administration from a single dashboard. Built using the **CodeIgniter PHP framework** with a **MySQL** database, running on a **XAMPP** local server.

> ⚠️ *This project is currently under active development.*

---

## ✨ Features

<div align="center">

| # | Feature | Description |
|:---:|:---|:---|
| 🔐 | **Admin Login** | Secure admin authentication system |
| 🏠 | **Room Management** | Add, edit, delete hotel rooms |
| 📅 | **Booking System** | Create and manage room reservations |
| 👥 | **Guest Management** | Track guest details and history |
| 📊 | **Dashboard** | Overview of bookings and availability |
| 🗄️ | **MySQL Database** | Persistent data storage via `lodge.sql` |

</div>

---

## 🛠️ Tech Stack

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-EF4223?style=for-the-badge&logo=codeigniter&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?style=for-the-badge&logo=xampp&logoColor=white)

</div>

---

## 🚀 Getting Started

### 📋 Prerequisites

```
✅ XAMPP (Apache + MySQL)
✅ PHP >= 7.4
✅ Browser (Chrome / Firefox)
✅ Git (optional)
```

### ⚙️ Installation Steps

```bash
# Step 1 — Clone the repository
git clone https://github.com/karthikbm33/Hotel-Room-Booking-Management-System.git

# Step 2 — Move to XAMPP htdocs folder
# Windows
C:\xampp\htdocs\Hotel-Room-Booking-Management-System

# macOS / Linux
/opt/lampp/htdocs/Hotel-Room-Booking-Management-System
```

```bash
# Step 3 — Setup the Database
1. Open XAMPP → Start Apache & MySQL
2. Go to → http://localhost/phpmyadmin
3. Create a new database → Name it: lodge
4. Click Import → Select lodge.sql from the repo
5. Click Go ✅
```

```bash
# Step 4 — Configure Database Connection
Open → application/config/database.php

$db['default'] = array(
    'hostname' => 'localhost',
    'username' => 'root',
    'password' => '',
    'database' => 'lodge',
);
```

```bash
# Step 5 — Run the Project
Open browser → http://localhost/Hotel-Room-Booking-Management-System
```

---

## 🔑 Admin Login Credentials

> ⚠️ *For demo / testing purposes only — change before production use*

```
📧  Email     →   email@gmail.com
🔒  Password  →   admin
```

---

## 📂 Project Structure

```
📦 Hotel-Room-Booking-Management-System/
│
├── 📂 application/          ← CodeIgniter app (controllers, models, views)
│   ├── 📂 controllers/      ← Business logic
│   ├── 📂 models/           ← Database models
│   └── 📂 views/            ← HTML templates
│
├── 📂 assets/               ← CSS, JS, images
│   ├── 📂 css/
│   ├── 📂 js/
│   └── 📂 images/
│
├── 📂 system/               ← CodeIgniter core (do not edit)
├── 📄 index.php             ← Entry point
├── 📄 lodge.sql             ← MySQL database file
├── 📄 LICENSE
└── 📄 README.md
```

---

## 🗺️ Roadmap

- [x] 🔐 Admin login system
- [x] 🏠 Room listing & management
- [x] 📅 Booking functionality
- [x] 🗄️ MySQL database integration
- [ ] 👤 Guest self-booking portal *(planned)*
- [ ] 📧 Email confirmation system *(planned)*
- [ ] 💳 Payment gateway integration *(planned)*
- [ ] 📱 Mobile responsive UI *(planned)*

---

## 👤 Author

<div align="center">

<img src="https://github.com/karthikbm33.png" width="90" alt="karthikbm33" />

### **Karthikbm**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karthikbm33)&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://linktr.ee/karthikbm)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](http://www.linkedin.com/in/karthikbm33)&nbsp;
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/Karthikbm33)

</div>

---

## 💬 Support

| 📧 Email | 💬 Telegram |
|:---|:---|
| [karthikshet21@yahoo.com](mailto:karthikshet21@yahoo.com) | [Chat\_kpt](https://t.me/Chat_kpt) |

---

## 🤝 Contributing

Contributions are welcome!

```
1. 🍴  Fork this repository
2. 🌿  git checkout -b feature/your-feature
3. ✏️   Make your changes
4. 📤  git push origin feature/your-feature
5. 🔁  Open a Pull Request
```

---

## 📜 License

```
GPL-3.0 License — Copyright (c) 2025 Karthikbm
```

See the full **[LICENSE](./LICENSE)** file for details.

---

<div align="center">

⭐ *Star this repo if it helped you!*

*Made with ❤️ by **[Karthikbm](https://github.com/karthikbm33)***

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:11998e,50:2d1b69,100:1a0533&height=100&section=footer" width="100%" />

</div>
