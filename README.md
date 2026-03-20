# GuideWire_SkyLogic
AI-Powered Insurance for India’s Gig Economy

----------------

Overview
-----------

Gig workers such as delivery partners working with platforms like Zomato, Swiggy, Amazon, Zepto, and Dunzo play a crucial role in supporting India’s rapidly growing digital economy. These workers depend heavily on daily deliveries for their income. However, their earnings are strongly influenced by external environmental conditions such as extreme weather, high pollution levels, or natural disasters.

When such disruptions occur, gig workers often experience reduced working hours or are unable to work at all. This can lead to a significant income loss, sometimes ranging from 20% to 30%. Despite facing these risks regularly, most gig workers currently do not have access to financial protection mechanisms during such events.

To address this issue, this project proposes an AI-enabled parametric insurance platform designed specifically for gig workers. The platform provides automated income protection whenever environmental disruptions affect their ability to work, while ensuring strong fraud resistance and system sustainability.

---

Problem Statement
------------------

Gig workers rely on daily deliveries for income, but environmental disruptions such as heavy rain, extreme temperatures, pollution, or disasters reduce their working hours and earnings.

Currently, there is:
- No accessible micro-insurance model  
- No fast claim processing  
- No protection against short-term income shocks  

This project builds a parametric insurance system that:
- Automatically detects disruptions  
- Validates real income impact  
- Triggers instant payouts  
- Prevents fraud and system abuse  

---

Key Features :
---------------

• Weekly Micro-Insurance Subscription  
Affordable plans aligned with gig workers’ weekly earning cycle.

• Parametric Trigger-Based Coverage  
Insurance activates automatically based on environmental thresholds.

• Automated Payout System  
No claims required—payouts are triggered instantly.

• Activity-Based Validation  
Ensures payouts reflect actual income loss.

• Risk-Based Premium Calculation  
Premiums are dynamically adjusted using probability-based models.

• AI-Driven Fraud Detection  
Detects GPS spoofing, duplicate accounts, and abnormal patterns.

• Continuity-Based Coverage  
Encourages consistent subscription through improved eligibility.

• Mobile-First Platform  
Simple and accessible for gig workers.

---

Persona-Based Scenario
--------------------------------

Persona: Shiva – Food Delivery Partner  

Weekly Income: ₹5000  

During heavy rainfall:
- Earnings drop to ₹3500  
- Income loss = ₹1500  

System Response:
- Rainfall trigger detected  
- Activity drop confirmed  
- ₹500 payout automatically credited  

---

Application Workflow
-----------------------

1. User Registration  
2. Weekly Subscription Activation  
3. Waiting Period (3–7 days)  
4. Real-Time Environmental Monitoring  
5. Activity Tracking  
6. Multi-Signal Validation  
7. Automatic Payout  

---

Weekly Premium Model
-------------------------------

| Weekly Premium | Coverage |
|---------------|----------|
| ₹20           | ₹500     |
| ₹40           | ₹1000    |
| ₹60           | ₹1500    |

Premium is calculated using:

Premium ≈ P(trigger) × payout + margin  

---

Parametric Insurance Triggers
-------------------------------

- Rainfall > 120 mm  
- Temperature > 45°C  
- AQI > 400  
- Disaster Alerts  

---

Sustainability & Misuse Prevention
-----------------------------------

• Waiting Period  
Prevents immediate exploitation after subscription  

• Continuity-Based Eligibility  
Consistent users receive full benefits  

• Activity Validation  
Payout requires both disruption AND reduced activity  

• Dynamic Pricing  
Adjusted based on risk levels  

---

Adversarial Defense & Anti-Spoofing Strategy
----------------------------------------------

To handle fraud scenarios such as fake GPS data and coordinated attacks, the system uses a multi-layer validation approach.

### 1. Multi-Signal Validation

Trigger = Environmental Event + Activity Drop + Location Confidence  

Ensures payouts are not based on a single condition.

---

### 2. GPS Spoofing Detection

Detects:
- Sudden location jumps  
- Unrealistic movement speeds  
- GPS vs network mismatch  

---

### 3. Activity-Based Verification

Validates real work behavior using:
- App usage patterns  
- Movement consistency  
- Delivery-like activity  

---

### 4. Fraud Ring Detection

Identifies coordinated attacks by detecting:
- Multiple users triggering payouts simultaneously  
- Similar behavior patterns across accounts  

---

### 5. Risk Scoring System

Each user is assigned a Fraud Risk Score.

- Low Risk → Instant payout  
- Medium Risk → Delayed verification  
- High Risk → Blocked payout  

---

AI / ML Integration
----------------------

• Risk Prediction  
Time-series analysis to estimate disruption probability  

• Premium Calculation  
Expected loss model  

• Fraud Detection  
Anomaly detection and behavioral analysis  

---

Platform Choice
-------------------

Mobile-first system with admin dashboard for monitoring.

---

System Architecture
-----------------------------------

Mobile App  
→ Backend API  
→ Environmental Data APIs + Activity Monitoring  
→ Parametric Decision Engine  
→ AI Risk Engine  
→ Payment Gateway  

---

Tech Stack
-------------

Frontend: React Native, React.js  
Backend: Node.js, Express  
Database: PostgreSQL, Firebase  
AI/ML: Python, Scikit-learn  
APIs: Weather, AQI  
Payments: Razorpay / UPI  

---

Development Plan
------------------

Phase 1: MVP  
Phase 2: AI Integration  
Phase 3: Automation  
Phase 4: Testing  

---

Future Enhancements
---------------------

- Gig platform integration  
- Personalized plans  
- Predictive alerts  

---

Impact
---------

- Reduces income volatility  
- Provides fast compensation  
- Builds trust in gig ecosystem  

---

Disclaimer
--------------

Prototype for hackathon. Real-world deployment requires regulatory compliance.

---

Key Idea  

From uncertain income → to automated income protection  
