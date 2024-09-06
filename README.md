# Enterprise Resource Planning (ERP) System

## Description

The **Enterprise Resource Planning (ERP) System** is a modular solution designed for small to medium-sized businesses to manage their operations efficiently. This system helps businesses track and manage their **inventory**, **sales**, and **financial records**, providing a unified platform for operational control. Built using **React.js** for the frontend and incorporating **state management**, **form validation**, and **data visualization**, the system is easy to extend and scale.

## Features

- **Dashboard**: Displays key business metrics, including inventory levels, sales figures, and financial data.
- **Inventory Management**: Allows users to manage and update product inventory, track supplier information, and monitor stock levels.
- **Sales Management**: Provides tools for managing customer orders, tracking sales, and viewing sales performance.
- **Financial Management**: Handles financial transactions, expense tracking, and reconciliation of financial records.
- **Reconciliation Portal**: Helps users reconcile discrepancies between inventory and financial data.
- **Authentication**: Secure user login and registration functionality.
- **Form Validation**: Uses Formik and Yup for handling and validating forms, ensuring data consistency.
- **Data Visualization**: Displays financial trends and business metrics using Chart.js.

## Table of Contents

- [Installation](#installation)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [Features](#features)
- [Usage](#usage)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## Installation

### Prerequisites

Ensure you have the following installed on your system:
- Node.js (>= 12.x)
- NPM (comes with Node.js)
- React.js (>= 17.x)

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/saifeldeen911/erp-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd erp-system
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

   The application should now be running on `http://localhost:3000`.

## Technologies Used

- **React.js**: Front-end JavaScript library for building user interfaces.
- **React Router**: For managing navigation within the app.
- **Context API**: For state management.
- **Formik & Yup**: For form handling and validation.
- **Chart.js**: For data visualization and charting.
- **Tailwind CSS**: For styling and layout.
- **Axios**: For API requests.

## Folder Structure

```
src/
│
├── assets/
│   └── images/
│
├── components/
│   ├── Dashboard/
│   │   ├── Dashboard.js
│   │   └── Dashboard.module.css
│   ├── Inventory/
│   │   ├── Inventory.js
│   │   ├── InventoryForm.js
│   │   └── Inventory.module.css
│   ├── Finance/
│   │   ├── Finance.js
│   │   ├── Reconciliation.js
│   │   └── Finance.module.css
│   ├── Sales/
│   │   ├── Sales.js
│   │   ├── SalesForm.js
│   │   └── Sales.module.css
│   ├── Authentication/
│   │   ├── Login.js
│   │   ├── Register.js
│   │   └── Auth.module.css
│   └── common/
│       ├── Button.js
│       ├── Input.js
│       └── Navbar.js
│
├── context/
│   ├── ERPContext.js
│   └── AuthContext.js
│
├── hooks/
│   ├── useERPData.js
│   └── useAuth.js
│
├── pages/
│   ├── Home.js
│   ├── InventoryManagement.js
│   ├── FinanceManagement.js
│   ├── SalesManagement.js
│   ├── LoginPage.js
│   └── routes.js
│
├── services/
│   ├── api.js
│   └── authService.js
│
├── App.js
├── index.js
└── tailwind.config.js
```

