# Guidewire-DEVTrails-2026

AI-Powered Insurance for Gig Delivery Workers

**Problem**

In India, delivery partners from platforms like Zomato, Swiggy, and Zepto depend on daily earnings to support their livelihood. However, external factors such as heavy rain, extreme heat, pollution, or sudden curfews can prevent them from working.

When these disruptions happen, they lose income for that day — and currently, there is no system to support them during such situations.

**Our Idea**

We are building a simple AI-powered insurance system that helps delivery workers protect their income.

Instead of traditional insurance, this system works automatically:

- The user pays a small weekly amount (like ₹20)
- The system keeps monitoring external conditions like weather
- If a disruption happens, the system automatically gives compensation

This removes the need for manual claims and ensures quick support.

**Target Persona**

We focused on food delivery partners working with platforms such as Zomato and Swiggy.

A typical user of our system is a delivery partner who:

- Works daily and earns based on completed deliveries
- Earns around ₹500–₹800 per day depending on working hours and demand
- Relies heavily on consistent daily income for basic needs
- Works outdoors and is directly affected by environmental conditions

These workers face several challenges:

- Heavy rain or flooding reduces order demand and makes delivery unsafe
- Extreme heat conditions reduce working hours due to health risks
- High pollution levels discourage outdoor work
- Curfews or local restrictions can completely stop operations

Since their income is directly linked to the number of deliveries they complete, even missing one or two days of work can significantly impact their weekly earnings. Most workers do not have financial backup or insurance support, which makes them highly vulnerable to such disruptions.

This makes them an ideal group for a simple, low-cost income protection system.

How the system works

1. The user logs into the app
2. Selects a weekly plan
3. The system tracks weather and environmental conditions
4. If a disruption like heavy rain is detected:
   - The system automatically triggers a claim
   - The user receives a payout instantly

The whole process is designed to be simple and automatic.

**Weekly Pricing**

We designed a simple weekly model because gig workers usually think in terms of weekly earnings.

- Basic Plan: ₹20/week  
- Premium Plan: ₹40/week  

Higher plans provide better coverage in case of income loss.

**What triggers a payout?**

The system uses predefined conditions like:

- Heavy rain  
- Extreme heat  
- High pollution  
- Local restrictions (curfews, closures)  

If any of these cross a certain level, the system assumes the worker cannot work and triggers a payout.

**Where AI comes in**

We plan to use AI in the following ways:

- Risk prediction: Identify areas where disruptions are likely
- Dynamic pricing: Adjust weekly premium based on risk
- Fraud detection: Detect unusual patterns like fake claims or incorrect locations

For this phase, these are part of our planned system.

**Key Features**

- Automatic claim triggering (no manual request needed)
- Instant payout simulation
- Simple and clean user interface
- Notification system for events and payouts
- Dashboard showing plan and earnings protection

**Tech Stack**

For the prototype:
- HTML, CSS, JavaScript

Planned for future:
- Backend: Node.js
- AI/ML: Python
- APIs: Weather API, Payment Gateway (mock)

**Why Web App?**

We chose a web application because:
- Easy to build and test quickly
- Accessible on any device
- Suitable for prototype demonstration

**Prototype**

We created a simple UI prototype that shows:

- Login screen  
- Dashboard  
- Plan selection  
- Disruption simulation (rain event)  
- Automatic payout popup  
- Notification system  

**Future Improvements**

- Real-time weather API integration  
- Advanced AI models for prediction  
- Fraud detection using GPS data  
- Mobile app version  
- Integration with delivery platforms

 **Adversarial Defense & Anti-Spoofing Strategy**

To handle large-scale fraud scenarios such as fake GPS spoofing and coordinated claim attacks, our system includes multiple layers of defense.

First, we do not rely only on GPS data. Instead, we validate user location using multiple signals such as device location consistency, network data, and historical movement patterns.

Second, we analyze user behavior patterns. If multiple users suddenly trigger claims from the same location or at the same time, the system flags this as suspicious activity.

Third, we compare real-time external data with user claims. For example, if a user reports heavy rain, the system verifies it using weather API data for that specific location.

Fourth, we track historical activity. If a user frequently claims payouts without consistent work patterns, the system marks them as high-risk.

Fifth, we implement anomaly detection using AI. This helps identify unusual claim spikes, repeated patterns, and coordinated fraud attempts.

To ensure fairness, flagged users are not immediately blocked. Instead, they are marked for further verification, so genuine users are not affected.

This multi-layered approach helps the system distinguish between genuine users and fraudulent actors while maintaining trust and reliability.

**Demo Video**
   **Link:**https://youtu.be/IBAt5hjjJ_A

**GitHub Repository**
 **Link:** https://github.com/Bhargavi-Bandla07/Guidewire-DEVTrails-2026.git

**Final Note**

This project focuses on solving a real problem faced by gig workers. Our goal is to provide a simple, reliable system that ensures they don’t lose income due to factors beyond their control.
