# Security Vulnerability Process

If you think you have discovered a security issue with rust-vmm, please do NOT
open a public issue. Our process for handling reported security concerns and
protecting rust-vmm customers through coordinated vulnerability disclosure
(CVD) is described below.

## Reporting Security Vulnerabilities

We ask anyone who discovers a security concern associated with any of the
rust-vmm components to report it with
[GitHub's private security reporting mechanism](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) in the respective
repository.

Please provide any supporting material (proof-of-concept code, tool
output, etc.) that would be useful in helping us understand the nature
and severity of the security concern.

We will post a non-automated acknowledgement reply within 1 business day
followed by an initial assessment of the issue within 5 business days.
Subsequently, we will work in partnership with you to assess any impact of the
issue and prepare a security advisory (including any patches with appropriate
fix) as needed.

## Embargo

If our assessment results in validating a vulnerability, we will work with you
to agree on an embargo period (we recommend at least 2 weeks AFTER any
necessary development time) which will provide rust-vmm customers enough time
to test our proposed fix and patch their products prior to any broader or more
public disclosure. Members of the rust-vmm organization and repository
maintainers agree not to publicly disclose any details of the security
issue until the embargo period expires.

## CVE Allocation

We will check whether you, as issue discoverer, have already reserved a CVE
number. If not, we will acquire a CVE candidate number on your behalf and
include the candidate number in any disclosure communications. Any eventual CVE
number will be used to submit a
[Rust Security Advisory](https://github.com/RustSec/advisory-db).
