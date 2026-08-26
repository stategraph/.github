# Security Policy

## Reporting a vulnerability

**Please do not report security vulnerabilities in public GitHub issues.**

Use either private channel:

- **GitHub private vulnerability reporting** — the **Report a vulnerability** button on the Security tab of the affected repository. Preferred: the report, our triage, the fix, and the published advisory all stay in one place.
- **Email** — [security@terrateam.io](mailto:security@terrateam.io). If you need encrypted transport, say so in a first message and we will arrange it.

Please include as much of the following as you have:

- affected version, image tag, or commit
- the impact — what an attacker gains
- steps to reproduce, ideally a minimal proof of concept
- any configuration required to trigger it

## What happens next

| Stage | Target |
| --- | --- |
| We acknowledge your report | 2 business days |
| We give you a severity rating and our reasoning | 5 business days |
| We update you while a fix is in progress | at least every 10 business days |

If we disagree with your severity assessment we will say so and explain why, rather than going quiet. If you think we have it wrong, push back.

## Remediation targets

Once a report is confirmed and validated, we work to these targets, measured from confirmation:

| Severity | Target |
| --- | --- |
| Critical | 7 days |
| High | 30 days |
| Medium | 90 days |
| Low | no fixed target; addressed in the normal release cycle |

## Disclosure

We publish through GitHub Security Advisories on the affected repository:

1. We confirm and triage privately.
2. We develop and test the fix in a private fork.
3. We request a CVE where the issue warrants one.
4. We publish the advisory and release the fix together, crediting you by name or handle unless you would rather stay anonymous.

We aim to publish within 90 days of your report, sooner once a fix ships. If you intend to disclose on your own timeline, tell us — we would rather coordinate than be surprised.

Watch the affected repository's releases to be notified when a security fix ships.

## Scope

In scope:

- the source code in this organisation's repositories
- the container images we publish to `ghcr.io/stategraph`
- the hosted service at stategraph.com

Out of scope, unless you can demonstrate real impact:

- findings that require an already-compromised host or privileged local access
- volumetric denial of service
- missing hardening headers, cookie flags, or TLS configuration with no demonstrated exploit
- social engineering, phishing, or physical attacks
- vulnerabilities in third-party dependencies with no demonstrated exploit path through our code — report those upstream, though we would still like to hear about them

## Safe harbour

If you make a good-faith effort to follow this policy, we will treat your research as authorised and will not pursue or support legal action against you.

Good faith means: report promptly, access only what is necessary to demonstrate the issue, do not access or modify data that is not yours, do not degrade the service for others, and give us reasonable time to fix the issue before disclosing it publicly.

## Staying current

Security fixes ship in the latest release. Running an up-to-date version is the most reliable way to stay protected.
