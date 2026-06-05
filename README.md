# FUTURE_CS_03
# API Security Risk Analysis 

## 📌 Overview
This repository contains the deliverables for **Cyber Security Task 3: API Security Risk Analysis**.  
The objective was to perform a read‑only security audit of demo/public APIs, identify common risks, and document findings in a professional report.

---

## 🎯 Objectives
- Analyze public/test APIs (e.g., ReqRes, JSONPlaceholder).
- Identify API security risks such as:
  - Unauthenticated endpoints
  - Excessive data exposure
  - Weak/missing authentication tokens
  - Authorization flaws
  - Missing rate limiting
  - Input validation gaps
- Classify risks by severity (Low / Medium / High).
- Explain business impact in simple language.
- Suggest clear remediation steps.

---

## 🛠️ Tools Used
- **Postman** – API request testing  
- **Insomnia** – Alternative API client  
- **Browser DevTools** – Inspect headers/responses  
- **Google Docs / MS Word** – Documentation  

---

## 📂 Repository Contents
- **Report.pdf / Report.docx** – Full API Security Risk Analysis Report  
- **Screenshots/** – Evidence from Postman (requests, error responses)  
- **README.md** – Methodology, scope, and summary  

---

## 🔍 Methodology
1. Selected demo/public APIs (ReqRes, JSONPlaceholder).  
2. Reviewed API documentation.  
3. Tested endpoints using Postman.  
4. Inspected headers, tokens, and responses.  
5. Identified risks and classified severity.  
6. Suggested remediation steps.  
7. Documented findings with screenshots.  

---

## ⚠️ Key Findings
- **401 Unauthorized** errors due to missing API keys (authentication risk).  
- Open endpoints exposing user data without proper authorization.  
- Lack of rate limiting on repeated requests.  
- Potential input validation gaps.  

---

## ✅ Recommendations
- Enforce API key or OAuth 2.0 authentication.  
- Implement role‑based access control.  
- Add rate limiting and throttling.  
- Validate and sanitize all inputs.  
- Minimize data exposure in responses.  

---

