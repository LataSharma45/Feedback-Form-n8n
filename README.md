# AI-Powered Feedback Management Workflow (n8n)

## Overview

Developed an **AI-powered customer feedback automation system** using **n8n** to streamline feedback processing and eliminate manual triage. The workflow leverages **Google Gemini AI** to analyze customer messages, classify them into actionable categories, and trigger automated business workflows in real time.

## Key Features

* Built an end-to-end **no-code/low-code automation workflow** in **n8n**.
* Integrated **Google Gemini AI** for intelligent feedback classification.
* Automatically categorizes customer feedback into:

  * **Complaint**
  * **Compliment**
  * **Feature Request**
* Sends an automated acknowledgment email to customers via **Gmail** when a complaint is detected.
* Instantly notifies the internal support team through **Slack** for faster response and issue resolution.
* Routes compliments and feature requests to the appropriate business channels for recognition and product improvement.
* Uses conditional workflow logic to ensure each feedback type follows the correct business process.
* Reduces manual effort, improves response time, and enables scalable customer support automation.

## Workflow

1. Customer submits feedback.
2. n8n receives the feedback.
3. Google Gemini AI analyzes the message.
4. AI classifies the feedback as Complaint, Compliment, or Feature Request.
5. Based on the classification:

   * **Complaint:** Sends a personalized email via Gmail and alerts the support team on Slack.
   * **Compliment:** Shares positive feedback with the team.
   * **Feature Request:** Routes the suggestion for product evaluation.

## Technologies Used

* **n8n** – Workflow automation
* **Google Gemini AI** – AI-powered text classification
* **Gmail API** – Automated email notifications
* **Slack API** – Real-time team notifications

## Skills Demonstrated

* AI Workflow Automation
* Prompt Engineering
* API Integration
* Business Process Automation
* Event-Driven Architecture
* Conditional Logic & Routing
* No-Code/Low-Code Development
* Customer Support Automation
* AI-Powered Decision Making
* Workflow Orchestration

## Business Impact

* Automated customer feedback processing from submission to notification.
* Eliminated manual feedback categorization through AI-powered classification.
* Enabled immediate support team alerts for complaints.
* Improved customer communication with automated email acknowledgments.
* Created a scalable workflow that can be extended with CRM, databases, ticketing systems, or analytics platforms.

## Architecture Image
<img width="1456" height="686" alt="image" src="https://github.com/user-attachments/assets/0d359066-73ef-4eb3-bdef-b14d6ac4eee4" />

<img width="1576" height="691" alt="image" src="https://github.com/user-attachments/assets/3db52e60-44cf-4224-8d07-795a1b5d393f" />

## Form
<img width="727" height="855" alt="image" src="https://github.com/user-attachments/assets/0c70d328-bf6b-41a3-8c84-ca1b47bd5ecd" />


