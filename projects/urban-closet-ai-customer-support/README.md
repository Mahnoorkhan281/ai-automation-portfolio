# Urban Closet — AI Customer Support Automation

## Overview
An AI-powered customer support automation system built for a fictional online clothing store.

## Features
- Receives customer inquiries through Google Sheets.
- Retrieves order details using Order IDs.
- Uses Groq AI to classify inquiries and assign priority.
- Generates customer support recommendations and suggested replies.
- Logs inquiries and AI results in Google Sheets.
- Includes human approval before creating email drafts.
- Updates approval status automatically.
- Creates Gmail drafts only for approved replies.

## Technologies
- n8n
- Groq API
- Google Sheets API
- Gmail API
- JavaScript
- JSON

## Workflow
1. Receive customer inquiry.
2. Retrieve order information.
3. Analyze the inquiry using AI.
4. Parse the AI response.
5. Save the results.
6. Request human approval.
7. Update approval status.
8. Create a Gmail draft if approved.

## Project Status
First version completed and tested.

**Note:** This is a learning portfolio project using fictional customer data. It is not connected to a real business.
