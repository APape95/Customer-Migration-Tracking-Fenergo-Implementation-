# Customer Migration Tracking Dashboard (Fenergo Implementation)

## 📌 Overview
This project delivers an end-to-end data solution to track the migration of CDD SMB customers from legacy systems into Fenergo.

The migration programme lacked a reliable way to measure progress due to a constantly changing scope and no single source of truth. This solution provides clear visibility of migration status, identifies blockers, and enables both operational and executive reporting.

---

## ❗ Problem Statement
Migration of CDD SMB customers to Fenergo had no single source of truth. A constantly changing scope meant the total population, progress, and migration blockers were unclear, limiting tracking, prioritisation, and board-level reporting.

---

## 🎯 Objectives
- Define a dynamic total population of customers in scope  
- Track migration progress across legacy and Fenergo systems  
- Identify and categorise migration blockers (exceptions)  
- Provide clear reporting for Product, Tech, and senior stakeholders  
- Enable prioritisation of technical fixes  

---

## 🛠️ Tech Stack
- **SQL** – Data extraction, transformation, and business logic  
- **Tableau** – Dashboard development and reporting  

**Data Sources:**
- Legacy customer systems  
- Fenergo (target system)  

---

## 🔄 Data Pipeline & Approach

### 1. Dynamic Scope Definition
- Built SQL logic to define the total in-scope population  
- Designed to handle frequently changing product definitions  

### 2. Migration Progress Tracking
- Joined legacy datasets with Fenergo records  
- Calculated:
  - Total population  
  - Number migrated  
  - % completion  

### 3. Exception Classification
- Identified customers not yet migrated  
- Categorised into:
  - **Eligible** (pending migration)  
  - **Exceptions** (blocked)  

- Defined exception types to highlight root causes  

---

## 📊 Dashboard Features (Tableau)

### Executive View
- Total customers in scope  
- % migrated  
- Remaining population  

### Operational Views
- Migration status breakdown  
- Exception categorisation  
- Drill-down to customer-level data  

---

## 📈 Key Outcomes
- Created a **single source of truth** for migration tracking  
- Enabled **real-time visibility** of migration progress  
- Identified **root causes of migration failures**  
- Supported **prioritisation of technical fixes**  
- Delivered **board-level reporting** for a critical transformation programme  

---

## 🧠 Key Skills Demonstrated
- SQL data transformation (joins, CTEs, aggregations)  
- Data integration across legacy and target systems  
- Data reconciliation and validation  
- Exception handling and classification logic  
- Dashboard development for multiple stakeholder levels  
- Translating business problems into data solutions  

---

## 🔍 Example Use Cases
- Track overall migration progress against a dynamic population  
- Identify blockers preventing customer migration  
- Monitor exception resolution over time  
- Provide clear, simplified reporting to senior stakeholders  

---

## ⚠️ Data Privacy
All data used in this project has been anonymised.  
Table and column names have been generalised to protect sensitive business information.

---

## 📷 Dashboard Screenshots

### Migration Overview
Shows overall migration progress, including total in scope, migrated, eligible, and exceptions.

![Migration Overview](https://raw.githubusercontent.com/APape95/Customer-Migration-Tracking-Fenergo-Implementation-/main/Migration%20Dashboard%20-%20Customer%20info%20removed.png)

---

### Exception Breakdown
Breakdown of migration blockers by category, enabling targeted resolution.

![Exception Breakdown](https://raw.githubusercontent.com/APape95/Customer-Migration-Tracking-Fenergo-Implementation-/main/Migration%20Dashboard%20-%20Exceptions%20-%20Customer%20info%20removed.png)

---

## 📢 Stakeholder Adoption & Impact

### Go-Live Communication
Following deployment, the dashboard was rolled out to Product and Tech stakeholders as the central source of truth for migration tracking.

[![Go Live Email](images/go-live-email.png)](https://github.com/APape95/Customer-Migration-Tracking-Fenergo-Implementation-/blob/main/Migration%20Dashboard%20-%20Go%20Live%20communication.png)

---

### Early Success & Feedback
Initial feedback highlighted improved visibility of migration progress and clearer identification of blockers.

[![Stakeholder Feedback](images/feedback-email.png)](https://github.com/APape95/Customer-Migration-Tracking-Fenergo-Implementation-/blob/main/Migration%20Dashboard%20-%20success%20story.png)
