
# 🚗 Driving License Management System

A **C# desktop application** with **SQL Server** for managing the full lifecycle of driving licenses: applications, renewals, replacements, tests, and blocking/unblocking.  

---

## 📌 Features
- **Applicant Management**: Store applicant info (National ID, name, DOB, contact, photo).  
- **License Issuance**: First-time, renewals, replacements (lost/damaged), international licenses.  
- **Tests**: Vision, Theory, and Practical tests with retake support.  
- **Categories**: Supports multiple license types with fees, validity, and age restrictions.  
- **Requests**: Track requests by ID or National ID (statuses: New, Canceled, Completed).  
- **System Management**:  
  - User roles & permissions  
  - Blocking/unblocking licenses with fines  
  - Audit logs  

---

## 🪪 License Categories
1. Small Motorcycles – $15, Min Age 18, Valid 5 yrs  
2. Heavy Motorcycles – $30, Min Age 21, Valid 5 yrs  
3. Private Cars – $20, Min Age 18, Valid 10 yrs  
4. Commercial – $200, Min Age 21, Valid 10 yrs  
5. Agricultural Vehicles – $50, Min Age 21, Valid 10 yrs  
6. Buses – $250, Min Age 21, Valid 10 yrs  
7. Heavy Trucks – $300, Min Age 21, Valid 10 yrs  

---

## 🛠️ Tech Stack
- **Frontend**: C# (WinForms / WPF)  
- **Backend**: SQL Server  
- **Architecture**: Layered (Presentation, Business, Data Access)  

---

## ⚙️ Installation
```bash
git clone https://github.com/mohamadnabilsaleh1/Driving-License-Management.git
