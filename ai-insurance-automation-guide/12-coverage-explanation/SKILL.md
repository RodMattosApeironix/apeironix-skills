---
name: coverage-explanation
title: Commercial Insurance Coverage Explanation
collection: ai-insurance-automation-guide
prompt_number: 12
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

# Commercial Insurance Coverage Explanation

## Purpose

Explain a specific commercial insurance coverage in clear, practical language so a business owner or decision-maker can understand what the coverage is designed to do, why it may matter, how it may apply in a real-world situation, and what common misunderstandings should be avoided.

This Skill is designed to help the insurance professional:

- Translate technical coverage concepts into plain English
- Explain why the coverage may matter to a particular business
- Connect insurance protection to real operational risk
- Provide realistic examples without guaranteeing claim outcomes
- Clarify common misconceptions
- Distinguish what the coverage generally addresses from what it does not replace
- Identify important dependencies, conditions, or limitations when relevant
- Help clients make more informed insurance decisions
- Improve coverage conversations without overwhelming the client with policy terminology

The objective is **not** to provide a dictionary definition.

The objective is to create a practical **Coverage Explanation** that helps the client understand:

> What is this coverage, why should I care, and when might it matter to my business?

---

# Core Outcome

A successful use of this Skill should allow the client to understand:

- What the coverage is designed to address
- What type of business risk creates the need for it
- Why the coverage may be relevant to their operations
- What a realistic claim scenario might look like
- What the coverage generally does not replace
- What common assumptions about the coverage may be wrong
- What policy details still need to be reviewed
- What questions the client should ask before relying on the coverage

The client should leave with greater clarity and confidence without being given a false guarantee about coverage.

---

# Best Used For

Use this Skill when explaining a specific coverage such as:

- General Liability
- Commercial Property
- Business Income
- Extra Expense
- Commercial Auto
- Hired and Non-Owned Auto
- Workers' Compensation
- Employers Liability
- Umbrella Liability
- Excess Liability
- Cyber Liability
- Social Engineering
- Crime
- Employment Practices Liability
- Directors & Officers Liability
- Fiduciary Liability
- Professional Liability
- Errors & Omissions
- Technology E&O
- Pollution Liability
- Contractors Pollution
- Inland Marine
- Equipment Breakdown
- Builders Risk
- Product Liability
- Product Recall
- Cargo
- Ocean Marine
- International Coverage
- Surety
- Other commercial insurance coverages

This Skill is especially useful in:

- Client meetings
- Proposal presentations
- Renewal discussions
- Coverage reviews
- New-client onboarding
- Educational content
- Executive summaries
- Email explanations
- Client training

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- A formal policy interpretation
- A claim-coverage determination
- A legal opinion
- Carrier claims advice
- A coverage-gap analysis
- A policy-form comparison
- Binding authority
- Carrier underwriting approval
- Regulatory advice
- A complete review of the client's insurance program

This is a **coverage education and client communication Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Commercial Insurance Advisors
- Commercial Insurance Producers
- Commercial Account Executives
- Commercial Account Managers
- Coverage Analysts
- Risk Advisors
- Agency Principals
- Claims Advocates
- Other authorized insurance professionals

---

# Required Inputs

At minimum, provide:

1. **Coverage name or coverage concept**

Recommended format:

```text
Coverage:
[INSERT]
```

Examples:

```text
Coverage:
Business Income
```

or:

```text
Coverage:
Hired and Non-Owned Auto Liability
```

If the requested coverage term is ambiguous, identify the ambiguity before providing a definitive explanation.

---

# Recommended Inputs

The following inputs materially improve the explanation:

- Client name
- Industry
- Business operations
- Employee count
- Revenue
- Locations
- Vehicle use
- Products
- Professional services
- Property exposure
- Contractual requirements
- Current policy
- Current limit
- Current deductible
- Current retention
- Current endorsement
- Client concern
- Specific scenario
- Recent claim
- Reason the coverage is being discussed
- Existing related coverage
- Known exclusions
- Known limitations
- Renewal decision
- Proposed coverage option

---

# Optional Intelligence Sources

When appropriate and current information is available, useful sources may include:

- Current policy language
- Current endorsements
- Carrier coverage summaries
- Carrier product materials
- Authoritative insurance forms
- Current regulatory guidance
- Industry-specific risk information
- Client operational information
- Current claim or loss information

When actual policy wording is available, it takes priority over generic coverage descriptions.

---

# Coverage Scope Standard

Before explaining a coverage, determine whether the user is asking about:

### General Coverage Concept

A high-level explanation of how the coverage typically works.

or:

### Specific Policy Coverage

An explanation of coverage under an actual policy, form, endorsement, or quote.

These are not the same.

When only the coverage name is provided:

- Explain the general concept
- Clearly state that actual coverage depends on policy wording
- Do not imply that every policy provides identical protection

When actual policy language is provided:

- Base the explanation on that wording
- Identify material differences from the general concept
- Avoid replacing the actual wording with a generic description

---

# Source Hierarchy

When policy-specific information is available, prioritize:

1. Current endorsements
2. Current policy form
3. Current declarations and schedules
4. Carrier-issued coverage documentation
5. Agency-verified policy information
6. Client-provided policy summary
7. General insurance knowledge

When explaining only a general coverage concept, clearly identify the explanation as general rather than policy-specific.

---

# Evidence Classification

Every material statement should be treated as one of the following.

## General Coverage Principle

A broadly accepted description of how a coverage is typically designed to function.

Example:

> Business Income coverage is generally designed to help replace lost income when covered physical damage interrupts operations.

---

## Policy-Specific Provision

Supported directly by the actual policy or endorsement.

Example:

> This policy includes a 72-hour waiting period before Business Income coverage begins.

---

## Practical Implication

A reasonable explanation of what the coverage may mean operationally.

Example:

> A business with only one manufacturing facility may have greater dependence on Business Income coverage because a major property loss could stop most revenue-producing activity.

---

## Illustrative Scenario

A hypothetical example used to explain the coverage.

---

## Requires Policy Review

An issue that depends on actual policy wording and cannot be determined from the general coverage name alone.

---

# Confidence Classification

Where useful, classify explanations:

### High Confidence

Supported directly by current policy wording or a clear coverage principle.

### Moderate Confidence

Generally applicable but dependent on policy details.

### Low Confidence

Highly dependent on policy wording, jurisdiction, or specific facts.

Do not create false certainty.

---

# Core Principle

## Explain the Risk Before Explaining the Insurance

Clients understand coverage better when they first understand the problem the coverage is intended to solve.

Do not begin with:

> Hired and Non-Owned Auto is...

Begin with:

> If an employee uses a personal vehicle for company business and causes a serious accident, the business may still be brought into the claim.

Then explain how the coverage may address that exposure.

The preferred sequence is:

**Business Risk → Coverage → Example → Limitation**

---

# Workflow

Follow the workflow in order unless circumstances clearly require another sequence.

---

## Step 1 — Identify the Coverage

Determine:

- Coverage name
- Line of business
- Whether it is primary coverage, endorsement, extension, or specialty coverage
- Whether the user wants a general or policy-specific explanation

Resolve ambiguous terminology when possible.

---

## Step 2 — Identify the Business Risk It Addresses

Ask:

> What real-world problem is this coverage designed to help manage?

Examples:

### Business Income

Loss of revenue following covered damage that interrupts operations.

### Hired and Non-Owned Auto

Business liability arising from rented vehicles or employee-owned vehicles used for company business.

### Cyber Liability

Financial and liability consequences of certain cyber incidents, privacy events, and technology failures.

### Employment Practices Liability

Claims involving allegations such as discrimination, harassment, retaliation, or wrongful termination.

Explain the risk first.

---

## Step 3 — Explain the Coverage in Plain English

Use a concise explanation.

The explanation should answer:

- Who or what is being protected?
- From what kind of event?
- What type of financial loss may be addressed?
- When might the coverage matter?

Avoid policy jargon unless necessary.

---

## Step 4 — Explain Why It Matters to the Client

Connect the coverage to the client's actual or likely operations.

Potential connections include:

- Employees
- Vehicles
- Property
- Customers
- Contracts
- Products
- Technology
- Data
- Professional advice
- Jobsite work
- Management decisions
- Revenue dependency
- Supply-chain dependency

Avoid generic statements such as:

> Every business needs this.

Instead explain why this business may need to evaluate it.

---

## Step 5 — Identify the Primary Loss Scenario

Develop one clear example.

The example should:

- Reflect a realistic business event
- Clearly connect to the coverage
- Avoid unnecessary complexity
- Explain how the policy may respond
- Identify what could change the outcome

Use conditional language.

---

# Scenario Integrity Standard

Examples are educational tools.

They are not coverage determinations.

Use language such as:

- May respond
- Could apply
- Subject to the policy terms
- Assuming the event meets the policy requirements

Do not state:

> The policy will pay.

unless an authorized determination has already been made.

---

## Step 6 — Identify Common Misunderstandings

Identify 2–4 misconceptions relevant to the coverage.

Examples:

### Hired and Non-Owned Auto

Misunderstanding:

> My employee's personal auto insurance handles everything.

Reality:

> The employee's personal insurance may respond first, but the business can still face liability depending on the circumstances.

### Cyber

Misunderstanding:

> Our IT company is responsible if we get hacked.

Reality:

> A technology provider may help manage systems, but the business may still face its own financial, legal, operational, or notification obligations.

### Umbrella

Misunderstanding:

> The umbrella automatically covers every type of claim after the primary policy reaches its limit.

Reality:

> Umbrella and excess policies have their own terms, exclusions, and underlying coverage requirements.

Misunderstandings should be corrected without sounding alarmist.

---

## Step 7 — Identify What the Coverage Does Not Replace

Where relevant, explain related protection that remains separate.

Examples:

Business Income does not replace:

- Property coverage
- Disaster recovery
- Business continuity planning

Cyber coverage does not replace:

- Cybersecurity controls
- Crime coverage
- Technology E&O in every circumstance

Umbrella does not automatically replace:

- Professional Liability
- Cyber
- D&O
- Employment Practices Liability

This helps prevent false assumptions.

---

## Step 8 — Identify Important Policy Variables

Explain which policy details can materially change the protection.

Potential variables include:

- Limits
- Sublimits
- Deductibles
- Retentions
- Waiting periods
- Coverage triggers
- Definitions
- Exclusions
- Endorsements
- Territory
- Retroactive dates
- Reporting requirements
- Covered persons
- Scheduled locations
- Underlying limits

Do not overwhelm the client.

Identify only the variables most important to the coverage.

---

## Step 9 — Identify Coverage Dependencies

Where relevant, explain what the coverage depends on.

Examples:

- Covered Cause of Loss
- Scheduled property
- Underlying coverage
- Timely claim reporting
- Required cyber controls
- Protective safeguards
- Contract wording
- Retroactive date
- Covered vehicle status

Explain dependencies in practical terms.

---

## Step 10 — Identify Client Responsibilities

Where useful, explain what the client should do.

Examples:

- Report incidents promptly
- Maintain required controls
- Keep exposure schedules current
- Notify the advisor about major operational changes
- Maintain required underlying limits
- Preserve documentation
- Follow carrier reporting requirements

Avoid implying that failure automatically eliminates coverage unless the policy supports that conclusion.

---

## Step 11 — Identify Related Coverages

Explain coverages that may interact with the requested coverage.

Examples:

### Business Income

Related to:

- Commercial Property
- Equipment Breakdown
- Utility Services
- Contingent Business Interruption

### Cyber

Related to:

- Crime
- Technology E&O
- Professional Liability
- Business Income

### Employment Practices Liability

Related to:

- D&O
- Fiduciary
- Workers' Compensation
- General Liability

This section should help the client understand the coverage within the broader program.

---

## Step 12 — Identify What Requires Policy Review

List issues that cannot be answered from the coverage name alone.

Examples:

- Actual limit
- Specific exclusions
- Sublimits
- Waiting period
- Who qualifies as an insured
- Geographic scope
- Reporting requirements
- Coverage trigger
- Claims-made retroactive date

Do not imply that the general explanation describes every policy.

---

## Step 13 — Determine Explanation Readiness

Classify the available information.

### Concept Explanation Ready

Enough information exists to explain the general coverage concept.

### Policy-Specific Explanation Ready

Actual policy wording is available and can support a specific explanation.

### Conditionally Ready

A useful explanation is possible, but important details are unknown.

### Not Ready for Policy-Specific Explanation

The requested conclusion requires actual policy wording that has not been supplied.

---

# Decision Rules

## Risk Before Coverage

Explain the real-world problem first.

---

## General Coverage Is Not Policy-Specific Coverage

Do not blur the distinction.

---

## Actual Policy Wording Takes Priority

When policy language is available, use it.

---

## Explain Value Without Selling Fear

Do not exaggerate loss scenarios to make the coverage sound necessary.

---

## Do Not Say Every Client Needs Every Coverage

Tie relevance to actual exposure.

---

## Keep Examples Simple

One good example is better than multiple complex hypotheticals.

---

## Misconceptions Should Be Material

Focus on assumptions that could meaningfully change client decisions.

---

## Coverage Is One Part of Risk Management

Where appropriate, explain operational controls that remain important.

---

## Unknown Means Unknown

If policy-specific terms are not available, say so.

---

# Materiality / Prioritization Framework

Prioritize explanation content using:

| Factor | Question |
|---|---|
| Client Relevance | Does this coverage relate directly to the business? |
| Severity | Could the underlying event create a large financial loss? |
| Frequency | Could the exposure arise regularly? |
| Financial Impact | Could the client retain substantial cost? |
| Coverage Dependency | Are there important conditions that affect protection? |
| Common Misunderstanding | Is there a frequent client assumption worth correcting? |
| Decision Relevance | Does this help the client decide whether or how to purchase coverage? |

Keep the explanation focused on what the client actually needs to understand.

---

# Output Requirements

Use the following structure unless the user requests another format.

---

# Commercial Coverage Explanation

## Coverage

**[Coverage Name]**

---

# 1. In Simple Terms

Explain the coverage in 1–3 short paragraphs.

Answer:

- What is it?
- What problem is it designed to address?
- How does it generally work?

Use plain English.

---

# 2. Why It Matters to This Business

Explain the connection between:

- The client's operations
- The underlying exposure
- The potential financial consequence

If client-specific context is unavailable, describe the types of businesses or situations where the coverage is commonly relevant.

---

# 3. Real-World Example

## Scenario

[Simple event]

## How the Coverage May Respond

[Plain-English explanation]

## What Could Change the Outcome

[Limit / exclusion / condition / policy wording]

---

# 4. Common Misunderstandings

## Misunderstanding 1

> [Common assumption]

**What to understand instead:**  
[Explanation]

## Misunderstanding 2

> [Common assumption]

**What to understand instead:**  
[Explanation]

Add no more than 4 unless requested.

---

# 5. Important Policy Details to Check

Identify the policy variables most likely to affect the coverage.

Examples:

- Limit
- Deductible
- Sublimit
- Waiting period
- Exclusions
- Reporting requirement
- Retroactive date
- Territory
- Covered persons
- Underlying coverage

---

# 6. What This Coverage Does Not Replace

Where relevant, explain:

- Related insurance
- Operational controls
- Risk-management practices

Keep this concise.

---

# 7. Client Takeaway

Provide one short conclusion.

Example:

> The key point is that Business Income coverage is designed to protect the income stream of the business when covered property damage interrupts operations. The important question is not only whether the coverage exists, but whether the limit and recovery period realistically match how long the business could be disrupted.

---

# Policy-Specific Review Needed

When applicable:

> This explanation describes the general purpose of the coverage. Actual protection depends on the specific policy, endorsements, limits, exclusions, definitions, and facts of a loss.

Identify the exact items that should be reviewed.

---

# Client Meeting Version

When requested, provide an even shorter conversational version.

Use:

### What It Is

[One sentence]

### Why You Care

[One sentence]

### Simple Example

[Two or three sentences]

### Biggest Misunderstanding

[One sentence]

### What We Should Check

[One sentence]

---

# Assumptions & Items Requiring Confirmation

Use whenever the explanation depends on an assumption.

| Assumption | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Assumption] | [Reason] | High / Moderate / Low | [Action] |

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Coverage is correctly identified
- [ ] General vs. policy-specific explanation is distinguished
- [ ] The underlying business risk is explained
- [ ] The coverage explanation is plain English
- [ ] Client relevance is established
- [ ] Scenario is realistic
- [ ] Scenario does not guarantee a claim outcome
- [ ] Common misunderstandings are material
- [ ] Important policy variables are identified
- [ ] Related coverages are considered when useful
- [ ] Coverage is not presented as a replacement for risk controls
- [ ] No unsupported policy terms are invented
- [ ] No unsupported coverage guarantees are made
- [ ] Technical terms are translated
- [ ] Policy-specific unknowns are disclosed
- [ ] Explanation is concise and client-friendly
- [ ] The final takeaway is clear

---

# Failure Conditions

The Skill should not be considered complete if:

- The explanation is merely a technical definition
- The business risk is not explained
- The coverage is described without explaining why it matters
- A hypothetical example is presented as guaranteed coverage
- Generic coverage is confused with specific policy coverage
- Common misconceptions are generic or irrelevant
- Important limitations are hidden
- Technical language remains unexplained
- The output uses fear to justify coverage
- Every business is told it needs the coverage
- Policy-specific details are invented
- Related risk-management responsibilities are ignored where material
- The client cannot explain the coverage back in simple terms after reading the output

If any failure condition exists, revise before finalizing.

---

# Guardrails

## Do Not Fabricate Coverage Terms

Never invent:

- Limits
- Deductibles
- Sublimits
- Exclusions
- Endorsements
- Definitions
- Waiting periods
- Retroactive dates
- Reporting requirements
- Covered persons
- Covered locations

---

## Do Not Guarantee Coverage

Never state:

- A claim will be covered
- A carrier will pay
- Coverage definitely applies
- An exclusion definitely does not apply

without appropriate authoritative support.

---

## Do Not Present General Descriptions as Policy Language

A general explanation should be identified as general.

Actual policy terms may differ.

---

## Do Not Use Fear-Based Selling

Avoid language designed primarily to scare the client.

Use realistic business consequences instead.

---

## Do Not Overstate Need

Coverage recommendations should depend on actual exposure.

Do not state that every company needs every coverage.

---

## Do Not Ignore Related Coverage

Where important, explain how the coverage interacts with other parts of the program.

---

## No Legal Advice

Legal or regulatory issues may arise from certain coverages.

Do not provide unsupported legal conclusions.

---

## Protect Confidential Information

Use only information necessary for the explanation.

Do not unnecessarily expose:

- Personally identifiable information
- Claimant information
- Sensitive employee data
- Financial account information
- Confidential business information
- Proprietary agency information

---

## Preserve Human Accountability

This Skill supports the insurance professional.

The authorized insurance professional, carrier, claims professional, or appropriate coverage authority remains responsible for:

- Final coverage interpretation
- Client recommendations
- Claim determinations
- Policy selection
- Binding
- Compliance
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like a trusted commercial insurance advisor sitting across the table from a business owner.

The tone should be:

- Clear
- Conversational
- Practical
- Confident
- Accurate
- Respectful
- Client-centered
- Calm

Avoid:

- Insurance jargon without explanation
- Legalistic wording
- Product-selling language
- Fear-based examples
- Excessive caveats
- Unsupported certainty
- Long technical descriptions

The client should understand why the coverage matters without feeling overwhelmed.

---

# Example

## Example Request

```text
Coverage:
Hired and Non-Owned Auto Liability

Client:
Regional consulting firm with 75 employees.

Context:
Employees occasionally rent vehicles for business travel and sometimes use personal cars to visit client locations.
```

---

## Example Output

### In Simple Terms

Hired and Non-Owned Auto Liability is designed to help protect the business when it becomes legally responsible for an auto accident involving a vehicle the company does not own.

That can include:

- A vehicle rented for company business
- An employee's personal vehicle being used for work

The coverage is primarily about protecting the company from liability. It is not generally designed to replace the employee's personal auto insurance or insure physical damage to every vehicle involved.

---

### Why It Matters to This Business

Your employees occasionally drive personal cars to client locations and rent vehicles for business travel.

Even though the company does not own those vehicles, the company could still be named in a lawsuit if an accident occurs while the employee is acting on behalf of the business.

That creates a liability exposure that may not be addressed by an owned-auto policy alone.

---

### Real-World Example

#### Scenario

An employee uses their personal car to drive to a client meeting and causes a serious accident.

The injured party files a lawsuit against both the employee and the company.

#### How the Coverage May Respond

The employee's personal auto insurance may respond first.

If the company is also legally responsible, Hired and Non-Owned Auto Liability may provide protection for the business, subject to the policy terms and applicable limits.

#### What Could Change the Outcome

Coverage could depend on:

- Why the employee was driving
- The specific policy wording
- Whether the vehicle qualifies as a non-owned auto
- Applicable exclusions
- Other available insurance

---

### Common Misunderstandings

#### Misunderstanding 1

> "The employee has personal auto insurance, so the company has no exposure."

**What to understand instead:**  
The employee's personal policy may protect the employee, but the company can still be named in a claim or lawsuit.

#### Misunderstanding 2

> "Hired and Non-Owned Auto covers damage to an employee's personal car."

**What to understand instead:**  
The coverage is primarily liability protection for the business. Physical damage to the employee's own vehicle usually involves separate insurance considerations.

#### Misunderstanding 3

> "We do not own vehicles, so we do not have auto risk."

**What to understand instead:**  
A business can still have auto liability exposure when employees rent vehicles or use personal vehicles for company business.

---

### Important Policy Details to Check

For this coverage, confirm:

- Liability limit
- Definition of hired auto
- Definition of non-owned auto
- Employee status
- Territory
- Applicable exclusions
- Whether umbrella coverage follows over the exposure

---

### Client Takeaway

The key point is that a company does not need to own vehicles to have auto liability exposure.

If employees drive rented or personal vehicles for business purposes, Hired and Non-Owned Auto Liability may be an important part of protecting the company from claims arising out of those activities.

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are a trusted insurance advisor explaining a specific coverage to a client. Your goal is to ensure the client understands what the coverage does, why it matters, and how it applies to their business.
>
> Explain the coverage below in a way that builds confidence and clarity, not confusion.
>
> Coverage:
> [INSERT]
>
> Avoid technical definitions unless they are translated into plain language. Focus on helping the client understand how this coverage protects them in real situations.
>
> Structure your response as:
>
> - What the coverage is, explained in simple terms
> - Why it matters to the client’s business or situation
> - A clear example scenario showing how it would respond
> - Common misunderstandings or assumptions clients often have
>
> Keep the tone clear, conversational, and easy to follow.

---

# Evolution From Prompt to Skill

The original prompt established the goal of explaining a specific insurance coverage in clear, client-friendly language.

This Skill expands that prompt into a reusable Coverage Intelligence workflow by adding:

- Required inputs
- Recommended inputs
- Optional intelligence sources
- Coverage Scope Standard
- Source hierarchy
- Evidence classification
- Confidence classification
- Business-risk-first explanation
- Client-relevance analysis
- Scenario Integrity Standard
- Misunderstanding framework
- Coverage replacement boundaries
- Policy-variable analysis
- Coverage-dependency analysis
- Client responsibility analysis
- Related-coverage analysis
- Policy-review requirements
- Explanation-readiness framework
- Client Meeting Version
- Quality-control checklist
- Failure conditions
- Insurance-specific guardrails
- Example implementation

The purpose is to transform a coverage-explanation prompt into a reusable **Coverage Education Skill**.

---

# Related Skills

Related Apeironix Skills include:

- [Commercial Insurance Coverage Gap Analysis](../03-coverage-gap-analysis/SKILL.md)
- [Commercial Insurance Executive Proposal Summary](../06-executive-proposal-summary/SKILL.md)
- [Commercial Insurance Business Classification Analysis](../10-business-classification-analysis/SKILL.md)
- [Commercial Insurance Policy Explanation in Plain English](../11-policy-explanation-plain-english/SKILL.md)
- Coverage Recommendation Summary
- Policy Comparison
- Endorsement Explanation
- Client Coverage Summary
- Risk Scenario Analysis

Links should be added as those Skills are published.

---

# Suggested Invocation

```text
Explain this Commercial Insurance Coverage.

Coverage:
[INSERT]

Client / Industry:
[OPTIONAL]

Business Operations:
[OPTIONAL]

Why We Are Discussing It:
[OPTIONAL]

Specific Policy Terms:
[OPTIONAL]

Client Question:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Coverage:
[INSERT]
```

---

# Version History

## 1.0.0

Initial public release.

Enhancements from the original Prompt #12 include:

- Coverage Scope Standard
- General vs. policy-specific distinction
- Business-risk-first framework
- Client-relevance analysis
- Scenario Integrity Standard
- Misunderstanding analysis
- Coverage replacement boundaries
- Policy-variable analysis
- Coverage-dependency framework
- Client responsibility analysis
- Related-coverage analysis
- Explanation-readiness classification
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
- Coverage education
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
