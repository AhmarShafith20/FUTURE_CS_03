# FUTURE_CS_03
Future Interns | Cyber Security Internship | Task 3

📌 Objective
Perform a read-only API Security Risk Analysis on a public/demo API, identify common security risks, classify their severity, assess business impact, and document professional remediation recommendations — just like a real AppSec consultant would.

🌐 API Tested
FieldDetailsAPI NameJSONPlaceholderBase URLhttps://jsonplaceholder.typicode.comTypePublic REST API (Demo/Test)AuthenticationNone required (part of findings)

🛠️ Tools Used
ToolPurposePostmanAPI endpoint testing and response inspectionBrowser DevToolsHeader analysis and network inspectionJSONPlaceholderPublic demo REST API — target for analysisOWASP API Security Top 10Industry framework for risk classificationMS Word / PDFProfessional report documentationGitHubRepository hosting and version control

⚠️ Scope & Ethics
✅ Allowed

Testing public / demo APIs only
Read-only GET requests
Safe POST to demo endpoints
Documentation-based analysis
Header, token, and response inspection

❌ Not Allowed

Exploitation or bypass attempts
Flooding / DoS testing
Attacking private or production APIs


All testing was conducted ethically and legally. No systems were harmed or exploited.


🔬 Methodology
1. API Selection         → Chose JSONPlaceholder (safe, public, demo)
2. Documentation Review  → Reviewed all available endpoints
3. Endpoint Testing      → Sent requests via Postman, recorded responses
4. Header Analysis       → Inspected response headers for security gaps
5. Risk Identification   → Mapped findings to OWASP API Security Top 10
6. Risk Classification   → Assigned severity: Low / Medium / High
7. Report Documentation  → Wrote professional security report with remediation

📋 Endpoints Tested
#MethodEndpointPurpose1GET/usersRetrieve all users2GET/users/1Retrieve single user by ID3GET/postsRetrieve all posts4GET/todosRetrieve all to-do items5POST/postsSimulate resource creation

🚨 Findings Summary
#FindingSeverityOWASP Category1Unauthenticated API Access🔴 HighAPI1:2023 – Broken Object Level Auth2Excessive Data Exposure🔴 HighAPI3:2023 – Excessive Data Exposure3Missing Rate Limiting🔴 HighAPI4:2023 – Unrestricted Resource Consumption4Broken Object Level Authorization🟡 MediumAPI1:2023 – BOLA5Missing Security Headers🟡 MediumAPI8:2023 – Security Misconfiguration6Unrestricted Write Access🟡 MediumAPI2:2023 – Broken Authentication

📁 Repository Structure
FUTURE_CS_03/
│
├── screenshots/
│   ├── Test1a.png              ← GET /users — Response Body
│   ├── test1b.png              ← GET /users — Response Headers
│   ├── Test-2.png              ← GET /users/1 — Single User Data
│   ├── Test-3_Get_All_100_Post_.png  ← GET /posts — 100 Records
│   ├── Test-4_Get_todos_.png   ← GET /todos — Todo Data
│   └── Test-5_POST_.png        ← POST /posts — 201 Created
│
├── report/
│   └── API_Security_Risk_Analysis_Report.pdf
│
└── README.md

📄 Deliverables

✅ Professional API Security Risk Analysis Report (PDF)
✅ 6 Postman Screenshots documenting all test results
✅ Public GitHub Repository (FUTURE_CS_03)
✅ README explaining tools, scope, and methodology


🔗 References

OWASP API Security Top 10
API Security Checklist
JSONPlaceholder


👤 Author
[Your Full Name]
Cyber Security Intern — Future Interns
Track Code: CS | Task: 03
📧 contact@futureinterns.com

This assessment was conducted solely for educational purposes as part of the Future Interns Cyber Security Internship Program.
