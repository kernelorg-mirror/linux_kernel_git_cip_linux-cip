# Security Policy

This project is supported under the Linux Foundation CRA stewardship framework,
as described at https://www.linuxfoundation.org/security. Security
vulnerabilities should be reported through the mechanisms described below,
which we will coordinate with our CRA steward. For actively exploited
vulnerabilities and severe incidents that may require CRA escalation, please
use the project’s emergency security reporting mechanisms as described below.

## Security Context

Open source software can be used in various contexts that may go far beyond
what it was originally designed and also secured for. Therefore, we describe
here what the CIP kernel maintenance is particularly covering and what is out
of scope.

Unlike the upstream kernel, the CIP kernel is maintained with the focus on
architectures and configurations defined by the CIP project members, see
https://gitlab.com/cip-project/cip-kernel/cip-kernel-config. Vulnerabilities
found in code paths not covered this way are considered out of scope.
Furthermore, vulnerabilities that are affecting the upstream Linux kernel as
well are in the responsibility of the kernel security team, see
https://www.kernel.org/doc/html/latest/process/security-bugs.html. In scope for
the CIP kernel are issues caused by patches not found in the corresponding
stable kernel (linux-6.12.y-cip vs. linux-6.12.y) or that are related to
missing backports after the corresponding stable kernel went end-of-life.

## Reporting a Vulnerability

Please DO NOT report any potential security vulnerability via a public channel
(mailing list, gitlab issue etc.). Instead, contact the CIP security team via
security@cip-project.org via email. Please provide a detailed description of
the issue, the steps to reproduce it, the affected versions and, if already
available, a proposal for a fix. You should receive a response within 5 working
days. If the issue is confirmed as a vulnerability by us, we will request a
CVE, publish the fix and give credits for your report if desired. This project
follows a 90 day disclosure timeline.
