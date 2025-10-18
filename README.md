# 🧪 API Testing Project — Restful Booker

## 📖 Overview
This project demonstrates **API testing** using **Postman** and **Newman** on the [Restful Booker API](https://restful-booker.herokuapp.com).  
It covers both **positive** and **negative** test scenarios — including booking creation, authentication, updating, deletion, and error handling — all documented and automated.

---

## 🧰 Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Postman** | Manual API testing |
| **Newman** | Command-line automation and reporting |
| **Excel** | Test case documentation |
| **GitHub** | Version control and portfolio showcase |

---

## ✅ Features Tested
| Category | Description |
|-----------|-------------|
| **Booking Creation** | Create new bookings with valid and invalid data |
| **Authentication** | Generate token using valid and invalid credentials |
| **Update Booking** | Update with/without token, invalid data |
| **Delete Booking** | Delete with/without token |
| **Get Booking** | Retrieve booking by ID and handle invalid ID |

---

## ⚙️ How to Run Tests

Run all tests and generate HTML reports:
```bash
newman run postman_collection/restful_booker_collection.json
