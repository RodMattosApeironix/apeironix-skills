---
name: claim-severity-assessment
title: Commercial Insurance Claim Severity Assessment
collection: ai-insurance-automation-guide
prompt_number: 17
category: commercial-pc
capability: claims-intelligence
primary_role: insurance-claims-analyst
secondary_roles:
  - commercial-account-manager
  - commercial-account-executive
  - claims-advocate
  - commercial-insurance-producer
  - risk-advisor
template_version: 2.1
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Commercial Insurance Claim Severity Assessment

## Purpose

Evaluate a reported commercial insurance claim to determine its apparent severity, potential financial exposure, escalation risks, and recommended immediate and short-term actions.

This Skill is designed to help the insurance professional:

- Summarize the claim clearly
- Assess apparent claim severity
- Identify potential financial exposure
- Identify injury severity indicators
- Identify third-party liability concerns
- Surface legal or regulatory risk
- Identify coverage uncertainty without making a coverage determination
- Detect factors that could escalate the claim
- Prioritize next actions
- Determine whether heightened claims advocacy or human escalation is warranted
- Help account managers and claims advocates focus attention on the losses that need it most

The objective is **not** to predict the final claim value or determine liability.

The objective is to answer:

> How serious could this claim become, what should we be watching, and what should we do now?

---

# Core Outcome

A successful use of this Skill should allow an insurance professional to understand:

- What happened
- Who is involved
- How severe the claim currently appears
- What factors drive severity
- What factors could increase financial exposure
- Whether bodily injury exists
- Whether third parties are involved
- Whether litigation or attorney involvement exists
- Whether business interruption or operational disruption exists
- Whether coverage questions need to be escalated
- Whether the claim could implicate excess or umbrella coverage
- What information is still missing
- What immediate actions should occur
- What short-term monitoring should occur

The output should support **claims triage, escalation, and advocacy**.

---

# Best Used For

Use this Skill when evaluating:

- Commercial Auto claims
- General Liability claims
- Property claims
- Workers' Compensation claims
- Product Liability claims
- Professional Liability matters
- Cyber incidents
- Employment Practices claims
- Pollution incidents
- Crime losses
- Inland Marine losses
- Umbrella / Excess notices
- Serious bodily injury claims
- Large property losses
- Multi-party losses
- Claims involving attorneys
- Claims involving litigation
- Potential catastrophic losses
- Claims with uncertain exposure
- Claims that may require heightened agency advocacy

This Skill is especially useful after FNOL and before or during early adjuster handling.

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- Carrier claim reserving
- Formal valuation
- Liability determination
- Coverage determination
- Legal advice
- Medical evaluation
- Workers' Compensation compensability determination
- Settlement authority
- Actuarial analysis
- Claim denial
- Regulatory reporting
- Litigation strategy
- Formal excess-carrier reporting

This is a **claims severity and exposure decision-support Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Insurance Claims Analysts
- Commercial Account Managers
- Commercial Account Executives
- Claims Advocates
- Commercial Insurance Producers
- Risk Advisors
- Agency Claims Leaders
- Other authorized insurance professionals

---

# Required Inputs

At minimum, provide:

1. **Claim details**

Recommended format:

```text
Claim Details:
[INSERT]
```

The information may come from:

- FNOL
- Claim notes
- Carrier correspondence
- Adjuster notes
- Client email
- Incident report
- Loss summary
- Attorney letter
- Agency case notes

Do not invent missing claim facts.

---

# Recommended Inputs

The following information materially improves the assessment:

- Claim type
- Carrier
- Policy
- Policy period
- Date of loss
- Date reported
- Claim number
- Adjuster
- Loss location
- Description of event
- Parties involved
- Injury information
- Property damage
- Estimated damages
- Reserve information
- Paid amount
- Outstanding reserve
- Medical treatment
- Hospitalization
- Lost time
- Attorney involvement
- Lawsuit status
- Demand amount
- Police report
- Witnesses
- Video or photos
- Business interruption
- Mitigation status
- Vehicle information
- Product information
- Contract information
- Potential additional insureds
- Coverage issues
- Excess or umbrella structure
- Subrogation potential
- Regulatory involvement
- Media attention
- Client concerns
- Adjuster concerns

---

# Preferred Source Documents

Where available, prioritize:

1. Current carrier claim information
2. FNOL
3. Adjuster correspondence
4. Official incident report
5. Police / fire / emergency documentation
6. Attorney correspondence
7. Medical-status information appropriate for claim handling
8. Repair / mitigation documentation
9. Client-confirmed information
10. Photos / video
11. Agency notes

Do not treat internal speculation as carrier-confirmed claim information.

---

# Document Completeness Standard

Where documents are supplied, classify the claim information as:

### Complete Enough for Preliminary Severity Assessment

Enough information exists to form a responsible early assessment.

### Partially Complete

A useful preliminary assessment is possible, but material information remains missing.

### Fragmentary

The available information is too limited for meaningful severity assessment.

Severity assessment at an early stage is inherently provisional.

Do not present early-stage conclusions as final.

---

# Source Hierarchy

When information conflicts, prioritize:

1. Current carrier / adjuster information
2. Official incident documentation
3. Direct client-confirmed facts
4. Legal correspondence
5. Direct witness or claimant information
6. Agency records
7. Professional inference

When material facts conflict:

- Identify the discrepancy
- Do not silently reconcile it
- Treat the issue as unresolved
- Identify who should confirm it

---

# Evidence Classification

Every material assessment statement should be treated as one of the following.

## Confirmed Fact

Directly supported by authoritative information.

Example:

> The claimant was hospitalized overnight.

---

## Reported Allegation

A statement made by a claimant, attorney, witness, or other party.

Example:

> The claimant's attorney alleges permanent impairment.

---

## Observed Claim Development

A claim-handling fact or trend.

Example:

> The claim has moved from emergency treatment to specialist care.

---

## Calculated Exposure Indicator

A derived measure based on available information.

Example:

> Current paid plus outstanding reserve totals $425,000.

---

## Severity Inference

A professional assessment based on available facts.

Example:

> The combination of surgery, lost time, and attorney representation creates elevated severity potential.

---

## Requires Investigation

A material issue that cannot yet be resolved.

---

## Requires Coverage Review

A potential coverage issue that should be evaluated by the appropriate authority.

---

# Confidence Classification

Where useful:

### High Confidence

Severity indicator is strongly supported by reliable claim information.

### Moderate Confidence

Assessment is reasonable but material information remains unresolved.

### Low Confidence

Claim development is too immature or ambiguous to support a reliable conclusion.

---

# Core Principle

## Severity Is Driven by More Than the Initial Damage Estimate

Claim severity should consider:

- Injury
- Liability
- Legal involvement
- Financial exposure
- Business impact
- Coverage uncertainty
- Number of parties
- Claim trajectory
- Potential excess involvement
- Escalation indicators

A claim that looks small at first notice may develop into a serious loss.

---

# Execution Readiness Standard

Before issuing a severity assessment, classify the information as:

### Ready for Preliminary Assessment

Enough information exists to identify meaningful severity indicators.

### Conditionally Ready

A preliminary assessment is possible but one or more major factors remain unknown.

### Not Ready

The available information is too limited to assess severity responsibly.

Do not assign a high-confidence severity level simply because the Skill requires one.

---

# Time Horizon / Execution Feasibility Standard

Claim severity evolves over time.

Identify:

- Time since loss
- Time since first report
- Stage of medical treatment
- Stage of litigation
- Stage of property repair
- Stage of investigation
- Current reserve development
- Time until major claim milestone

A newly reported claim should not be assessed using the same certainty as a mature claim.

---

# Workflow State Standard

Relevant claim states may include:

1. FNOL Received
2. Carrier Acknowledged
3. Adjuster Assigned
4. Investigation
5. Treatment / Repair Ongoing
6. Liability Under Review
7. Coverage Under Review
8. Attorney Involved
9. Litigation
10. Demand Received
11. Negotiation
12. Excess Notification
13. Resolution Pending
14. Closed
15. Reopened

Do not confuse claim stage with claim severity.

---

# Workflow

## Step 1 — Identify the Claim Type

Determine the primary claim category:

- Auto
- General Liability
- Property
- Workers' Compensation
- Product Liability
- Cyber
- EPLI
- Professional Liability
- Pollution
- Crime
- Other

Claim type helps determine relevant severity indicators.

---

## Step 2 — Summarize the Claim

Create a concise summary including:

- Who
- What
- When
- Where
- How
- Known damage
- Known injury
- Current status

Keep factual narrative separate from interpretation.

---

## Step 3 — Identify Bodily Injury Exposure

Where applicable, assess:

- Number of injured persons
- Injury type
- Emergency treatment
- Hospitalization
- Surgery
- Specialist treatment
- Lost time
- Permanent impairment allegation
- Fatality
- Minor involvement
- Future medical treatment
- Attorney involvement

Do not diagnose.

---

# Bodily Injury Severity Indicators

Potential escalation indicators include:

- Fatality
- Brain injury
- Spinal injury
- Paralysis
- Amputation
- Burns
- Multiple fractures
- Surgery
- Hospitalization
- Permanent impairment
- Long-term disability
- Multiple claimants
- Child claimant
- Significant wage loss
- Large future medical exposure

These are severity indicators, not valuation conclusions.

---

## Step 4 — Identify Property Severity

Assess:

- Total damage
- Critical equipment
- Building damage
- Inventory loss
- Business personal property
- Vehicle damage
- Environmental damage
- Business interruption
- Temporary relocation
- Repair duration
- Replacement lead time
- Mitigation costs

A modest physical damage number may still create major business interruption.

---

## Step 5 — Identify Business Interruption Exposure

Determine whether:

- Operations stopped
- Revenue is affected
- Key location is unavailable
- Critical equipment is down
- Supply chain is disrupted
- Customers are affected
- Extra expense is occurring

Business impact may materially increase severity.

---

## Step 6 — Identify Third-Party Exposure

Determine:

- Number of third parties
- Bodily injury
- Property damage
- Customer impact
- Contractual relationships
- Additional insured involvement
- Claimant sophistication
- Attorney involvement

Multi-party claims often create increased complexity.

---

## Step 7 — Evaluate Liability Complexity

Identify factors such as:

- Clear liability
- Disputed liability
- Comparative fault
- Multiple defendants
- Contractual allocation
- Subcontractor involvement
- Product responsibility
- Premises control
- Vehicle ownership
- Employee scope of work

Do not determine final liability.

---

# Liability Concern Standard

Classify liability when useful as:

### Apparently Favorable

Available facts may support a defensible position.

### Mixed / Unclear

Material liability facts remain disputed.

### Apparently Adverse

Available facts suggest meaningful exposure.

### Requires Investigation

Insufficient information.

Do not use these labels as formal liability determinations.

---

## Step 8 — Identify Legal Escalation Indicators

Examples:

- Attorney representation
- Demand letter
- Lawsuit
- Preservation letter
- Subpoena
- Government investigation
- Regulatory notice
- Reservation of rights
- Coverage counsel
- Mediation
- Arbitration

These may materially change claim handling.

---

## Step 9 — Identify Coverage Uncertainty

Look for:

- Late notice
- Unscheduled location
- Unscheduled vehicle
- Excluded activity
- Contractual issue
- Prior-known circumstance
- Claims-made reporting question
- Policy period issue
- Other-insurance issue
- Umbrella attachment issue

Do not resolve coverage.

Flag:

> Requires carrier / coverage review.

---

## Step 10 — Identify Excess / Umbrella Exposure

Determine whether:

- Current reserve approaches primary limits
- Severity could exceed primary limits
- Multiple claimants could erode limits
- Defense costs affect limits
- Umbrella or excess notice requirements may apply
- Contractual limits create concern

Do not wait until a claim actually exceeds primary limits before considering excess notification.

---

# Excess Notification Trigger Standard

Where available information suggests a reasonable possibility that a claim could approach underlying limits:

- Flag excess / umbrella notification for review
- Identify current limits if known
- Identify reserve or severity indicators
- Recommend timely human review

Do not make a formal excess-notice determination unless authorized.

---

## Step 11 — Identify Financial Exposure

Where available, capture:

- Paid amount
- Outstanding reserve
- Total incurred
- Property estimate
- Medical cost
- Demand amount
- Wage loss
- Legal expense
- Business interruption
- Remediation costs

Do not invent a claim value.

---

## Step 12 — Evaluate Claim Development

Look for signs the claim is worsening.

Examples:

- Increasing medical treatment
- Surgery recommendation
- New claimant
- Attorney retention
- Increasing reserve
- Litigation
- New business interruption
- Expanded property damage
- Coverage dispute
- Regulatory involvement

Also identify positive development where appropriate.

---

# Claim Trajectory Standard

Classify when useful:

### Improving

Exposure appears to be stabilizing or reducing.

### Stable

No meaningful severity change identified.

### Developing

New information continues to materially affect exposure.

### Deteriorating

Severity indicators are increasing.

### Indeterminate

Insufficient information.

Severity level and claim trajectory are separate concepts.

---

## Step 13 — Identify Subrogation / Recovery Potential

Where relevant, determine whether another party may bear responsibility.

Examples:

- Other driver
- Manufacturer
- Contractor
- Vendor
- Property owner
- Utility
- Equipment manufacturer

Do not make final recovery determinations.

Flag preservation needs when relevant.

---

## Step 14 — Identify Evidence Preservation Needs

Potential evidence includes:

- Vehicle
- Equipment
- Product
- Surveillance video
- Photos
- Contracts
- Logs
- Electronic data
- Employee records
- Maintenance records
- Telematics
- Security data

Material evidence should not be lost during early claim handling.

---

## Step 15 — Identify Severity Escalation Factors

Potential factors:

- Fatality
- Severe injury
- Multiple claimants
- Child claimant
- Attorney involvement
- Litigation
- Media attention
- Regulatory investigation
- Major business interruption
- Environmental damage
- Catastrophic property damage
- Coverage uncertainty
- Potential excess involvement
- High-profile claimant
- Contractual indemnification dispute
- Fraud concern

---

## Step 16 — Assign Severity

Use one of the following:

### Low

Characteristics may include:

- Minor damage
- No significant injury
- Limited third-party exposure
- No legal involvement
- Clear handling path
- Low escalation potential

### Moderate

Characteristics may include:

- Meaningful property damage
- Non-catastrophic injury
- Some liability uncertainty
- Limited attorney involvement
- Potential for additional development

### High

Characteristics may include:

- Serious bodily injury
- Significant financial exposure
- Attorney representation
- Litigation
- Major property loss
- Significant business interruption
- Multiple parties
- Potential excess involvement
- Material coverage uncertainty

### Critical

Characteristics may include:

- Fatality
- Catastrophic bodily injury
- Multiple severe injuries
- Large-scale property destruction
- Major environmental event
- Significant cyber event
- Severe business interruption
- High likelihood of excess involvement
- Government or media attention
- Potentially catastrophic financial exposure

Severity is an early triage assessment, not a final valuation.

---

# Severity Rationale Standard

Every severity assignment should identify:

1. Primary severity driver
2. Secondary severity driver
3. Key uncertainty
4. Escalation factor
5. Reason the claim is not classified one level higher or lower, where useful

Avoid assigning severity solely from total incurred.

---

## Step 17 — Identify Key Risk Flags

Potential categories:

- Bodily injury
- Fatality
- Attorney involvement
- Litigation
- Multiple claimants
- Third-party exposure
- Coverage uncertainty
- Excess exposure
- Business interruption
- Environmental issue
- Regulatory issue
- Media risk
- Contractual liability
- Subrogation
- Evidence preservation
- Claim delay
- Reserve development
- Fraud indicators

Include only material flags.

---

## Step 18 — Determine Immediate Actions

Potential immediate actions:

- Confirm carrier notice
- Escalate to claims advocate
- Contact adjuster
- Notify excess carrier
- Preserve evidence
- Forward attorney correspondence
- Obtain medical-status update
- Obtain repair / mitigation information
- Confirm business interruption
- Obtain police report
- Confirm client contact
- Coordinate emergency services

Immediate means time-sensitive.

---

## Step 19 — Determine Short-Term Actions

Potential actions over the next several days or weeks:

- Monitor reserve
- Review adjuster plan
- Confirm liability investigation
- Obtain claimant status
- Review contractual obligations
- Track treatment
- Review repair progress
- Evaluate subrogation
- Confirm umbrella reporting
- Schedule client update
- Escalate unresolved coverage issue

---

## Step 20 — Assign Ownership

For each action, identify the owner:

- Agency
- Claims advocate
- Adjuster
- Carrier
- Client
- Legal counsel
- Vendor
- Other party

---

## Step 21 — Establish Monitoring Triggers

Define what developments should trigger reassessment.

Examples:

- Surgery
- Attorney retention
- Lawsuit
- Demand
- Reserve increase
- New claimant
- Fatality
- Business interruption extension
- Coverage reservation
- Excess notification
- Regulatory involvement

---

# Monitoring Trigger Standard

Claims should be reassessed when material facts change.

A prior "moderate" severity rating should not remain static if:

- Medical treatment escalates
- Reserve increases materially
- Litigation begins
- Business interruption expands
- Coverage questions emerge

Severity is a **dynamic state**, not a permanent label.

---

# Data Integrity Standard

Before finalizing, review for:

- Conflicting dates
- Conflicting injury information
- Reserve inconsistencies
- Duplicate claimants
- Outdated claim information
- Paid vs. reserve confusion
- Incorrect limits
- Missing policy layer information

Do not silently reconcile material inconsistencies.

---

# Calculation Integrity Standard

When using financial values:

- Distinguish paid
- Distinguish outstanding reserve
- Distinguish total incurred
- Identify demand amount separately
- Do not treat demand as expected settlement
- Do not treat reserve as final claim value
- Identify currency and period where relevant

---

# Authority vs. Inference Standard

Distinguish clearly between:

### Carrier / Adjuster Determination

Formal claim position.

### Claim Facts

Documented information.

### AI Severity Assessment

Triage analysis based on available information.

### Professional Recommendation

Recommended agency or claims-advocacy action.

### Decision Authority

Carrier, adjuster, claims counsel, legal counsel, or other authorized party.

The Skill does not become the claims authority simply because it identifies risk.

---

# Neutral Narrative Standard

Use attribution for disputed or unverified information.

Examples:

> The claimant alleges...

> The insured reports...

> The adjuster notes...

> Counsel asserts...

Do not transform allegations into facts.

---

# Human Review Escalation Standard

Require elevated human review for:

- Fatality
- Catastrophic bodily injury
- Child claimant
- Multiple severe injuries
- Major property loss
- Major business interruption
- Environmental event
- Significant cyber event
- Lawsuit
- Attorney demand
- Government investigation
- Media attention
- Coverage dispute
- Potential uninsured exposure
- Potential excess penetration
- Reservation of rights involving material exposure
- Major client dissatisfaction with claim handling

AI may identify and organize the issue.

Authorized claims professionals should direct the response.

---

# Update Cadence Standard

For high or critical claims, define a monitoring cadence.

Potential examples:

- At every material claim development
- Weekly during active severe injury treatment
- Upon reserve increase
- Upon legal development
- Upon coverage position
- Upon excess notification
- Prior to client claim-review meetings

Avoid unnecessary status reporting when nothing material has changed.

---

# Stop Rules

Severity assessment should move to monitoring when:

- Initial severity is assigned
- Material risk flags are identified
- Immediate actions are assigned
- Short-term actions are assigned
- Monitoring triggers are defined

Reassess when new material facts emerge.

Do not repeatedly reassess without new information.

---

# Completion Criteria Standard

The preliminary severity assessment is complete when:

1. Claim summary is documented
2. Severity level is assigned
3. Severity rationale is stated
4. Key risk flags are identified
5. Coverage uncertainty is flagged where applicable
6. Potential excess exposure is considered
7. Immediate actions are defined
8. Short-term actions are defined
9. Owners are assigned
10. Monitoring triggers are established
11. Human escalation is identified where required

Claim-resolution completion is outside the scope of this Skill.

---

# Decision Rules

## Severity Is Not the Same as Reserve

Reserve is one indicator.

Do not use it as the sole severity measure.

---

## Demand Is Not Claim Value

A claimant demand is a position, not a final valuation.

---

## Serious Injury Requires Escalation

Do not wait for a large reserve to recognize severity.

---

## Coverage Uncertainty Increases Complexity

But does not automatically mean coverage is unavailable.

---

## Liability Must Remain Neutral

Do not make final fault determinations.

---

## Claim Trajectory Matters

A developing claim may require more attention than a currently larger but stable claim.

---

## Excess Exposure Should Be Considered Early

Do not wait until underlying limits are exhausted.

---

## Facts Before Assumptions

Label inference clearly.

---

# Materiality / Prioritization Framework

Prioritize claim issues using:

| Factor | Question |
|---|---|
| Bodily Injury | Is serious injury present or possible? |
| Financial Exposure | Could the claim create substantial cost? |
| Liability | Is fault disputed or adverse? |
| Legal | Is counsel or litigation involved? |
| Third Party | Are multiple or sophisticated claimants involved? |
| Business Impact | Are operations disrupted? |
| Coverage | Is there uncertainty or potential gap? |
| Excess | Could underlying limits be approached? |
| Regulatory | Is government involvement possible? |
| Claim Trajectory | Is exposure increasing? |
| Evidence | Could key evidence be lost? |
| Urgency | Does immediate action matter? |

---

# Output Requirements

Use the following structure unless the user requests another format.

# Commercial Claim Severity Assessment

## 1. Assessment Readiness

**Status:** Ready / Conditionally Ready / Not Ready

**Claim Stage:** [Stage]

**Assessment Confidence:** High / Moderate / Low

---

## 2. Claim Summary

Provide a concise factual summary.

---

## 3. Severity Assessment

**Severity:** Low / Moderate / High / Critical

### Primary Reason

[Reason]

### Secondary Factors

- [Factor]
- [Factor]

### Key Uncertainty

[Unresolved issue]

### Claim Trajectory

Improving / Stable / Developing / Deteriorating / Indeterminate

---

## 4. Financial Exposure Snapshot

Where available:

**Paid:** [ ]  
**Outstanding Reserve:** [ ]  
**Total Incurred:** [ ]  
**Demand:** [ ]  
**Estimated Property Damage:** [ ]  
**Business Interruption:** [ ]

Do not invent values.

---

## 5. Key Risk Flags

| Risk Flag | Status | Why It Matters | Priority |
|---|---|---|---|
| Bodily Injury | [ ] | [ ] | High / Medium / Low |
| Legal | [ ] | [ ] | [ ] |
| Coverage | [ ] | [ ] | [ ] |
| Excess | [ ] | [ ] | [ ] |

Include only relevant flags.

---

## 6. Liability / Third-Party Considerations

Summarize:

- Parties
- Liability complexity
- Claimant involvement
- Contractual issues
- Other responsible parties

Remain neutral.

---

## 7. Coverage / Policy Issues Requiring Review

List any issues that should be evaluated by the appropriate authority.

Do not determine coverage.

---

## 8. Potential Excess / Umbrella Concern

**Status:** No Current Indicator / Monitor / Review for Notice / Significant Concern

Explain why.

---

## 9. Immediate Actions

| Priority | Action | Owner | Timing |
|---|---|---|---|
| 1 | [Action] | [Owner] | Immediate |

---

## 10. Short-Term Actions

| Action | Owner | Target Timing | Trigger / Objective |
|---|---|---|---|
| [Action] | [Owner] | [Timing] | [Objective] |

---

## 11. Monitoring Triggers

Reassess severity if:

- [Trigger]
- [Trigger]
- [Trigger]

---

## 12. Claims Advocate Perspective

Provide a concise internal summary answering:

- What should we watch most closely?
- Where could the claim deteriorate?
- What should the agency make sure does not get missed?

This section is internal.

---

# Assumptions & Items Requiring Confirmation

| Assumption / Unknown | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Item] | [Reason] | High / Moderate / Low | [Action] |

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Claim type is understood
- [ ] Claim stage is identified
- [ ] Facts are separated from allegations
- [ ] Injury severity is considered
- [ ] Property severity is considered
- [ ] Business interruption is considered
- [ ] Third-party exposure is considered
- [ ] Liability complexity is considered
- [ ] Attorney / litigation status is considered
- [ ] Coverage uncertainty is identified but not resolved
- [ ] Excess exposure is considered
- [ ] Paid / reserve / incurred values are distinguished
- [ ] Demand is not treated as claim value
- [ ] Claim trajectory is evaluated
- [ ] Severity level is supported
- [ ] Severity rationale is explicit
- [ ] Monitoring triggers are defined
- [ ] Immediate actions are specific
- [ ] Short-term actions are specific
- [ ] Owners are assigned
- [ ] Human escalation occurs where required
- [ ] No medical diagnosis is made
- [ ] No liability determination is made
- [ ] No coverage determination is made

---

# Failure Conditions

The Skill should not be considered complete if:

- Severity is assigned without reasoning
- Reserve is treated as final claim value
- Demand is treated as expected settlement
- Injury seriousness is ignored
- Claim trajectory is ignored
- Attorney involvement is ignored
- Third-party exposure is ignored
- Potential excess involvement is ignored
- Coverage uncertainty is turned into a coverage conclusion
- Liability is assigned without authority
- Allegations are presented as facts
- Immediate actions are missing
- Ownership is unclear
- Monitoring triggers are missing
- Critical claims are not escalated for human review

If any failure condition exists, revise or escalate.

---

# Guardrails

## Do Not Predict Final Claim Value

Do not state a definitive ultimate value unless provided by an authorized claims source.

---

## Do Not Determine Liability

Use neutral language.

---

## Do Not Determine Coverage

Coverage conclusions belong to authorized claims and coverage professionals.

---

## Do Not Diagnose Injury

Use only reported medical information.

---

## Do Not Treat Reserves as Facts About Ultimate Outcome

Reserves may change.

---

## Do Not Treat Demands as Settlement Value

A demand is a negotiating position.

---

## Do Not Overstate Severity

Severity should reflect available evidence.

Do not inflate claim concern simply because litigation exists.

---

## Do Not Understate Severity

Early low reserves do not eliminate catastrophic potential.

---

## Protect Sensitive Information

Use only information necessary for claim analysis.

Avoid unnecessary exposure of:

- Medical records
- SSNs
- Financial account data
- Driver license numbers
- Sensitive employee information
- Confidential legal communications

---

## Preserve Human Accountability

This Skill supports the insurance professional.

The authorized carrier, adjuster, claims advocate, legal counsel, or other appropriate professional remains responsible for:

- Liability determination
- Coverage determination
- Reserving
- Investigation
- Excess notice
- Legal strategy
- Settlement
- Client advice
- Regulatory reporting
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced claims analyst advising an account manager or claims advocate.

The tone should be:

- Objective
- Analytical
- Concise
- Practical
- Claims-focused
- Non-alarmist
- Action-oriented
- Neutral

Avoid:

- Dramatic language
- Blame
- Unsupported claim valuation
- Coverage conclusions
- Liability conclusions
- Excessive caution
- Long claim-note summaries

The output should help the claims team decide where to focus attention.

---

# Example

## Example Request

```text
Claim Details:

Commercial auto claim.

Employee driving company pickup rear-ended another vehicle at highway speed.

Loss occurred three weeks ago.

Third-party driver was transported by ambulance and later underwent cervical surgery.

Claimant now has attorney.

Client says police report places insured driver at fault.

Carrier currently has $250,000 bodily injury reserve.

Auto liability limit is $1,000,000.

Client also has $5,000,000 umbrella.

No lawsuit yet.

Claimant attorney has requested policy limits information.

Insured vehicle damage approximately $18,000.

No employee injury.
```

---

## Example Output

# Commercial Claim Severity Assessment

## 1. Assessment Readiness

**Status:** Ready for Preliminary Assessment  
**Claim Stage:** Active Investigation / Attorney Involved  
**Assessment Confidence:** Moderate

---

## 2. Claim Summary

The insured's employee was involved in a rear-end commercial auto collision approximately three weeks ago. The third-party driver was transported by ambulance and has subsequently undergone cervical surgery.

The claimant is now represented by counsel, and the attorney has requested policy-limit information.

The carrier currently maintains a $250,000 bodily injury reserve. The underlying auto liability limit is reported as $1 million, with a $5 million umbrella above it.

No lawsuit has been filed at this time.

---

## 3. Severity Assessment

**Severity: High**

### Primary Reason

The combination of cervical surgery and attorney representation creates meaningful bodily injury severity potential.

### Secondary Factors

- Reportedly adverse liability
- Policy-limit information request
- Potential future medical and wage-loss exposure
- Possibility of excess-layer involvement if damages develop significantly

### Key Uncertainty

Long-term medical prognosis, permanent impairment, wage loss, and claimant demand are not yet known.

### Claim Trajectory

**Developing**

The claim has progressed from initial emergency treatment to surgery and attorney involvement.

---

## 4. Financial Exposure Snapshot

**BI Reserve:** $250,000  
**Underlying Auto Limit:** $1,000,000  
**Umbrella:** $5,000,000  
**Insured Vehicle Damage:** Approximately $18,000  
**Claimant Demand:** Not yet reported

The current reserve should not be treated as the claim's final value.

---

## 5. Key Risk Flags

| Risk Flag | Status | Why It Matters | Priority |
|---|---|---|---|
| Serious Bodily Injury | Present | Cervical surgery materially increases severity potential | High |
| Attorney Involvement | Present | Indicates formal claim advocacy and potential demand development | High |
| Liability | Apparently adverse based on reported facts | May reduce defensibility if confirmed | High |
| Excess Exposure | Monitor / Review for Notice | Serious injury could develop toward underlying limits | High |
| Litigation | Not yet filed | Could increase cost and complexity if initiated | Medium |

---

## 6. Potential Excess / Umbrella Concern

**Status:** Review for Notice

Given the reported surgery, attorney representation, and apparently adverse liability, the agency should confirm whether the carrier has evaluated the claim for umbrella notification requirements.

This does not mean the claim will exceed the $1 million underlying limit.

It means the severity indicators justify early review.

---

## 7. Immediate Actions

| Priority | Action | Owner | Timing |
|---|---|---|---|
| 1 | Confirm adjuster is aware of cervical surgery | Claims Advocate / Adjuster | Immediate |
| 2 | Confirm umbrella notification status | Carrier / Claims Advocate | Immediate |
| 3 | Confirm police report and liability investigation | Adjuster | Immediate |
| 4 | Forward any attorney correspondence not already provided | Client / Agency | Immediate |

---

## 8. Short-Term Actions

| Action | Owner | Target Timing | Objective |
|---|---|---|---|
| Monitor medical development | Adjuster / Claims Advocate | Ongoing | Understand severity trajectory |
| Monitor reserve development | Claims Advocate | Next claim review | Identify material change |
| Confirm permanent impairment / wage loss status when available | Adjuster | As treatment develops | Evaluate exposure |
| Monitor for demand or lawsuit | Agency / Carrier | Ongoing | Trigger reassessment |

---

## 9. Monitoring Triggers

Reassess immediately if:

- Claimant submits a substantial demand
- Permanent impairment is alleged
- Additional surgery is recommended
- Reserve materially increases
- Lawsuit is filed
- Underlying carrier recommends excess notice
- Claimant alleges substantial lost earnings

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are a claims analyst evaluating a reported loss to determine severity, exposure, and recommended actions.
>
> Review the claim details below and assess the situation as if you are advising an account manager or claims advocate on how to proceed.
>
> Claim Details:
> [INSERT]
>
> Focus on identifying potential financial exposure, liability concerns, and any factors that could escalate the claim. Where information is limited, make reasonable assumptions and clearly note them.
>
> Structure your response as:
>
> - Concise claim summary
> - Severity assessment (low, moderate, high, or critical) with brief reasoning
> - Key risk flags (legal exposure, injury, third-party involvement, coverage uncertainty, etc.)
> - Recommended actions (immediate and short-term steps)
>
> Keep the output practical, actionable, and aligned with real-world claims handling.

---

# Evolution From Prompt to Skill

The original prompt established the goal of evaluating claim severity and identifying next actions.

This Skill expands that prompt into a reusable Claims Intelligence workflow by adding:

- Preliminary assessment readiness
- Source hierarchy
- Evidence classification
- Claim-stage analysis
- Bodily Injury Severity Indicators
- Property severity analysis
- Business interruption analysis
- Third-party exposure analysis
- Liability Concern Standard
- Legal escalation analysis
- Coverage uncertainty review
- Excess Notification Trigger Standard
- Financial exposure structure
- Claim Trajectory Standard
- Subrogation review
- Evidence preservation
- Severity escalation factors
- Severity Rationale Standard
- Immediate and short-term action framework
- Ownership Standard
- Monitoring Trigger Standard
- Data Integrity Standard
- Calculation Integrity Standard
- Authority vs. Inference Standard
- Neutral Narrative Standard
- Human Review Escalation Standard
- Update cadence
- Stop rules
- Completion criteria
- Claims-specific guardrails
- Example implementation

The purpose is to transform a severity-assessment prompt into a reusable **Claim Severity Intelligence Skill** capable of supporting future claims AI Teammates and advocacy workflows.

---

# Related Skills

Related Apeironix Skills include:

- [Commercial Insurance First Notice of Loss (FNOL)](../16-first-notice-of-loss/SKILL.md)
- [Commercial Insurance Client Situation Communication](../14-client-situation-communication/SKILL.md)
- [Commercial Insurance Client Service Response](../15-client-service-response/SKILL.md)
- Claims Escalation
- Claims Status Communication
- Loss Run Analysis
- Excess Claim Notification Review
- Claim Advocacy Strategy
- Litigation Claim Monitoring

Links should be added as those Skills are published.

---

# Suggested Invocation

```text
Perform a Commercial Claim Severity Assessment.

Claim Type:
[OPTIONAL]

Policy / Carrier:
[OPTIONAL]

Claim Details:
[INSERT]

Current Reserve:
[OPTIONAL]

Policy Limits:
[OPTIONAL]

Current Claim Stage:
[OPTIONAL]

Known Concerns:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Claim Details:
[INSERT]
```

---

# Version History

## 1.0.0

Initial public release using the Apeironix Gold Standard Template v2.1.

Enhancements from the original Prompt #17 include:

- Claim-stage analysis
- Severity readiness classification
- Bodily injury severity indicators
- Liability concern framework
- Legal escalation analysis
- Excess notification review
- Claim trajectory
- Financial exposure controls
- Monitoring triggers
- Ownership
- Human escalation
- Completion criteria
- Neutral attribution
- Claims-specific quality controls
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
