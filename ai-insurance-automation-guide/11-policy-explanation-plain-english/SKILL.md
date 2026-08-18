---
name: policy-explanation-plain-english
title: Commercial Insurance Policy Explanation in Plain English
collection: ai-insurance-automation-guide
prompt_number: 11
category: commercial-pc
capability: coverage-intelligence
primary_role: commercial-insurance-advisor
secondary_roles:
  - commercial-insurance-producer
  - commercial-account-executive
  - commercial-account-manager
  - coverage-analyst
  - risk-advisor
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Commercial Insurance Policy Explanation in Plain English

## Purpose

Translate commercial insurance policy language into clear, practical, client-friendly explanations while preserving the meaning, limitations, conditions, and uncertainty contained in the actual policy.

This Skill is designed to help the insurance professional:

- Explain what a policy is designed to cover
- Translate technical insurance wording into everyday language
- Identify meaningful exclusions without overwhelming the client
- Explain conditions that may affect how coverage responds
- Clarify deductibles, limits, sublimits, waiting periods, and other restrictions
- Connect policy language to real-world business situations
- Identify where the policy wording requires additional interpretation
- Avoid unsupported claims about whether a future loss will or will not be covered
- Help business owners make better-informed insurance decisions

The objective is **not** to paraphrase every paragraph in the policy.

The objective is to help the client understand:

> What protection do I have, what important limitations should I know about, and what do I need to do for the policy to work as intended?

---

# Core Outcome

A successful use of this Skill should allow the client to understand:

- What the policy is intended to protect
- What kinds of events or losses may trigger coverage
- What major exclusions are relevant
- What conditions could affect coverage
- What limits or sublimits matter
- What financial responsibility the client retains
- What obligations the client has
- What scenarios require further professional review
- What questions the client should ask before relying on the policy

The client should leave with greater clarity without being given a false guarantee about coverage.

---

# Best Used For

Use this Skill when explaining:

- Commercial Property policies
- General Liability policies
- Commercial Auto policies
- Workers' Compensation policies
- Umbrella and Excess Liability policies
- Cyber policies
- Employment Practices Liability policies
- Directors & Officers policies
- Professional Liability policies
- Crime policies
- Inland Marine policies
- Equipment Breakdown coverage
- Pollution policies
- Product Liability coverage
- Product Recall policies
- Builders Risk policies
- Specialty policies
- Endorsements
- Exclusions
- Coverage forms
- Renewal policy changes
- Client questions about policy wording

This Skill is especially useful when technical policy language needs to be translated for:

- Business owners
- CFOs
- COOs
- Controllers
- HR leaders
- Operations leaders
- Other non-insurance executives

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- A formal legal opinion
- A definitive claim-coverage determination
- Carrier claims interpretation
- Coverage counsel
- Binding authority
- A formal policy comparison
- A complete coverage-gap analysis
- Regulatory advice
- Contract interpretation
- Final claims advice
- Carrier-specific coverage confirmation

This is a **policy communication and coverage-understanding Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Commercial Insurance Advisors
- Commercial Insurance Producers
- Commercial Account Executives
- Commercial Account Managers
- Coverage Analysts
- Risk Advisors
- Claims Advocates
- Agency Principals
- Other authorized insurance professionals

---

# Required Inputs

At minimum, provide:

1. **Policy content**

Recommended format:

```text
Policy Content:
[PASTE POLICY LANGUAGE]
```

The supplied content may include:

- Coverage forms
- Definitions
- Insuring agreements
- Exclusions
- Conditions
- Endorsements
- Declarations
- Sublimits
- Deductibles
- Extensions
- Additional coverage provisions

If the supplied content represents only part of the policy, state that the explanation is limited to the material provided.

---

# Recommended Inputs

The following inputs materially improve the explanation:

- Policy type
- Carrier
- Policy number
- Policy period
- Named insured
- Industry
- Business operations
- Relevant locations
- Coverage limits
- Deductibles
- Sublimits
- Retentions
- Endorsements
- Exclusions
- Client question
- Specific scenario the client is concerned about
- Current claim or incident
- Applicable contracts
- Prior policy version
- Renewal changes
- Other policies that may interact with the coverage

---

# Preferred Source Documents

Where available, prioritize:

1. Full current policy
2. Current endorsements
3. Current declarations
4. Current schedules
5. Current coverage forms
6. Carrier-issued policy summary
7. Carrier-issued proposal
8. Agency-verified summary
9. Client-provided summary
10. Historical policy

When a summary conflicts with the policy, the current policy language should control the explanation.

---

# Source Hierarchy

When multiple policy sources conflict, prioritize:

1. Current endorsements
2. Current policy form
3. Current declarations and schedules
4. Carrier-issued policy documentation
5. Agency-verified documentation
6. Client-provided summaries
7. Historical policy documents
8. General insurance knowledge

Endorsements may modify, restrict, or expand the base policy form.

Do not explain a base form without considering applicable endorsements when those endorsements are available.

---

# Policy Completeness Standard

Before explaining the policy, determine whether the available material is:

### Complete Enough for Broad Explanation

Core forms, declarations, and relevant endorsements are available.

### Partially Complete

Useful explanation is possible, but important policy sections may be missing.

### Fragmentary

Only a small excerpt is available.

When material is incomplete:

- State what was reviewed
- Explain only what the available wording supports
- Identify important missing sections
- Do not imply the entire policy has been reviewed

---

# Evidence Classification

Every material explanation should fall into one of the following categories.

## Direct Policy Provision

Supported directly by the supplied policy language.

Example:

> The policy states that the insured must notify the carrier as soon as practicable after a loss.

---

## Plain-English Interpretation

A simplified explanation of a direct provision.

Example:

> In practical terms, the carrier expects the business to report a loss promptly rather than waiting until the situation becomes more complicated.

---

## Practical Implication

A real-world consequence reasonably derived from the policy language.

Example:

> Delayed reporting could make the claim process more difficult and may affect the carrier's ability to investigate.

---

## Illustrative Example

A hypothetical scenario used only to explain how the wording might operate.

Example:

> If a pipe bursts and damages inventory, the property coverage may respond differently depending on the cause of the water damage and applicable exclusions.

---

## Requires Further Policy Review

An issue that cannot be resolved from the supplied language.

Example:

> Whether this exclusion is modified by another endorsement cannot be determined from the excerpt provided.

---

# Confidence Classification

Where useful, classify explanations:

### High Confidence

The policy language directly and clearly supports the explanation.

### Moderate Confidence

The interpretation is reasonable but may depend on another policy provision.

### Low Confidence

The available wording is incomplete or ambiguous.

Do not overstate certainty.

---

# Core Principle

## Simplify the Language, Not the Meaning

Plain English should make insurance easier to understand.

It should not:

- Remove important conditions
- Ignore exclusions
- Overstate coverage
- Create guarantees
- Change the legal meaning
- Convert uncertainty into certainty

The goal is:

> Easier to understand, equally accurate.

---

# Workflow

Follow the workflow in order unless circumstances clearly require another sequence.

---

## Step 1 — Identify the Policy Type

Determine:

- Line of coverage
- Policy form
- Coverage section
- Whether the material is a base form or endorsement
- Whether multiple policies may interact

Do not interpret policy wording without understanding what part of the program it belongs to.

---

## Step 2 — Identify the Insuring Agreement

Locate or determine the provision that explains what the policy is designed to cover.

Identify:

- Covered event
- Covered property
- Covered liability
- Covered person or organization
- Trigger
- Territory
- Timing
- Other relevant requirements

Translate this first.

---

## Step 3 — Identify Who or What Is Insured

Determine:

- Named insured
- Additional insureds
- Employees
- Executives
- Covered property
- Covered vehicles
- Covered locations
- Covered operations

Do not assume all entities, people, property, or operations are insured.

---

## Step 4 — Identify the Coverage Trigger

Determine what must happen before coverage may apply.

Potential triggers include:

- Direct physical loss
- Occurrence
- Claim made
- Wrongful act
- Accident
- Bodily injury
- Property damage
- Cyber event
- Equipment breakdown
- Employment practice
- Professional error

Explain the trigger in plain language.

---

## Step 5 — Identify the Coverage Limits

Identify:

- Per-occurrence limit
- Aggregate limit
- Per-claim limit
- Property limit
- Location limit
- Sublimit
- Annual aggregate
- Shared limit

Explain what each meaningful limit represents.

Example:

Instead of:

> $1M Each Occurrence / $2M General Aggregate

Prefer:

> The policy can generally provide up to $1 million for a covered occurrence, subject to the policy terms, with up to $2 million available across certain covered claims during the policy period.

Do not oversimplify aggregate mechanics where they are more complex.

---

## Step 6 — Identify Deductibles and Retentions

Explain:

- Deductible
- Self-insured retention
- Waiting period
- Percentage deductible
- Wind/hail deductible
- Cyber retention

Make clear what the insured may need to pay or absorb before coverage responds.

Do not treat deductibles and self-insured retentions as interchangeable when policy mechanics differ.

---

## Step 7 — Identify Major Exclusions

Review exclusions and prioritize those likely to matter to the client's actual business.

Potential examples:

- Professional services
- Pollution
- Cyber
- Employment practices
- Auto
- Aircraft
- Products
- Contractual liability
- Intentional acts
- Wear and tear
- Flood
- Earthquake
- Communicable disease
- Certain construction operations
- Residential work
- Abuse or molestation

Do not list every exclusion unless requested.

Focus on material exclusions.

---

# Exclusion Relevance Standard

For each major exclusion, explain:

### What the Exclusion Does

Plain-language description.

### Why It Could Matter

Connection to the client's operations.

### What to Confirm

Whether another endorsement or policy modifies the exclusion.

Do not describe an exclusion as a coverage gap without considering endorsements and other policies.

---

## Step 8 — Identify Exceptions to Exclusions

Some exclusions contain exceptions that restore limited coverage.

Do not explain:

> This is excluded.

if the exclusion contains a meaningful exception.

Review the entire provision.

---

## Step 9 — Review Endorsements

Determine whether endorsements:

- Expand coverage
- Restrict coverage
- Change definitions
- Add exclusions
- Change limits
- Change deductibles
- Add insureds
- Modify territory
- Change reporting requirements

Explain material endorsements in plain language.

---

# Endorsement Interaction Standard

Never assume the base policy wording remains unchanged when an endorsement applies.

When multiple provisions interact:

1. Identify the base provision
2. Identify the endorsement
3. Explain what changed
4. Explain the practical effect
5. Flag unresolved conflicts for professional review

---

## Step 10 — Identify Important Conditions

Review conditions that may affect how coverage responds.

Potential examples:

- Prompt notice
- Cooperation
- Proof of loss
- Maintenance requirements
- Protective safeguards
- Vacancy
- Duties after loss
- Reporting requirements
- Claims-made reporting
- Consent requirements
- Audit requirements

Explain:

> What the client needs to do.

Conditions are often as important as exclusions.

---

## Step 11 — Identify Definitions That Change Meaning

Insurance policies define important terms.

Examples:

- Occurrence
- Claim
- Property damage
- Bodily injury
- Employee
- Pollutant
- Computer system
- Wrongful act
- Covered property

Do not rely solely on everyday meanings when the policy defines the term differently.

Translate important definitions.

---

## Step 12 — Identify Time-Sensitive Provisions

Where relevant, identify:

- Claim reporting deadline
- Notice requirement
- Retroactive date
- Extended reporting period
- Waiting period
- Period of restoration
- Limitation period
- Policy period

Explain practical consequences.

---

## Step 13 — Identify Geographic or Territorial Limits

Determine:

- Coverage territory
- Covered locations
- Scheduled premises
- International limitations
- State-specific provisions

Do not assume worldwide coverage.

---

## Step 14 — Identify Coverage Dependencies

Coverage may depend on:

- Scheduled property
- Scheduled vehicles
- Scheduled locations
- Required underlying limits
- Protective safeguards
- Contract wording
- Timely reporting
- Other insurance

Explain material dependencies.

---

## Step 15 — Translate Technical Terms

When technical terms cannot be avoided, define them immediately.

Example:

> **Aggregate limit** — the maximum amount the policy will pay for certain covered claims during the policy period.

Keep definitions concise.

---

## Step 16 — Identify What Matters Most to the Client

Prioritize the explanation based on:

- Client operations
- Severity exposure
- Common losses
- Client concern
- Contract requirements
- Retained risk
- Major exclusions
- Conditions

Do not spend equal time on every provision.

---

## Step 17 — Create Real-World Examples

Provide 2–3 simple hypothetical examples.

Each example should identify:

### Scenario

What happened.

### How the Policy Might Apply

Explain the likely coverage mechanics based on the supplied wording.

### What Could Change the Outcome

Identify:

- Exclusion
- Condition
- Limit
- Deductible
- Endorsement
- Missing fact

Use words such as:

- May
- Could
- Subject to
- Based on the supplied wording

Do not guarantee claim outcomes.

---

# Example Integrity Standard

Examples are educational illustrations.

They are not claim determinations.

Every example should be consistent with the supplied policy wording.

Do not invent an example that implies coverage broader than the policy supports.

---

## Step 18 — Identify Client Responsibilities

Where relevant, explain what the insured should do to preserve the intended protection.

Examples:

- Report claims promptly
- Maintain protective safeguards
- Keep schedules current
- Notify the broker of operational changes
- Maintain required underlying limits
- Preserve records
- Cooperate with the carrier
- Follow claims-made reporting requirements

This section should be practical.

---

## Step 19 — Identify Material Unknowns

List issues that cannot be resolved.

Examples:

- Missing endorsement
- Missing definition
- Other insurance provision
- Coverage territory
- Underlying policy
- Schedule
- Carrier interpretation

Do not fill gaps with assumptions unless clearly identified.

---

## Step 20 — Determine Explanation Readiness

Classify the available policy information.

### Explanation Ready

Enough policy information exists for a reliable client explanation.

### Conditionally Ready

A useful explanation is possible, but material provisions remain missing.

### Not Ready for Reliable Explanation

The excerpt is too limited to responsibly explain the coverage.

Do not create a confident explanation from fragmentary wording.

---

# Decision Rules

## Policy Wording Before General Knowledge

The supplied policy language takes priority over generic descriptions of how a type of insurance usually works.

---

## Current Endorsements Before Base Form

An endorsement may change the policy materially.

---

## Materiality Over Exhaustiveness

Focus on the provisions most likely to affect the client.

---

## Plain English Without Legal Rewrite

Translate the meaning.

Do not attempt to rewrite the contract.

---

## Never Guarantee a Claim Outcome

Even when wording appears clear, actual claims may depend on:

- Facts
- Definitions
- Conditions
- Exclusions
- Endorsements
- Applicable law
- Carrier interpretation

---

## Examples Must Be Conditional

Use hypothetical examples to educate, not determine coverage.

---

## Do Not Ignore Conditions

Coverage discussions should include what the client must do.

---

## Do Not Treat an Exclusion in Isolation

Review:

- Exceptions
- Endorsements
- Other coverage parts

before reaching a conclusion.

---

## Unknown Means Unknown

If necessary information is missing, say so.

---

# Materiality / Prioritization Framework

Prioritize policy provisions using:

| Factor | Question |
|---|---|
| Severity | Could this affect a major loss? |
| Frequency | Is this likely to arise often? |
| Client Relevance | Does it relate directly to operations? |
| Financial Impact | Could the client retain substantial cost? |
| Coverage Impact | Could it materially change how coverage responds? |
| Contractual Impact | Could it affect customer or lender requirements? |
| Client Action | Does the insured need to do something? |
| Confidence | Is the explanation strongly supported by the policy? |

Use professional judgment.

---

# Output Requirements

Use the following structure unless the user requests another format.

---

# Plain-English Policy Explanation

## Policy Snapshot

**Policy Type:** [Type]  
**Carrier:** [If known]  
**Policy Period:** [If known]  
**Named Insured:** [If known]  
**Material Reviewed:** [Sections/forms/endorsements]

---

# 1. Explanation Readiness

**Status:** Explanation Ready / Conditionally Ready / Not Ready for Reliable Explanation

### Important Missing Material

[List if applicable]

---

# 2. What This Policy Is Designed to Cover

Explain:

- The main purpose
- What events may trigger coverage
- Who or what is protected
- Major limits
- Deductible or retention

Use plain English.

---

# 3. What It Does Not Cover

Identify only material exclusions.

For each:

## [Exclusion]

**Plain-English meaning:**  
[Explanation]

**Why it could matter:**  
[Business relevance]

**What to confirm:**  
[Endorsement / other policy / fact]

---

# 4. Key Limitations and Conditions

Use a concise table where helpful.

| Provision | Plain-English Meaning | Why It Matters |
|---|---|---|
| [Condition / Limit] | [Explanation] | [Impact] |

---

# 5. What the Client Needs to Do

Identify practical responsibilities.

Examples:

- Report losses promptly
- Maintain required safeguards
- Keep schedules updated
- Notify the advisor of operational changes
- Maintain required underlying coverage

---

# 6. Real-World Examples

Provide 2–3 examples.

## Example 1 — [Scenario]

**What happens:**  
[Scenario]

**How the policy may apply:**  
[Explanation]

**What could change the outcome:**  
[Condition / exclusion / missing information]

Repeat as appropriate.

---

# 7. Key Takeaways

Provide 3–5 concise points.

Example:

1. The policy is designed primarily to protect against [risk].
2. The most important limitation is [issue].
3. The client retains the first [deductible/retention] where applicable.
4. [Condition] is important for maintaining coverage.
5. [Issue] should be reviewed separately.

---

# 8. Questions / Items Requiring Further Review

List unresolved issues.

| Question / Issue | Why It Matters | What Is Needed |
|---|---|---|
| [Issue] | [Reason] | [Document / confirmation] |

---

# Client Meeting Version

When requested, also provide a shorter conversational version suitable for a client meeting.

Use:

### In Simple Terms

[Short explanation]

### The Biggest Thing It Protects

[Risk]

### The Biggest Limitation to Understand

[Limitation]

### What You Need to Do

[Action]

### Example

[Simple scenario]

---

# Assumptions & Items Requiring Confirmation

Use whenever inference affects the explanation.

| Assumption | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Assumption] | [Reason] | High / Moderate / Low | [Action] |

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Correct policy material was reviewed
- [ ] Policy type is identified
- [ ] Current endorsements are considered when available
- [ ] The insuring agreement is understood
- [ ] Coverage trigger is explained
- [ ] Material limits are explained
- [ ] Deductibles or retentions are explained
- [ ] Major relevant exclusions are identified
- [ ] Exclusion exceptions are considered
- [ ] Material conditions are explained
- [ ] Important definitions are considered
- [ ] Time-sensitive requirements are identified
- [ ] Territorial limitations are considered where relevant
- [ ] Client responsibilities are identified
- [ ] Examples are consistent with policy wording
- [ ] Examples are clearly hypothetical
- [ ] No claim outcome is guaranteed
- [ ] Missing policy information is disclosed
- [ ] Technical terminology is defined
- [ ] Plain-English translation preserves meaning
- [ ] Output focuses on what matters to the client
- [ ] Explanation is understandable to a non-insurance professional

---

# Failure Conditions

The Skill should not be considered complete if:

- The output simply paraphrases policy wording sentence by sentence
- Technical jargon remains unexplained
- Major exclusions are omitted
- Conditions are ignored
- Endorsements are ignored when supplied
- Exclusion exceptions are overlooked
- The explanation overstates coverage
- A hypothetical example is presented as a claim determination
- Missing policy provisions are silently assumed
- Generic knowledge replaces the supplied policy language
- Material client responsibilities are omitted
- The explanation is technically accurate but not understandable
- The explanation is simple but materially inaccurate

If any failure condition exists, revise before finalizing.

---

# Guardrails

## Do Not Invent Policy Language

Never fabricate:

- Coverage
- Definitions
- Exclusions
- Endorsements
- Limits
- Deductibles
- Sublimits
- Conditions
- Covered locations
- Covered entities
- Reporting requirements

---

## Do Not Guarantee Coverage

Never state:

- "This claim is covered."
- "This claim will be paid."
- "The carrier must cover this."
- "This exclusion definitely applies."

unless an authorized coverage determination has already been made and the user is asking only for explanation of that determination.

Prefer:

> Based on the wording provided, the policy appears designed to...

or:

> Coverage may apply, subject to the policy terms and the facts of the loss.

---

## Do Not Hide Important Limitations for Simplicity

Plain English does not justify omitting:

- Exclusions
- Deductibles
- Retentions
- Conditions
- Sublimits
- Waiting periods
- Reporting requirements

when they are material.

---

## Do Not Explain an Exclusion Without Its Exceptions

Read the full provision when available.

---

## Do Not Ignore Endorsements

Endorsements may override the base form.

---

## Do Not Treat a Partial Policy as Complete

When only an excerpt is supplied:

- State the limitation
- Explain only what the excerpt supports
- Identify what additional material is needed

---

## No Legal Advice

Policy interpretation can involve applicable law and legal questions.

Do not provide unsupported legal conclusions.

Recommend appropriate legal or coverage counsel when necessary.

---

## Protect Confidential Information

Do not unnecessarily expose:

- Personally identifiable information
- Claimant information
- Sensitive employee information
- Financial account information
- Confidential client information
- Proprietary business information

---

## Preserve Human Accountability

This Skill supports the insurance professional.

The authorized insurance professional, carrier, claims professional, coverage counsel, or other appropriate authority remains responsible for:

- Formal coverage interpretation
- Claim determination
- Legal interpretation
- Client recommendations
- Policy placement
- Compliance
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced commercial insurance advisor explaining a policy across the table from a business owner.

The tone should be:

- Clear
- Practical
- Accurate
- Conversational
- Respectful
- Client-friendly
- Calm
- Direct

Avoid:

- Insurance jargon without explanation
- Legalistic language
- Fear-based explanations
- Overly cautious filler
- Unsupported certainty
- Excessive disclaimers
- Long technical reproductions of policy wording

The client should understand the policy better after reading the explanation.

---

# Example

## Example Request

```text
Policy Content:

Business Income and Extra Expense Coverage

We will pay for the actual loss of Business Income you sustain due to the necessary suspension of your operations during the period of restoration.

The suspension must be caused by direct physical loss of or damage to property at premises described in the declarations.

The loss or damage must be caused by or result from a Covered Cause of Loss.

72-hour waiting period applies to Business Income coverage.
```

---

## Example Output

### What This Policy Is Designed to Cover

In simple terms, this coverage is designed to help replace lost business income when your operations have to stop because covered physical damage occurs at an insured location.

For example, if a covered fire damages your facility and you cannot operate while repairs are being made, the policy may help replace income the business would otherwise have earned during that shutdown.

The coverage only applies when the shutdown results from physical loss or damage that is covered by the policy.

---

### Key Limitation

The policy includes a **72-hour waiting period** for Business Income coverage.

That means the business generally absorbs the income loss during the first 72 hours of a qualifying shutdown before Business Income coverage begins, subject to the rest of the policy terms.

---

### Real-World Example 1 — Fire at the Main Facility

**What happens:**  
A covered fire damages the company's primary location and operations stop for three weeks.

**How the policy may apply:**  
Business Income coverage may help replace qualifying lost income during the restoration period after the applicable 72-hour waiting period.

**What could change the outcome:**  
The cause of the fire, the applicable policy exclusions, the actual period of restoration, the insured location, and other policy provisions.

---

### Real-World Example 2 — Equipment Stops Working Without Physical Damage

**What happens:**  
A critical machine stops functioning because of mechanical failure, but there is no covered physical damage.

**How the policy may apply:**  
The Business Income wording shown requires covered direct physical loss or damage. Based on this excerpt alone, the shutdown may not trigger Business Income coverage.

**What could change the outcome:**  
Equipment Breakdown coverage or another endorsement may provide additional protection and should be reviewed.

---

### Key Takeaways

1. The coverage is designed to protect income when a covered physical loss shuts down operations.
2. Physical damage at a covered premises is an important trigger.
3. A 72-hour waiting period applies before Business Income coverage begins.
4. Other endorsements or coverage parts may change how the policy responds.

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are a commercial insurance advisor explaining a policy to a business owner who does not have a technical insurance background. Your objective is to make the policy easy to understand while preserving accuracy and clarity.
>
> Review the policy content below and translate it into plain English. Focus on what actually matters to the client, not policy language or technical wording.
>
> Policy Content:
> [PASTE]
>
> Think in terms of how a client experiences risk in the real world. Avoid jargon, define anything that could be confusing, and explain concepts as if you were walking a client through this in a meeting.
>
> Structure your response as:
>
> - What the policy is designed to cover, explained simply
> - What it does not cover, focusing on meaningful exclusions
> - Key limitations or conditions that could affect how coverage responds
> - 2–3 simple real-world examples showing how the policy would apply
>
> Keep the explanation clear, practical, and client-friendly.

---

# Evolution From Prompt to Skill

The original prompt established the goal of translating policy language into clear client communication.

This Skill expands that prompt into a reusable Coverage Intelligence workflow by adding:

- Required inputs
- Recommended inputs
- Preferred source documents
- Source hierarchy
- Policy Completeness Standard
- Evidence classification
- Confidence classification
- Insuring-agreement analysis
- Coverage-trigger analysis
- Insured-person/property analysis
- Limit explanation
- Deductible and retention explanation
- Exclusion Relevance Standard
- Exclusion exception review
- Endorsement Interaction Standard
- Condition analysis
- Definition analysis
- Time-sensitive provision review
- Territorial limitation review
- Coverage-dependency analysis
- Technical-term translation
- Client relevance prioritization
- Example Integrity Standard
- Client-responsibility analysis
- Material-unknown identification
- Explanation-readiness framework
- Client Meeting Version
- Quality-control checklist
- Failure conditions
- Insurance-specific guardrails
- Example implementation

The purpose is to transform a policy-explanation prompt into a reusable **Policy Understanding Skill**.

---

# Related Skills

Related Apeironix Skills include:

- [Commercial Prospect Intelligence Brief](../01-prospect-intelligence-brief/SKILL.md)
- [Commercial Insurance Meeting Strategy Builder](../02-meeting-strategy-builder/SKILL.md)
- [Commercial Insurance Coverage Gap Analysis](../03-coverage-gap-analysis/SKILL.md)
- [Commercial Insurance Renewal Strategy Builder](../04-renewal-strategy-builder/SKILL.md)
- [Commercial Insurance Executive Proposal Summary](../06-executive-proposal-summary/SKILL.md)
- [Commercial Insurance Exposure Summary Builder](../08-exposure-summary-builder/SKILL.md)
- [Commercial Insurance Business Classification Analysis](../10-business-classification-analysis/SKILL.md)
- Policy Comparison
- Coverage Interpretation
- Client Coverage Summary
- Endorsement Explanation
- Renewal Coverage Change Summary
- Claim Scenario Analysis

Links should be added as those Skills are published.

---

# Suggested Invocation

```text
Explain this Commercial Insurance Policy in Plain English.

Policy Type:
[OPTIONAL]

Client / Industry:
[OPTIONAL]

Client Question:
[OPTIONAL]

Policy Content:
[PASTE]

Additional Context:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Policy Content:
[PASTE]
```

---

# Version History

## 1.0.0

Initial public release.

Enhancements from the original Prompt #11 include:

- Policy Completeness Standard
- Policy source hierarchy
- Evidence classification
- Insuring-agreement analysis
- Coverage-trigger framework
- Limit and retention explanation
- Exclusion Relevance Standard
- Exception analysis
- Endorsement Interaction Standard
- Condition analysis
- Definition analysis
- Time-sensitive provision review
- Coverage-dependency analysis
- Example Integrity Standard
- Client-responsibility framework
- Explanation-readiness assessment
- Client Meeting Version
- Quality-control standards
- Failure conditions
- Insurance-specific guardrails
- Example implementation

---

# About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for:

- Judgment
- Relationships
- Client service
- Risk advisory
- Coverage understanding
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
