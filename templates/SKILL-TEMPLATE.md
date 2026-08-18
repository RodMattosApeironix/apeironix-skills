---
name: skill-name
title: Human-Readable Skill Title
collection: collection-name
prompt_number: 0
category: category-name
capability: capability-name
primary_role: primary-user-role
secondary_roles:
  - secondary-role
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Apeironix Gold Standard Skill Template

## Template Usage Standard

This template defines the publishing standard for public Apeironix Skills.

An Apeironix Skill should be more than a prompt.

It should define a reusable, operationally executable capability that helps an insurance professional, AI assistant, AI agent, or AI Teammate perform a repeatable insurance workflow with greater consistency, structure, and quality.

Every published Skill should be:

- Insurance-specific
- Practical
- Operationally executable
- Clear about required information
- Explicit about assumptions and uncertainty
- Prioritized by materiality
- Structured around real insurance workflows
- Designed for human accountability
- Free from fabricated insurance or client information
- Reusable across humans, AI assistants, agents, and AI Teammates

Not every section below will apply equally to every Skill.

Use the sections that materially improve execution.

Do not include a section merely because it appears in the template.

However, every Skill should address the core areas of:

1. Purpose
2. Inputs
3. Workflow
4. Decision rules
5. Output requirements
6. Quality control
7. Guardrails
8. Human accountability

---

# Skill Title

Replace this heading with the final public Skill title.

Example:

# Commercial Insurance Coverage Gap Analysis

---

# Purpose

Clearly explain what this Skill is designed to accomplish.

Describe:

- The insurance workflow
- The business problem
- The intended user
- The desired outcome
- The value the Skill should create

The purpose should answer:

> What does this Skill enable an insurance professional or AI Teammate to do better?

Avoid generic descriptions.

Prefer:

> Evaluate an existing commercial insurance program to identify material coverage gaps, structural weaknesses, inadequate limits, exclusions, and operational exposures.

Avoid:

> Help analyze insurance.

---

# Core Outcome

Describe what a successful use of the Skill should enable the user to understand, decide, prepare, or produce.

Use practical questions where helpful.

Example:

A successful use of this Skill should allow the user to answer:

- What is the most important issue?
- What information is missing?
- What requires professional judgment?
- What should happen next?

The user should finish with a clear outcome, not merely more information.

---

# Best Used For

List the situations in which the Skill should be used.

Examples:

- Prospect preparation
- Policy review
- Renewal preparation
- Coverage analysis
- Meeting strategy
- Submission preparation
- Client communication
- Claims review
- Account management
- Cross-sell analysis

Be specific.

---

# Do Not Use This Skill As

Define important boundaries.

Examples:

This Skill is not a substitute for:

- Legal advice
- Binding authority
- Carrier underwriting decisions
- Formal policy interpretation
- Claim-coverage determinations
- Regulatory opinions
- Verified client discovery

This section should prevent misuse without making the Skill overly cautious.

---

# Intended Users

Identify the primary and secondary users.

Examples:

- Commercial Insurance Producers
- Employee Benefits Advisors
- Account Executives
- Account Managers
- Coverage Analysts
- Risk Advisors
- Agency Operations Teams
- Claims Advocates
- Other authorized insurance professionals

Only include roles that reasonably use the Skill.

---

# Required Inputs

Identify the minimum information required to perform the Skill.

Use numbered items when appropriate.

Example:

1. Company Name
2. Industry
3. Primary Location

Recommended input format:

```text
Company Name: [INSERT]
Industry: [INSERT]
Location: [INSERT]
```

If a required input is missing, instruct the Skill to:

- Identify what is missing
- Avoid inventing the information
- Request the missing information when necessary
- Proceed only where a partial analysis remains useful

---

# Recommended Inputs

Identify information that materially improves the quality of the result but is not always mandatory.

Examples may include:

- Revenue
- Employee count
- Payroll
- Locations
- Current policies
- Loss runs
- Renewal date
- Vehicle count
- Customer types
- Contracts
- Company website
- Claims history
- Known client concerns

This section should help users provide better context without creating unnecessary barriers.

---

# Optional Intelligence Sources

Use this section for research-oriented Skills.

Potential sources may include:

- Official company website
- Company About page
- Public filings
- Regulatory records
- Industry associations
- Public job postings
- News coverage
- Trade publications
- Reliable business databases
- Public permit information
- Public transportation information
- Other credible public sources

Only include sources relevant to the Skill.

Do not encourage unnecessary collection of sensitive or irrelevant information.

---

# Preferred Source Documents

Use this section for document-driven Skills.

Example hierarchy:

1. Full current policy
2. Current endorsements
3. Current declarations
4. Current schedules
5. Current proposal
6. Agency Management System data
7. Client-provided summary
8. Historical documents

Use this section instead of Optional Intelligence Sources when the Skill primarily analyzes files or policy documents.

---

# Research Standard

Use this section when the Skill requires external research.

Explain:

- How deeply the AI should research
- What it should look for
- What constitutes sufficient research
- What should not be inferred without evidence

Example:

> Do not stop after locating a company description. Research enough to understand how the business operates, what assets it relies on, where revenue is generated, and what could materially interrupt operations.

The purpose of research should always connect back to the insurance workflow.

---

# Context Interpretation Standard

Use this section when the Skill works primarily from notes, CRM entries, emails, or unstructured context.

Distinguish between categories such as:

## Known Fact

Information explicitly stated.

## User or Producer Observation

An interpretation expressed by a human.

## Reasonable Inference

A likely conclusion based on context or industry norms.

## Open Question

An unresolved issue requiring discovery.

Do not collapse these categories.

---

# Source Hierarchy

When multiple sources are available, define which should take priority.

Example:

1. Current policy forms and endorsements
2. Carrier-issued documents
3. Agency-verified information
4. Client-provided information
5. Public authoritative sources
6. Industry norms and inference

When sources conflict:

- Identify the discrepancy
- Do not silently choose one
- Use the most authoritative source available
- Flag material conflicts for human review

---

# Evidence Classification

Where useful, classify findings.

Suggested categories:

## Verified Fact

Directly supported by a credible source.

## Documented Finding

Supported by supplied policy or account information.

## Reasonable Industry Inference

Based on common industry practices or exposure patterns.

## Discovery Hypothesis

A possible issue worth investigating.

## Exposure-Dependent Concern

A concern that matters only if a specific operational fact is confirmed.

## Requires Form Review

An issue that cannot be resolved without reviewing actual policy language.

Use only the classifications relevant to the Skill.

---

# Confidence Classification

Where useful, classify conclusions:

### High Confidence

Supported by direct, current, or authoritative information.

### Moderate Confidence

Supported by multiple indicators or strong industry norms.

### Low Confidence

Possible but requires meaningful confirmation.

Do not create false precision.

---

# Core Principle

Define the most important operating principle of the Skill.

Examples:

## Never Convert an Inference Into a Fact

or:

## Identify Real Exposure, Not Theoretical Defects

or:

## Every Meeting Needs a Defined Outcome

This principle should guide the AI when there is ambiguity.

---

# Workflow

Follow the workflow in order unless the specific circumstances clearly justify another sequence.

Build enough steps to make the Skill operationally useful.

Avoid vague instructions such as:

> Analyze the information.

Instead define what analysis means.

---

## Step 1 — [Step Name]

Explain:

- What to review
- What to identify
- What to distinguish
- What questions to ask internally
- What should be produced

---

## Step 2 — [Step Name]

[Instructions]

---

## Step 3 — [Step Name]

[Instructions]

---

## Step 4 — [Step Name]

[Instructions]

---

## Step 5 — [Step Name]

[Instructions]

---

# Optional Workflow Modules

Add additional modules when the workflow requires them.

Examples:

- Exposure mapping
- Property analysis
- Business-income analysis
- Contractual risk review
- Cyber analysis
- Claims review
- Frequency/severity analysis
- Underwriter perspective
- Meeting strategy
- Wedge identification
- Program coordination
- Entity review
- Market comparison
- Employee communication

Do not force irrelevant modules into a Skill.

---

# Decision Rules

Define the principles the Skill should use when making choices.

Examples:

## Materiality Over Volume

Prioritize the issues that could materially affect:

- Coverage
- Cost
- Risk
- Claims
- Operations
- Compliance
- Client decisions

Do not create long lists simply for completeness.

---

## Facts vs. Recommendations

Clearly distinguish:

### Fact
Supported by evidence.

### Observation
A meaningful pattern or issue.

### Recommendation
A suggested action requiring judgment.

---

## No Silent Assumptions

If an assumption is required:

1. State the assumption.
2. Explain why it is necessary.
3. Identify what would confirm it.

---

## Current Information Takes Priority

When multiple periods or versions exist, prioritize current information.

Do not present expired information as current.

---

## Insurance Insight Over Generic Commentary

Connect observations to:

- Exposure
- Coverage
- Loss potential
- Underwriting
- Risk control
- Client impact

Avoid generic business commentary.

---

## Severity Before Trivia

Prioritize issues capable of materially affecting:

- Balance sheet
- Operations
- Revenue
- Reputation
- Claims
- Insurability

---

# Materiality / Prioritization Framework

Use this section when findings must be ranked.

Potential factors:

| Factor | Question |
|---|---|
| Severity | How large could the loss or impact be? |
| Frequency | How likely is it? |
| Financial Impact | Could it materially affect the client? |
| Operational Impact | Could it interrupt operations? |
| Coverage Certainty | How likely is the program to respond? |
| Contractual Impact | Could obligations exceed protection? |
| Urgency | Does this require action now? |
| Evidence | How strongly is the concern supported? |

Possible priority levels:

### Critical

Potential for severe uninsured or underinsured loss, material coverage failure, or major operational impact.

### High

Meaningful exposure requiring prompt attention.

### Moderate

Important but not immediately threatening.

### Informational

Useful context with limited immediate impact.

Do not rank every issue as Critical or High.

---

# Output Requirements

Define exactly how the result should be presented.

Unless the user requests another format, create a predictable structure.

Example:

# [Skill Output Name]

## Snapshot

[Basic identifying information]

## Executive Summary

[Highest-value findings]

## Key Findings

[Prioritized findings]

## Detailed Analysis

[Tables or structured analysis]

## Issues Requiring Attention

[Critical or unresolved issues]

## Recommended Next Steps

[Specific actions]

---

# Output Tables

When tables improve clarity, define the exact format.

Example:

| Priority | Concern | Potential Impact | Confidence | Recommended Action |
|---|---|---|---|---|
| High | [Issue] | [Impact] | Moderate | [Action] |

Avoid tables when prose communicates the result more effectively.

---

# Assumptions & Items Requiring Confirmation

Use this section whenever meaningful inference is involved.

Suggested format:

| Assumption | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Assumption] | [Reason] | High / Moderate / Low | [Action] |

This section should prevent inferred information from being mistaken for verified fact.

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Correct client/account/business was reviewed
- [ ] Required inputs were available
- [ ] Current information was prioritized
- [ ] Facts are supported
- [ ] Inferences are clearly labeled
- [ ] No unsupported values were invented
- [ ] Material issues are prioritized
- [ ] Industry-specific logic was applied
- [ ] Output follows the required structure
- [ ] Recommendations are practical
- [ ] Missing information is disclosed
- [ ] Human-review items are identified
- [ ] No binding, legal, or unsupported coverage conclusions are made
- [ ] The final result prioritizes insight over volume

Add Skill-specific checks as needed.

---

# Failure Conditions

Define what makes the Skill incomplete or unacceptable.

Examples:

The Skill should not be considered complete if:

- Required information is missing and not disclosed
- Generic commentary replaces insurance-specific analysis
- Inferences are presented as facts
- Material risks are ignored
- Unsupported coverage conclusions are made
- Policy language is invented
- Recommendations are not actionable
- No prioritization is provided when prioritization is required
- The output does not meaningfully help the intended user

If a failure condition exists, revise before finalizing.

---

# Guardrails

## Do Not Fabricate Information

Never invent:

- Coverage
- Limits
- Premium
- Deductibles
- Endorsements
- Exclusions
- Claims
- Revenue
- Payroll
- Employee counts
- Locations
- Policy provisions
- Carrier requirements
- Client facts

unless supported by credible information.

---

## Do Not Bind or Alter Coverage

This Skill cannot:

- Bind insurance
- Issue policies
- Change coverage
- Change limits
- Confirm carrier acceptance
- Confirm underwriting approval

---

## Do Not Guarantee Coverage

Do not state that:

- A claim is covered
- A claim is excluded
- A policy definitely responds
- A limit is definitely sufficient
- A carrier will accept a risk

without appropriate authoritative support and human review.

---

## Do Not Treat Summaries as Full Policies

When working from summaries or declarations:

Remember they may omit:

- Definitions
- Conditions
- Exclusions
- Endorsements
- Sublimits
- Aggregates
- Territory
- Reporting requirements
- Retroactive dates

When appropriate, state:

> Full policy-form review is required.

---

## No Legal Advice

Legal, contractual, or regulatory issues may be identified.

Do not provide unsupported legal conclusions.

Recommend qualified legal or compliance review when necessary.

---

## Protect Confidential Information

Use only information necessary to perform the requested workflow.

Do not unnecessarily expose:

- Personally identifiable information
- Protected health information
- Credentials
- Financial account information
- Confidential client records
- Proprietary agency information
- Sensitive company information

---

## Preserve Human Accountability

AI supports the insurance professional.

The authorized professional remains responsible for:

- Final judgment
- Coverage recommendations
- Client communication
- Carrier strategy
- Submission accuracy
- Compliance
- Binding decisions
- Legal or regulatory escalation

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Define the tone appropriate to the Skill.

Typical Apeironix standard:

- Practical
- Insurance-specific
- Analytical
- Concise
- Client-centered
- Commercially aware
- Non-alarmist
- Actionable

Avoid:

- Generic clichés
- Fear-based selling
- Excessive jargon
- Unsupported certainty
- Product dumping
- Long unprioritized lists
- Artificially cautious language that obscures the real issue

Write like an experienced insurance professional performing the workflow.

---

# Example

## Example Request

```text
[INSERT FICTIONAL EXAMPLE INPUT]
```

---

## Example Output Excerpt

Provide a realistic but concise example showing:

- Expected reasoning structure
- Output format
- Level of specificity
- Appropriate use of assumptions
- Materiality
- Human-review points

Do not use real confidential client information in public examples.

---

# Original Prompt

If the Skill is derived from the Apeironix AI Insurance Automation Guide, preserve the original prompt here.

Example:

> [ORIGINAL PROMPT TEXT]

Preserving the original prompt creates a clear historical connection between:

**Prompt → Skill**

Do not materially rewrite the original prompt in this section.

---

# Evolution From Prompt to Skill

Explain what was added beyond the original prompt.

Potential enhancements include:

- Required inputs
- Recommended inputs
- Source hierarchy
- Evidence classification
- Confidence classification
- Research standards
- Insurance-specific workflow logic
- Decision rules
- Prioritization
- Output standards
- Quality checks
- Failure conditions
- Guardrails
- Human accountability
- Example implementation

The purpose is to show how a useful prompt became a reusable insurance capability.

---

# Related Skills

List related Apeironix Skills.

Example:

- Commercial Prospect Intelligence Brief
- Commercial Insurance Meeting Strategy Builder
- Commercial Coverage Gap Analysis
- Loss Run Analysis
- Renewal Preparation

Use direct links when those Skills are published.

Example:

```md
- [Commercial Prospect Intelligence Brief](../01-prospect-intelligence-brief/SKILL.md)
```

---

# Suggested Invocation

Provide a user-friendly invocation.

Example:

```text
Perform a [Skill Name].

Company: [OPTIONAL]
Industry: [OPTIONAL]

Primary Input:
[PASTE INFORMATION]

Additional Context:
[OPTIONAL]
```

---

# Minimum Viable Invocation

Provide the smallest useful input.

Example:

```text
Primary Input:
[PASTE REQUIRED INFORMATION]
```

---

# Version History

## 1.0.0

Initial public release.

Document major enhancements or changes.

Example:

- Added structured workflow
- Added evidence classification
- Added quality controls
- Added guardrails
- Added output standards

Future updates should follow semantic versioning where practical.

Examples:

- `1.0.1` — Minor wording or clarification
- `1.1.0` — Meaningful workflow improvement
- `2.0.0` — Major structural or behavioral change

---

# About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for:

- Judgment
- Relationships
- Client service
- Risk advisory
- Analysis
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
