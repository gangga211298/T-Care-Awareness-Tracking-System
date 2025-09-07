# T-Care Awareness Tracking System  

## Background  
Toyota launched an after-sales service programme called **T-Care** in **July 2022**, available at all authorized Toyota workshops.  

This programme offers:  
- Free service and parts for up to **7 periodic services**, or for **3 years / 60,000 km**.  
- **Extended warranty** for **1 year / 20,000 km**, provided that the customer routinely services their vehicle every 6 months.  

However, at **Astrido Toyota Kebon Jeruk**, the claim rate remained low during the January–April 2023 period:  
- 1st Service : 80%  
- 2nd Service : 75%  

This condition is detrimental to customers, as they could potentially lose their Extended Warranty benefits.  

**Several main causes were identified:**  
- Customer awareness of T-Care was only **61%** (below the 100% target).  
- Customer interest after being educated remained relatively low (**65%**).  
- Salespeople still recorded customer feedback manually using *Google Sheets*.  
- After-Sales PICs (*MRA & SA*) did not have access to customer education and interest data.  
- Management found it difficult to monitor T-Care comprehensively.  

---

## Objectives  
The project aims to:  
1. **Facilitate Sales** in conducting T-Care education and recording customer feedback/verbatim in a structured manner.  
2. **Integrate data** across all relevant PICs (*Sales & After-Sales*).  
3. Provide **monitoring tools** to support preventive, appropriate, and specific actions.  

---

## Tools & Technology  
- **AppSheet** → Application for customer education & verbatim input.  
- **Google Sheets** → Primary database for storing input results.  
- **Looker Data Studio** → Monitoring dashboard for Management and After-Sales PICs.  

---

## Flow of Use of the T-Care Awareness Tracking System Application  

The system involves all PICs at **Astrido Toyota Kebon Jeruk**, namely:  
- Admin  
- Salesman  
- Customer Relations Coordinator (CRC)  
- Maintenance Reminder Appointment (MRA)  
- Service Advisor (SA)  

**Flow of use:**  
<img width="4381" height="1074" alt="Picture4" src="https://github.com/user-attachments/assets/ee78c160-b496-4cef-8fe6-18f610cd5076" />

### Step 1 – Data Entry by Admin  
Admin inputs new customer vehicle data, such as:  
- VIN  
- Model  
- License plate number  
- Customer name  
- Salesman name  

### Step 2 – Pre-DEC by Salesman  
Salesman prepares H-1 before vehicle handover, including setting the service reminder on the customer’s head unit.  

### Step 3 – DEC by Salesman  
During vehicle delivery (*DEC*), Salesman performs:  
- T-Care education  
- Survey of T-Care interest  
- Service workshop preference  
- Education on T-Intouch and Insurance  

Results are recorded in the application and forwarded to **CRC**.  

### Step 4 – Post Delivery Follow-Up (PDFU) by CRC  
CRC follows up **3 days after DEC** to confirm:  
- Vehicle condition  
- Verification of T-Care education  

Results are input into the application and forwarded to **MRA**.  

### Step 5 – Service Reminder by MRA  
MRA reminds customers **H-7 before 1st Service**, assists with booking, and ensures punctual service.  
Results are recorded and forwarded to **SA**.  

### Step 6 – 1st Service by SA  
During the **1st Service**, SA confirms:  
- T-Care benefits  
- 2nd Service schedule  
- Preferred workshop  
- Head unit reminder setup for 2nd Service  

All data is entered into the application, then forwarded back to **MRA** for a 2nd Service reminder (±5 months later).  

---

## Monitoring & Dashboard  
All steps in the T-Care Awareness Tracking System are **fully integrated** and monitored in **real time** through an **interactive dashboard**.  

The dashboard provides visibility on:  
- Education status  
- Awareness levels  
- Customer interest  
- Periodic service progress  

With these insights, **Management, Sales, and After-Sales** teams can make decisions that are:  
- Personalized  
- Timely  
- Data-driven  

---

## Application & Dashboard Demo  
- 📱 **Application**: [T-Care AppSheet](https://www.appsheet.com/newshortcut/e11524a1-0482-459a-842a-086da3997dfe)
- **For login: (Username: Gangga | Password: Gangga)**
<img width="1280" height="720" alt="Slide1" src="https://github.com/user-attachments/assets/c39a545a-9196-47cb-a11a-0847546ba733" />
<img width="1280" height="720" alt="Slide2" src="https://github.com/user-attachments/assets/b75aa49b-a99a-44ff-aec9-e7efba7bff29" />

- 📊 **Dashboard**: [T-Care Looker Studio](https://lookerstudio.google.com/u/0/reporting/775f16e3-0b50-46a9-b93a-67038ed32540)  
![T-Care_Awareness_Tracking_Dashboard](https://github.com/user-attachments/assets/74eec5cb-f0e4-4799-a88b-03afeceae98c)

---

## Results & Insight  
The implementation of the T-Care Awareness Tracking System has simplified the education and monitoring process, which was previously done manually in Google Sheets.  

With this system:  
- Salespeople can easily input **customer education** and **survey data** directly through the application.  
- **CRC and MRA** can monitor data in real time to take more appropriate and timely follow-up actions.  
- **Service Advisors (SA)** can access **customer education history**, enabling personalised communication during service.  
- **Management** has access to a monitoring dashboard displaying:  
  - Customer awareness and interest in T-Care  
  - First service claim progress  
  - Service reminder status  
  - Customer commitment to routine servicing  

**Implementation Results:**
<img width="1280" height="720" alt="TYY" src="https://github.com/user-attachments/assets/b357d788-24c2-45ac-92d3-777ce5e34d66" />

✨ With this system, processes that were previously *manual, fragmented, and difficult to monitor* are now **automated, integrated, and transparent**.  

---

## Project Achievements  
The **T-Care Awareness Tracking System** is a key component of the **Trade-Cycle Management (TCM) project** at **Astrido Toyota Kebon Jeruk**, serving as a Pilot Project.  

Under the direct guidance and supervision of the **Board of Directors (BOD) of Astrido Toyota** and **Toyota Astra Motor (TAM)**, this project has successfully achieved the following:  
- ✅ Direct review (*genba*) by the BOD of Astrido and TAM  
- 🏆 1st Place Winner at the **2023 Regional Kaizen Innovation Marathon (RKIM)**  
- 🔄 Replicated (*Yokoten*) to **17 other Astrido Toyota branches**  
- 📌 Became the **benchmark for TCM implementation** across all Toyota dealers in Indonesia  

<img width="1280" height="720" alt="DSDSD" src="https://github.com/user-attachments/assets/cbef4a98-b29b-4319-b17d-cdcbf638c99f" />

---

## Key Learnings  

### 🔗 No-Code Tools Integration  
- Learned how to connect *AppSheet*, *Google Sheets*, and *Looker Studio* into an interconnected system.  
- **Challenge:** ensuring consistent data structure for easy processing and visualisation.  

### 🛠 Workflow Design  
- Understood the importance of designing a **clear process flow** for each PIC (*Admin, Salesman, CRC, MRA, SA*).  
- Learned that proper flow documentation helps minimise miscommunication and ensures smoother adoption.  

### 📊 Data-Driven Decision Making  
- Real-time **dashboards** provide insights that were previously impossible with manual processes.  
- Customer **awareness** and **interest** can now be monitored directly, enabling faster, more specific decisions by Management.  

### 🚀 Future Improvements  
- Integrate **automatic notifications** (WhatsApp/Email) for service reminders.  
- Add a **tracking feature** up to the **7th service** for more comprehensive monitoring.  
- Connect data to the **CRM system** for a more complete customer journey view.  
