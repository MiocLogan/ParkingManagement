# Parking Management Database Project

This project contains a MySQL-based relational database system for managing a parking facility. It includes SQL scripts for creating and populating tables, as well as triggers to automate key actions such as payment record generation and slot status updates.

## 📦 Project Contents

- `parkingmanagement_users.sql`
- `parkingmanagement_vehicles.sql`
- `parkingmanagement_parkingslots.sql`
- `parkingmanagement_parkingrecords.sql`
- `parkingmanagement_payments.sql`

Each file corresponds to a table in the system. Triggers and constraints are included to maintain data integrity and automation.

## 🚀 How to Use

1. **Open MySQL Workbench**
2. **Create a new schema** (e.g., `parkingmanagement`)
3. **Select your new schema** in the left panel
4. **Import the SQL files** one by one:
   - Go to `File` > `Open SQL Script`
   - Load each `.sql` file and click **Execute**

The tables, data, and triggers will be created automatically.

## ✅ Features

- Automatic payment record creation on new parking check-in
- Automatic slot status update on check-in/check-out
- Well-structured relational model using foreign keys and indexing

## 🛠 Requirements

- MySQL Workbench
- MySQL Server 8.0+

---


> This project is intended for academic demonstration and can be extended with procedures, views, and UI integration if needed.

Logan Mioč 230302200
Elhan Zeba 230302230

