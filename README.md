# TNSkills Salesforce – Customer Support Ticket Priority Prediction and Automated Assignment System

## 🎫 Project Overview

The **Customer Support Ticket Priority Prediction and Automated Assignment System Using Agentforce** is a Salesforce-based solution designed to automate the analysis, prioritization, and assignment of customer support tickets.

The system analyzes customer support ticket descriptions and classifies them into **High, Medium, or Low priority** based on configured urgency conditions.

The solution uses a custom Salesforce object named **Support Ticket Intelligence** to store customer support information such as Account, Contact, Issue Type, Description, Priority Level, Status, Assigned Agent, and SLA Breach Risk.

An **Auto-Launched Flow** retrieves the latest support ticket associated with a customer Account, analyzes the ticket description, determines its priority, creates an urgent Task for High-priority tickets, and assigns the ticket to the appropriate support user.

The system is integrated with **Agentforce** through a dedicated **Support Ticket Priority Analysis** subagent, providing users with a conversational way to analyze ticket information and receive priority and assignment details.

---

## 👥 Team Details

| Role | Name | Email |
|---|---|---|
| Team Lead | SURTHIGA P | surthiga1215@gmail.com |
| Team Member | DHARANIRAJAM K | dharanirajam5@gmail.com |
| Team Member | VISHALI S | vishalikjs@gmail.com |
| Team Member | JANAVI V | vjanu0808@gmail.com |

### Team ID

`SWTID-2026-9353`

---

## 🎥 Project Demo

[▶️ Watch Project Demo](https://drive.google.com/file/d/1wwOja5hfYD9nkjXzIaCYIo2jhh0L7hcS/view?usp=sharing)

---

## 🤖 Agentforce Details

### Agentforce Subagent

**Support Ticket Priority Analysis**

The Agentforce subagent is designed to analyze customer support ticket information and determine the appropriate priority based on the configured instructions and automation logic.

### Agentforce Capabilities

The Agentforce integration can:

- Retrieve the latest support ticket associated with an Account
- Analyze ticket information
- Determine ticket priority
- Return High, Medium, or Low priority
- Trigger the Salesforce Flow
- Provide assignment information
- Return the final ticket-processing result conversationally

---

## 🎯 Project Objectives

The main objectives of the project are:

- Automatically classify support tickets based on priority
- Retrieve and analyze the latest customer ticket
- Create urgent Tasks for High-priority tickets
- Assign tickets to the appropriate support agent
- Reduce manual ticket prioritization and assignment
- Improve response time
- Improve support-team productivity
- Provide conversational ticket analysis through Agentforce
- Identify critical customer issues faster

---

## ✨ Key Features

### 🎫 Automated Ticket Prioritization

Support tickets are classified into:

- 🔴 High Priority
- 🟠 Medium Priority
- 🟢 Low Priority

### ⚡ Automated Task Creation

When a ticket is identified as High Priority, the Flow automatically creates a Task for urgent handling.

### 👤 Automated Agent Assignment

The system assigns the support ticket and generated Task to the configured Salesforce support user.

### 🤖 Agentforce-Powered Analysis

Users can interact with the system through Agentforce to retrieve and analyze customer support ticket information.

### 🔄 Automated Salesforce Flow

The Auto-Launched Flow handles:

- Account retrieval
- Latest ticket retrieval
- Ticket description analysis
- Priority classification
- High-priority Task creation
- Agent assignment
- Final response generation

### 📊 SLA Breach-Risk Information

The Support Ticket Intelligence object maintains SLA breach-risk information to help identify tickets requiring attention.

### 🗂️ Centralized Data

Customer, Account, Contact, ticket, priority, assignment, and task information are maintained within Salesforce.

---

## 🛠️ Technologies & Salesforce Features

The project uses:

- Salesforce CRM
- Salesforce Lightning Experience
- Salesforce Developer Environment
- Custom Salesforce Objects
- Salesforce Flow
- Auto-Launched Flow
- Agentforce
- Agentforce Subagents
- Flow-Based Agentforce Actions
- Salesforce Profiles
- Salesforce Roles
- Salesforce Permissions
- Salesforce Reports & Dashboards

---

## 🗂️ Custom Object

### Support Ticket Intelligence

The **Support Ticket Intelligence** custom object acts as the central data structure for managing customer support ticket information.

It contains information related to:

- Account
- Contact
- Issue Type
- Description
- Priority Level
- Status
- Assigned Agent
- SLA Breach Risk

The object is connected with Salesforce Account and Contact records and is used by the Flow and Agentforce components.

---

## 🔄 Salesforce Automation

The **Support Ticket Intelligence Auto-Launched Flow** automates the complete ticket-processing workflow.

### Flow Process

```text
Customer Account
       ↓
Support Ticket Creation
       ↓
Ticket Description
       ↓
Support Ticket Intelligence
       ↓
Automated Flow
       ↓
Ticket Priority Analysis
       ↓
Priority Classification
       ↓
Agent Assignment
       ↓
Urgent Task / Normal Handling
       ↓
Status Update
