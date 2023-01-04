### 📕 Security Policy
```
⚠️ This is ONLY for Security and Vulnerability related bugs ⚠️
```
Want to report a Bug or Issue that isnt security related? 
📝 [Click here to post an Issue](https://github.com/dlxmedia/commnunity/issue/new)

<br>

### ⚡️ Posting a Vulnerability 

Report security bugs via email at: security@eplay.com

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
