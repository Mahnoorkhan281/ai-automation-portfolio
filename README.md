# Mahnoor — AI Automation Portfolio

Hi! I'm Mahnoor, a BS Artificial Intelligence student learning AI automation.

This portfolio showcases automation projects I've built using n8n and other automation tools.

## Projects
Projects will be added here as i build them.

### 1. Form to Google Sheets Automation

Automatically collects customer inquiries through a form and saves them to Google Sheets.

**Tools:** n8n, Google Sheets

[View Project](./projects/form-to-google-sheets)

---
### 2. Automatic Email Confirmation
An n8n workflow that sends a confirmation email through Gmail after a user submits a form.

[View Project](./projects/automatic-email-confirmation)

### 3. Customer Inquiry Router
Automatically routes customer inquiries based on inquiry type and prepares different email responses for complaints and general inquiries.

[View Project](./projects/customer-inquiry-router/)

### 4. Inventory Management Automation System

An inventory automation project built with **n8n, Google Sheets, and JavaScript** to streamline order processing and stock monitoring.

### Workflows

**1. Order Processing & Inventory Management**
- Receives customer orders through a form.
- Validates orders against available stock.
- Records accepted and rejected orders.
- Updates inventory after accepted orders.
- Sends automated customer emails.

**2. Low Stock Alert Automation**
- Checks inventory every hour.
- Identifies products at or below their minimum stock level.
- Records new low-stock alerts in Google Sheets.
- Sends email notifications for new alerts.
- Prevents duplicate alerts for unresolved issues.

### Technologies
- n8n
- Google Sheets
- JavaScript
- Email automation

### Project Files and Screenshots

[**View the complete project, workflow exports, and screenshots →**](projects/inventory-management-system/README.md)

This project demonstrates workflow automation, conditional logic, data processing, inventory management, and automated notifications.

### 5. Urban Closet — AI Customer Support Automation

An AI-powered customer support workflow built using **n8n, Groq AI, Google Sheets, and Gmail**.

- Automatically receives customer inquiries.
- Retrieves order details from Google Sheets.
- Uses AI to classify complaints and assign priority.
- Generates suggested customer replies.
- Includes human approval before creating email drafts.
- Updates approval status and creates Gmail drafts only for approved responses.

**Tools:** n8n, Groq AI, Google Sheets, Gmail API, JavaScript

[**View Project →**](https://github.com/Mahnoorkhan281/ai-automation-portfolio/tree/main/projects/urban-closet-ai-customer-support)

More projects coming soon.

# Urban Closet — AI Customer Support Automation

An AI-powered customer support workflow built with n8n, Groq AI, Google Sheets, and Gmail.

## Project Overview

This project automates customer support operations for a fictional online clothing store called Urban Closet.

It receives customer inquiries, retrieves order information, analyzes messages using AI, generates suggested replies, and allows a human to approve or reject responses before creating Gmail drafts.

## Features

- Automatically receives new customer requests from Google Sheets.
- Retrieves customer order details using Order ID.
- Uses AI to classify customer inquiries and determine priority.
- Generates AI-powered customer support recommendations and replies.
- Records support requests and AI results in Google Sheets.
- Provides a human approval form.
- Updates approval status automatically.
- Creates Gmail drafts for approved responses only.
- Prevents rejected responses from reaching Gmail drafts.

## Tools & Technologies

- n8n — Workflow automation
- Groq API — AI processing
- Google Sheets — Order database and support logs
- Gmail API — Email draft creation
- JavaScript — AI response parsing
- JSON — Data exchange

## Workflow

1. Receive customer inquiry.
2. Retrieve order information.
3. Analyze inquiry using AI.
4. Parse the AI-generated response.
5. Save results in the support log.
6. Request human approval.
7. Update approval status.
8. Create a Gmail draft if approved.

## Key Skills Demonstrated

- Workflow automation
- API integration
- AI integration
- Data handling
- Conditional logic
- JavaScript
- Human-in-the-loop automation

## Project Status

**First version completed and tested.**

This is a learning and portfolio project. It uses fictional customer data and is not connected to a real clothing business.

## Author

Mahnoor Khan
