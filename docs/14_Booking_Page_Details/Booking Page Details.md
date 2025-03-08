---
sidebar_position: 1
---

# 🎟️ 14. Booking Management

Manage **customer bookings**, track payments, control booking statuses, and ensure seamless reservations.

---

## 📌 14.1. Booking List Overview

### 📊 Displayed Data:

| Field                 | Description                                                                                |
| --------------------- | ------------------------------------------------------------------------------------------ |
| **Booking Reference** | Unique ID for each booking.                                                                |
| **User**              | Customer’s name.                                                                           |
| **Number of Guests**  | Total attendees.                                                                           |
| **Booking Amount**    | Total price in SAR.                                                                        |
| **Discount Value**    | Amount deducted as a discount.                                                             |
| **Paid Amount**       | Amount actually paid by the customer.                                                      |
| **Ticket Type**       | Type of ticket (**Morning, Evening, Full Day**).                                           |
| **Booking Date**      | Scheduled date of the booking.                                                             |
| **Creation Date**     | Date and time the booking was made.                                                        |
| **Status**            | Color-coded booking status (**Approved, Canceled, Rejected, Expired, Ready to Complete**). |
| **Actions**           | Options for managing the booking.                                                          |

---

## 🔍 14.2. Booking Filters & Search

🔹 **Filter by Status** → **Approved | Canceled | Rejected | Expired | Ready to Complete**  
📅 **Date Filter** → **Today | Yesterday | Last 7 Days | Last 30 Days | This Month | Last Month | Custom Range**  
🔎 **Search Bar** → Search by **booking reference, user name, or ticket type**

---

## ⚙️ 14.3. Booking Actions Menu

📝 **Show** → View full booking details.  
🗑️ **Delete** → Remove booking from records.  
📜 **Logs** → Track booking modifications and changes.

---

## 📝 14.4. Booking Details Page

### 📌 **Left Panel (Main Booking Information)**

| Field                    | Description                                        |
| ------------------------ | -------------------------------------------------- |
| 📌 **QR Code**           | Scannable code for **check-in**.                   |
| 🔢 **Booking Reference** | Unique identifier (**e.g., KJ25347**).             |
| 📅 **Booking Date**      | Scheduled date (**e.g., 01-05-2025**).             |
| ⏳ **Creation Date**     | Date when the **booking was made**.                |
| 💰 **Paid Amount**       | Amount paid (**e.g., 0 SAR**).                     |
| 💵 **Booking Amount**    | Total cost before discounts (**e.g., 220 SAR**).   |
| 🔄 **Status**            | Current booking status (**e.g., Under Review**).   |
| 🎟️ **Ticket Category**   | Ticket type (**Morning Ticket, Full Day Ticket**). |

### 📌 **Right Panel (Notes Section & Payment Summary)**

| Field                    | Description                                   |
| ------------------------ | --------------------------------------------- |
| 📝 **Notes Dropdown**    | Select or add a **note** for the booking.     |
| 💾 **Save Notes Button** | Saves any **modifications to notes**.         |
| 📜 **Notes Table**       | Displays **added notes** with timestamps.     |
| 💵 **Sub Total**         | Displays the **total cost before discounts**. |
| 🔖 **Discount Applied**  | Shows any **discount applied**.               |
| 💳 **Total Paid**        | Final amount **paid by the customer**.        |

---

## 👥 14.5. Guest Information (Who is Coming Section)

### 📌 Displayed Data:

| Field                    | Example Value         |
| ------------------------ | --------------------- |
| **Name**                 | "Rosalie Quamilbao"   |
| **Phone Number**         | "+966567594567"       |
| **Email**                | "samindbra@gmail.com" |
| **Identity Card Type**   | "Iqama"               |
| **Identity Card Number** | "2549425859"          |
| **Type**                 | "Man"                 |
| **Payment Status**       | "Not Paid"            |
| **Total Amount**         | "220 SAR"             |

---

## 🍽️ 14.6. Activity & Food Sections

Displays **activities or food items associated with the booking**.

| Field             | Description                        |
| ----------------- | ---------------------------------- |
| **Name**          | Activity or food item name.        |
| **User**          | Customer associated with the item. |
| **Quantity**      | Number of items booked.            |
| **Used Quantity** | Number of items used.              |
| **Status**        | Availability or usage status.      |

🔹 **No data appears** if no items have been added.

---

## 🔗 14.7. Booking Interconnection & Functionality

✔️ **Bookings are linked** to the **ticketing system, user management, and payment processing**.  
✔️ **Logs track every modification** to a booking, ensuring **transparency**.  
✔️ **Booking statuses help organize reservations** and prevent **errors in scheduling**.

---
