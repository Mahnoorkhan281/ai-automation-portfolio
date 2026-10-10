# Project 3: Customer Inquiry Router

## Overview
An n8n workflow that checks the type of customer inquiry and sends a different email depending on the result.

## How It Works
1. A customer submits a form with their name, inquiry type, and email address.
2. The IF node checks whether the inquiry type equals `Complaint`.
3. The True branch prepares a priority complaint message and sends it through Gmail.
4. The False branch prepares a general inquiry message and sends it through Gmail.

## Tools Used
- **n8n:** Workflow automation and conditional logic
- **Gmail:** Automated email delivery

## Concepts Practiced
- Form triggers
- IF conditions and True/False branches
- Edit Fields nodes
- Expressions and data mapping
- Gmail integration

## Workflow File
The exported n8n workflow JSON is included in this folder.

## Screenshots

### Complete Workflow
![Customer Inquiry Router Workflow](./Screenshot%202026-10-10%20170913.png)

### IF Condition and Branches
![IF condition and branches](./Screenshot%202026-10-10%20171141.png)

### Complaint Branch
![Complaint branch](./Screenshot%202026-10-10%20171217.png)

### General Inquiry Branch
![General inquiry branch](./Screenshot%202026-10-10%20171315.png)

### Workflow Test
![Workflow test](./Screenshot%202026-10-10%20171717.png)

## Author
Mahnoor — BS Artificial Intelligence Student
