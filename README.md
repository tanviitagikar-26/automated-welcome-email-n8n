# Automated Welcome Email Workflow using n8n

##  Project Overview

This project is a beginner-level workflow automation built using **n8n**.

The workflow connects **Google Forms, Google Sheets, and Email** to automatically send a personalized welcome email whenever a new form response is added to the connected Google Sheet.

The main purpose of this project is to understand the fundamentals of **workflow automation, triggers, integrations, and automated email communication** using n8n.

---

## Workflow

```text
Google Form
     ↓
Google Sheets
     ↓
n8n Google Sheets Trigger
     ↓
Send an Automated Welcome Email
```

---

##  How It Works

1. A user submits their information through a Google Form.
2. The submitted response is automatically stored in Google Sheets.
3. The **Google Sheets Trigger** in n8n checks for newly added rows.
4. When a new row is detected, n8n retrieves the submitted information.
5. The workflow uses the user's name, email address, and internship information.
6. n8n automatically sends a personalized welcome email to the submitted email address.

---

##  Features
🔹 Google Forms integration
🔹 Google Sheets integration
🔹 Automated workflow trigger
🔹 Automatic email sending
🔹 Personalized email content
🔹 Dynamic use of form response data
🔹 Reduces repetitive manual email work

---

##  Technologies & Tools

* **n8n** – Workflow automation
* **Google Forms** – Collecting user responses
* **Google Sheets** – Storing form responses
* **SMTP / Email** – Sending automated emails

---

##  Example

### Input

A user submits the Google Form with:

```text
Name: Priya
Email: priya@example.com
Internship: Data Analytics
```

### Automated Output

The workflow automatically sends:

```text
Subject: Welcome to the team, Priya!

Hi Priya,

Thank you for submitting your response for the Data Analytics internship!

We are glad to have you on board. We will review your submission and get back to you with next steps shortly.

Best regards,
Your Name
```

The name, email address, and internship information are dynamically taken from the Google Sheets data.

---

##  Workflow Preview

The workflow consists of two main n8n nodes:

**Google Sheets Trigger → Send an Email**

---

##  Project Objective

The objective of this project was to learn how to automate a repetitive communication task by connecting multiple applications through n8n.

Instead of manually sending a welcome email for every new form submission, the workflow automatically handles the process whenever a new response is received.

---

##  What I Learned

While building this project, I learned:

* The basics of n8n workflow automation
* How workflow triggers work
* How to connect Google Sheets with n8n
* How to use data from Google Sheets inside an automation
* How to send emails automatically using n8n
* How to use dynamic expressions in n8n
* How different applications can work together in an automated workflow
* The importance of testing an automation before deployment

---

##  Future Improvements

This is the first version of the project. I plan to improve the workflow as I learn more advanced automation concepts.

Possible future improvements include:

* [ ] Add business-owner notifications
* [ ] Add multiple follow-up emails
* [ ] Add email templates
* [ ] Add conditional workflows
* [ ] Add lead tracking
* [ ] Integrate with a CRM
* [ ] Add WhatsApp notifications
* [ ] Add error handling
* [ ] Add workflow logging
* [ ] Add more advanced n8n integrations

---

##  Security

This repository does **not** contain:

* API keys
* Passwords
* OAuth tokens
* SMTP passwords
* Private Google Sheets
* Personal credentials

The uploaded workflow file uses placeholders instead of real credentials or private information.

> **Note:** Before importing the workflow into your own n8n instance, you must configure your own Google Sheets and email credentials.

---

##  Repository Structure

```text
automated-welcome-email-n8n/
│
├── README.md
├── workflow.json
└── workflow.png
```

### File Description

| File            | Description                    |
| --------------- | ------------------------------ |
| `README.md`     | Project documentation          |
| `workflow.json` | Sanitized n8n workflow         |
| `workflow.png`  | Screenshot of the n8n workflow |

---

##  Project Status

**Completed – Beginner Automation Project**

This project represents my first practical project with **n8n and workflow automation**.

I am continuing to learn n8n and plan to build more advanced automation workflows in the future.

---

##  Author

**Tanvi Sachin Itagikar**

Engineering Student | Cybersecurity & AI Enthusiast | Learning Workflow Automation

---

If you found this project useful, feel free to explore the workflow and follow my learning journey.
