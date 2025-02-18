Here is a detailed `README.md` file for your **Sales and Inventory Management Web Application**:

---

# Sales and Inventory Management Web Application

## Project Overview

The **Sales and Inventory Management Web Application** is designed to enhance retail operations in a mobile phone store. It provides functionalities such as product management, order tracking, sales analysis, and inventory monitoring.

### Features:
- **User Authentication**: Admin login with username and password.
- **Product Management**: Add, edit, delete, and manage products.
- **Inventory Tracking**: Monitor stock levels and replenish products.
- **Order Management**: View, edit, delete orders with customer details.
- **Category & Brand Management**: Maintain product categories and brands.
- **Sales Analysis**: Visual representation of sales using charts.
- **Reports & Purchase History**: Track product purchases and transactions.
- **User-Friendly Dashboard**: View product counts, paid orders, categories, and brands at a glance.

---

## Technologies Used:
- **Frontend**: HTML, CSS, JavaScript, DataTable.net
- **Backend**: C#, ASP.NET
- **Database**: SQL Server
- **Visualization**: Google Charts
- **Development Tools**: Visual Studio 2015, GitHub

---

## Setup Instructions:

### 1. Clone the Repository
```sh
git clone <repository_url>
```
Navigate to the cloned folder:
```sh
cd Sales-Inventory-Management
```

### 2. Open the Project in Visual Studio 2015
- Launch **Visual Studio 2015**.
- Open the project by selecting **File > Open > Project/Solution**.
- Load the `.sln` file.

### 3. Configure the Database
- The database scripts are included in the GitHub repository.
- Import the SQL database into your **SQL Server**.

### 4. Update Database Connection
- Locate `web.config` file.
- Update the database connection string to match your SQL Server setup.

### 5. Run the Application
- Press **F5** or click **Start** to launch the application.
- The application will start from `Login.aspx`.

### 6. Login Credentials:
```
Username: admin
Password: admin
```

---

## Application Workflow

### **Login Page**
- Admin can log in with credentials.

### **Dashboard**
- Displays total products, orders, categories, and brands.
- Sales analysis charts are available.

### **Product Management**
- Add new products with details (SKU, Name, Price, Quantity, Status).
- Edit and delete products.
- Monitor product stock levels.

### **Order Management**
- Track customer orders with billing details.
- Modify or delete orders as needed.

### **Inventory Management**
- Identify low-stock or out-of-stock items.
- Replenish stock easily.

### **Sales Analysis**
- Graphical reports of sales based on brand and category.
- Monthly and yearly filters available.

### **Categories & Brands**
- Add, edit, and manage product categories and brands.

---

## Screenshots
(Screenshots have been uploaded in the GitHub repository under `screenshots/` directory.)

---

## Troubleshooting
- Ensure **SQL Server** is running before launching the application.
- Verify that database connection strings in `web.config` are correct.
- If there are missing libraries, restore packages using:
  ```sh
  NuGet Package Manager > Restore Packages
  ```
- Run Visual Studio in **Administrator Mode** if there are permission issues.

---

## Future Enhancements
- Role-based authentication (Admin, Staff).
- Implement email notifications for low stock.
- Generate PDF reports for orders and inventory.

---

## Contributing
- Fork the repository.
- Create a new branch for your feature (`feature-branch-name`).
- Commit changes and push to your forked repository.
- Create a Pull Request.

---

## License
This project is licensed under the **MIT License**.

---

This `README.md` provides clear instructions on setup, functionality, and usage of the inventory management system. Let me know if you need any modifications or additions! 🚀
