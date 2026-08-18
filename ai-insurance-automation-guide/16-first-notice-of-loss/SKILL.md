---
name: first-notice-of-loss
title: Commercial Insurance First Notice of Loss (FNOL)
collection: ai-insurance-automation-guide
prompt_number: 16
category: commercial-pc
capability: claims-intelligence
primary_role: insurance-claims-intake-specialist
secondary_roles:
  - commercial-account-manager
  - commercial-account-executive
  - claims-advocate
  - commercial-insurance-producer
  - client-service-specialist
template_version: 2.1
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Commercial Insurance First Notice of Loss (FNOL)

## Purpose

Transform raw, incomplete, or unstructured claim intake notes into a clean, accurate, organized First Notice of Loss report that can be reviewed by a carrier, adjuster, claims advocate, or internal insurance team.

This Skill is designed to help the insurance professional:

- Identify the essential facts of the loss
- Organize claim information logically
- Separate confirmed facts from assumptions
- Identify missing or ambiguous information
- Surface urgent claim-handling needs
- Distinguish known damage from possible damage
- Identify parties involved
- Clarify dates, locations, and circumstances
- Prepare a concise carrier-ready claim narrative
- Recommend immediate next actions
- Reduce claim-reporting delays caused by incomplete intake
- Preserve an accurate record of what was known at first notice

The objective is **not** to determine coverage, liability, or fault.

The objective is to create an accurate and actionable **First Notice of Loss** from the information available at intake.

---

# Core Outcome

A successful use of this Skill should allow the carrier, adjuster, or claims team to understand:

- Who is involved
- What happened
- When it happened
- Where it happened
- How the loss reportedly occurred
- What type of loss is involved
- What damage or injury is currently known
- Whether emergency action has been taken
- Whether additional parties are involved
- What information remains missing
- What needs to happen next
- Whether the matter requires urgent escalation

The report should be immediately usable without forcing the reviewer to reconstruct the loss from scattered notes.

---

# Best Used For

Use this Skill for intake involving:

- Commercial Auto claims
- General Liability claims
- Property claims
- Workers' Compensation claims
- Inland Marine claims
- Equipment Breakdown claims
- Cyber incidents
- Crime losses
- Professional Liability claims
- Employment Practices matters
- Product Liability claims
- Pollution incidents
- Umbrella / Excess notice
- Third-party bodily injury
- Third-party property damage
- Premises incidents
- Contractor losses
- Vehicle accidents
- Theft
- Fire
- Water damage
- Weather damage
- Employee injuries
- Customer allegations
- Early notice of circumstances

This Skill is especially useful when claim information originates from:

- Phone notes
- Email
- Text
- Voicemail
- Service case
- Producer notes
- Client portal
- Internal handoff
- Incident report

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- A coverage determination
- A liability determination
- A fault determination
- Legal advice
- Carrier claim adjudication
- Medical advice
- Workers' Compensation compensability determination
- Claim settlement authority
- Formal incident investigation
- Carrier-specific mandatory claim form
- Regulatory reporting
- OSHA reporting
- Law-enforcement reporting
- Emergency response

This is a **claim intake and First Notice of Loss preparation Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Insurance Claims Intake Specialists
- Commercial Account Managers
- Commercial Account Executives
- Claims Advocates
- Commercial Insurance Producers
- Client Service Specialists
- Agency Claims Teams
- Other authorized insurance professionals

---

# Required Inputs

At minimum, provide:

1. Raw claim intake notes

Recommended format:

```text
Notes:
[INSERT]
```

The notes may be incomplete.

Do not invent missing claim facts simply to complete the FNOL.

---

# Recommended Inputs

The following information materially improves the FNOL:

- Insured name
- Contact name
- Contact phone
- Contact email
- Policy type
- Policy number
- Carrier
- Date of loss
- Time of loss
- Location of loss
- Date reported
- Description of incident
- Parties involved
- Injuries
- Property damage
- Vehicle information
- Driver information
- Witnesses
- Police report
- Fire department involvement
- Emergency services
- Claimant information
- Employee information
- Third-party information
- Damaged property
- Estimated damage
- Current condition of property
- Mitigation performed
- Towing
- Temporary repairs
- Medical treatment
- Work status
- Attorney involvement
- Photos
- Video
- Incident report
- Contract information
- Other insurance information
- Urgent business needs
- Preferred adjuster contact
- Prior carrier notice

---

# Preferred Source Documents

Where available, prioritize:

1. Client or insured's direct incident report
2. Current policy information
3. Police / fire / emergency report
4. Incident report
5. Photos or video
6. Driver / vehicle information
7. Witness information
8. Repair or mitigation documents
9. Medical or occupational incident information appropriate for claim reporting
10. Agency case notes
11. Prior correspondence

Do not treat unverified third-party statements as confirmed facts.

---

# Document Completeness Standard

Where documents are supplied, classify the intake set when useful as:

### Complete Enough for FNOL

Enough information exists to report the claim responsibly.

### Partially Complete

The claim can likely be reported, but important information remains outstanding.

### Fragmentary

The available information is too limited to create a reliable FNOL.

The standard for FNOL is not the same as the standard for final claim investigation.

Do not delay claim reporting solely because every detail is not yet known if enough information exists to provide responsible notice.

---

# Source Hierarchy

When information conflicts, prioritize:

1. Direct insured / client-confirmed facts
2. Official incident documentation
3. Current policy or agency records
4. Direct witness information
5. Carrier correspondence
6. Agency notes
7. Professional inference

If key facts conflict:

- Identify the discrepancy
- Do not silently reconcile it
- State the competing versions where material
- Flag the issue for adjuster confirmation

---

# Evidence Classification

Every material FNOL statement should be classified internally as one of the following.

## Confirmed Fact

Directly supported by the insured or authoritative documentation.

Example:

> The accident occurred on August 15 at approximately 3:30 p.m.

---

## Reported Allegation

A statement made by another party that has not been independently verified.

Example:

> The claimant alleges that the insured vehicle entered the intersection against the light.

---

## Observed Condition

A condition reported or documented after the event.

Example:

> Photos show visible front-end damage to the insured vehicle.

---

## Unknown

Information not yet available.

---

## Requires Adjuster Investigation

An issue requiring claim investigation.

Example:

> Fault for the accident has not been determined.

---

## Requires Coverage Review

An issue that may affect coverage but should not be resolved at FNOL.

Example:

> The vehicle's scheduled status should be confirmed by the carrier.

---

# Confidence Classification

Where useful:

### High Confidence

Supported by direct or authoritative information.

### Moderate Confidence

Supported by one credible source but not independently confirmed.

### Low Confidence

Information is ambiguous, conflicting, or incomplete.

FNOL accuracy is more important than appearing complete.

---

# Core Principle

## Report What Is Known. Identify What Is Unknown. Do Not Investigate the Claim by Assumption.

FNOL is the starting point of the claim process.

It should preserve:

- Facts
- Timing
- Parties
- Damage
- Immediate needs

without prematurely deciding:

- Liability
- Fault
- Coverage
- Cause
- Compensability
- Settlement value

---

# Execution Readiness Standard

Before recommending claim submission, determine whether the intake is:

### Ready for FNOL

Enough information exists to identify the insured, event, approximate date, and basic loss circumstances.

### Conditionally Ready

The claim can be reported, but material information should follow.

### Not Ready

The available information is too limited to identify the insured, event, or basic loss.

Do not hold a time-sensitive claim merely because nonessential details are missing.

---

# Time Horizon / Execution Feasibility Standard

Claims may contain time-sensitive issues.

Identify:

- Date of loss
- Date reported
- Reporting delay
- Emergency mitigation need
- Medical treatment need
- Property protection need
- Towing / storage
- Business interruption
- Evidence preservation
- Legal deadline if documented
- Carrier reporting requirement if known

If immediate action is required, prioritize the operational need before polishing the report.

---

# Workflow State Standard

Use claim intake states when relevant:

1. Received
2. Validated
3. Ready for FNOL
4. Waiting on Client
5. Submitted to Carrier
6. Carrier Acknowledged
7. Claim Number Received
8. Adjuster Assigned
9. Additional Information Pending
10. Escalated
11. FNOL Complete

Do not confuse:

> FNOL submitted

with:

> Claim resolved.

---

# Workflow

## Step 1 — Identify the Insured

Capture:

- Insured name
- Contact
- Business name
- Policy or line
- Carrier
- Policy number if available

If policy information is unavailable, note it.

---

## Step 2 — Identify the Loss Type

Classify the event when possible.

Examples:

- Auto accident
- Property damage
- Fire
- Water
- Theft
- Bodily injury
- Employee injury
- General liability
- Cyber incident
- Crime
- Professional allegation
- Employment allegation
- Product incident
- Pollution

Do not force a classification when unclear.

---

## Step 3 — Establish the Core Five Facts

Capture:

### Who

Who was involved?

### What

What happened?

### When

When did it occur?

### Where

Where did it occur?

### How

How did the event reportedly happen?

These form the claim summary.

---

## Step 4 — Establish the Reporting Timeline

Identify:

- Date of loss
- Time of loss
- Date reported to agency
- Whether carrier has already been notified
- Whether there was a delay
- Reason for delay if known

Do not imply late notice has coverage consequences without authority.

---

## Step 5 — Identify Parties Involved

Depending on the claim:

- Insured
- Driver
- Employee
- Claimant
- Injured party
- Property owner
- Customer
- Contractor
- Subcontractor
- Witness
- Other vehicle operator
- Attorney
- Police
- Fire department

Avoid unnecessary sensitive information.

---

## Step 6 — Identify Known Injury Information

Where applicable:

- Whether anyone was injured
- Number of injured parties
- General nature of reported injury
- Whether emergency treatment occurred
- Hospital or clinic if relevant
- Employee work status if appropriate
- Whether attorney representation is known

Do not diagnose injuries.

Do not request unnecessary medical detail.

---

## Step 7 — Identify Known Property Damage

Capture:

- Property damaged
- Owner
- Nature of damage
- Current condition
- Estimated amount if provided
- Whether property is usable
- Temporary repairs
- Mitigation
- Towing
- Storage
- Business interruption

Do not invent damage estimates.

---

## Step 8 — Identify Vehicle Information

For auto losses, capture when available:

- Year
- Make
- Model
- VIN
- License plate
- Driver
- Ownership
- Damage
- Tow location
- Other vehicle information
- Police report number

---

## Step 9 — Identify Employee Injury Information

For workers' compensation matters, capture:

- Employee
- Job title
- Date / time
- Work location
- Activity being performed
- Injury description
- Supervisor
- Medical treatment
- Work status
- Witnesses

Do not make compensability determinations.

---

## Step 10 — Identify Immediate Risk-Control Actions

Determine whether steps have been taken to:

- Stop active water
- Secure property
- Contact fire department
- Call emergency services
- Tow vehicle
- Prevent further damage
- Shut down equipment
- Preserve evidence
- Notify law enforcement
- Isolate cyber systems
- Protect employees or public

Do not instruct users to enter unsafe conditions.

---

# Mitigation vs. Repair Standard

Distinguish:

### Emergency Mitigation

Reasonable action intended to prevent additional damage.

### Permanent Repair

Final corrective work.

FNOL should identify what has occurred without directing permanent repair decisions that may require carrier coordination.

---

## Step 11 — Identify Witnesses and Evidence

Capture:

- Witness names/contact if available
- Photos
- Video
- Dashcam
- Security footage
- Police report
- Incident report
- Contracts
- Receipts
- Repair estimates
- Medical paperwork

Recommend preservation of relevant evidence where appropriate.

---

## Step 12 — Identify Third-Party Allegations

If another party has made a demand or allegation:

- Record it accurately
- Attribute the statement
- Do not adopt it as fact

Example:

> The claimant states that water from the insured's unit damaged the floor below.

Not:

> The insured caused water damage to the floor below.

unless confirmed.

---

# Neutral Narrative Standard

Use factual and neutral language.

Avoid:

- "Our insured caused..."
- "The claimant was at fault..."
- "This is clearly covered..."
- "The employee was negligent..."

unless those matters are already authoritatively determined.

Preferred:

> The insured reports...

> The claimant alleges...

> The available notes indicate...

> Liability has not been determined.

---

## Step 13 — Identify Missing Information

Prioritize missing information that matters to claim setup.

Examples:

- Exact loss date
- Exact location
- Contact information
- Injury status
- Police report
- Claimant information
- Vehicle information
- Damaged property
- Photos
- Description of event
- Current emergency condition

Do not create a long wish list of low-value information.

---

## Step 14 — Prioritize Missing Information

Classify missing information:

### Critical Before Reporting

Without it, the claim cannot reasonably be identified.

### Important Follow-Up

Useful for adjuster evaluation but should not necessarily delay notice.

### Supplemental

Helpful but nonessential for FNOL.

This prevents unnecessary reporting delays.

---

## Step 15 — Identify Urgency

Classify:

### Routine

No immediate safety, operational, or severity concern identified.

### Time Sensitive

Prompt action is advisable.

### Urgent

Immediate claim handling or mitigation is needed.

### High Severity / Escalation

Potential for:

- Serious bodily injury
- Fatality
- Major property loss
- Significant business interruption
- Environmental release
- Cyber compromise
- Multiple claimants
- Media attention
- Attorney involvement
- Major third-party demand

High-severity classification is a workflow priority, not a coverage determination.

---

# Human Review Escalation Standard

Require elevated human review for:

- Fatality
- Serious bodily injury
- Hospitalization
- Multiple injured parties
- Major fire
- Significant environmental release
- Major cyber event
- Potentially catastrophic loss
- Claim involving a minor
- Attorney demand
- Government investigation
- Media-sensitive incident
- Allegation against an executive
- Potential uninsured exposure
- Coverage dispute
- Significant reporting delay
- Material client complaint about claim handling

AI may prepare the FNOL.

An authorized claims professional should oversee escalation.

---

## Step 16 — Identify Policy Information

Capture known policy information.

Do not determine whether coverage applies.

If policy details appear inconsistent:

> Requires carrier / claims confirmation.

---

## Step 17 — Build the Claim Summary

Write a concise paragraph including:

- Who
- What
- When
- Where
- How

Example:

> The insured reports that on August 15 at approximately 3:30 p.m., an employee operating a company-owned Ford F-250 was involved in a two-vehicle collision at the intersection of Main Street and First Avenue in Reno, Nevada. The insured reports damage to both vehicles. One third-party occupant reportedly complained of neck pain and was evaluated at the scene. Police responded. Liability has not been determined.

---

## Step 18 — Build the Structured Detail Section

Organize information by category.

Avoid repeating the same fact in multiple sections unless needed for clarity.

---

## Step 19 — Identify Recommended Next Actions

Potential next actions:

- Submit FNOL to carrier
- Obtain claim number
- Confirm adjuster assignment
- Send photos
- Obtain police report
- Obtain claimant contact information
- Preserve damaged property
- Forward demand letter
- Coordinate mitigation
- Obtain employee injury information
- Follow carrier instructions
- Schedule client status update

Do not make coverage or settlement recommendations at FNOL.

---

## Step 20 — Establish Ownership

For each action, identify the owner.

Potential owners:

- Client
- Agency
- Carrier
- Adjuster
- Employee
- Vendor
- Claims advocate
- Other third party

---

## Step 21 — Establish Next Update

If the claim remains open in the intake stage, define:

- When client will receive claim number
- When adjuster assignment is expected if known
- When agency will follow up
- What event triggers the next update

Do not promise carrier response times unless confirmed.

---

# Data Integrity Standard

Before finalizing, review for:

- Conflicting dates
- Conflicting locations
- Duplicate parties
- Missing contact information
- Inconsistent vehicle information
- Ambiguous cause
- Unsupported assumptions
- Incorrect policy identifiers

Do not silently repair a material inconsistency.

---

# Data Normalization Standard

Safe normalization may include:

- Standardizing date formats
- Standardizing phone formats
- Standardizing state names
- Standardizing names where clearly identical
- Organizing vehicle details
- Structuring addresses

Do not silently:

- Change factual statements
- Merge potentially different parties
- Infer ownership
- Infer fault
- Infer injury severity
- Infer cause

---

# Ownership Standard

Every material next action should have an owner.

Example:

| Action | Owner |
|---|---|
| Submit FNOL | Agency |
| Provide photos | Client |
| Assign adjuster | Carrier |
| Obtain police report | Adjuster / Client, depending on process |

---

# Update Cadence Standard

If claim acknowledgment or adjuster assignment remains pending, define a follow-up trigger.

Example:

> Agency will follow up if carrier acknowledgment is not received within the expected service window.

Do not leave time-sensitive FNOLs without active follow-up.

---

# Stop Rules

FNOL intake work should move to the next phase when:

- Enough information exists for responsible claim reporting
- Carrier notice is submitted
- Claim number is obtained or acknowledgment received
- Adjuster assignment is confirmed when part of the agency workflow
- Outstanding supplemental items are clearly documented

Do not continue delaying notice in pursuit of nonessential information.

---

# Completion Criteria Standard

FNOL preparation is complete when:

1. Core claim facts are documented
2. Material missing information is identified
3. Urgency is assessed
4. Claim narrative is prepared
5. Required parties and damage are documented
6. Recommended next steps are assigned
7. Carrier reporting status is clear

If the Skill is used as part of an operational claim-reporting workflow, completion may additionally require:

8. FNOL submitted
9. Carrier acknowledgment received
10. Claim number recorded
11. Internal claim record updated
12. Client advised of next step

Do not confuse FNOL completion with claim resolution.

---

# Decision Rules

## Accuracy Over Completeness

Do not invent missing information.

---

## Do Not Delay Notice for Nonessential Details

FNOL exists to begin the claim process.

---

## Facts Are Not Fault

Do not convert event descriptions into liability determinations.

---

## Allegations Must Be Attributed

Use:

> Claimant alleges...

not:

> Insured caused...

unless confirmed.

---

## No Coverage Determination at Intake

FNOL should report the event.

Carrier or authorized claims professionals determine coverage.

---

## Do Not Diagnose Injury

Record reported injury information neutrally.

---

## Severity Should Drive Escalation

Potential high-severity matters should receive human attention quickly.

---

## Preserve Evidence

Where appropriate, recommend preservation without directing destructive or unsafe activity.

---

# Materiality / Prioritization Framework

Prioritize intake information using:

| Factor | Question |
|---|---|
| Safety | Is anyone still at risk? |
| Severity | Could the loss be significant? |
| Injury | Are bodily injuries involved? |
| Property | Is there major or ongoing damage? |
| Business Impact | Are operations disrupted? |
| Third Party | Is another party involved? |
| Legal / Regulatory | Is there attorney or government involvement? |
| Evidence | Could evidence be lost? |
| Reporting | Is prompt carrier notice needed? |
| Completeness | Is enough known to report responsibly? |

---

# Internal vs. External Information Boundary Standard

Information appropriate for carrier FNOL may differ from internal agency commentary.

## Carrier-Appropriate

- Facts
- Parties
- Damage
- Incident description
- Known injury
- Evidence
- Immediate actions
- Missing information

## Internal Only

- E&O concerns
- Coverage speculation
- Liability speculation
- Sales commentary
- Client blame
- Carrier criticism
- Private strategy
- Unsupported hypotheses

Do not insert internal speculation into a carrier-ready FNOL.

---

# Output Requirements

Use the following structure unless the user requests another format.

# First Notice of Loss Report

## 1. FNOL Readiness

**Status:** Ready / Conditionally Ready / Not Ready

**Urgency:** Routine / Time Sensitive / Urgent / High Severity

**Loss Type:** [Type]

---

## 2. Claim Summary

Provide a concise who / what / when / where / how narrative.

---

## 3. Insured Information

**Named Insured:**  
[ ]

**Primary Contact:**  
[ ]

**Phone:**  
[ ]

**Email:**  
[ ]

**Policy / Coverage:**  
[ ]

**Carrier:**  
[ ]

**Policy Number:**  
[ ]

---

## 4. Loss Information

**Date of Loss:**  
[ ]

**Time of Loss:**  
[ ]

**Date Reported:**  
[ ]

**Location:**  
[ ]

**Type of Loss:**  
[ ]

**Reported Cause / Circumstances:**  
[ ]

---

## 5. Parties Involved

| Party | Role | Contact | Injury / Damage | Notes |
|---|---|---|---|---|
| [Party] | [Role] | [Contact] | [Details] | [Notes] |

---

## 6. Known Injury Information

Where applicable:

- Injured party
- Reported injury
- Medical treatment
- Work status
- Emergency response

Use only known information.

---

## 7. Known Property / Vehicle Damage

| Property / Vehicle | Owner | Damage | Current Location / Condition | Estimate |
|---|---|---|---|---|
| [Item] | [Owner] | [Damage] | [Status] | [If known] |

---

## 8. Emergency / Mitigation Actions

List actions already taken.

Examples:

- Emergency services contacted
- Water shut off
- Towing arranged
- Property secured
- Temporary mitigation initiated

---

## 9. Authorities / Reports

**Police:** [Yes / No / Unknown]  
**Police Report #:** [ ]  
**Fire Department:** [ ]  
**Other Authority:** [ ]

---

## 10. Evidence Available

- Photos
- Video
- Witnesses
- Incident report
- Police report
- Contract
- Estimates
- Other

---

## 11. Missing / Incomplete Information

| Priority | Missing Information | Why It Matters | Owner |
|---|---|---|---|
| Critical / Important / Supplemental | [Item] | [Reason] | [Owner] |

---

## 12. Issues Requiring Adjuster Review

Examples:

- Liability
- Coverage
- Cause
- Damages
- Injury severity
- Third-party responsibility

Do not resolve these at FNOL.

---

## 13. Recommended Next Steps

| Priority | Action | Owner | Timing |
|---|---|---|---|
| 1 | [Action] | [Owner] | [Timing] |

---

## 14. Claim Reporting Status

**Carrier Notified:** Yes / No / Unknown  
**Date Submitted:** [ ]  
**Claim Number:** [ ]  
**Adjuster:** [ ]  
**Adjuster Contact:** [ ]  
**Next Update:** [ ]

---

# Carrier-Ready Narrative

Provide a concise narrative that can be pasted into a carrier FNOL portal or email.

Example structure:

> The insured reports that on [DATE] at approximately [TIME], [EVENT] occurred at [LOCATION]. [PARTIES] were involved. Known damage includes [DAMAGE]. Known injuries include [INJURY / NONE REPORTED / UNKNOWN]. [EMERGENCY RESPONSE] occurred. [AUTHORITIES] were contacted. Liability and coverage have not been determined. Additional information currently outstanding includes [ITEMS].

---

# Assumptions & Items Requiring Confirmation

Use only when necessary.

| Assumption / Unclear Item | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Item] | [Reason] | High / Moderate / Low | [Action] |

Do not place assumptions into the carrier narrative as facts.

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Correct insured is identified
- [ ] Loss type is identified where possible
- [ ] Who / what / when / where / how are addressed
- [ ] Date of loss is documented or flagged missing
- [ ] Date reported is documented
- [ ] Location is documented or flagged missing
- [ ] Parties are separated clearly
- [ ] Allegations are attributed
- [ ] Injury information is neutral
- [ ] Property damage is accurately described
- [ ] Emergency action is documented
- [ ] Authorities are documented where applicable
- [ ] Evidence is identified
- [ ] Missing information is prioritized
- [ ] Critical missing items are not silently assumed
- [ ] FNOL readiness is stated
- [ ] Urgency is stated
- [ ] No liability conclusion is made
- [ ] No coverage determination is made
- [ ] No medical diagnosis is made
- [ ] Internal speculation is excluded from carrier-ready output
- [ ] Next steps have owners
- [ ] Reporting status is clear
- [ ] Completion criteria are satisfied

---

# Failure Conditions

The Skill should not be considered complete if:

- The output simply repeats the raw notes
- Core loss facts are not organized
- Missing information is invented
- Conflicting facts are silently reconciled
- Fault is assigned without authority
- Coverage is assumed
- Injury severity is exaggerated or diagnosed
- Claimant allegations are presented as fact
- Urgent mitigation needs are ignored
- Material missing information is not identified
- Submission readiness is not evaluated
- No next actions are provided
- Ownership is unclear
- Carrier reporting status is unclear
- The FNOL narrative includes internal speculation

If any failure condition exists, revise or escalate.

---

# Guardrails

## Do Not Fabricate Claim Facts

Never invent:

- Date
- Time
- Location
- Cause
- Injury
- Damage
- Parties
- Witnesses
- Policy
- Carrier
- Police report
- Claim number
- Adjuster
- Coverage

---

## Do Not Determine Fault

FNOL should not state fault unless formally established.

Use neutral language.

---

## Do Not Determine Coverage

Never state:

- This is covered
- This will be paid
- Coverage definitely applies
- Coverage definitely does not apply

unless an authorized determination has already been made.

---

## Do Not Diagnose Injuries

Record only what is reported.

---

## Do Not Advise Unsafe Action

Do not direct clients to:

- Enter dangerous buildings
- Touch electrical hazards
- Confront claimants
- Move unsafe equipment
- Disturb hazardous materials

Emergency safety comes first.

---

## Do Not Admit Liability

Avoid statements that create unnecessary admissions.

Report facts.

---

## Protect Sensitive Information

Use only information necessary for claim reporting.

Avoid unnecessary exposure of:

- Social Security numbers
- Medical records
- Driver license numbers
- Financial account information
- Sensitive employee data
- Credentials

Use secure channels where required.

---

## Preserve Human Accountability

This Skill supports the insurance professional.

The authorized insurance professional, carrier, adjuster, claims advocate, legal counsel, or other appropriate party remains responsible for:

- Claim submission
- Coverage review
- Liability determination
- Investigation
- Settlement
- Regulatory reporting
- Legal escalation
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced claims intake specialist.

The tone should be:

- Neutral
- Factual
- Clear
- Structured
- Concise
- Professional
- Claims-oriented
- Non-accusatory

Avoid:

- Emotional language
- Blame
- Liability conclusions
- Coverage conclusions
- Excessive narrative
- Internal commentary
- Unsupported certainty

The report should be easy for a claims professional to scan quickly.

---

# Example

## Example Request

```text
Notes:

Client called Monday morning.

One of their plumbers was driving company Ford Transit on Friday afternoon around 4:15 in Reno near McCarran and Longley.

Employee says traffic stopped suddenly and he rear-ended a Toyota Camry.

Police came.

Ford has front-end damage and was towed to ABC Towing.

Toyota driver said neck hurt and ambulance checked her but client doesn't know if she went to hospital.

Employee says he's fine.

Client thinks Toyota may have two passengers but isn't sure.

Has photos and police exchange sheet.

No claim submitted yet.

Policy is with Carrier A.
```

---

## Example Output

# First Notice of Loss Report

## 1. FNOL Readiness

**Status:** Conditionally Ready  
**Urgency:** Time Sensitive  
**Loss Type:** Commercial Auto

---

## 2. Claim Summary

The insured reports that on Friday at approximately 4:15 p.m., an employee driving a company-owned Ford Transit was involved in a rear-end collision with a Toyota Camry near McCarran Boulevard and Longley Lane in Reno, Nevada.

The insured vehicle reportedly sustained front-end damage and was towed to ABC Towing.

The driver of the Toyota reportedly complained of neck pain and was evaluated by emergency medical personnel at the scene. It is not yet known whether additional treatment occurred.

Police responded to the accident.

Liability, injury severity, and total damages have not been determined.

---

## 3. Key Claim Details

**Insured:** [Client Name]  
**Carrier:** Carrier A  
**Policy Number:** Not provided  
**Loss Type:** Commercial Auto  
**Date of Loss:** Friday — exact date required  
**Time:** Approximately 4:15 p.m.  
**Location:** Near McCarran Blvd. and Longley Ln., Reno, Nevada

### Insured Vehicle

**Vehicle:** Ford Transit  
**Driver:** Employee — name required  
**Damage:** Front-end damage  
**Location:** ABC Towing

### Third Party

**Vehicle:** Toyota Camry  
**Driver:** Name required  
**Reported Injury:** Neck pain  
**Medical Response:** Evaluated at scene  
**Hospital Treatment:** Unknown

### Additional Occupants

Possible additional passengers were reported, but number and injury status are unconfirmed.

---

## 4. Evidence Available

- Photos
- Police exchange sheet

---

## 5. Missing / Incomplete Information

| Priority | Missing Information | Why It Matters |
|---|---|---|
| Critical | Exact date of loss | Required for claim setup |
| Important | Employee driver's name | Claim identification |
| Important | Policy number | Carrier claim reporting |
| Important | Third-party driver contact | Adjuster follow-up |
| Important | Number of Toyota occupants | Potential injury exposure |
| Important | Medical treatment status | Severity assessment |
| Supplemental | Police report number | Investigation support |

---

## 6. Recommended Next Steps

| Priority | Action | Owner |
|---|---|---|
| 1 | Submit FNOL to Carrier A using available information | Agency |
| 2 | Obtain exact date of loss and employee driver information | Client |
| 3 | Forward photos and police exchange sheet | Client / Agency |
| 4 | Record claim number when issued | Agency |
| 5 | Confirm adjuster assignment | Carrier / Agency |
| 6 | Provide supplemental claimant information when available | Client |

---

## Carrier-Ready Narrative

The insured reports that an employee operating a company-owned Ford Transit was involved in a rear-end collision with a Toyota Camry at approximately 4:15 p.m. near McCarran Boulevard and Longley Lane in Reno, Nevada. The insured vehicle sustained reported front-end damage and was towed to ABC Towing. The Toyota driver reportedly complained of neck pain and was evaluated by emergency medical personnel at the scene. Additional treatment is unknown. Police responded. The insured has photos and a police exchange sheet available. Liability and injury severity have not been determined. Exact loss date, driver information, third-party contact information, and possible passenger information remain outstanding.

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are an experienced insurance claims intake specialist responsible for preparing a clean, accurate First Notice of Loss (FNOL) report from raw intake notes.
>
> Review the information below and convert it into a structured FNOL report that could be reviewed by a carrier, adjuster, or internal claims team. Focus on clarity, completeness, and identifying any missing or unclear information.
>
> Notes:
> [INSERT]
>
> Organize the information logically and avoid simply repeating the notes. Where details are incomplete or ambiguous, clearly identify the gaps.
>
> Structure your response as:
>
> - Claim summary (who, what, when, where, and how the loss occurred)
> - Key claim details (parties involved, type of loss, location, dates, and any known damages)
> - Missing or incomplete information that should be obtained
> - Recommended next steps to move the claim forward
>
> Keep the report clean, professional, and ready for immediate use.

---

# Evolution From Prompt to Skill

The original prompt established the goal of converting raw claim notes into a clean First Notice of Loss.

This Skill expands that prompt into a reusable Claims Intelligence workflow by adding:

- Structured claim intake
- Document Completeness Standard
- Source hierarchy
- Evidence classification
- Confidence classification
- Execution readiness
- Claim workflow states
- Time-sensitive claim handling
- Insured / party identification
- Injury intake
- Property damage intake
- Vehicle loss intake
- Workers' Compensation intake
- Emergency mitigation review
- Mitigation vs. Repair Standard
- Evidence preservation
- Neutral Narrative Standard
- Missing-information prioritization
- Claim urgency classification
- Human Review Escalation Standard
- Ownership Standard
- Update Cadence Standard
- Stop rules
- Completion Criteria Standard
- Data Integrity Standard
- Data Normalization Standard
- Internal vs. External Information Boundary Standard
- Carrier-ready FNOL narrative
- Quality-control checklist
- Failure conditions
- Insurance-specific guardrails
- Example implementation

The purpose is to transform a claim-intake prompt into a reusable **Claims Intake Intelligence Skill** capable of supporting future AI Teammate execution.

---

# Related Skills

Related Apeironix Skills include:

- [Commercial Insurance Client Situation Communication](../14-client-situation-communication/SKILL.md)
- [Commercial Insurance Client Service Response](../15-client-service-response/SKILL.md)
- Claims Status Communication
- Claims Escalation
- Loss Run Analysis
- Claim Documentation Request
- Workers' Compensation Claim Intake
- Commercial Auto Claim Intake
- Property Claim Intake

Links should be added as those Skills are published.

---

# Suggested Invocation

```text
Prepare a Commercial Insurance First Notice of Loss.

Client:
[OPTIONAL]

Policy / Carrier:
[OPTIONAL]

Notes:
[INSERT]

Supporting Information:
[OPTIONAL]

Current Claim Status:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Notes:
[INSERT]
```

---

# Version History

## 1.0.0

Initial public release using the Apeironix Gold Standard Template v2.1.

Enhancements from the original Prompt #16 include:

- FNOL readiness classification
- Claim urgency classification
- Evidence classification
- Neutral claim narrative
- Missing-information prioritization
- Injury and damage intake
- Evidence preservation
- Mitigation review
- Human escalation
- Workflow states
- Ownership
- Update cadence
- Stop rules
- Completion criteria
- Data integrity controls
- Internal/external information boundary
- Carrier-ready narrative
- Quality-control standards
- Claims-specific guardrails
- Example implementation

---

# About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for:

- Judgment
- Relationships
- Client service
- Claims advocacy
- Risk advisory
- Analysis
- Communication
- Growth

while AI handles more of the repetitive work surrounding those responsibilities.

Apeironix is building an AI Operating Layer designed to work alongside the systems insurance agencies already use.

### Your people make the decisions. Your AI Teammates do the work.

**Keep your systems. Activate an AI Workforce.**

Learn more at [Apeironix.com](https://apeironix.com).

---

# License

This Skill is made available under the Apache License 2.0.

See the repository `LICENSE` file for complete terms.
