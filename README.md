# SalesForce - FlowOpportunity

# 🧠 Salesforce Automation: Create Project from Opportunity

This project automates the creation of a **Project record** whenever an **Opportunity** is marked as *Closed Won* in Salesforce.

## ⚙️ Objective
To demonstrate a record-triggered flow that links Opportunities to custom Project objects, optimizing post-sales automation.

## 🧩 Features
- Automatically creates a `Project__c` record after an Opportunity is created or updated to *Closed Won*.
- Copies key information such as:
  - Project Name = Opportunity Name
  - Opportunity Relationship
  - Owner = Opportunity Owner

## 🧱 Salesforce Components
- **Object:** Project__c  
- **Flow Type:** Record-Triggered Flow  
- **Trigger:** A record is created or updated  
- **Condition:** `StageName = Closed Won`  
- **Optimization:** Actions and Related Records  

## 🧰 Tools & Skills
- Salesforce Flow Builder  
- Object Manager Configuration  
- Debug and Record Testing  
- Basic Admin & Low-Code Automation 
