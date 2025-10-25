# Airbnb Clone — User Stories

## Objective
This document translates the **Use Case Diagram** interactions into actionable **User Stories** that describe how users interact with the Airbnb Clone system.  
Each story follows the format:  
> “As a [type of user], I want to [perform an action] so that I can [achieve a goal].”

---

## 🧑‍💻 1. User Registration and Authentication
**User Story:**  
As a **new user**, I want to be able to **create an account and log in securely** so that I can **access and use the Airbnb platform**.  

**Acceptance Criteria:**
- User can register with email and password.
- The system validates unique email addresses.
- Users can log in and log out successfully.
- Passwords are encrypted for security.

---

## 🏠 2. Property Listing (Host)
**User Story:**  
As a **host**, I want to **add and manage property listings** so that I can **rent out my spaces to potential guests**.  

**Acceptance Criteria:**
- Hosts can create, update, and delete listings.
- Each listing includes title, description, location, and price per night.
- Listings are visible to all registered guests for booking.

---

## 🔍 3. Property Search and Booking (Guest)
**User Story:**  
As a **guest**, I want to **search for available properties and book one** so that I can **plan my stay easily**.  

**Acceptance Criteria:**
- Guests can search using filters like location, price, or property type.
- The system displays only available properties.
- Guests can view details before booking.
- Booking is confirmed once payment is made.

---

## 💳 4. Payment Processing
**User Story:**  
As a **guest**, I want to **make secure payments for my bookings** so that I can **complete my reservation without issues**.  

**Acceptance Criteria:**
- Guests can pay using credit card, PayPal, or Stripe.
- Payment details are securely processed through the payment gateway.
- The system generates a payment receipt and confirmation.

---

## 💬 5. Messaging Between Users
**User Story:**  
As a **guest or host**, I want to **send and receive messages** so that I can **communicate about property details, check-in times, or questions before booking**.  

**Acceptance Criteria:**
- Messages show sender and recipient details.
- Users can view message history.
- Notifications appear for new messages.

---

## ⭐ 6. Reviews and Ratings
**User Story:**  
As a **guest**, I want to **leave a review and rating for the property** so that I can **share feedback with other users**.  

**Acceptance Criteria:**
- Reviews include a rating between 1–5 and a comment.
- Hosts can view all reviews related to their listings.
- Reviews are displayed on the property detail page.

---

## 🛠️ 7. Admin Management
**User Story:**  
As an **admin**, I want to **monitor and manage users, properties, and transactions** so that I can **maintain a safe and reliable platform**.  

**Acceptance Criteria:**
- Admins can view user and property records.
- Admins can approve or remove listings.
- Admins can review flagged accounts or content.

---

## ✅ Summary
These user stories outline the key functionalities of the Airbnb Clone backend:
- User authentication and access control.  
- Property listing and management.  
- Booking and secure payment flow.  
- User communication and feedback systems.  
- Administrative oversight for platform quality.

**Next Steps:**  
These user stories will guide backend API design, database schema, and feature implementation.

---

**Author:** *Hilda*  
**Repository:** `alx-airbnb-project-documentation`
