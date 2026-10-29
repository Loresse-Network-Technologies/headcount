## In an insurance carrier or TPA, the process is also the regulatory record

In a general business, a process map exists to make work faster and more reliable. In an insurance
carrier, health or dental payer, or third-party administrator, the documented process has a second
job: state market conduct examiners, ERISA auditors, and SOC 1 / SOC 2 assessors test whether the
desk followed its written standard operating procedures (SOPs) on every sampled claim.

Four things that change how processes are designed and documented on an insurance floor:

- **Every manual decision point needs an explicit rule and an audit trail.** An SOP that says
  "review the claim for coverage" is un-auditable and produces different answers across shifts.
  Write the procedure at the decision-tree level: which screen or field to check, what document
  proves the condition, which adjustment reason code applies, and what file note template records
  the evidence.
- **Exception queues are where throughput and compliance both break.** Auto-adjudication handles
  clean claims in seconds; human touch time sits inside pended-claim queues (coordination of
  benefits, clinical review, high-dollar authority, and sanctions hits). Design every pend status
  with a single owner, an outbound trigger, a follow-up diary interval, and an aging ceiling — see
  `insurance-claims:claims-supervision-and-qa`.
- **Authority matrices and human-in-the-loop gates are system controls, not prose.** If an adjuster
  with $5,000 authority can release a $25,000 check because the system only warns instead of
  blocking, the process does not have a control. Encode dollar authority, coverage-denial sign-off,
  and OFAC sanctions holds (`insurance-claims:siu-and-sanctions-investigation`) as hard system
  gates.
- **Version every claim manual and desk procedure by effective date.** When a market conduct exam
  reviews claims paid eighteen months ago, the examiner asks for the SOP and benefit rule version in
  force on that date of service, not the one on the wiki today.
