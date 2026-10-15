# Inventory Management Automation System

An inventory automation project built with n8n and Google Sheets.

## Workflow 1: Order Processing & Inventory Management
- Receives customer orders through a form.
- Checks product availability and requested quantity.
- Updates inventory after accepted orders.
- Sends order confirmation or rejection emails.

## Workflow 2: Low Stock Alert Automation
- Checks inventory every hour.
- Identifies products below their minimum stock level.
- Records new alerts in Google Sheets.
- Sends email notifications for new alerts.
- Avoids duplicate alerts for unresolved issues.

## Tools Used
- n8n
- Google Sheets
- Email automation
- JavaScript

## Purpose
To reduce manual order processing, maintain accurate stock records, and notify the owner when inventory needs replenishment.
# Inventory Management Automation System

An automation project built with **n8n, Google Sheets, and JavaScript** to streamline order processing, manage inventory, and send low-stock alerts through email.

## Project Overview

This project consists of two connected-purpose workflows that automate different parts of inventory management. The first processes customer orders and updates stock, while the second monitors inventory and notifies the owner when products need restocking.

## Workflow 1: Order Processing & Inventory Management

This workflow automates the customer order process.

**How it works:**
1. Receives customer order details through a form.
2. Checks the requested product and quantity against available inventory.
3. Determines whether the order can be accepted.
4. Records accepted or rejected orders in Google Sheets.
5. Updates inventory after an accepted order.
6. Sends an order confirmation or rejection email to the customer.

**Key features:**
- Automated order validation
- Inventory quantity updates
- Order record management
- Conditional processing for accepted and rejected orders
- Automated customer email notifications

### Workflow Screenshot

![Order Processing & Inventory Management Workflow](Screenshot%202026-10-15%20180840.png)

## Workflow 2: Low Stock Alert Automation

This workflow monitors inventory and identifies products that have reached or fallen below their minimum stock level.

**How it works:**
1. Runs on an hourly schedule.
2. Retrieves inventory and existing stock alert records from Google Sheets.
3. Identifies products whose stock quantity is at or below the minimum stock level.
4. Checks existing alerts to avoid creating duplicate unresolved alerts.
5. Records new low-stock alerts in Google Sheets.
6. Sends an email notification when a new alert is generated.

**Key features:**
- Scheduled inventory monitoring
- Minimum stock threshold checking
- Duplicate alert prevention
- Automated alert logging
- Email notifications for restocking

### Workflow Screenshot

![Low Stock Alert Automation Workflow](Screenshot%202026-10-15%20181043.png)

## Tools & Technologies

- **n8n** — Workflow automation
- **Google Sheets** — Inventory and order data management
- **JavaScript** — Data processing and conditional logic
- **Email** — Automated customer notifications and stock alerts
- **GitHub** — Version control and project documentation

## What I Learned

Through this project, I practised:
- Building multi-step automation workflows
- Connecting forms, Google Sheets, and email services
- Using conditional logic to handle different order outcomes
- Processing and validating inventory data with JavaScript
- Implementing duplicate-prevention logic
- Scheduling recurring automation tasks
- Exporting and documenting n8n workflows for a portfolio

## Project Files

- `order-processing-inventory-management.json` — Order processing workflow export
- `low-stock-alert-automation.json` — Low-stock alert workflow export
- `Screenshot 2026-10-15 180840.png` — Order processing workflow screenshot
- `Screenshot 2026-10-15 181043.png` — Low-stock alert workflow screenshot

## Project Goal

The goal is to reduce repetitive manual work, improve inventory visibility, process orders more consistently, and notify the owner when stock needs attention.

**Note:** The two workflows are separate automations that use the same inventory-management concept. They are not directly connected to trigger one another.
