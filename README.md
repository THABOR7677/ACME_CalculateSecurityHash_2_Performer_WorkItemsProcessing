# ACME_CalculateSecurityHash_2_Performer_WorkItemsProcessing

## 📌 Project Overview
This UiPath project is the **Performer** part of the ACME Calculate Client Security Hash automation.  
It retrieves **Work Items (WI5)** from an **Orchestrator Queue**, logs into the **ACME System 1 portal**, and processes each item by calculating and submitting the Client Security Hash.

---

## 🛠 Features
- Built on **UiPath REFramework**.
- Fetches transactions from Orchestrator Queue.
- Logs into **ACME System 1** automatically.
- Calculates and submits the **Client Security Hash**.
- Implements retry, logging, and exception handling.

---

## 📂 Project Structure
- **Main.xaml** → Entry point of the automation.
- **Framework folder** → REFramework state machine (Init, GetTransactionData, Process, End).
- **Data folder** → Config file (`Config.xlsx`) containing Orchestrator assets and settings.

---

## 📋 Requirements
- UiPath Studio **2022.10+** (or higher).
- Access to **ACME System 1** demo site.
- UiPath Orchestrator account with a configured Queue.
- Required packages:
  - UiPath.Excel.Activities
  - UiPath.System.Activities
  - UiPath.UIAutomation.Activities

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/ACME_CalculateSecurityHash_2_Performer_WorkItemsProcessing.git
