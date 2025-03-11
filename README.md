# Brainwave_Matrix_Intern-
# Inventory Management System

## 📦 Overview
The **Inventory Management System** is a complete web-based application built using **Python (Flask)** and **SQLite**. It helps businesses to manage inventory, track stock levels, generate reports, and manage users with authentication.

## 💻 Features
- ✅ **User Authentication:** Login/Signup with secured credentials.
- ✅ **Add/Edit/Delete Products:** Manage product details easily.
- ✅ **Track Inventory:** View stock levels and low-stock alerts.
- ✅ **Generate Reports:** Download inventory reports in Excel format.
- ✅ **Responsive UI:** Clean and user-friendly interface using HTML/CSS/Bootstrap.
- ✅ **Database Management:** Product and user data stored in SQLite.

## 📊 Technologies Used
- **Backend:** Python Flask
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite
- **Libraries:** Pandas, Openpyxl, Flask-SQLAlchemy

## 📂 Folder Structure
```
Inventory-Management-System
│
├── app.py          <-- Main Backend File
├── requirements.txt <-- Project Dependencies
├── inventory.db    <-- SQLite Database
├── instance        <-- Contains database
├── templates       <-- All Frontend Files
│   ├── login.html
│   ├── signup.html
│   ├── index.html
│   ├── add.html
│   ├── edit.html
│   ├── low_stock.html
```

## 💾 Installation
1. Clone the repository:
```bash
https://github.com/Krishnaveni-6/Brainwave_Matrix_Intern-
cd Inventory-Management-System
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python app.py
```

4. Open your browser and visit:
```
http://localhost:5000
```

## 📊 How to Use
- **Signup/Login** to access the dashboard.
- **Add Product:** Add new products to your inventory.
- **Edit Product:** Update product information.
- **Delete Product:** Remove products from inventory.
- **Low Stock Alert:** Check products with low stock.
- **Download Report:** Export inventory data in Excel.
