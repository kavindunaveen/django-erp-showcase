# Django ERP & Business Automation Case Study

A production-inspired ERP case study demonstrating how I designed and developed business workflows using **Python, Django, PostgreSQL, JavaScript, Bootstrap, HTML, and CSS**.

> This repository is a technical showcase based on my commercial ERP development experience.  
> The original production source code, company data, credentials, and proprietary business logic are private.

---

## 👨‍💻 My Role

**Full-Stack / Django Software Engineer**

I worked across the full development lifecycle, including:

- Business requirement analysis
- Database and model design
- Django backend development
- Frontend development
- Business workflow automation
- User roles and access control
- Reporting and dashboards
- Deployment and maintenance
- Direct communication with business users and management

The system was developed to replace several manual and disconnected operational processes with a centralized business platform.

---

## 🎯 Business Problem

The organization handled important operations across multiple manual processes, spreadsheets, documents, and separate systems.

This created challenges such as:

- Limited visibility of inventory movements
- Manual quotation and invoice handling
- Difficulty tracking purchasing activities
- Disconnected production records
- Limited management reporting
- Repetitive manual data entry
- Difficulty retrieving historical transactions
- Lack of centralized customer and supplier information

The objective was to build a centralized ERP platform that could support daily business operations through structured digital workflows.

---

## 🏗️ Solution

I developed a modular Django-based ERP platform covering major business functions such as:

- CRM
- Customer management
- Supplier management
- Inventory
- Sales
- Procurement
- Manufacturing
- Finance-related workflows
- Deliveries
- User management
- Dashboards and reporting

The application was structured using multiple Django apps so that individual business modules could be maintained and expanded independently.

---

# 🧩 Major Modules

## 1. CRM & Customer Management

The CRM module centralizes customer-related information and sales activities.

Key functions include:

- Customer records
- Contact information
- Sales activity tracking
- Customer transaction history
- Internal customer management workflows

---

## 2. Inventory Management

The inventory module provides visibility and control over stock movements.

Features include:

- Product master data
- Product categories
- Brands
- Units of measurement
- Stock-in transactions
- Stock-out transactions
- Stock adjustments
- Stock ledger
- Inventory history
- Product pricing
- Media and product image management

The stock ledger maintains an audit-friendly history of inventory movements.

---

## 3. Sales Management

The sales workflow supports the process from quotation through invoicing and delivery.

Typical workflow:

```text
Customer
   ↓
Quotation
   ↓
Sales Order
   ↓
Invoice
   ↓
Payment Status
   ↓
Delivery
