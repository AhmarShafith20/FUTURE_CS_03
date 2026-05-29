# FUTURE_CS_03

Cyber Security Internship Project  
Future Interns | Track: CS | Task: 03

---

## 📌 Project Overview

This project performs a **read-only security analysis** of a public REST API (JSONPlaceholder).  
The goal is to identify common API security vulnerabilities, classify their severity, map them to OWASP API Security Top 10, and provide remediation recommendations.

This is an **educational security assessment** conducted in a safe and ethical environment.

---

## 🌐 API Information

- **API Name:** JSONPlaceholder  
- **Base URL:** https://jsonplaceholder.typicode.com  
- **Type:** Public REST API (Demo/Test API)  
- **Authentication:** Not required  

---

## 🛠️ Tools Used

- Postman → API testing and request execution  
- Browser DevTools → Header inspection  
- JSONPlaceholder API → Target system  
- OWASP API Security Top 10 → Risk classification framework  
- GitHub → Version control and repository hosting  

---

## 📋 Endpoints Tested

| Method | Endpoint | Purpose |
|--------|----------|--------|
| GET | /users | Retrieve all users |
| GET | /users/1 | Retrieve single user |
| GET | /posts | Retrieve all posts |
| GET | /todos | Retrieve all to-do items |
| POST | /posts | Simulate resource creation |

---

## 🔬 Methodology

1. Selected a safe public API (JSONPlaceholder)  
2. Reviewed API documentation  
3. Performed GET and POST requests using Postman  
4. Inspected responses and headers  
5. Identified security risks  
6. Mapped findings to OWASP API Security Top 10  
7. Documented results in a structured report  

---

## 🚨 Key Security Findings

- Unauthenticated API Access  
- Excessive Data Exposure  
- Missing Rate Limiting  
- Broken Object Level Authorization (BOLA)  
- Missing Security Headers  
- Unrestricted Write Access  

---

## 📊 Risk Classification Summary

- 🔴 High Severity Issues:
  - Broken Object Level Authorization
  - Excessive Data Exposure
  - Missing Rate Limiting

- 🟡 Medium Severity Issues:
  - Security Misconfiguration
  - Broken Authentication (Unrestricted Write Access)

---

## 📄 Deliverables

- ✅ API Security Risk Analysis Report (PDF)
- ✅ Postman request screenshots (6 images)
- ✅ GitHub repository with structured files
- ✅ README documentation

---

## 🔗 References

- OWASP API Security Top 10  
- https://jsonplaceholder.typicode.com  
- API Security Best Practices (OWASP Guide)

---

## 👤 Author

**Ahmar Shafith Baijur Ahamed**  
Cyber Security Intern — Future Interns  
Track: CS | Task: 03  

---

## ⚠️ Disclaimer

This project was conducted strictly for **educational purposes only** using a public demo API.  
No real systems were attacked, exploited, or harmed.
