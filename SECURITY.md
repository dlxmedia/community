### 📕 Security Policy
```
⚠️ This is ONLY for Security and Vulnerability related bugs ⚠️
```
Want to report a Bug or Issue that isnt security related? 
📝 [Click here to post an Issue](https://github.com/dlxmedia/commnunity/issue/new)

<br>

### ⚡️ Posting a Vulnerability 

### 📝 [Report a Vulnerability ONLY via this FORM](https://github.com/dlxmedia/community/security/advisories/new)
##### or [Use this Google FORM](https://docs.google.com/forms/d/e/1FAIpQLSda_QNDQwFJTFtzGVkYhAaXc5m4Sqv6ivSeHYBhNigtA3jCqg/viewform?usp=pp_url&entry.1820994568=WWW.EPLAY.COM&entry.868338315=3&entry.149164797=Summary:%0A%5Badd+summary+of+the+vulnerability%5D%0A%0ASteps+To+Reproduce:%0A%5Badd+details+for+how+we+can+reproduce+the+issue%5D%0A%0A%5Badd+step%5D%0A%5Badd+step%5D%0A%5Badd+step%5D%0ASupporting+Material/References:%0A%5Blist+any+additional+material+(e.g.+screenshots,+logs,+etc.)%5D%0A%0A%5Battachment+/+reference%5D)

Normally your report will be acknowledged within 5 days, and you'll receive
a more detailed response to your report within 10 days indicating the
next steps in handling your submission. These timelines may extend when
our triage volunteers are away on holiday, particularly at the end of the
year.

After the initial reply to your report, the security team will endeavor to keep
you informed of the progress being made towards a fix and full announcement,
and may ask for additional information or guidance surrounding the reported
issue.

### 💰 ePlay Bug Bounty Program

Eplay engages in an official bug bounty program for security researchers and responsible public disclosures.
- Rewards are based on severity per CVSS ([the Common Vulnerability Scoring Standard](https://www.first.org/cvss/))
- All bounty amounts will be at the discretion of the eplay Bug Bounty team.
- All bounty amounts will be paid via `Paypal`
- Reports submitted using methods that violate policy rules will not be eligible for a reward.
- To be eligible for a reward, the report must be for bounty eligible assets as defined in the scope section of our policy (see below)
- Multiple reports describing the same vulnerability against multiple assets or endpoints where the root cause is the same will be treated as one report. - Do not submit duplicate reports for the same issue across multiple sites as the duplicates will be closed, and the issue will be treated as one report.
> While we aim for consistency, previous reports and prior bounty amounts will not set a precedent for future report eligibility or severity.
> Understand that there could be submissions for which we accept the risk, have other compensating controls, or will not address in the manner expected.
> When this happens, we will act as transparently as we can to provide you with the necessary context as how the decision was made.

### 👍 Scope
- `www.eplay.com` (Main ePlay Website)
- `my.eplay.com` (Streamer Admin & Stats)
- `api.eplay.com` (Main API)

### 🚫 Out of Scope
> ePlay reserves the right to add to and subtract from the Exclusions list depending on the evaluated severity of reported vulnerabilities and risk acceptance.

- Clickjacking on pages with no sensitive actions
- Cross-Site Request Forgery (CSRF) (This is something we're actively working on adding protection for)
- Attacks requiring MITM or physical access to a user's device
- Previously known vulnerable libraries without a working Proof of Concept
- Comma Separated Values (CSV) injection without demonstrating a vulnerability
- Missing best practices in SSL/TLS configuration
- Any activity that could lead to the disruption of our service (DoS).
- Content spoofing and text injection issues without showing an attack vector/without being able to modify HTML/CSS
- Any activity that could lead to the disruption of our service (DoS), including but not limited to, inundating support services with invalid requests
- Bruteforce oracle attacks against unauthenticated endpoints
- Missing best practices in Content Security Policy
- Missing HttpOnly or Secure flags on cookies
- Missing email best practices (Invalid, incomplete or missing SPF/DKIM/DMARC records, etc.)
- Vulnerabilities only affecting users of outdated or unpatched browsers [Less than 2 stable versions behind the latest released stable version]
- Software version disclosure / Banner identification issues / Descriptive error messages or headers (e.g., stack traces, application or server errors)
Tabnabbing
- Issues that require unlikely user interaction by the victim
- Ability to send a message with a tip (regular chat or private chat)
- Social engineering

### 📘 Program Rules

#### ✅ DO:
> - Read and abide by the program policy.
> - Perform testing using only accounts that are your own personal/test accounts or an account that you have explicit permission from the account holder to utilize.
> - Exercise caution when testing to avoid negative impact to customers and the services they depend on.
> - STOP testing if you are unsure about the impact it may have on our systems. If you think you may cause, or have caused, damage with testing a vulnerability, report your initial finding(s) and request authorization to continue testing.

#### ❌ DO NOT:
> - Do not Brute force credentials or guess credentials to gain access to systems.
> - Do not participate in denial of service attacks.
> - Do not upload shells or create a backdoor of any kind.
> - Do not engage in any form of social engineering of eplay employees, customers, or vendors.
> - Do not engage or target any eplay employee, customer, or vendor during your testing.
> - Do not attempt to extract, download, or otherwise exfiltrate data that you believe may have PII or other sensitive data other than your own.
> - Do not change passwords of any account that is not yours or that you do not have explicit permission to change. If ever prompted to change a password of an account you did not register yourself or an account that was not provided to you, stop and report the finding immediately.
> - Do not do anything that would be considered a privacy violation, cause destruction of data, or interrupt or degrade our service. Do not interact with accounts you do not own or without the explicit permission of the account holder.

### 💰 Rewards

The rewards is based on severity of the vulnerability found and will be determined by our team.
> The minimum bounty is `$100` and max is `$500`

### ⛨ Safe harbor

**ePlay** supports safe harbor for security researchers who:

*   Make a good faith effort to avoid privacy violations, destruction of data,
    and interruption or degradation of our services
*   Only interact with accounts you own or with explicit permission of the
    account holder.
    If you do encounter Personally Identifiable Information (PII) contact us
    immediately, do not proceed with access, and immediately purge any local
    information
*   Provide us with a reasonable amount of time to resolve vulnerabilities prior
    to any disclosure to the public or a third-party
*   We will consider activities conducted consistent with this policy to
    constitute “authorised” conduct and will not pursue civil action or initiate
    a complaint to law enforcement.
    We will help to the extent we can if legal action is initiated by a third
    party against you

Please submit a report to us before engaging in conduct that may be inconsistent
with or unaddressed by this policy.

---
For any question about this security policy, please contact <security@eplay.com>
