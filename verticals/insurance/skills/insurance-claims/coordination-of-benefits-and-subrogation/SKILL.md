---
name: coordination-of-benefits-and-subrogation
description: Determines order of benefit determination across multiple health, dental, auto, or property plans and executes third-party subrogation and overpayment recovery — applying NAIC birthday, active-versus-retiree, custodial-parent, and Medicare Secondary Payer rules, calculating secondary payable amounts under standard COB and carve-out methods, and pursuing tortfeasor or workers' compensation recovery. Use this when a claimant has more than one insurance plan, when calculating secondary payment after a primary EOB, or when evaluating subrogation and reimbursement liens.
---

# Coordination of benefits and subrogation

Paying a claim without checking who else owes it is the single largest source of recoverable claim
leakage in health, dental, auto, and property-casualty operations. Coordination of benefits (COB)
decides which plan pays first when two or more plans cover the same person for the same service;
subrogation and reimbursement recover money after a loss caused by a third party or covered under
workers' compensation.

## Order of benefit determination (who pays first)

Never let a policyholder or provider choose which plan is primary. Order of benefit determination
follows statutory and NAIC Model Regulation hierarchy rules, applied in strict sequence until the
first rule that distinguishes the plans resolves the order:

1. **No-COB plan rule.** A plan without a coordination-of-benefits provision is always primary over
   a plan that contains one.
2. **Non-dependent vs. dependent.** The plan covering the person as an employee, member, subscriber,
   or policyholder pays primary; the plan covering that same person as a dependent (spouse or child)
   pays secondary.
3. **Dependent children of parents not separated or divorced (the Birthday Rule).** The plan of the
   parent whose birthday (month and day only, never the birth year) falls earlier in the calendar
   year is primary. If both parents share the exact same month and day of birth, the plan that has
   covered a parent longer is primary.
4. **Dependent children of separated, divorced, or never-married parents.** Unless a court decree
   explicitly assigns financial responsibility for health or dental coverage to one parent — and the
   plan has actual knowledge of that decree — the order is:
   - First, the plan of the custodial parent;
   - Second, the plan of the spouse of the custodial parent;
   - Third, the plan of the non-custodial parent;
   - Fourth, the plan of the spouse of the non-custodial parent.
5. **Active employee vs. laid-off, retired, or COBRA continuation.** The plan covering a person as
   an actively working employee (or that person's dependent) is primary over a plan covering the
   person as a retired, laid-off, or COBRA continuation beneficiary.
6. **Medicare Secondary Payer (MSP) rules.** When a beneficiary has both Medicare and group health
   plan coverage, federal MSP thresholds govern rather than the NAIC active/retiree default alone:
   - **Working aged (65 or older) through active employment:** Group health plan is primary if the
     employer has 20 or more employees; Medicare is primary if fewer than 20 employees.
   - **Disability (under 65) through active employment:** Group health plan is primary if the
     employer has 100 or more employees.
   - **End-Stage Renal Disease (ESRD):** The group health plan remains primary during the 30-month
     coordination period regardless of employer size, after which Medicare becomes primary.
   - **Workers' compensation, no-fault, and liability insurance:** Always primary over Medicare for
     injury-related care.
7. **Longer vs. shorter length of coverage.** If none of the rules above establishes the primary
   plan, the plan that has covered the person for the longer continuous period is primary.

## Calculating the secondary payment

Knowing that your plan is secondary does not tell you how much to pay. Read the plan document's COB
method before calculating a dollar:

- **Standard (traditional) COB / 100% allowable expense:** The secondary plan calculates what it
  would have paid as primary, then pays the lesser of that amount or the remaining allowable
  expense after the primary plan's payment, so combined payments never exceed 100% of total
  allowable expenses.
- **Non-duplication of benefits (carve-out) COB:** The secondary plan calculates what it would have
  paid had it been primary, then subtracts what the primary plan actually paid. If the primary plan
  paid equal to or more than the secondary plan's normal benefit, the secondary plan pays **$0.00**.
- **Maintenance of benefits (MOB):** The secondary plan reduces its covered charge by the primary
  payment and applies its own deductible and coinsurance to the remainder.
- **In-network write-offs:** Never pay a provider's contractual write-off from the primary carrier
  unless the secondary plan document and provider contract explicitly define allowable expense to
  include it. Ensure the primary Explanation of Benefits (EOB) or 837 COB loop data shows billed
  amount, primary allowed amount, primary paid amount, and patient responsibility.

## Subrogation, third-party liability, and workers' compensation

While COB coordinates two benefit plans without fault, subrogation steps into the insured's shoes
to recover payments from an at-fault third party or primary casualty insurer.

- **Spot the trigger at intake.** Trauma diagnosis codes (ICD-10 S00-T88 and external cause codes
  V00-Y99), workplace accidents, motor vehicle collisions, slip-and-fall injuries, product defects,
  and dog bites on health or dental claims — or rear-end collisions, defective appliances, and
  neighboring water leaks on property/auto claims — must trigger an immediate third-party questionnaire
  or subrogation referral.
- **Distinguish workers' compensation from third-party tort.** Health and dental plans generally
  exclude work-related injuries outright; when a claim arises out of employment and workers'
  compensation coverage applies, the health/dental claim is typically denied (or paid conditionally
  under a state lien statute) rather than coordinated. Third-party tort claims (such as an off-duty
  auto accident) are typically paid under the health plan subject to a subrogation or reimbursement
  lien against the tort recovery.
- **Verify plan jurisdiction and equitable defenses.** An ERISA self-funded plan with clear plan
  language disclaiming the **Make-Whole Doctrine** and the **Common Fund Doctrine** holds a markedly
  stronger recovery position than a fully insured plan governed by state anti-subrogation or
  make-whole statutes. Check whether the plan is self-funded or fully insured and verify state law
  before compromising or asserting a lien.
- **Put all parties on notice early.** Send formal written notice of lien to the member, the
  member's plaintiff counsel, and the third-party liability carrier before the liability claim
  settles. Once settlement funds are disbursed without notice, recovery drops sharply.

## Never

- Determine primary versus secondary coverage using the parents' birth years instead of month and day under the NAIC Birthday Rule.
- Pay a secondary claim from a patient balance bill or invoice summary without verifying the primary plan's official Explanation of Benefits or electronic remittance data.
- Apply standard 100% COB calculation to a self-funded plan whose plan document specifies non-duplication of benefits (carve-out), or vice versa.
- Pay above the primary plan's contracted provider write-off so that combined primary and secondary payments exceed the lowest contractual allowance required by the plan.
- Close a trauma, motor-vehicle, or property-damage claim with third-party fault indicators without logging a subrogation or workers' compensation evaluation and issuing timely notice of lien.
- Assert or waive an ERISA or state-law reimbursement lien without verifying whether the plan is self-funded or fully insured and whether make-whole or common-fund rules apply.
