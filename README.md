# Booking Project
**Web-Based Appointment and Reservation Management System**

---

## 1. Project Identification
| Subject | Detail |
| :--- | :--- |
| **Project Name** | Booking Project |
| **Developer** | Ratchanon Noknoy |
| **Core Technology** | PHP (Server-Side) / MySQL (Database) |
| **Repository URL** | [github.com/ratchanon-noknoy2318/Booking-Project](https://github.com/ratchanon-noknoy2318/Booking-Project) |
| **Live Portfolio** | [ratchanon-portfolio.onrender.com](https://ratchanon-portfolio.onrender.com/) |
| **License** | MIT License |

---

## 2. System Architecture
The application is built using a **Modular Multilayer Architecture**, ensuring a clean Separation of Concerns (SoC). This structure facilitates easier maintenance and secure data handling between the client and the server.

| Layer | Responsibility | Technical Implementation |
| :--- | :--- | :--- |
| **Presentation Layer** | User Interface & UX | Developed using semantic HTML5 and Custom CSS3. Implements responsive design principles to ensure cross-browser and cross-device compatibility. |
| **Application Layer** | Business Logic | Powered by PHP to manage user authentication, session states, and the core reservation workflow (booking logic). |
| **Data Access Layer** | Persistence & Security | Utilizes MySQL for relational data storage. Employs Prepared Statements to mitigate SQL Injection risks and maintain data integrity. |

---

## 3. User Roles & Capabilities
The system provides a distinct experience for two primary user tiers:

| Role | Functional Capabilities |
| :--- | :--- |
| **User Portal** | Account registration, secure authentication, real-time availability viewing, and submission of room or appointment reservations. |
| **Admin Portal** | Centralized management dashboard for oversight of all system activities, including the ability to approve, modify, or cancel any booking. |

---

## 4. Technical Specifications
| Category | Specification | Description |
| :--- | :--- | :--- |
| **Backend Engine** | PHP 7.4+ | Server-side execution for processing logic and database interaction. |
| **Database** | MySQL | Relational database management system for secure record persistence. |
| **Frontend Style** | Custom CSS3 | Native styling approach for optimized performance and lightweight asset delivery. |
| **Security** | Secure Hashing & PDO | Implementation of industry-standard security practices for data and password protection. |
| **Environment** | LAMP / WAMP / LEMP | Optimized for deployment on standard PHP-enabled web servers. |

---

## 5. Functional Capabilities
| Feature | Technical Detail |
| :--- | :--- |
| **Conflict Prevention** | Algorithmic checking of database records to prevent overlapping schedules and double-booking. |
| **Input Sanitization** | Server-side validation and filtering of user inputs to ensure system stability. |
| **State Management** | PHP-based session control to manage user login states and administrative privileges. |
| **Administrative Control** | High-level CRUD operations (Create, Read, Update, Delete) for reservation management. |

---

## 6. Installation & Deployment
| Step | Action | Instruction |
| :--- | :--- | :--- |
| 1 | **Clone Repository** | `git clone https://github.com/ratchanon-noknoy2318/Booking-Project.git` |
| 2 | **Database Setup** | Import the provided SQL schema from the `/sql` directory into your MySQL server. |
| 3 | **Configuration** | Update the database connection parameters in the `config/` directory files. |
| 4 | **Access** | Deploy the directory to your web server and access the application via `localhost` or your domain. |

---

## 7. Contact Information
| Channel | Detail |
| :--- | :--- |
| **LinkedIn** | [linkedin.com/in/ratchanon-noknoy](https://www.linkedin.com/in/ratchanon-noknoy/) |
| **Portfolio** | [ratchanon-portfolio.onrender.com](https://ratchanon-portfolio.onrender.com/) |
| **Email** | ratchanon.noknoy2318@gmail.com |

---
*Copyright (c) 2024 Ratchanon Noknoy. All Rights Reserved.*
