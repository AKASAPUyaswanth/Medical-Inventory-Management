# Medical-Inventory-Management

# PROJECT DEMONSTRATION

[Watch the demo here](https://www.youtube.com/watch?v=8eWPnbrNOqs)




             # MEDICAL INVENTORY MANAGEMENT SYSTEM


Project Category: Salesforce  
Skills Required: Salesforce Admin, Salesforce Developer, Apex, Flows, Reports

--------------------------------------------------------------------------------
1. 📌 Project Description
--------------------------------------------------------------------------------
The Medical Inventory Management System is a comprehensive Salesforce application 
designed to streamline and manage various aspects of medical inventory.

It maintains detailed supplier and product records, manages purchase orders and 
order items, tracks inventory levels and expiry dates, and provides automated 
flows and reports for intelligent decision-making.


--------------------------------------------------------------------------------
2. 🛠️ Technologies Used
--------------------------------------------------------------------------------
- Salesforce Lightning Platform
- Apex Programming
- Flow Builder
- Reports and Dashboards
- Validation Rules
- Custom Objects, Fields, and Relationships

--------------------------------------------------------------------------------
3. 🧭 Project Flow / Milestones
--------------------------------------------------------------------------------
**Milestone 1: Developer Account Creation**
- Salesforce developer org account created at: https://developer.salesforce.com

**Milestone 2: Object Creation**
- Custom Objects:
  - Supplier
  - Product
  - Purchase Order
  - Order Item
  - Inventory Transaction

**Milestone 3: Tabs**
- Created tabs for all custom objects for easy navigation

**Milestone 4: Lightning App**
- Created “Medical Inventory Management” app

**Milestone 5: Fields**
- Added required fields like Product ID, Unit Price, Quantity, Expiry Date, etc.

**Milestone 6: Page Layouts**
- Customized page layouts to organize key fields under Product Details, Supplier Info, etc.

**Milestone 7: Compact Layouts**
- Compact layouts created for mobile/responsive quick views

**Milestone 8: Validation Rules**
- Created rules to restrict invalid data (e.g., no negative quantity)

**Milestone 9: Profiles**
- Inventory Manager and Purchase Manager profiles cloned and configured

**Milestone 10: Roles**
- Defined Inventory Manager and Purchase Manager roles with hierarchy

**Milestone 11: Users**
- Created Salesforce users assigned with custom roles and profiles

**Milestone 12: Permission Sets**
- Created permission sets to grant Create + Read access to Order Items

**Milestone 13: Flows**
- Flow to calculate Actual Delivery Date based on Order Date + 3 days

**Milestone 14: Triggers**
- Apex trigger to automatically calculate and update Total Order Cost

**Milestone 15: Reports**
- Created:
  - Purchase Orders based on Suppliers
  - Complete Purchase Details Report

**Milestone 16: Dashboards**
- Medical Inventory Dashboard with charts like donut and bar graphs

**Milestone 17: Conclusion**
- Verified functionalities, cross-checked with acceptance criteria

--------------------------------------------------------------------------------
4. 📁 Folder Structure
--------------------------------------------------------------------------------
/project-files
    ├── Apex Triggers (CalculateTotalAmountTrigger, Handler)
    ├── Flows (Actual Delivery Date Flow)
    ├── Validation Rules (MinStockValidation)
    ├── Page Layouts (Customized for all objects)

 /dataset
    ├── Products.csv (Product ID, Name, Price, Min Stock)
    ├── Suppliers.csv (Name, Email, Phone, Address)
    ├── Orders.csv (PO ID, Date, Supplier ID, Order Cost)

 /output-screenshots
    ├── Dashboard.png
    ├── Product Record View.png
    ├── Reports Summary.png
    ├── Flow Builder.png
    ├── User Assignment.png
    ├── Trigger Execution Result.png

--------------------------------------------------------------------------------
5. 📊 Reports and Dashboards
--------------------------------------------------------------------------------
- **Report 1**: Purchase Orders Based on Suppliers
  - Grouped by Supplier
  - Columns: Order Count, Total Order Cost

- **Report 2**: Complete Purchase Details Report
  - Grouped by: Supplier, PO ID, Actual Delivery Date
  - Columns: Product ID, Name, Quantity Received, Amount

- **Dashboard**: Medical Inventory Dashboard
  - Donut Chart for Orders
  - Bar Chart for Suppliers vs Total Cost

--------------------------------------------------------------------------------
6. ✅ Testing
--------------------------------------------------------------------------------
**Functional Testing**
- Field Validations
- Profile Restrictions
- Trigger Output Accuracy
- Flow Automation Logic

**Performance Testing**
- All reports loaded in < 2 sec for up to 50 records
- Trigger optimized using aggregate queries

--------------------------------------------------------------------------------
7. 📋 How to Deploy
--------------------------------------------------------------------------------
1. Login to Salesforce Developer Org
2. Setup custom objects, fields, relationships
3. Configure tabs, profiles, roles, users
4. Deploy Flows, Triggers via Developer Console
5. Add datasets using Data Import Wizard or Data Loader
6. Build Reports & Dashboard

--------------------------------------------------------------------------------
8. 📖 Live Demo Script (Short)
--------------------------------------------------------------------------------
1. Launch the “Medical Inventory Management” app
2. Show Products tab – add/view stock items
3. Go to Suppliers – explain contact info storage
4. Navigate to Purchase Orders – create one with expected delivery
5. Move to Order Items – auto-calculates amount
6. Open Flow – explain automation of Actual Delivery Date
7. Open Developer Console – show trigger execution
8. View Reports tab – show grouped purchase orders
9. Show Dashboard – view insights via graphs

--------------------------------------------------------------------------------
9. 📌 Final Notes
--------------------------------------------------------------------------------
- This project offers a real-world simulation of Inventory Management within Salesforce.
- All business logic has been abstracted using triggers and flows for efficiency.
- Reports and dashboards add valuable analytical capability for stakeholders.

--------------------------------------------------------------------------------
10. 📜 License
--------------------------------------------------------------------------------
This project is created for educational and demonstration purposes.

Mentor Appreciation: Thank you for your support and guidance throughout this project!

================================================================================
