# 🎉 Event Management System – Salesforce Capstone Project

## 📌 Project Overview
Managing events manually often leads to missed registrations, confusion in resource allocation, and difficulty in tracking participants or generating reports.  
This project aims to build a **Salesforce-based Event Management System** that streamlines the entire process of organizing events — from registrations to reporting.

---

## 🎯 Problem Statement
Event organizers face challenges in handling registrations, communicating with participants, tracking sponsors, and monitoring resources. Without a centralized system, it becomes difficult to manage event operations effectively.  

The objective is to **design and implement a Salesforce CRM solution** that enables efficient event planning, participant management, and performance tracking through automation and dashboards.

---

## ✅ Objectives
- Create and manage multiple **events** (date, venue, type, capacity).  
- Allow **participant registration** and track details in Salesforce.  
- Send automated **confirmation emails and reminders** for events.  
- Maintain records of **sponsors and resources** allocated per event.  
- Build **reports and dashboards** for event performance insights.  

---

## ⚙️ Key Features
1. **Event Creation & Management**  
   - Store event details: name, type, venue, capacity, and dates.  

2. **Participant Registration**  
   - Capture registrations as Leads/Contacts.  
   - Track status: Registered, Confirmed, Attended.  

3. **Automated Communication**  
   - Confirmation emails upon registration.  
   - Reminder notifications before the event.  

4. **Resource & Sponsor Tracking**  
   - Assign resources like halls, food, logistics.  
   - Track sponsor contributions for each event.  

5. **Reports & Dashboards**  
   - Total registrations vs capacity.  
   - Event revenue and sponsor contributions.  
   - Participant demographics and attendance.  

---

## 🛠️ Tech Stack
- **Salesforce CRM** (Core platform)  
- **Objects:** Leads, Contacts, Accounts, Opportunities, Custom Objects (Events, Sponsors, Resources)  
- **Automation:** Flows, Validation Rules, Email Alerts  
- **Reports & Dashboards:** Event-wise performance and participation tracking  

---

## 📂 Phase-wise Progress

### 🔹 Phase 1 – Requirement Gathering & Design
- Understood the **problem statement** and identified event management challenges.  
- Defined the **objectives and scope** of the solution.  
- Designed the **data model** (Events, Participants, Sponsors, Resources).  
- Documented the **features and workflows** required in Salesforce.  

📁 Deliverables:  
- Project proposal & requirement document.  
- Initial GitHub repo setup with project overview.  

---

### 🔹 Phase 2 – Salesforce Setup & Configuration
- Created a **new Salesforce Lightning App**: *Event Management System*.  
- Built **custom objects** like Event Details, Participant Info, and Sponsors.  
- Added **custom fields** (date, picklist, text, relationships).  
- Created **tabs** for easy navigation of custom objects.  
- Configured **profiles/permissions** for controlled access.  
- Captured **screenshots** of setup (available in `/Phase2_Salesforce_Setup/` folder).  

📁 Deliverables:  
- Salesforce app configuration screenshots.  
- Updated GitHub repo with Phase 2 documentation.  

---

🔹 Phase 3 – Event Management Data Modeling
Designed and implemented the data model for comprehensive event tracking.
Created custom objects and defined relationships:
- Event__c → EventRegistration__c (Master-Detail)
- Event__c → Sponsor__c (Lookup)
- Event__c → Resource__c (Lookup)
Documented the schema in Phase3_Event_Management_Data_Modeling.pdf.
Ensured data integrity with validation rules and proper field types.
Prepared reports and dashboards based on the new data model.
📁 Deliverables:

Phase3_Event_Management_Data_Modeling.pdf added to repository.
Updated README with Phase 3 progress and screenshots 

## 👨‍💻 Author
This project is developed as part of **TCS Lastmile Salesforce Capstone Project**.  
Repo maintained by: **Kattamuri Aswini Sudha**  
