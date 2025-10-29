# 🏦 MeowNow – Banking KYC Process Automation

### 🔹 Overview
**MeowNow** is an intelligent KYC (Know Your Customer) process automation system built using **ServiceNow App Engine Studio**.  
It streamlines banking KYC verification by automating document collection, verification, approvals, and compliance tracking — reducing manual errors and speeding up onboarding.

---

### ⚙️ Tech Stack
- **Platform:** ServiceNow App Engine Studio  
- **Workflow Automation:** Flow Designer, Approval Engine, SLA Policies  
- **Integration APIs:** Surepass (PAN/Aadhaar Verification), DigiLocker (Govt Document Fetch), OpenFin (Front-end Integration)  
- **Database:** Custom ServiceNow Tables (KYC Requests, Verification Tasks, Manager Reviews)  
- **Testing:** Automated Test Framework (ATF)  
- **UI/UX:** Service Portal, Virtual Agent, Knowledge Articles  
- **Reporting:** ServiceNow Dashboards & Analytics

---

### 🚀 Working

1. **Customer Submission:**  
   User submits KYC details and documents through a Record Producer form in the Service Portal.  

2. **Document Verification:**  
   Flow Designer triggers automatic verification via **Surepass** or **DigiLocker APIs**.  
   OCR and validation logic ensure accuracy before assigning tasks.

3. **Workflow Routing:**  
   The system auto-routes requests to the **KYC Verifier**, then to **KYC Manager** for approval, based on SLA policies.  

4. **SLA Enforcement:**  
   - 24h for verification  
   - 48h for managerial approval  
   - Auto-escalations on SLA breaches  

5. **Notifications & Status Tracking:**  
   Real-time emails and Service Portal updates for submission, approval, or re-submission.  

6. **Dashboard & Reporting:**  
   Managers monitor performance, SLA status, and request metrics using ServiceNow Reports & Analytics.  

7. **Chatbot & Help:**  
   Integrated **Virtual Agent** assists users with queries and document upload guidance.

---

### 📦 Features
- End-to-end digital KYC process  
- Real-time API verification (PAN, Aadhaar)  
- SLA-driven approvals and escalation  
- Role-based access control (Verifier, Manager, Compliance)  
- Automated emails and portal updates  
- Custom dashboards for monitoring  

---

### 🧠 Future Enhancements
- Integration with AI-driven fraud detection  
- Multi-language chatbot support  
- Predictive analytics for compliance insights

---

### 🧩 Built With
**ServiceNow App Engine Studio**, leveraging low-code tools for workflow automation, integrations, and analytics.

---
