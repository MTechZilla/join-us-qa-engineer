# Senior QA Engineer - Take-Home Assignment  
Thank you for your interest in joining MTechZilla. This assignment gives you a chance to demonstrate your senior-level QA skills: functional testing across UI/API/DB, edge-case thinking, test strategy, automation awareness, and quality mindset.

**Time expectation:** ~90 minutes  
**Submission format:** A Markdown document (or PDF) with your responses + (optional) example automation snippet.  
**Send to:** jobs@mtechzilla.com with subject line “Senior QA Assignment – [Your Name]”.

---

## Assignment Scenario  
You’ve been asked to join a project at MTechZilla where we build a web and mobile-responsive application. The feature we want you to test is a simplified “User Registration & Profile” workflow.  

**Feature description:**  
- User visits the web or mobile app and selects “Register”.  
- They provide name, email, password.  
- After registration, they log in.  
- They navigate to “My Profile” and edit their profile (name, avatar, biography).  
- The system persists changes in a PostgreSQL (PSQL) database via API.  
- The system must support API endpoints, web UI, and mobile UI.  
- We want to include automated checks, regression coverage, integration with profile module, and database validation.

---

## Your Tasks  
Please provide your responses to each of the sections below.

### 1. Test Strategy & Plan  
- Outline your high-level test strategy for this feature.  
- Indicate what types of testing you’ll perform (e.g., functional, UI, API, DB, smoke, regression, integration, security).  
- Describe how you’d prioritise and allocate testing efforts for web + mobile.  
- Explain how you will ensure quality across the lifecycle (from dev hand-off to production).  

### 2. Test Case Design (Edge-case thinking)  
- Provide **10-15** test cases (happy path + edge/failure cases) covering web + mobile + API + database. For each case provide:  
  - Test case ID  
  - Description  
  - Preconditions  
  - Steps  
  - Expected result  
  - Which layer(s) it covers (UI, API, DB)  
- Highlight any subtle/complex cases where the user story might not cover everything (show your ability to think beyond the spec).

### 3. Automation Approach  
- Describe which automation framework(s) you would choose (we use front-end tech; you can assume JavaScript/TypeScript + Cypress).  
- Outline one or two sample test scripts (either pseudocode or actual) that cover critical scenarios (web UI and/or API).  
- Explain how you’d integrate these automated tests into CI/CD, and how you’d maintain them (flakiness, data setup, environment management).  

### 4. Database & API Testing  
- Describe how you would validate database state after UI/API operations (PSQL).  
- Describe how you would test the API endpoints: what tools (e.g., Postman), test data, negative tests, response validation, error codes.  
- Mention how you’d test integration between UI, API, and database (end-to-end).  

### 5. Security, Smoke & Regression Testing  
- What smoke tests would you include to ensure the feature is “release ready”?  
- What regression tests would you identify (what existing areas might this new feature impact)?  
- What basic security test cases would you add (e.g., authentication bypass, XSS, SQL injection, invalid data, avatar upload validation, API rate limiting)?  

### 6. Quality Metrics & Reporting  
- Suggest metrics you’d track to measure QA effectiveness for this feature (e.g., test coverage, defect density, automation pass rate, time to fix, escaped defects).  
- How would you report status to stakeholders (PM, Dev Lead, Product Owner)?  

### 7. Optional Bonus – Example Automation Snippet  
- If you have time and want to showcase your automation coding skill, include **one small snippet** (in JS/TS) using Cypress (or your preferred tool) that tests a critical path (e.g., registration + login).  
- Keep it brief (~30–45 lines).  

---

## Submission Instructions  
1. Create a Markdown file named `SeniorQA_Assignment_[YourName].md` (or a PDF).  
2. If you include code snippet(s), embed them in the Markdown or provide a GitHub Gist link.  
3. Keep your response within **~2–3 pages** of content (plus optional snippet).  
4. Submit by emailing to **jobs@mtechzilla.com** with the subject line:  
   `Senior QA Assignment – [Your Name]`  
5. We will review your submission

---

## What we’re looking for  
We’re hiring a **Senior QA Engineer** who:  
- Has strong functional testing skills across UI, API, DB.  
- Can derive test cases beyond the user story and handle edge/failure scenarios.  
- Understands testing across mobile & web, API endpoints, databases (PSQL).  
- Has experience in regression, smoke, integration and basic security testing.  
- Has hands-on automation experience (preferably Cypress + JavaScript/TypeScript) and knows how to plug it into CI/CD pipelines.  
- Communicates clearly, writes clean test plans, and thinks strategically about quality.

---

Thank you for your time. We appreciate your effort and look forward to your submission!  
— The MTechZilla Talent Team  
