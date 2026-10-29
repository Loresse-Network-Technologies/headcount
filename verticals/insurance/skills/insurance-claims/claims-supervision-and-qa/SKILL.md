---
name: claims-supervision-and-qa
description: Supervises claims adjudication teams and audits claim files — reviewing high-dollar authority escalations, measuring financial and procedural claim leakage, enforcing statutory unfair-claims turnaround clocks, governing human-in-the-loop review queues, and managing reopen and pending-inventory health. Use this to review an adjuster authority request, design or score a claims QA audit, diagnose claim leakage or rising pend queues, or manage statutory prompt-pay compliance across a claims operation.
---

# Claims supervision and quality assurance

A claims operation fails in two opposite ways, and a supervisor is paid to prevent both: paying
what is not owed because nobody checked the coverage or the fee schedule, and delaying or underpaying
what is owed because queues, handoffs, or perverse metrics got in the way. The first shows up in
the loss ratio as leakage; the second shows up in a market conduct examination as an unfair claims
settlement practice finding.

## Authority governance and high-dollar sign-off

Tiered authority exists so that routine claims move at touch speed while complex or high-severity
exposures get a second pair of eyes before money or a coverage position leaves the building.

When reviewing an escalation above an adjuster's authority limit:

- **Read the primary source documents, not only the adjuster's summary.** Before approving a large
  payment, a policy-limit settlement, or a coverage denial, inspect the declarations page, the
  controlling endorsement, the operative clinical or damage report, and the sanctions screening
  disposition yourself. Signing off on a summary alone turns a two-person control into a rubber
  stamp.
- **Verify that coverage, liability, and damages are independently supported.** On a liability or
  casualty file, confirm how comparative fault was weighed, what the venue and verdict range look
  like, and whether every policy limit demand carries a documented response deadline. On a health
  or dental file, confirm that contract allowances, benefit maximums, and coordination of benefits
  were calculated before the high-dollar threshold was reached.
- **Record a structured supervisor note.** State what was reviewed, what authority is granted (a
  specific dollar range or determination approval), what conditions attach, and the date of the
  next required diary review.

## Auditing for claim leakage vs. procedural compliance

Most quality assurance programs measure whether the adjuster filled in every screen field and call
a 98% checklist score quality. A file can have every mandatory field populated and still overpay a
claim by forty percent.

Separate QA audits into two distinct scores so one never masks the other:

1. **Financial accuracy (hard and soft leakage).** Hard leakage is an explicit overpayment: paying a
   duplicate invoice, missing a deductible or coinsurance share, paying primary when another payer
   was primary under `insurance-claims:coordination-of-benefits-and-subrogation`, applying the
   wrong fee schedule, or missing a subrogation recovery. Soft leakage is paying more than the claim
   warranted because investigation was late, reserves were neglected, or independent medical or
   peer review was skipped.
2. **Procedural and statutory compliance.** Acknowledgment within the statutory window, timely
   payment or pend notice within prompt-pay clocks, accurate EOB and denial language, proper
   reservation of rights, and complete diary documentation.

Sample both **random closed claims** (to measure baseline accuracy across the floor) and **targeted
high-risk strata** — high-dollar payments, overridden edits, reopened claims, manual price overrides,
and claims settled just below an adjuster's authority threshold. Claims clustering 1% to 5% below
an authority ceiling are the classic tell of authority-splitting or under-settlement to avoid
supervisory review.

## Statutory clocks and pending-queue hygiene

Unfair claims settlement practices acts and ERISA/ACA claims regulations run on calendar and
business-day clocks: days to acknowledge receipt, days to request missing information, days to
accept or deny after proof of loss, and days to issue payment after settlement.

Manage the floor from aging cohorts, not average turnaround time:

- **Average turnaround hides the tail.** A desk that auto-adjudicates 80% of clean claims in one
  day and leaves the remaining 20% sitting unworked for forty-five days reports a nine-day average
  and fails its market conduct exam. Track the 90th and 99th percentile age and every claim
  approaching a statutory breach threshold.
- **Pend queues require a valid external dependency.** A claim pended for medical records, itemized
  bills, other-insurance information, or SIU clearance must carry an outbound request date, a
  follow-up diary date, and an automatic expiration clock. Pends used by adjusters to pause their
  desk aging metric without an active external request are a control failure.
- **Audit reopens and zero-pay closures.** Closing a claim without payment to clear a monthly
  backlog target, then reopening it the next week, corrupts cycle-time reporting and reserve
  development. Track the reopen rate per adjuster and audit files closed and reopened within
  thirty days.

## Governing human-in-the-loop (HITL) and auto-adjudication queues

Where straight-through processing or AI-assisted triage routes exceptions to human reviewers, the
supervisor owns the boundary between what the system decides and what a human must verify.

- **Never let an exception queue become a click-through habit.** When an edit or AI confidence flag
  routes a claim to a human desk, require the reviewer to record the reason for overriding or
  accepting the flag. Measure override rates by edit code: an edit overridden 95% of the time is a
  broken rule creating alert fatigue; an edit overridden 100% of the time by one adjuster is a
  training or compliance problem.
- **Gate high-consequence actions behind mandatory HITL.** Coverage denials, rescissions, SIU
  referrals, OFAC sanctions alerts (`insurance-claims:siu-and-sanctions-investigation`), and
  payments above threshold must require affirmative human disposition — never an automated default
  when a timer expires.
- **Feed QA findings back into rules and documentation.** When three adjusters make the same error
  on a new endorsement or benefit plan design, fix the adjudication rule and update the desk
  procedure via `operations:process-design` rather than issuing a floor-wide reminder email.

## Never

- Approve an authority escalation from an adjuster's summary note without inspecting the underlying policy, billing, and clinical or damage documents.
- Blend procedural checklist scores with financial leakage into a single QA percentage that hides overpayment or underpayment.
- Judge prompt-pay compliance from average turnaround time instead of aging tails and statutory deadline cohorts.
- Allow adjusters to pend or close-and-reopen claims to pause internal SLA clocks without an active external information request.
- Reward raw claim closure count without pairing it with financial accuracy, reopen rate, and appeal overturn rate.
