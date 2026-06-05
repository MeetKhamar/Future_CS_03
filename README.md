# FUTURE_CS_03
API Security Risk Report
API Security Risk Analysis
Overview

For this project, I performed a read-only API security assessment on a public demo API.
The objective was to identify potential security risks in API design and explain their business impact in a clear, practical manner.

This assessment was conducted ethically and focused strictly on observation and analysis rather than exploitation.

Scope

The assessment covered:

Public API endpoints
Authentication mechanisms
Response data exposure
Security headers
Rate limiting controls

No exploitation, bypass attempts, or service disruption techniques were used.

Tools Used
Postman (API request testing)
Browser Developer Tools (header and response inspection)
API documentation review


The API was analyzed using a structured security review approach:

Reviewing API documentation
Testing publicly accessible endpoints
Inspecting request and response headers
Evaluating authentication and access controls
Assessing data exposure risks
Identifying protective mechanisms such as rate limiting
Key Findings

The assessment identified several security considerations:

Some endpoints allow public data access without authentication
Predictable resource identifiers may enable automated data enumeration
API responses expose more information than necessary
Certain security headers are not fully implemented
Rate limiting is present but uses a high request threshold

These findings highlight opportunities to strengthen API security and reduce exposure to misuse.
