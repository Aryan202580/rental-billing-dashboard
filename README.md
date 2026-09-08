# rental-billing-dashboard
A modern web-based Rental Billing &amp; Property Management Dashboard for managing tenants, monthly rent, utilities, payments, receipts, reports and UPI-based billing.
# 🏠 Rental Billing Dashboard

A modern, lightweight and easy-to-use **Rental Billing & Property Management Dashboard** designed to simplify monthly rent, utility billing, payment tracking and receipt management for residential rental properties.

The application is built as a **single HTML file**, making it easy to run locally without a backend or installation.

## ✨ Features

### 🏢 Property & Tenant Management

* Add and manage tenant records
* Store tenant name, flat and floor information
* Manage multiple tenants across different floors
* Edit and maintain tenant details
* Organize billing records tenant-wise

### 🧾 Monthly Billing

Create detailed monthly bills containing:

* Monthly Rent
* Electricity Charges
* Maintenance Charges
* PNG Gas Charges
* Other Charges
* Discounts / Adjustments
* Amount Paid
* Balance Due

The system also prevents duplicate bills for the same tenant and billing month.

### ⚡ Electricity Calculator

Built-in electricity calculation system allows you to enter:

* Previous meter reading
* Current meter reading
* Electricity rate per unit

The dashboard automatically calculates:

**Units Consumed = Current Reading − Previous Reading**

and calculates the corresponding electricity amount.

### 💳 Payment Management

Track tenant payments with:

* Amount received
* Payment date
* Payment method
* Transaction / Reference ID
* Partial payments
* Remaining balance
* Payment status

Supported billing statuses include:

* `PENDING`
* `PARTIALLY PAID`
* `PAID`

### 📱 UPI Payment & QR Code

Bills can contain a dynamically generated UPI payment link and QR code.

The payment URI is generated using the configured UPI ID, payable amount and bill number, allowing tenants to conveniently make payments from compatible UPI applications.

### 🧾 Payment Receipts

Once a bill is fully paid, a payment receipt can be generated from the bill.

### 📄 Export & Printing

Generated bills and receipts can be:

* Downloaded as PDF
* Downloaded as images
* Printed directly

### 📊 Monthly Collection Reports

View monthly billing and collection information including:

* Total billed amount
* Total collected amount
* Pending amount
* Payment status
* Tenant-wise billing information

Reports can also be exported as CSV.

### 📲 WhatsApp Sharing

Bills and receipts can be shared through WhatsApp for convenient communication with tenants.

### ⚙️ Custom Settings

The dashboard provides configurable property information including:

* Property / Building Name
* Property Address
* Owner Name
* Manager Name
* Manager Phone Number
* UPI ID
* Bank Details
* Default Due Date
* Electricity Rate
* Payment Instructions

## 💾 Data Persistence

The application is designed to save records locally in the browser using `localStorage`.

Tenant records, bills, settings and billing counters are persisted so that data remains available when the HTML application is reopened in the same browser environment.

> **Important:** Since this is currently a browser-based local application, the stored data is tied to the browser/device where it was entered. It is not automatically synchronized between different devices.

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* Browser LocalStorage
* UPI Deep Links
* QR Code generation
* HTML2Canvas
* jsPDF

## 🚀 Getting Started

No installation or build process is required.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/rental-billing-dashboard.git
```

### 2. Open the project

Open the HTML file directly in your browser:

```text
Rental-Billing-Dashboard.html
```

### 3. Start managing your property

Add tenants, create monthly bills, record payments and generate receipts.

## 📁 Project Structure

```text
rental-billing-dashboard/
│
├── Rental-Billing-Dashboard.html
├── README.md
└── LICENSE
```

The current application is intentionally kept as a single-file web application for simplicity and portability.

## 🔐 Privacy & Data

The application does not require a server or database for its current local-storage mode.

Billing data is stored in the browser's local storage.

If the browser's site data is cleared, locally stored records may be deleted. For important business records, regular backups/export should be maintained.

## 🎯 Use Cases

This dashboard can be useful for:

* Individual landlords
* Residential building owners
* Property managers
* PG / rental property operators
* Small rental businesses
* Multi-floor residential properties

## 🔮 Future Improvements

Potential future versions can include:

* Cloud database synchronization
* Multi-device access
* Owner & manager login
* Role-based permissions
* Online tenant portal
* Automatic payment verification
* Automated WhatsApp/SMS reminders
* Cloud backup
* Advanced analytics
* Multiple property management
* Automated monthly bill generation

## 👨‍💻 Author

**Aryan**

Designed and created as a practical rental property billing management solution.

## 📄 License

This project is available for personal and educational use. Add an appropriate open-source license if you plan to distribute or modify the project publicly.
