---
name: siu-and-sanctions-investigation
description: Investigates Special Investigations Unit (SIU) fraud referrals and dispositions OFAC, SDN, and PEP sanctions screening alerts — scoring true matches against false positives using secondary identifiers, executing mandatory payment blocks or rejections, documenting evidentiary red flags without defamatory claim notes, and escalating confirmed matches to the compliance officer. Use this to disposition a FinScan or OFAC sanctions hit, investigate suspected provider or claimant fraud, or prepare a statutory fraud or sanctions filing.
---

# SIU fraud and OFAC sanctions investigation

Sanctions screening and fraud investigation sit on the hardest legal boundary in an insurance
operation. An OFAC violation is strict liability: paying a claim, issuing a policy, or returning
premium to a Specially Designated National (SDN) or blocked person violates federal law even if the
adjuster did not know. Conversely, accusing a policyholder or provider of fraud in a claim file
without objective evidence exposes the carrier to defamation and bad-faith liability.

## OFAC, SDN, and PEP sanctions alert disposition

Sanctions screening tools (such as FinScan, LexisNexis Bridger, or Dow Jones watchlists) screen
policyholders, claimants, beneficiaries, providers, payees, and loss locations against the OFAC
Specially Designated Nationals (SDN) list, consolidated sanctions lists, and Politically Exposed
Persons (PEP) databases. Because fuzzy name matching is tuned for high recall, most raw alerts are
false positives — and every single one requires a documented, auditable disposition before a dollar
moves.

Follow a strict evidentiary comparison protocol for every alert:

1. **Compare primary and secondary identifiers.** Never clear an alert on name spelling differences
   alone. Compare full legal name, aliases/AKAs, date of birth, tax identification number (SSN, EIN,
   TIN, or national ID), street address, city/country, and vessel or entity registration numbers
   against the watchlist record and the claim or policy file.
2. **Apply deterministic exclusion rules for false positives.** An alert may be dispositioned as a
   **False Positive** only when a reliable secondary identifier conflicts — for example, a verified
   date of birth off by decades, a confirmed corporate EIN belonging to a domestic healthcare
   provider sharing a common name with a foreign entity, or an individual match against a corporate
   watch entry where entity type is incompatible. Record the exact disqualifying identifier in the
   audit log.
3. **Never clear an unresolved partial match by assumption.** If the claim file lacks a date of
   birth, address, or tax ID needed to rule out an SDN hit with a high name-similarity score, hold
   the payment and request the missing verification document (`W-9`, government ID, or corporate
   registration) before dispositioning the alert.
4. **Distinguish blocking from rejecting.** When a true match is confirmed or cannot be ruled out:
   - **Block (freeze):** If the target is on the SDN list or subject to a blocking program (including
     entities owned 50% or more in the aggregate by one or more blocked persons under the OFAC 50
     Percent Rule), freeze the funds or policy interest in a blocked account and route immediately
     to the OFAC Compliance Officer for required reporting to OFAC within 10 business days.
   - **Reject:** If the transaction involves a prohibited trade or service in a sanctioned
     jurisdiction without a blockable property interest, reject the transaction and report to OFAC
     within 10 business days.
   - **PEP hits:** A Politically Exposed Person match is not an automatic payment prohibition unless
     paired with a sanctions listing; route confirmed PEP matches to compliance for enhanced due
     diligence (EDD) according to the carrier's AML program.

## Special Investigations Unit (SIU) fraud triage and red-flag analysis

Adjusters spot anomalies; SIU investigates them. Keep that separation clean.

- **Triage referrals on objective red flags, not gut feel.** High-signal indicators include:
  - *Claimant/policyholder anomalies:* losses occurring immediately after policy inception or a
    coverage-limit increase; inconsistent trauma mechanisms across emergency room records and
    recorded statements; metadata manipulation or stock photos in submitted damage images; prior
    claim history matching the same staged loss pattern via ISO ClaimSearch.
  - *Provider and billing anomalies:* billing for services never rendered (phantom billing);
    systematic upcoding to high-complexity CPT or CDT codes across an entire patient panel;
    unbundling global procedures; impossible daily service volumes (more than 24 hours of timed
    procedures billed in a single day); identical clinical narratives copied across unrelated
    patients; or waiver of copayments and deductibles paired with inflated out-of-network billing.
- **Maintain a separate, access-controlled SIU investigative file.** Keep sensitive investigative
  work product, surveillance logs, link analysis, and law-enforcement referrals in the restricted
  SIU case system (`security:access-and-identity`), not in the general claim notes that surface on
  routine desk screens or discovery exports.
- **Coordinate with the claims desk on statutory clocks.** An SIU referral does not automatically
  suspend state prompt-pay deadlines unless state statute explicitly tolls the clock upon a
  documented condition. Tell the claims desk in writing whether to pend for specific verification
  (such as an Examination Under Oath, independent medical exam, or provider medical-record audit)
  or pay undisputed portions.
- **Mandatory state fraud bureau reporting.** Most states require carriers to file a formal fraud
  referral (DFR / NHCAA / NAIC fraud portal) when the carrier has a reasonable belief that a
  fraudulent insurance act has been committed. Ensure the filing states verified facts and exhibits,
  and invoke statutory immunity protections by keeping communications factual and non-malicious.

## Never

- Release a claim payment, refund, or policy issuance while an open OFAC or SDN alert remains unreviewed or lacks secondary-identifier verification.
- Clear a sanctions alert as a false positive based on a middle initial or minor transliteration difference when date of birth, address, or tax ID has not been checked.
- Tip off a blocked party or suspected fraud ring why a payment is frozen on a sanctions hold or under active SIU investigation.
- Write conclusory accusations of "fraud", "criminal", or "liar" in claim or SIU notes; document only verifiable facts, discrepancies, and source records.
- Deny a claim solely because an SIU referral was opened without establishing an evidentiary and contractual basis for the denial.
