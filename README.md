
# Staff Software Engineer Take-Home Challenge

<img src="https://github.com/Dealflow-ApS/staff-backend-engineer-challenge/blob/492051754a921411dce3f273ec3f08edf9729979/logo.gif" alt="logo" width="70"/>

Congratulations on making it this far :zap:. If you've received this, it means that you are now among the top applicants who applied for this position 😎. 
<br /><br />All the best with this challenge; see you at the finish line :godmode:. <br /><br />
<img src="https://github.com/Dealflow-ApS/staff-backend-engineer-challenge/blob/492051754a921411dce3f273ec3f08edf9729979/global.png" alt="logo" width="60"/>
<img src="https://github.com/Dealflow-ApS/staff-backend-engineer-challenge/blob/492051754a921411dce3f273ec3f08edf9729979/limitless.png" alt="logo" width="70"/>

## Overview

Your challenge is to build a **full-stack payment application** that mimics Stripe's Payment Links functionality. This application should allow users to create payment links that they can share with their customers to accept payments. You are free to use any payment gateway (including Stripe) behind the scenes to process payments.

This challenge is designed to evaluate your ability to build a production-ready system while considering security, analytics, scalability, and how you leverage modern tools, including AI. You'll be judged on technical execution, decision-making, code quality, and ability to communicate and document your thought process.

---

## Requirements

### 1. **Payment Links Application**
- Users should be able to create payment links by entering details like:
  - **Amount**
  - **Currency**
  - **Description**
  - **Expiration date**
- Once a payment link is created, a URL should be generated and shared with the customer.
- The customer should be able to click the link and make a payment using the provided gateway (Stripe, PayPal, or any other).

### 2. **Payment Gateway Integration**
- You are free to use **any payment gateway**, including Stripe, PayPal, or others, to handle actual payment processing behind the scenes.
- The payment processing must be functional in a real or sandbox environment.
- Handle different payment statuses: success, pending, failure.

### 3. **Security**
- Implement industry-standard **security best practices**, including but not limited to:
  - **Authentication & Authorization** for creating and accessing payment links (use JWT or OAuth).
  - **Data Encryption** for sensitive information like payment details.
  - **Input Validation** to prevent SQL Injection, XSS, etc.
  - **Rate Limiting** to protect against denial-of-service attacks.
- Protect against **payment fraud** by implementing secure payment flows.

### 4. **Analytics**
- Build an **analytics dashboard** where the user can track:
  - Total payments received
  - Success, failure, and pending statuses of payments
  - Filter by date, amount, or currency
  - Breakdown by payment method (e.g., credit card, bank transfer)
- Optionally, integrate third-party analytics platforms like **Google Analytics** to track user interactions with the payment links.

### 5. **AI Integration**
- You are **encouraged to use AI tools** to improve your development process. Specifically:
  - **Document** the AI tools used during the project:
    - The **AI prompts** you used (provide a list).
    - Any **code generated** by AI.
    - Insights or optimizations that AI helped uncover.

---

## Bonus Points

- **Scalability**: Discuss or demonstrate how your solution can scale. Consider database design, API load, and payment processing limits.
- **Testing**:
  - Implement **unit tests** for key functionality.
  - Set up **automated testing** for API endpoints and critical business logic.
- **CI/CD Pipeline**: Set up a basic CI/CD pipeline to automate testing and deployment.
- **Logging and Monitoring**:
  - Implement logging to capture important events (e.g., payment status changes, failed attempts, etc.).

---

## Technical Specifications

- **Front-end**: You may use any of the following front-end technology - React / Next.js
- **Back-end**: Backend technology: Python
- **Database**: Store user and payment information in a database of your choice (e.g., MySQL, PostgreSQL, MongoDB).
- **API**: Expose a RESTful API to interact with the payment link system.
- **Hosting**: You can deploy your app to a cloud platform like AWS, GCP, Heroku, or any hosting provider you prefer. Provide instructions on how to run the app locally.

---

## Deliverables

1. **Code Repository**:
   - Submit a **GitHub** repository (or another version control platform).
   - The repository should include clear **commit messages** that reflect your workflow.
   - A **README.md** with setup instructions, explaining how to run the project locally and any other relevant information.

2. **Documentation**:
   - Provide a document (Markdown or PDF) explaining your design choices, the architecture of your system, and why you made certain technical decisions.
   - Include a **section about AI tools used**, specifying:
     - Which tools you used and why.
     - Specific **AI prompts** you used.
     - **What AI helped you achieve** and any limitations you encountered.
   
3. **Demo**:
   - Optional but highly recommended: Provide a **deployed demo link** where we can interact with the application live.
   - Alternatively, record a short video explaining and demonstrating key features.

4. **Post-Submission Interview**:
   - After reviewing your submission, we’ll have a short interview to discuss your approach, challenges, and any questions about your implementation.

---

## Evaluation Criteria

- **Problem-Solving**: How well did you approach the problem? Did you break it down into manageable parts and solve each aspect effectively?
- **Code Quality**: Is your code clean, maintainable, and well-organized? Did you follow best practices and conventions?
- **Security**: How well did you implement security measures, including authentication, data protection, and secure payment handling?
- **Scalability**: Can your application scale with increased traffic or data?
- **Documentation**: Is your project well-documented? Can other developers easily understand and contribute to the project?
- **AI Usage**: Did you effectively use AI tools to enhance your workflow? Were the prompts clear, and did they help solve meaningful parts of the problem?
- **Completeness**: Did you fulfill all the required features? Bonus points for any additional functionality or creativity you add.
- **Communication**: How clearly can you explain your approach, both in documentation and the post-submission interview?

---

## Time Limit

You will have **5 days** to complete this take-home challenge. If you need an extension or have any questions, feel free to reach out.

---

Good luck, and we look forward to seeing your solution!
