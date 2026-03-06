🤖 Zero-Touch B2B Client Onboarding System

Status: Operational | Tech Stack: Zapier, Google Workspace (Forms, Drive, Gmail), HubSpot CRM

📖 The Business Problem

In high-growth consulting or trade environments, manual onboarding is a bottleneck. When I started this project, the goal was to eliminate the 2-3 hour manual "setup" period that usually follows a new client signing.

Manual steps replaced:

Monitoring form submissions.

Manually creating file directories in Google Drive.

Manually drafting and sending welcome emails.

Manually updating the CRM pipeline.

🛠️ The Solution (Architecture)

I architected a multi-step automation "Brain" using Zapier to handle the data flow between three core business pillars.

1. The Entry Point (Google Forms)

Purpose: Standardized data collection.

Logic: Captures Company Name, Contact Details, and Service Type. This acts as the "Single Source of Truth."

2. The Logic Engine (Zapier)

Trigger: New Form Response

Logic Branching:

Action A: Create a dynamic folder in Google Drive using the [Company Name] variable from the form.

Action B: Generate a personalized Gmail welcome message.

Variable Mapping: I utilized the "Alternate Link" variable from the Drive step to ensure the client receives their specific folder key instantly.

3. The Result (Client Experience)

Outcome: Within 60 seconds of clicking "Submit," the client has a secure folder and a professional welcome in their inbox.

Business Impact: 100% reduction in administrative lead time for onboarding.

📸 Technical Walkthrough (Proof of Work)

1. The Automation Logic (Zapier)

This screenshot demonstrates the multi-step "Zap" that connects the intake form to the cloud storage and communication layers.

2. Automated Output (Google Drive)

Proof of the system successfully generating unique, organized client directories upon form submission.

3. Client Communication (Gmail)

The personalized welcome email containing the dynamic link to the specific client folder.

📈 Skills Demonstrated

Process Engineering: Mapping a business need to a technical workflow.

SaaS Integration: Expert-level configuration of Google API and Zapier.

Data Integrity: Ensuring variables map correctly across different software platforms.

Customer Experience (CX): Reducing friction in the client journey.

Developed by Hajar Haddi
<img width="1229" height="483" alt="welcome-email" src="https://github.com/user-attachments/assets/0d143550-585f-4598-a6fc-4f3d541be104" />

<img width="909" height="488" alt="zapier-workflow" src="https://github.com/user-attachments/assets/46fc932c-311f-4cbd-a3b9-c16e7e0b86fd" />

<img width="1230" height="545" alt="drive-output" src="https://github.com/user-attachments/assets/c36bea36-7752-48ce-9143-bd5aae06d38a" />

