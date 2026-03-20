# GuideWire_SkyLogic
AI-Powered Insurance for India’s Gig Economy

----------------

Overview
-----------

Gig workers such as delivery partners working with platforms like Zomato, Swiggy, Amazon, Zepto, and Dunzo play a crucial role in supporting India’s rapidly growing digital economy. These workers depend heavily on daily deliveries for their income. However, their earnings are strongly influenced by external environmental conditions such as extreme weather, high pollution levels, or natural disasters.

When such disruptions occur, gig workers often experience reduced working hours or are unable to work at all. This can lead to a significant income loss, sometimes ranging from 20% to 30%. Despite facing these risks regularly, most gig workers currently do not have access to financial protection mechanisms during such events.

To address this issue, this project proposes an AI-enabled parametric insurance platform designed specifically for gig workers. The platform provides automated income protection whenever environmental disruptions affect their ability to work.

The system utilizes real-time environmental data, risk-based models, and automated payout mechanisms to deliver quick financial support. By offering a structured and affordable subscription model, the platform ensures that gig workers receive timely compensation without complicated claim procedures.

---

Problem Statement
------------------

Gig workers such as delivery partners working with platforms like Zomato, Swiggy, Amazon, Zepto, and Dunzo rely on daily deliveries for their income. However, environmental conditions such as heavy rain, extreme temperatures, pollution, or natural disasters can reduce their working hours and lead to income loss.

Most gig workers currently lack insurance coverage or financial safety nets to protect them from such disruptions. Additionally, traditional insurance systems involve manual and time-consuming claim processes.

This project aims to develop a smart parametric insurance system that automatically compensates gig workers when predefined environmental conditions occur. Using real-time environmental data, risk modeling, and automated payouts, the system ensures fast, transparent, and reliable income protection.

---

Key Features :
---------------

• Monthly Micro-Insurance Subscription with Weekly Billing  
Gig workers enrol in a structured monthly plan with weekly auto-deductions, ensuring affordability while preventing misuse.

• Parametric Triggers Based on Environmental Data  
The system monitors real-time environmental conditions such as rainfall, temperature, pollution levels, and disaster alerts to determine when coverage should activate.

• Automated Payout System  
When predefined environmental conditions are met, compensation is automatically processed without requiring manual claim submissions.

• Risk-Based Premium Calculation  
Premiums are calculated using expected loss models based on disruption probability and payout value.

• AI-Driven Fraud Detection  
Anomaly detection models analyze user behavior to identify suspicious activity such as fake GPS or duplicate accounts.

• Mobile-First Platform  
A user-friendly mobile application allows gig workers to subscribe, track coverage, receive alerts, and access payouts easily.

---

Persona-Based Scenario
--------------------------------

Persona 1: Sahil – Food Delivery Partner

Profile  
• Age: 23  
• Platform: Swiggy  
• Weekly Income: ₹5000  

Scenario  

Due to heavy rainfall in the city, Shiva is unable to complete many deliveries. As a result, his weekly earnings decrease.

Category        Amount  
Normal Weekly Earnings        ₹5000  
Actual Earnings During Disruption        ₹3500  
Income Loss        ₹1500  

Since the rainfall level exceeds the predefined parametric threshold, the platform automatically triggers an insurance payout of ₹500 to support Sahil during the disruption.

---

Application Workflow
-----------------------

1. User Registration  
The gig worker registers on the platform using their mobile number.

2. Insurance Subscription  
The worker subscribes to a monthly insurance plan with weekly deductions.

3. Waiting Period Activation  
Coverage becomes active after a short waiting period (7–10 days) to prevent misuse.

4. Environmental Data Collection  
The system continuously collects real-time environmental data (weather, pollution, disasters) from external APIs.

5. Risk Monitoring  
The system evaluates disruption probability using historical and real-time data.

6. Trigger Detection  
If predefined parametric trigger conditions are met, the system activates the insurance process.

7. Automatic Payout  
The compensation amount is automatically transferred to the worker’s account via UPI without requiring a manual claim process.

---

Subscription & Pricing Model
-------------------------------

To ensure sustainability and prevent adverse selection, the platform uses a structured subscription model.

Key Mechanisms  

• Monthly Lock-in Period  
Users must subscribe at the beginning of a billing cycle and cannot enter/exit mid-cycle.

• Waiting Period  
Coverage activates after 7–10 days from subscription.

• Weekly Auto-Deduction  
Premiums are deducted weekly within the monthly plan.

• Dynamic Pricing  
Premiums vary based on city, season, and risk level.

Example Insurance Plans  

| Weekly Premium | Coverage Amount |
|---------------|----------------|
| ₹20           | ₹500 payout    |
| ₹40           | ₹1000 payout   |
| ₹60           | ₹1500 payout   |

---

Parametric Insurance Triggers
-------------------------------

Instead of verifying individual claims, the system uses predefined environmental thresholds to automatically trigger payouts.

1. Rainfall Trigger  
Condition: Rainfall > 120 mm/day  

2. Heatwave Trigger  
Condition: Temperature > 45°C  

3. Air Pollution Trigger  
Condition: AQI > 400  

4. Disaster Alert Trigger  
Condition: Official disaster warning issued  

---

AI / ML Integration
----------------------

Artificial Intelligence and data-driven models are used to improve pricing, detect fraud, and predict environmental risks.

1. Premium Calculation  

Premium is calculated using an expected loss model:

Premium ≈ P(trigger) × payout + margin  

This ensures pricing aligns with actual risk levels.

---

2. Fraud Detection  

Method: Anomaly Detection (Isolation Forest)

Detects:  
• Fake or manipulated location data  
• Duplicate user accounts  
• Abnormal activity patterns  

---

3. Risk Prediction  

Method: Time-series analysis (moving average / ARIMA)

Output:  
• Probability of environmental disruption in a given region  

---

Platform Choice
-------------------

The system follows a mobile-first approach.

Reasons:  
• High smartphone usage among gig workers  
• GPS-based validation  
• Real-time notifications  
• Easy access and usability  

Administrator Dashboard  

A web-based dashboard is used for:  
• Monitoring triggers and risks  
• Tracking subscriptions and payouts  
• Analyzing system performance  

---

System Architecture
-----------------------------------

Gig Worker Mobile App  
        │  
Backend API (Node.js / Express)  
        │  
AI Risk Engine (Python)  
        │  
Environmental Data APIs  
        │  
Parametric Insurance Engine  
        │  
Payment Gateway (UPI / Razorpay)  

---

Tech Stack
-------------

Frontend  
• React Native  
• React.js  

Backend  
• Node.js  
• Express.js  

Database  
• PostgreSQL  
• Firebase  

AI / ML  
• Python  
• Scikit-learn  

APIs  
• OpenWeather API  
• AQI APIs  

Payments  
• Razorpay / UPI  

Cloud  
• AWS / Google Cloud  

---

Development Plan
------------------

Phase 1 – Research  
Phase 2 – MVP  
Phase 3 – AI Integration  
Phase 4 – Payments  
Phase 5 – Testing  

---

Future Enhancements
---------------------

• Integration with gig platforms  
• Personalized insurance plans  
• Predictive alerts  
• Nationwide scalability  

---

Impact
---------

• Improved financial security  
• Reduced income volatility  
• Faster compensation  
• Stronger gig economy ecosystem  

---

Disclaimer
--------------

This project is a prototype developed for a hackathon. Real-world implementation would require integration with licensed insurance providers and regulatory compliance.

---

Key Idea  

From uncertain income → to automated income protection  
