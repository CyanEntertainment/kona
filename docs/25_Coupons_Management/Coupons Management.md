---
sidebar_position: 1
---

# 💰 25. Coupons Management

Manages the **creation, editing, activation, and organization** of discount coupons.

---

## 📋 25.1. Coupons Overview

### 📊 **Displayed Data:**

| Field          | Description                                                     |
| -------------- | --------------------------------------------------------------- |
| **ID**         | Unique identifier for each coupon.                              |
| **Code**       | The coupon’s unique identifier.                                 |
| **Amount**     | The discount value (**Percentage** or **Fixed Amount**).        |
| **Type**       | Specifies whether the discount is **Percentage** or **Fixed**.  |
| **Valid Date** | The **start and end date** of the coupon validity.              |
| **Status**     | **🟢 Active** (Green) or **🔴 Inactive** (Red).                 |
| **Actions**    | Options to **activate/inactivate, edit, or delete** the coupon. |

---

## 🔍 25.2. Filtering & Search Options

Allows users to **refine their view** of available coupons.

### 🎛 **Filtering Options:**

🔎 **Search Bar** → Search by:  
✔️ **Coupon Code**  
✔️ **Amount**  
✔️ **Type**  
✔️ **Date Range**

📌 **Filter by Status:**  
🟢 **Active** | 🔴 **Inactive**

---

## ⚙️ 25.3. Coupon Actions & Management

Users can **perform various actions** on coupons.

### 🎯 **Available Actions:**

🔻 **Set Coupon to Inactive** → Temporarily disables the coupon **without deleting** it.  
✏️ **Edit** → Opens a **detailed editor** to modify coupon details.  
🗑️ **Delete** → **Permanently removes** the coupon.

---

## ✏️ 25.4. Coupon Creation & Editing

Administrators can **create and modify** discount coupons.

### 📋 **Editable Fields:**

| Field                   | Description                                                                      |
| ----------------------- | -------------------------------------------------------------------------------- |
| **Coupon Type**         | **Fixed** or **Percentage** discount.                                            |
| **Discount Amount**     | Defines the **value of the coupon**.                                             |
| **Code**                | The **unique identifier** of the coupon.                                         |
| **Min Booking Amount**  | Minimum purchase required to **apply the coupon**.                               |
| **Max Discount Amount** | Maximum discount cap (**for percentage-based coupons**).                         |
| **Usage Limits**        | **Per Coupon** (total available uses) and **Per User** (individual usage limit). |
| **Target Users**        | Filters for specific groups (**e.g., Sports Guests, Club Members**).             |
| **Validity Period**     | Selects the **Start Date** & **End Date** via a calendar picker.                 |

### 🎯 **Actions:**

💾 **Save** → Stores the updated coupon details.  
❌ **Cancel** → Discards any changes.

---

## 🔗 25.5. System Integration & Workflow

✔️ **Discount Processing** → Ensures discounts apply **correctly** at checkout.  
✔️ **Automated Activation/Deactivation** → Coupons are **only valid** within the specified date range.  
✔️ **Targeted Promotions** → Allows admins to apply **coupons** to specific **user groups**.

---

## 🎯 25.6. Conclusion

The **Coupons Management Module** provides a **structured way** to handle promotional discounts **effectively**.  
It ensures **flexibility in planning and organizing** coupon-based promotions while offering **filtering, activation controls, and automated workflows** for administrators.
