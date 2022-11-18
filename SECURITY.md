# Security Policy
## Supported versions

Unless designated otherwise, only the latest release is officially supported. Security fixes will result in a new patch release, at minimum. Significant issues may be backported to prior minor and major versions at the maintainer's discretion.

## Reporting a vulnerability in a Fidelity open source project

While minor security issues may be disclosed via a bug report, we do not accept significant security disclosures via public GitHub Issues. We ask that you [disclose significant issues privately through GitHub](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability) so that we have a chance to mitigate them in the codebase before they become more broadly known.

Examples of security issues which may be disclosed via a bug report include:

* Dependencies with publicly-disclosed issues, e.g., "Dependency (x) needs to be updated."
* Dependencies without active security advisories which have reached end-of-life or which have been abandoned, e.g., "Dependency (x) has reached EOL"

Examples of significant security disclosures which should be [disclosed through GitHub's security vulnerability reporting process](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability) and **not via public bug report** include the following:

* Privilege escalation
* Unexpected remote code execution
* Container escape
* Leakage of secure data
* Anything which, given the circumstances, is of equivalent severity to the above

All disclosures must include detailed instructions on reproducing the issue. If possible, please provide a proof of concept or Dockerfile demonstrating the issue so that we can reproduce your environment and respond more quickly.

Fidelity will assess the severity of the issue and provide a disposition and timeline directly back to the reporter. The maintainer will coordinate a new release and assess the need for backports.

Once a release has been scheduled, Fidelity will work with the reporter on communicating the discovery and resolution of the vulnerability.

## Security concerns with Fidelity products and services

Our open source maintainers are unable to respond or escalate issues beyond the scope of Fidelity's open source projects. If you have a security concern with your account or a non-open source Fidelity product or service, please [visit the Fidelity security site](https://www.fidelity.com/security/report-an-issue) for more information on the appropriate reporting path.

## Getting help

If you have other questions about the contents of this policy, please open an issue. To reach the Fidelity OSPO directly, please email [opensource@fmr.com](mailto:opensource@fmr.com).