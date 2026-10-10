# NeuronFort

> A community-maintained guide to open-source cybersecurity tools, learning resources, and responsible security practice.

NeuronFort is a friendly starting point for people learning defensive security. It collects trusted, open-source tools by job, explains where they fit, and points newcomers toward an ethical learning path.

## Choose your next step

| If you want to… | Start with… |
| --- | --- |
| Learn the fundamentals | The [four-week defensive learning path](docs/learning-path.md). |
| Add a useful resource | The [tool evaluation checklist](docs/tool-evaluation.md). |
| Suggest a link or correction | An issue using one of our templates. |
| Contribute a larger improvement | [CONTRIBUTING.md](CONTRIBUTING.md). |

## Start here

Security work should always be authorized. Use these tools only on systems you own or where you have explicit, written permission to test. The goal is to understand, protect, and improve systems—not to access or disrupt someone else's.

If you are new to cybersecurity, build the fundamentals first:

1. Learn networking: IP addresses, DNS, HTTP(S), routing, and ports.
2. Learn a little Linux and the command line.
3. Practice safely in a lab, CTF, or deliberately vulnerable application.
4. Read a report, document your findings, and learn how remediation works.

## Tool map

| Area | Tools | What they help with |
| --- | --- | --- |
| Network visibility | [Wireshark](https://www.wireshark.org/), [Zeek](https://zeek.org/) | Inspect traffic and identify unusual behavior. |
| Vulnerability management | [Greenbone Community Edition](https://greenbone.github.io/docs/latest/), [Nuclei](https://github.com/projectdiscovery/nuclei) | Find known weaknesses in authorized environments. |
| Web application testing | [OWASP ZAP](https://www.zaproxy.org/), [Burp Suite Community Edition](https://portswigger.net/burp/communitydownload) | Understand and test web application security. |
| Endpoint and forensics | [Velociraptor](https://docs.velociraptor.app/), [Autopsy](https://www.autopsy.com/) | Investigate endpoints and analyze evidence. |
| Detection engineering | [Sigma](https://sigmahq.io/), [YARA](https://virustotal.github.io/yara/) | Write portable detection rules and identify malware patterns. |
| Password defense | [KeePassXC](https://keepassxc.org/), [Have I Been Pwned](https://haveibeenpwned.com/) | Improve credential hygiene and assess exposure. |
| Security monitoring | [Wazuh](https://wazuh.com/), [Security Onion](https://securityonionsolutions.com/) | Centralize telemetry, alerts, and investigations. |

Tool availability, licensing, and capabilities change over time. Always check the project's official documentation before using a tool in production.

## Learn by doing—safely

These platforms provide legal, intentionally designed practice environments:

- [OWASP WebGoat](https://owasp.org/www-project-webgoat/) — hands-on web-security lessons.
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — guided web-app labs.
- [picoCTF](https://picoctf.org/) — beginner-friendly capture-the-flag challenges.
- [OverTheWire](https://overthewire.org/wargames/) — command-line and security fundamentals.
- [TryHackMe](https://tryhackme.com/) — guided learning paths and labs.

## A practical defensive workflow

1. **Inventory** what you own: services, software, identities, and data.
2. **Harden** systems with updates, least privilege, MFA, backups, and secure defaults.
3. **Observe** logs and network activity so abnormal behavior has context.
4. **Test** only with authorization and a defined scope.
5. **Fix and verify** findings, then record what changed.

## Recommended habits

- Keep systems and dependencies updated.
- Use a password manager and enable multi-factor authentication.
- Back up important data and test that recovery works.
- Treat unexpected files, links, and requests with care.
- Share security findings privately and give maintainers time to fix them.

## Contribute

NeuronFort grows through practical, well-sourced contributions. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request. For expected community behavior, see [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

To report a vulnerability in this repository or its project infrastructure, follow [SECURITY.md](SECURITY.md). Do not publish sensitive details in a public issue.

## Scope

NeuronFort prioritizes defensive security, responsible disclosure, and educational use. It does not host exploit payloads, credential theft guidance, evasion techniques, or instructions for unauthorized access.

## License

Unless noted otherwise, this repository's written content is available under the [MIT License](LICENSE).
