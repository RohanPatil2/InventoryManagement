---

# **Sales and Inventory Management Web Application**  

## **Project Overview**  
The **Sales and Inventory Management Web Application** is designed to streamline **mobile phone store operations**, enabling **real-time inventory tracking, order processing, and sales analysis**.

### **Key Features**  
✅ **User Authentication**: Secure admin login.  
✅ **Product Management**: Add, edit, delete products with SKU, images, price, and stock count.  
✅ **Inventory Tracking**: Monitor stock levels & replenish items.  
✅ **Order Management**: Track customer orders and view sales history.  
✅ **Category & Brand Management**: Organize products efficiently.  
✅ **Sales Analysis**: Interactive charts for brand and category-wise sales.  
✅ **Purchase History**: Maintain past transactions and restock logs.  
✅ **Dashboard Overview**: Get insights into store performance.  

---

## **Technologies Used**  
- **Frontend**: HTML, CSS, JavaScript, DataTable.net  
- **Backend**: C#, ASP.NET  
- **Database**: SQL Server  
- **Visualization**: Google Charts  
- **Development Tools**: Visual Studio 2015, GitHub  

---

## **Setup Instructions**  

### **1. Clone the Repository**  
```sh
git clone <repository_url>
```
Navigate to the cloned folder:  
```sh
cd Sales-Inventory-Management
```

### **2. Open the Project in Visual Studio 2015**  
- Launch **Visual Studio 2015**.  
- Open the project by selecting **File > Open > Project/Solution**.  
- Load the `.sln` file.  

### **3. Configure the Database**  
- The **SQL database scripts** are available in the repository.  
- Import the SQL database into **SQL Server**.  

### **4. Update Database Connection**  
- Locate `web.config` file.  
- Modify the **database connection string** to match your local SQL Server setup.  

### **5. Run the Application**  
- Press **F5** or click **Start** to launch the app.  
- The application will start from **Login.aspx**.  

### **6. Login Credentials**  
```
Username: admin  
Password: admin  
```

---

## **Application Modules & Screenshots**  

### **1. Login Page**  
![Login Page](Picture1.jpg)  
- Secure **admin authentication** to access the system.  

---

### **2. Dashboard Overview**  
![Dashboard](Picture7.jpg)  
- Displays **Total Products, Paid Orders, Categories, and Brands**.  
- Interactive **Sales Analysis** using Google Charts.  

---

### **3. Product Management**  
![Product List](Picture2.jpg)  
- **Add, edit, delete products** with SKU, name, price, quantity, and image.  
- **Stock status** is displayed as **Active (green)** or **Inactive (red)**.  

📌 **Delete Confirmation**  
![Delete Product](Picture10.jpg)  
- A confirmation pop-up appears when a product is deleted.  

---

### **4. Inventory Tracking**  
![Low Stock & Out of Stock](Picture5.jpg)  
- Displays **Out-of-Stock** and **Low-Level Stock** items.  
- Admin can **replenish stock** directly with the click of a button.  

---

### **5. Category & Brand Management**  
![Category Management](Picture4.jpg)  
- Manage **product categories** (Smartphones, Tablets, Accessories, etc.).  
- Categories can be **edited, deleted, or set as unavailable**.  

---

### **6. Order Management**  
![Order Management](Picture8.jpg)  
- View **customer orders** with details such as:  
  - **Bill Number**  
  - **Customer Name & Phone**  
  - **Date & Total Amount**  
- Options to **View, Edit, or Delete** orders.  

---

### **7. Purchase History**  
![Purchase History](Picture9.jpg)  
- Maintains **transaction records** of past purchases.  
- Includes **timestamps, product details, and remarks**.  

---

### **8. Sales Analysis**  
![Sales Analysis](Picture6.jpg)  
- Provides **visual analytics** of sales using pie charts.  
- Two charts:  
  - **Phone Brand Sales Analysis** (Apple, Huawei, Samsung).  
  - **Category Sales Analysis** (Impact Trade vs. Smartphone sales).  
- **Date filter** (Year & Month) available for custom analysis.  

---

## **Screenshots Directory**  
The following images illustrate different sections of the system:  

| **Image**  | **Description** |
|------------|---------------|
| ![Picture1](Picture1.jpg) | Add New Product Page  |
| ![Picture2](Picture2.jpg) | Product List (Inventory)  |
| ![Picture3](Picture3.jpg) | Updated Stock Page  |
| ![Picture4](Picture4.jpg) | Category Table  |
| ![Picture5](Picture5.jpg) | Low-Stock & Out-of-Stock Products  |
| ![Picture6](Picture6.jpg) | Sales Analysis Dashboard  |
| ![Picture7](Picture7.jpg) | Admin Dashboard  |
| ![Picture8](Picture8.jpg) | Order Management Page  |
| ![Picture9](Picture9.jpg) | Purchase History Page  |
| ![Picture10](Picture10.jpg) | Product Deletion Confirmation  |

---

## **Troubleshooting**  
- Ensure **SQL Server** is running before launching the app.  
- Check `web.config` for correct **database connection string**.  
- If missing libraries, restore packages using:  
  ```sh
  NuGet Package Manager > Restore Packages
  ```
- Run Visual Studio in **Administrator Mode** to avoid permission issues.  

---

## **Future Enhancements**  
✅ **Role-Based Authentication** (Admin, Staff)  
✅ **Email Notifications** for low stock alerts  
✅ **PDF Reports** for orders and inventory  

---

## **Contributing**  
1. **Fork** the repository.  
2. **Create a new branch** (`feature-branch-name`).  
3. **Commit and push** your changes.  
4. **Submit a Pull Request** for review.  

---

## 👤 Author
**Rohan Patil** <br> 
GitHub: [@RohanPatil2](https://github.com/RohanPatil2)<br>
**Shreyas Khandale**<br>
Github: [@sherurox](https://github.com/sherurox).<br>


---

## **License**  
This project is licensed under the **MIT License**.  

---
