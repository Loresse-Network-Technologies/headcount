---
name: claims-adjusting
description: Adjudicates property, casualty, health, and dental claims from first notice of loss through payment or denial — verifying policy coverage and effective dates, reviewing CPT, CDT, ICD-10, and itemized billing against fee schedules, setting and updating case reserves, and drafting explanation of benefits and settlement letters within assigned authority. Use this to triage a new claim, verify coverage against declarations and endorsements, audit medical or dental procedure codes, calculate allowed amounts and member cost-sharing, set reserves, or draft a claim determination.
---

# Claims adjusting

A claim file is a legal and financial record written in real time. Every note, reserve change,
coverage check, and payment or denial letter must read cleanly to three people who were not in the
room when the decision was made: the policyholder or provider, a claims supervisor auditing leakage,
and a state Department of Insurance market conduct examiner reading the file two years later.

This skill structures practitioner claim adjudication across property and casualty, health, dental,
and third-party administrator (TPA) operations. Statutory prompt-pay clocks, coverage interpretation
rules, and bad-faith standards vary by state and line of business; escalate contested coverage
questions to `insurance-claims:claims-supervision-and-qa` or qualified coverage counsel.

## Coverage verification comes before valuation

Never price a loss or negotiate a bill before confirming that coverage was in force on the date of
loss and that the claim falls within the insuring agreement. Checking coverage in the wrong sequence
is how an adjuster waives a defense or creates an estoppel argument by investigating quantum while
an obvious coverage bar sits unread on the declarations page.

Verify in this order and record each check in the file notes:

1. **Policy status and effective dates.** Confirm the date of loss or date of service falls between
   the policy effective date and expiration or cancellation date, and that premium was paid or
   within a statutory grace period. Watch for retroactive eligibility terminations on group health
   and dental plans.
2. **Insured, member, or covered property identity.** Confirm the claimant, patient, dependent,
   vehicle, or scheduled location is actually listed as covered on the declarations page or
   eligibility feed on the date of loss. Check dependent age limits, waiting periods for major
   restorative or prosthodontic dental services, and newly acquired property reporting windows.
3. **Insuring agreement first, exclusions and endorsements second.** Establish what grants coverage
   before reading what takes it away. Endorsements and riders modify the base form; read the
   endorsement schedule from the bottom up because an endorsement overrides the base policy wording
   every time.
4. **Deductibles, coinsurance, copayments, and maximums.** Check annual or per-occurrence
   deductibles eroded to date, out-of-pocket maximums, annual benefit maximums, lifetime limits on
   specific benefits such as orthodontia, and sub-limits on specialized perils.
5. **Other insurance and recovery triggers.** Flag any indication of another plan, workers'
   compensation, auto medical payments, or a negligent third party at intake and route to
   `insurance-claims:coordination-of-benefits-and-subrogation` before issuing primary payment.

Where coverage is questionable on a liability or property claim, issue a timely **reservation of
rights** letter that quotes the specific policy language under investigation before continuing to
investigate the loss.

## Medical, dental, and itemized bill adjudication

On health, dental, workers' compensation, and bodily injury claims, the submitted charge is the
beginning of the calculation, not the amount owed.

- **Validate code-to-documentation alignment.** On dental claims (ADA J430D / 837D), verify CDT
  procedure codes against tooth numbers, surfaces, quadrant designations, periodontal charting, and
  diagnostic radiographs. On medical and facility claims (CMS-1500 / 837P and UB-04 / 837I), check
  CPT/HCPCS procedure codes, modifiers, revenue codes, place of service, and ICD-10-CM diagnosis
  pointers against clinical notes.
- **Apply bundling and frequency edits.** Identify unbundled procedures that belong to a global or
  comprehensive code — such as separate charges for local anesthesia, suture removal, or routine
  post-operative care included in a surgical package, or periapical radiographs billed alongside a
  full-mouth series on the same date of service. Verify frequency limitations (such as prophylaxis
  twice per calendar year or bitewings once per twelve months) and alternate benefit provisions
  (such as amalgam or composite downgrades on posterior teeth when the plan document specifies the
  least costly professionally acceptable treatment).
- **Calculate the allowed amount accurately.** Contracted in-network providers are paid against the
  negotiated fee schedule, and the provider writes off the balance above the contracted allowance.
  Out-of-network claims are adjudicated against the plan's usual, customary, and reasonable (UCR)
  percentile, Medicare-based percentage, or scheduled allowance, with balance-billing protections
  applied where the No Surprises Act or state surprise-billing laws govern.
- **Check prior authorization and predetermination.** Confirm whether the procedure required prior
  authorization or pre-treatment estimate and whether an approved authorization covers the date of
  service and billed code.

## Case reserve adequacy

A reserve is not a guess and it is not a negotiation ceiling. It is the carrier's or self-funded
plan's balance-sheet recognition of the probable total cost to resolve the claim based on the facts
known today.

- **Set an initial reserve as soon as the facts outgrow the statistical average.** Formula or
  tabular reserves work at first notice of loss when facts are sparse; the moment medical reports,
  repair estimates, or liability evaluations arrive, replace the formula reserve with an evaluation
  of expected indemnity and allocated loss adjustment expense (ALAE).
- **Avoid stair-stepping.** Raising a reserve five times by small increments as bills arrive means
  the file was under-reserved at every prior step, distorting actuarial loss-development triangles
  and reinsurance reporting. Estimate the ultimate exposure once the severity is visible.
- **Adjust promptly when facts change.** A surgical recommendation, an attorney representation
  letter, a comparative-negligence witness statement, or a sub-limit cap changes the exposure on
  the day it arrives, not at the quarterly file review.

## Explanation of benefits (EOB) and settlement communication

Every determination — payment, partial payment, request for additional information, or denial —
must tell the recipient what was decided, why, and what they can do next.

- **State the exact basis.** Never deny or reduce a line item with a cryptic internal edit code
  alone. Pair the adjustment reason code (CARC/RARC on 835 remittances) with plain-language prose
  citing the specific policy section, certificate of coverage paragraph, or clinical guideline.
- **Separate undisputed from disputed amounts.** Where part of a claim is clearly owed and another
  part requires investigation or additional documentation, pay the undisputed portion within the
  statutory prompt-pay window and pend only the contested lines with a specific document request.
- **Respect authority limits.** An adjuster adjudicates and settles only up to their written dollar
  and coverage authority. Anything above that threshold, any total policy-limit demand, or any
  allegation of bad faith routes to `insurance-claims:claims-supervision-and-qa` with a structured
  authority request memo before any offer or denial is communicated.

## Never

- Pay or deny a claim before verifying policy effective dates, member or asset eligibility, and the insuring agreement.
- Speculate about fraud, malingering, or policyholder dishonesty in claim file notes; record only objective facts and refer red flags to `insurance-claims:siu-and-sanctions-investigation`.
- Stair-step case reserves to match incoming invoices instead of reserving for probable ultimate exposure.
- Commit to a settlement, payment, or coverage denial above your written dollar or coverage authority without documented supervisor sign-off.
- Withhold payment on undisputed claim lines while investigating a separate disputed line item.
- Issue a partial or full denial without citing the specific policy provision, benefit limitation, or clinical criterion and the claimant's appeal rights.
