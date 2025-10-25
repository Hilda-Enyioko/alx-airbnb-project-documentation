# Airbnb Clone Backend — Use Case Diagram

## Objective
The objective of this task is to **visualize the system interactions** between users and the backend system through a **Use Case Diagram**.  
This diagram illustrates how different types of users (actors) — such as guests, hosts, and admins — interact with the system to perform various operations like registration, booking, and payment.

---

## 1. Key Actors

| Actor | Description |
|-------|--------------|
| **Guest (User)** | A user who signs up to browse, book, and review properties. |
| **Host** | A user who lists properties, manages bookings, and communicates with guests. |
| **Admin** | The system administrator responsible for user management, property moderation, and platform monitoring. |
| **Payment Gateway** | An external system integrated for handling payments (e.g., PayPal, Stripe, Credit Card). |

---

## 2. Primary Use Cases

### **For Guest**
- Register an account  
- Log in / Log out  
- Search for properties  
- View property details  
- Book a property  
- Make payment  
- Cancel booking  
- Write and view reviews  
- Send messages to hosts  

### **For Host**
- Register as host / Upgrade account  
- Log in / Log out  
- Add property listing  
- Edit or delete property  
- View bookings for their properties  
- Accept or reject bookings  
- Communicate with guests through messaging  
- View guest reviews  

### **For Admin**
- Log in to dashboard  
- Manage users (activate/deactivate accounts)  
- Manage properties (approve or remove listings)  
- Oversee payments and refunds  
- Handle reports and policy violations  

### **For Payment Gateway**
- Process booking payments  
- Validate transaction details  
- Send payment confirmation to system  

---

## 3. Relationships Between Actors and Use Cases

| Relationship Type | Example |
|--------------------|---------|
| **Include (→)** | “Book Property” → *includes* → “Make Payment” |
| **Extend (↪)** | “Register Account” ↪ *extends* → “Email Verification” |
| **Association (—)** | “Guest” — “Book Property” (direct interaction) |

---

## 4. System Overview (Use Case Description)

The **Airbnb Clone System** allows guests to search and book properties listed by hosts.  
When a guest books a property, the payment gateway handles the transaction and updates the booking status.  
Admins manage overall platform integrity, while both guests and hosts can communicate directly through a built-in messaging feature.

---

## 5. Visual Representation

### Diagram Overview

Below is the list of components you should include in your **Draw.io Use Case Diagram**:

#### **Actors**
- Guest (User)
- Host
- Admin
- Payment Gateway

#### **Use Cases**
1. Register / Login  
2. Manage Profile  
3. Add Property  
4. Search Property  
5. Book Property  
6. Make Payment  
7. Manage Booking  
8. Leave Review  
9. Send Message  
10. Manage Users (Admin)  
11. Manage Properties (Admin)  
12. Process Payments (Gateway)

#### **Associations**
- Guest → Register, Login, Search, Book, Pay, Review, Message  
- Host → Register, Login, Add Property, Manage Property, Manage Booking, Message  
- Admin → Manage Users, Manage Properties, Oversee Payments  
- Payment Gateway → Process Payments  

---

## 6. Deliverable

- **File Name:** `use-case-diagram.png`  
- **File Path:** `use-case-diagram/use-case-diagram.png`  
- **Tool Used:** [Draw.io](https://savanna.alxafrica.com/rltoken/C9c1zKT6CST6FiUa6r6jUg)  
- **Repository:** `alx-airbnb-project-documentation`

---

## ✅ Summary

The **Use Case Diagram** visually captures how:
- **Guests** interact with the platform to book stays and make payments.  
- **Hosts** manage property listings and bookings.  
- **Admins** maintain system control and monitor activities.  
- **Payment Gateway** handles transaction validation and processing.

This diagram serves as the **foundation for defining system requirements** and ensuring clarity in backend implementation and testing.

---

**Author:** *Hilda*  
**Repository:** `alx-airbnb-project-documentation`
