---
name: policyholder-and-provider-appeals
description: Reviews and resolves policyholder, member, and provider appeals, grievances, and Department of Insurance regulatory complaints — conducting independent de novo review of adverse benefit determinations and claim denials, verifying clinical and contractual rationale, enforcing ERISA, ACA, and state statutory turnaround clocks, and drafting compliant determination and external-review notices. Use this to adjudicate an internal appeal, draft an appeal uphold or overturn letter, route an independent external review, or respond to a state Department of Insurance inquiry.
---

# Policyholder and provider appeals

An appeal is the last internal chance to correct a wrong claim decision before it becomes a
regulatory complaint, an independent external review overturn, or bad-faith litigation. Treating the
appeals desk as a rubber stamp to defend the original adjuster's denial defeats its purpose and
multiplies the cost of every mistake.

## Independent de novo review

Federal law (ERISA and the ACA for health and dental plans) and state unfair claims standards
require that an appeal be reviewed without deference to the initial adverse determination.

- **Different reviewer, appropriate credentials.** The appeal reviewer must not be the person who
  made the initial adverse determination or a subordinate of that person. Where the appeal involves
  medical necessity, dental necessity, experimental/investigational status, or clinical judgment,
  the determination must be reviewed by a licensed healthcare professional (such as a board-certified
  peer physician or licensed dentist in the relevant specialty) who was not consulted on the initial
  denial.
- **Re-examine the entire record plus new submissions.** Read the full policy or Summary Plan
  Description (SPD), the complete claim history, the original EOB, and every operative report,
  chart note, radiograph, or legal argument submitted with the appeal. Check whether the original
  denial cited the right policy form for the date of service (`insurance-claims:claims-adjusting`).
- **Overturn cleanly when the original decision was wrong.** If the new clinical documentation
  satisfies the coverage criteria or the original edit was applied in error, overturn the denial
  promptly, direct reprocessing with interest where prompt-pay statutes require it, and log the root
  cause for `insurance-claims:claims-supervision-and-qa`.

## Statutory timelines and appeal classification

Appeal clocks are non-negotiable statutory obligations, and the clock starts the day the written
(or urgent oral) appeal hits any intake channel of the carrier or TPA — not the day it reaches the
appeals queue.

Track and triage immediately by appeal class:

- **Urgent / expedited pre-service appeals:** Where the standard timeframe could seriously
  jeopardize the claimant's life, health, or ability to regain maximum function, resolve and notify
  as expeditiously as the medical condition requires and within the federal/state ceiling (typically
  72 hours or less).
- **Pre-service (prior authorization) standard appeals:** Resolve within the applicable ERISA/ACA or
  state statutory window (typically 15 to 30 calendar days depending on single- or two-level appeal
  structure).
- **Post-service claim appeals and provider payment disputes:** Resolve within the statutory or
  contractual window (typically 30 to 60 calendar days for member post-service appeals; verify state
  provider-dispute resolution clocks separately).
- **Property and casualty coverage reconsideration:** Acknowledge and respond within the state
  Unfair Claims Settlement Practices Act communication and investigation windows.

Never reclassify a member grievance or coverage appeal as a "customer service inquiry" to keep it
off the regulatory appeal log.

## Writing a legally defensible appeal determination

When an adverse determination is upheld in whole or in part, the written notice is a regulated
legal document. Every uphold notice must include:

1. **The specific reason or reasons for the adverse determination** in clear, non-technical language
   alongside the applicable billing or adjustment codes.
2. **Reference to the specific policy, certificate, or plan provisions** on which the determination
   is based, quoted or cited by exact section and page/paragraph.
3. **Clinical or scientific rationale** when based on medical/dental necessity or experimental
   exclusion, either explaining the clinical judgment applied to the claimant's specific medical
   facts or offering the complete guideline/criterion free of charge upon request.
4. **Access to the claim file.** A statement that the claimant is entitled to receive, upon request
   and free of charge, reasonable access to and copies of all documents, records, and other
   information relevant to the claim.
5. **Next-step appeal and external review rights.** Clear instructions and deadlines for any
   second-level internal appeal, independent external review (IRO) where applicable, ERISA Section
   502(a) civil action rights for employee benefit plans, and contact information for the state
   Department of Insurance consumer assistance office or ombudsman.

## Responding to Department of Insurance (DOI) and regulatory complaints

When a policyholder or provider files a complaint with a state Department of Insurance, Department
of Managed Health Care, or Department of Labor, the response clock is short (often 15 to 21 calendar
days) and every factual assertion is subject to market conduct verification.

- **Build a chronological, document-backed timeline.** List policy effective dates, date of service
  or loss, date claim received, every request for information, date of initial determination, date
  of appeal, and date of response, attaching every referenced notice and EOB as a numbered exhibit.
- **Audit the file for statutory violations before replying.** If a prompt-pay deadline was missed
  or an edit misfired, admit the processing error factually, pay the claim plus any statutory
  interest before submitting the DOI response, and state the corrective action taken. Defending an
  indefensible processing error in front of a regulator turns a single claim mistake into a systemic
  market conduct criticism (`legal-risk:regulatory-compliance`).

## Never

- Assign an appeal to the adjuster who issued the initial denial or to a subordinate of that adjuster.
- Uphold a clinical or medical/dental necessity denial without a documented review by an appropriately licensed clinical peer.
- Start the statutory appeal turnaround clock from the date the file was routed to the appeals desk instead of the date the carrier or TPA received it.
- Reclassify a formal appeal or grievance as a routine customer-service inquiry to avoid appeal reporting or turnaround clocks.
- Issue an appeal uphold letter that omits the specific policy provision, the clinical rationale, or the mandatory external-review and Department of Insurance notice disclosures.
- Submit a Department of Insurance complaint response without verifying every date and assertion against the primary claim file exhibits and routing through compliance review.
