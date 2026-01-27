# Booking System with LINE Notify (Internship)

**Automated Reservation Platform**  

---

## System Summary
| Item | Detail |
| :--- | :--- |
| Project | Booking System with LINE Notify |
| Type | Internship Project |
| Backend | PHP |
| Database | MySQL |
| Integration | LINE Notify API |
| Live System (Login) | https://kosamphi.moph.go.th/booking/login.php |

> Note: The live system is restricted to authorized internal users.

---

## Architecture Overview
| Layer | Description |
| :--- | :--- |
| Presentation | User and Admin web pages |
| Business Logic | Booking validation and availability checks |
| Integration | LINE Notify API handling |
| Data Layer | MySQL data persistence |

---

## Directory Structure
| Path | Responsibility |
| :--- | :--- |
| `/core` | Core booking logic and notification handling |
| `/config` | Database and LINE Notify configuration |
| `/modules` | Booking, user, and admin modules |
| `/assets` | Static resources (CSS / JavaScript) |
| `/uploads` | Optional file attachments |

---

## Booking & Notification Flow
| Step | Process |
| :--- | :--- |
| 1 | User submits booking request |
| 2 | System validates availability |
| 3 | Data stored in MySQL |
| 4 | LINE Notify sends alert to admin |
| 5 | Admin approves or rejects |
| 6 | System notifies user via LINE |

---

## Design Considerations
| Focus | Approach |
| :--- | :--- |
| Maintainability | Modular system structure |
| Reliability | Server-side validation |
| User Experience | Real-time notifications |
| Simplicity | Lightweight backend implementation |

---

## Developer
| Name | Contact |
| :--- | :--- |
| **Ratchanon Noknoy** | https://www.linkedin.com/in/ratchanon-noknoy/ |

---

MIT License © 2024 Ratchanon Noknoy
