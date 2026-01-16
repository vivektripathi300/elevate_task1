1. Broken Access Control 🔓

What it is:
Users can act outside their intended permissions.

Why it’s dangerous:

Attackers can access other users’ data

Privilege escalation (user → admin)

Direct data exposure

Example:

Changing /user/123 to /user/124 to see another user’s data

📌 Most common and most damaging vulnerability.

2. Cryptographic Failures 🔐

(formerly Sensitive Data Exposure)

What it is:
Sensitive data is not properly protected.

Why it’s dangerous:

Passwords, credit cards, and PII can be stolen

Enables identity theft and fraud

Example:

Passwords stored in plain text

Data transmitted over HTTP instead of HTTPS

📌 Weak encryption = no protection.

3. Injection 💉

What it is:
Untrusted input is sent to an interpreter (SQL, OS, LDAP).

Why it’s dangerous:

Full database compromise

Remote command execution

Data loss or destruction

Example:

' OR 1=1 --


📌 Injection attacks can completely take over systems.

4. Insecure Design 🧱

What it is:
Security is not considered during application design.

Why it’s dangerous:

No patch can fully fix design flaws

Leads to systemic vulnerabilities

Example:

No rate limiting on login → brute force attacks

📌 Security must start at design stage.


5. Security Misconfiguration ⚙️

What it is:
Improperly configured servers, frameworks, or services.

Why it’s dangerous:

Exposes admin panels

Default credentials abused

Debug mode leaks data

Example:

Public cloud storage

Open admin consoles

📌 Most cloud breaches happen here.
