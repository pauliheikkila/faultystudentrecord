*This vulnerability report template is offered to you by the GitHub Security Lab. Use it as an inspiration for your own reports. Reporting a vulnerability using this template does not imply that this report has been acknowledged by the GitHub Security Lab. Remove this first section and any mention of the GitHub Security Lab when you use this template.* 

# Vulnerability Report

I identified potential security vulnerabilities in [FaultyStudentRecord].

I am committed to working with you to help resolve these issues. In this report you will find everything you need to effectively coordinate a resolution of these issues.

If at any point you have concerns or questions about this process, please do not hesitate to reach out to me at [kikkelis.kokkelis@kuukkeli.com].

If you are _NOT_ the correct point of contact for this report, please let me know!

## Summary

*Short summary of the problem. Make the impact and severity as clear as possible. For example: An unsafe deserialization vulnerability allows any unauthenticated user to execute arbitrary code on the server.*

## Product

[FaultyStudentRecord]

## Tested Version

[1.0]

## Details

All of the inputs fields in the main.py have not been hardened, making them vulnerable to SQL-injection attacks.

## PoC

Use any input field to inject SQL-code into the input

## Impact

[possible to edit or destroy the database in its entirity.]

## Remediation

*Harden all user inputs so they only submit string, without it being interpreted as SQL-code*

## GitHub Security Advisories

If possible, please could you create a private [GitHub Security Advisory](https://help.github.com/en/github/managing-security-vulnerabilities/creating-a-security-advisory) for these findings? This allows you to invite me to collaborate and further discuss these findings in private before they are [published](https://help.github.com/en/github/managing-security-vulnerabilities/publishing-a-security-advisory). I will be happy to collaborate with you, and review your fix to make sure that all corner cases are covered. 
When you use a GitHub Security Advisory, you can request a CVE identification number from GitHub. GitHub usually reviews the request within 72 hours, and the CVE details will be published after you make your security advisory public. Publishing a GitHub Security Advisory and a CVE will help notify the downstream consumers of your project, so they can update to the fixed version.

## Credit

*List all researchers who contributed to this disclosure.*
Matti Nykänen
Martina Aitolehti
Sauli Niinistö
Käärijä
Stefan Therman
Mummotunnelin mummo #3
*If you found the vulnerability with a specific tool, you can also credit this tool.*
Vasara
Leka
Ratakisko

## Contact

[contact]

## Disclosure Policy

*Describe or link to your disclosure policy. It's important to have a disclosure policy where the public disclosure deadline, and the potential exceptions to it, are clear. You are free to use the [GitHub Security Lab disclosure policy](https://securitylab.github.com/advisories/#policy), which is copied below for your convenience, if it resonates with you.*

The *your_team_name_here* research team is dedicated to working closely with the open source community and with projects that are affected by a vulnerability, in order to protect users and ensure a coordinated disclosure. When we identify a vulnerability in a project, we will report it by contacting the publicly-listed security contact for the project if one exists; otherwise we will attempt to contact the project maintainers directly.

If the project team responds and agrees the issue poses a security risk, we will work with the project security team or maintainers to communicate the vulnerability in detail, and agree on the process for public disclosure. Responsibility for developing and releasing a patch lies firmly with the project team, though we aim to facilitate this by providing detailed information about the vulnerability.

Our disclosure deadline for publicly disclosing a vulnerability is: 90 days after the first report to the project team.

We **appreciate the hard work** maintainers put into fixing vulnerabilities and understand that sometimes more time is required to properly address an issue. We want project maintainers to succeed and because of that we are always open to discuss our disclosure policy to fit your specific requirements, when warranted.
