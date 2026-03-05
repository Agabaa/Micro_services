# Micro_services
## Name
Itungo Agaba

## Course
BSCS 3:2

## Reg number
M23B23/018


## 1. How Netflix Uses Microservices 

1. **Independent Services**  
   Netflix divides its system into many small independent services instead of one large application. Each service performs a specific task and communicates with others through APIs.

2. **User Management Service**  
   A dedicated service manages user accounts, profiles, authentication, and login information. This allows Netflix to update account features without affecting other parts of the platform.

3. **Recommendation System**  
   Netflix uses a microservice that analyzes user viewing behavior and suggests movies or shows a user might enjoy. This service runs machine learning algorithms to personalize content.

4. **Video Streaming Service**  
   When a user presses play, several services work together to deliver the video. One service identifies the content, another determines the correct video quality based on internet speed, and another connects the user to the nearest server.

5. **Billing and Subscription Service**  
   Payments and subscriptions are handled by a separate service. This ensures secure and independent processing of customer payments.

6. **Scalability and Reliability**  
   Microservices allow Netflix to scale specific services when needed. For example, during the release of a popular show, Netflix can increase streaming resources without affecting other services like billing.

---

## 2. Two Other Companies That Use Microservices 

1. **Amazon**  
   Amazon uses microservices to run its e-commerce platform. Different services manage the product catalog, customer orders, payments, inventory management, and delivery tracking. This architecture allows Amazon to update and scale individual parts of the system easily.

2. **Uber**  
   Uber uses microservices to manage different parts of its ride-hailing platform. Separate services handle ride requests, driver matching, GPS location tracking, fare calculation, payment processing, and notifications. This allows the system to operate efficiently in many cities worldwide.

---

## 3. Companies That Moved Back to Monolithic Systems 

1. **Amazon Prime Video**  
   Amazon Prime Video changed part of its monitoring system from microservices to a monolithic architecture. The microservices approach created high infrastructure costs, so the company simplified the system to reduce expenses.

2. **Segment**  
   Segment originally adopted microservices but later combined several services into a more centralized system. They found that managing too many small services increased operational complexity and made debugging more difficult.
