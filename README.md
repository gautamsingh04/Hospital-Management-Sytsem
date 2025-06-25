# 🏥 Hospital Management System

A simple yet functional Hospital Management System built using C++. This project simulates basic hospital operations such as managing patient records, doctor records, appointment bookings, and billing.

---

## 📌 Features

- 👨‍⚕️ Doctor registration and listing
- 🧑‍🦽 Patient registration and record management
- 📅 Appointment scheduling
- 💰 Billing and payment details
- 📂 File-based data storage (no external database required)
- 🧾 Clear menu-driven user interface in terminal

---

## 🛠️ Tech Stack

- Language: **C++**
- Data Storage: **File Handling in C++**
- IDE: Any C++ supported IDE (e.g., Code::Blocks, Visual Studio, VS Code)

---

## 📂 Project Structure

```
Hospital-Management-Sytsem/
│
├── main.cpp                  # Entry point for the application
├── doctor.cpp                # Logic for doctor-related functionalities
├── patient.cpp               # Logic for patient management
├── appointment.cpp           # Appointment handling
├── billing.cpp               # Billing system
├── headers/
│   ├── doctor.h              # Doctor class definitions
│   ├── patient.h             # Patient class definitions
│   ├── appointment.h         # Appointment class definitions
│   ├── billing.h             # Billing class definitions
│   └── utilities.h           # Common utility functions
└── README.md                 # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/gautamsingh04/Hospital-Management-Sytsem.git
cd Hospital-Management-Sytsem
```

### 2. Compile the Program

If you're using g++:

```bash
g++ main.cpp doctor.cpp patient.cpp appointment.cpp billing.cpp -o hospital
```

### 3. Run the Application

```bash
./hospital
```

---

## 📸 Screenshots

> _You can add terminal screenshots of the program in action here to visually showcase functionality._

---

## ✅ Future Improvements

- GUI using Qt or a web front-end
- Database integration (MySQL or SQLite)
- Admin login and role-based access control
- Medical history and report uploads

---

## 🧑‍💻 Author

**Gautam Singh**  
🔗 [GitHub](https://github.com/gautamsingh04)  
📧 gautamsingh0406@gmail.com

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
