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
