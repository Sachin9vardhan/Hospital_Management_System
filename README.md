# Hospital Management System

A real-world inspired desktop application for managing hospital operations like patient records, appointments, and staff interaction.

This system is developed using:

* Java Swing (GUI)
* Spring Boot (Backend)
* MySQL or H2 Database
* RESTful APIs
* OOP design principles

---

## 📁 Project Structure

```
hospital-management-system/
├── backend/              # Spring Boot backend (API & DB)
│   ├── controllers/
│   ├── models/
│   ├── services/
│   ├── repositories/
│   └── HospitalManagementApplication.java
│
└── desktop-client/       # Java Swing frontend
    ├── views/
    ├── models/
    ├── controllers/
    └── Main.java
```

---

## 🚀 Getting Started

### Prerequisites

* Java 17+
* Maven
* MySQL (optional, H2 in-memory DB also supported)

### Backend Setup (Spring Boot)

1. Navigate to backend folder:

   ```bash
   cd backend
   ```
2. Configure database in application.properties
3. Build and run:

   ```bash
   mvn spring-boot:run
   ```

### Frontend Setup (Swing)

1. Open desktop-client project in IntelliJ or any Java IDE
2. Run `Main.java`

---

## 🌟 Features

### User Roles:

* Admin
* Doctor
* Receptionist

### Functional Modules:

* Patient registration and search
* Appointment scheduling
* Doctor's medical records management
* Role-based access control

---

## 🔐 Security

* Backend secured with role-based access
* Future support for JWT or session authentication

---

## 📡 API Endpoints (Sample)

| Method | Endpoint          | Description          |
| ------ | ----------------- | -------------------- |
| GET    | /api/patients     | Get all patients     |
| POST   | /api/patients     | Add new patient      |
| GET    | /api/doctors      | List all doctors     |
| POST   | /api/appointments | Schedule appointment |

---

## 📦 Technologies Used

* Java
* Spring Boot
* Hibernate (JPA)
* Java Swing
* MySQL / H2

---

## 📌 TODO

* [ ] Add authentication & login GUI
* [ ] Add PDF export for reports
* [ ] Add support for medical billing

---

