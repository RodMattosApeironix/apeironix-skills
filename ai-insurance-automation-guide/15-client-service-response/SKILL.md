---
name: client-service-response
title: Commercial Insurance Client Service Response
collection: ai-insurance-automation-guide
prompt_number: 15
category: commercial-pc
capability: service-intelligence
primary_role: commercial-insurance-account-manager
secondary_roles:
  - commercial-account-executive
  - commercial-insurance-producer
  - client-service-specialist
  - service-team-lead
  - risk-advisor
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Commercial Insurance Client Service Response

## Purpose

Create a clear, efficient, professional response to a commercial insurance client service request that demonstrates responsiveness, establishes ownership, sets realistic expectations, and moves the request toward completion.

This Skill is designed to help the insurance professional:

- Acknowledge the client quickly
- Confirm what is being requested
- Identify what can be handled immediately
- Identify what information is still required
- Clarify who owns the next action
- Set an expected completion time or next-update time
- Communicate carrier or third-party dependencies
- Avoid vague promises
- Reduce unnecessary back-and-forth
- Maintain confidence throughout the service process
- Create a clean client-facing response without internal operational clutter

The objective is **not** to send a generic acknowledgment such as:

> We received your request and will get back to you.

The objective is to tell the client:

> We understand what you need, here is what is happening now, here is what we need from you if anything, and here is when you will hear from us next.

---

# Core Outcome

A successful use of this Skill should leave the client understanding:

- That the request was received
- That the request was understood correctly
- What action has already been taken
- What still needs to happen
- Whether the client needs to provide anything
- Whether a carrier or another third party is involved
- Who owns the next action
- When the request is expected to be completed
- When the client will receive another update if completion timing is uncertain
- What to do next

The client should not need to send another email simply to ask:

> Did you get this, and what is happening?

---

# Best Used For

Use this Skill when responding to requests involving:

- Certificates of Insurance
- Evidence of insurance
- Auto ID cards
- Policy documents
- Endorsement requests
- Adding or removing vehicles
- Adding or removing drivers
- Adding or removing locations
- Additional insured requests
- Loss payee requests
- Lender requests
- Mortgagee changes
- Name or address changes
- Coverage change requests
- Limit change requests
- Deductible questions
- Billing questions
- Audit questions
- Claims assistance
- Policy cancellation requests
- Reinstatement requests
- Renewal questions
- Underwriting information requests
- Policy-copy requests
- Schedule requests
- Premium questions
- Finance questions
- General policy-service questions

This Skill is particularly useful for high-volume account-management workflows where consistency and speed matter.

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- Binding confirmation
- Coverage authorization
- Carrier approval
- Formal cancellation notice
- Legal advice
- Claim coverage determination
- Carrier-issued documentation
- Compliance-required notices
- A completed endorsement
- Proof that a policy change has taken effect
- A carrier commitment
- A formal service-level agreement unless one already exists

This is a **service communication and workflow-control Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Commercial Insurance Account Managers
- Commercial Account Executives
- Commercial Insurance Producers
- Client Service Specialists
- Service Team Leads
- Risk Advisors
- Agency Service Teams
- Other authorized insurance professionals

---

# Required Inputs

At minimum, provide:

1. **Client service request**

Recommended format:

```text
Request:
[INSERT]
```

The request may be:

- An email
- A text message
- A call note
- A case description
- A portal message
- An internal handoff
- A service ticket

If the request is ambiguous, identify the ambiguity before representing that an action has been completed.

---

# Recommended Inputs

The following inputs materially improve the response:

- Client name
- Contact name
- Company name
- Policy type
- Policy number
- Carrier
- Effective date
- Renewal date
- Request date
- Requested effective date
- Requested change
- Supporting documents
- Contract or certificate holder information
- Vehicle information
- Driver information
- Location information
- Lender information
- Claim information
- Deadline
- Client urgency
- Carrier service standard
- Agency service standard
- Current request status
- Action already taken
- Outstanding client information
- Carrier dependency
- Third-party dependency
- Expected completion time
- Next-update commitment

---

# Preferred Source Documents

Where available, prioritize:

1. Client's current request
2. Current policy documents
3. Current endorsement schedule
4. Current Agency Management System data
5. Carrier service communication
6. Current certificate information
7. Supporting client documents
8. Agency case notes
9. Prior correspondence

Do not rely on stale policy information when current information is available.

---

# Source Hierarchy

When service information conflicts, prioritize:

1. Current client-confirmed request
2. Current policy or carrier record
3. Current carrier communication
4. Current agency system record
5. Current supporting documentation
6. Prior correspondence
7. Internal notes

If the client request conflicts with current policy information:

- Identify the discrepancy
- Do not silently assume which is correct
- Ask for clarification only when the conflict cannot otherwise be resolved
- Avoid taking irreversible action based on uncertain information

---

# Request Interpretation Standard

Before drafting the response, determine exactly what the client is asking for.

Classify the request as one or more of:

- Information request
- Document request
- Policy change request
- Coverage change request
- Billing request
- Claims assistance
- Certificate request
- Administrative correction
- Cancellation request
- Renewal request
- Underwriting requirement
- Urgent service request
- Other

Then identify:

- Requested outcome
- Requested effective date
- Deadline
- Information provided
- Information missing
- Authority required
- Carrier involvement required

Do not confuse the client's stated request with the action actually authorized.

---

# Request Status Standard

Every service request should be classified internally as one of the following:

## Received

The request has been received but no substantive action has yet been taken.

## In Progress

The agency has begun processing the request.

## Waiting on Client

The request cannot move forward until the client provides information or authorization.

## Waiting on Carrier

The agency has submitted the request and is awaiting carrier action.

## Waiting on Third Party

Completion depends on another party.

## Completed — Agency Action

The agency's portion of the work is complete, but final carrier processing may remain.

## Completed — Confirmed

The requested action has been completed and appropriately confirmed.

## Unable to Complete

The request cannot be completed as requested and requires another solution.

Do not tell the client that a request is complete merely because it was submitted to the carrier.

---

# Evidence Classification

Every material statement should be treated as one of the following.

## Confirmed Action

An action that has actually been completed.

Example:

> We submitted the vehicle-add request to the carrier this morning.

---

## Pending Action

An action that has not yet been completed.

Example:

> The carrier is reviewing the requested endorsement.

---

## Client Requirement

Information or authorization needed from the client.

Example:

> We still need the vehicle VIN before the change can be submitted.

---

## Third-Party Dependency

Completion depends on the carrier, lender, claims adjuster, vendor, or another party.

Example:

> Once the carrier processes the endorsement, we will send you the updated evidence of insurance.

---

## Estimated Timeline

A reasonable expectation based on known workflow timing.

Example:

> We expect a carrier response within two business days.

Do not present an estimate as guaranteed.

---

# Confidence Classification

Where useful, classify operational statements:

### High Confidence

Action or timing is directly confirmed.

### Moderate Confidence

Timing is based on normal workflow but depends on another party.

### Low Confidence

Outcome or timing remains uncertain.

Do not create artificial certainty.

---

# Core Principle

## Responsiveness Is More Than Speed

A fast reply that does not clarify ownership or next steps is not strong service.

A high-quality service response should answer four questions:

1. Did you understand my request?
2. What are you doing about it?
3. Do you need anything from me?
4. When will I hear from you again?

---

# Workflow

Follow the workflow in order unless circumstances clearly require another sequence.

---

## Step 1 — Identify the Client's Requested Outcome

Determine what the client ultimately wants.

Examples:

- Certificate issued
- Vehicle added
- Location removed
- Policy copy sent
- Claim reported
- Billing corrected
- Additional insured added
- Cancellation processed
- Coverage reviewed

Focus on the outcome, not just the wording of the email.

---

## Step 2 — Identify Urgency

Determine whether the request is:

### Routine

Normal service request with no immediate deadline.

### Time Sensitive

A deadline exists.

### Urgent

Delay could cause meaningful business disruption.

### High Stakes

Potential coverage lapse, uninsured exposure, cancellation, claim escalation, or significant financial impact exists.

Higher-risk requests should receive increased human attention.

---

# Urgency Classification Standard

Do not label every client request urgent.

Urgency should be based on:

- Effective date
- Contract deadline
- Closing date
- Vehicle acquisition
- Jobsite requirement
- Coverage lapse risk
- Claim deadline
- Legal or regulatory deadline
- Business interruption risk

Use actual facts.

---

## Step 3 — Identify Whether the Request Is Complete

Ask:

> Do we have everything needed to move this request forward?

Potential missing information includes:

- Effective date
- VIN
- Driver name
- Driver license
- Address
- Certificate holder
- Additional insured wording
- Contract
- Lender information
- Payroll
- Revenue
- Coverage selection
- Signed authorization
- Cancellation form
- Claim details

Do not ask the client for information that is already available in current agency or carrier records.

---

# Information Reuse Standard

Before asking the client to provide information:

1. Check the information already supplied in the request
2. Check available policy or agency records
3. Check prior relevant client communication where appropriate
4. Ask only for information genuinely needed and unavailable

Do not create client friction by repeatedly requesting information the agency already possesses.

---

## Step 4 — Identify Authority Requirements

Determine whether the agency can:

- Complete the request directly
- Submit the request to the carrier
- Provide information only
- Require named-insured authorization
- Require carrier approval
- Require underwriting approval

Do not represent that a policy change has been made when only a request has been submitted.

---

## Step 5 — Identify Immediate Agency Action

Determine what can be done now.

Examples:

- Pull policy documents
- Issue certificate within authority
- Submit endorsement
- Contact carrier
- Open claim
- Request billing correction
- Review coverage
- Prepare cancellation request
- Update internal records
- Escalate issue

Take or clearly identify the next executable action.

---

## Step 6 — Identify Client Dependencies

If client action is required, specify:

### What Is Needed

[Information / authorization]

### Why It Is Needed

[Reason]

### Deadline

[If applicable]

### How to Provide It

[Email / portal / attachment / signature]

Avoid broad statements such as:

> We need more information.

---

## Step 7 — Identify Carrier or Third-Party Dependencies

Determine whether completion depends on:

- Carrier service center
- Underwriter
- Billing department
- Claims adjuster
- Premium finance company
- Lender
- Certificate holder
- Vendor
- TPA

Explain the dependency without making the client manage it.

---

## Step 8 — Establish Ownership

Every action should have an owner.

Potential owners:

- Agency
- Client
- Carrier
- Underwriter
- Claims adjuster
- Billing department
- Premium finance company
- Lender
- Other third party

Use clear language.

Example:

> We have submitted the request to the carrier. Our team will follow up with them, and you do not need to contact the carrier directly.

---

# Ownership Standard

Avoid ambiguous statements such as:

> This is being worked on.

Prefer:

> Our service team submitted the request to Travelers today and will follow up with underwriting if we have not received a response by Wednesday.

---

## Step 9 — Establish Completion Timeline

If the completion time is known, state it.

Example:

> We expect to have the certificate to you by 3:00 p.m. today.

If timing depends on another party, explain that.

Example:

> The request is now with underwriting. Their normal turnaround is approximately two business days, and we will update you sooner if we receive a response.

Do not guarantee third-party timelines.

---

## Step 10 — Establish Next-Update Commitment

If completion timing is uncertain, set the next communication point.

Example:

> If we do not have the endorsement by Thursday, we will still send you a status update that afternoon.

The client should not have to chase the agency.

---

# Next-Update Standard

For open service requests, provide either:

- Expected completion time

or

- Next-update time

Every open material service request should have at least one.

---

## Step 11 — Draft the Acknowledgment

Keep acknowledgment concise.

Examples:

> Thanks for sending this over. We can help with the vehicle change.

> I received your request for the updated certificate and am working on it now.

Avoid excessive introductions.

---

## Step 12 — Confirm the Requested Action

Restate the request only when it improves clarity.

Example:

> We'll add the 2026 Ford F-250 effective August 20 and remove the 2021 Silverado.

This helps catch misunderstandings before processing.

---

## Step 13 — Explain What Has Been Done

Use precise language.

Examples:

> We submitted the change to the carrier this morning.

> I pulled the policy and am reviewing the additional insured requirement against the contract.

> The certificate has been issued and is attached.

Do not write:

> Taken care of.

unless the requested outcome is actually complete.

---

## Step 14 — Explain What Is Still Required

If anything remains:

> To complete the change, we still need the VIN and purchase date.

Keep the request specific.

---

## Step 15 — State Timing

Use actual expected timing.

Examples:

> We expect to have this completed today.

> The request requires carrier approval. We expect an update within two business days.

> I will update you by Friday afternoon even if the carrier review is still pending.

---

## Step 16 — State Client Next Step

If no client action is required, say so when useful:

> Nothing further is needed from you at this time.

If action is required:

> Please send the signed form, and we will submit the cancellation as soon as it is received.

---

## Step 17 — Close With Control

The closing should reinforce ownership.

Examples:

> We'll monitor this through completion and send the updated documents as soon as they are available.

or:

> Once we receive the VIN, we'll take it from there.

Avoid vague closings such as:

> Let us know if you need anything else.

when a more specific service commitment is appropriate.

---

# Service Completion Standard

Do not treat these actions as equivalent:

### Request Received

The client asked for something.

### Request Submitted

The agency sent the request to the carrier.

### Request Approved

The carrier approved the request.

### Request Processed

The carrier completed the transaction.

### Documentation Received

The updated policy evidence is available.

### Client Confirmed

The client has received the final result when appropriate.

The service workflow should use the correct completion stage.

---

# Decision Rules

## Acknowledge Without Overwriting

The client does not need a long introductory paragraph.

---

## Do Not Ask for Information Already Available

Reuse reliable information where possible.

---

## Do Not Say "Completed" When Only Submitted

This is one of the most important service rules.

---

## Every Open Request Needs Timing

State either:

- Completion expectation

or

- Next-update timing

---

## Every Required Action Needs an Owner

Client, agency, carrier, or third party.

---

## Carrier Dependency Should Not Become Client Work

The agency should manage normal carrier follow-up unless the client specifically needs to act.

---

## Avoid False Precision

Do not invent exact completion times.

---

## Client Clarity Over Internal Workflow

Do not expose unnecessary internal case-routing details.

---

## Concise Does Not Mean Incomplete

Include all information necessary for the client to know:

- Status
- Action
- Timing
- Next step

---

# Materiality / Prioritization Framework

Prioritize response content using:

| Factor | Question |
|---|---|
| Client Action | Does the client need to do something? |
| Urgency | Is there a deadline? |
| Coverage Impact | Could delay affect protection? |
| Financial Impact | Could delay affect cost or payment? |
| Operational Impact | Could the client's business be disrupted? |
| Dependency | Does another party control completion? |
| Timing | When can the client expect a result? |
| Uncertainty | Is any outcome unresolved? |

Put the most decision-relevant information first.

---

# Output Requirements

Use the following structure unless the user requests another format.

---

# Client Service Response

## Service Assessment

**Request Type:** [Certificate / Endorsement / Billing / Policy / Claim / Other]  
**Urgency:** Routine / Time Sensitive / Urgent / High Stakes  
**Status:** Received / In Progress / Waiting on Client / Waiting on Carrier / Waiting on Third Party / Completed

---

# 1. Internal Request Summary

Provide a concise internal summary before drafting the client response.

### Client Requested

[Request]

### Action Already Taken

[Action]

### Information Missing

[If any]

### Agency Owner

[Owner if known]

### External Dependency

[Carrier / third party if applicable]

### Expected Completion

[Timing]

### Next Update

[Timing]

This section is internal and should not appear in the client-facing message unless appropriate.

---

# 2. Suggested Subject Line

Provide one concise subject line.

Examples:

- Update on Your Certificate Request
- Vehicle Change Request — Next Steps
- Policy Change Request Received
- Update on Your Billing Request
- Documents Requested

---

# 3. Client Response

Draft the complete response.

Recommended structure:

### Acknowledgment

Brief confirmation that the request was received.

### Action / Status

Explain what has already been done or what is happening now.

### What We Need

Identify any missing client information.

### Timing

State expected completion or next-update time.

### Next Step

Make the client's role clear.

### Closing

Reinforce ownership.

---

# 4. Client Action Required

When applicable:

| Action | Deadline | Why Needed |
|---|---|---|
| [Action] | [Date] | [Reason] |

Omit when no client action is required.

---

# 5. Internal Follow-Up Actions

| Action | Owner | Due | Status |
|---|---|---|---|
| [Action] | [Agency / Carrier / Client] | [Date] | [Status] |

Use for operational follow-through.

---

# 6. Completion Criteria

State what must occur before the request should be considered complete.

Example:

> Complete when the carrier processes the vehicle change, revised policy documentation is received, and the updated auto ID card is sent to the client.

This prevents requests from being closed prematurely.

---

# Short Response Version

When requested, provide a short version suitable for quick service emails.

Structure:

> Hi [Name],  
>
> I received your request for [request]. [Action taken/current status].  
>
> [Information needed, if any.]  
>
> We expect [completion timing], or I will update you by [next-update time].  
>
> [Client next step / Nothing further needed from you.]  
>
> We'll monitor this through completion.

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Client request is correctly understood
- [ ] Requested outcome is identified
- [ ] Request type is classified
- [ ] Urgency is realistic
- [ ] Available agency data was considered before asking the client for more information
- [ ] Required client information is specific
- [ ] Authority requirements are considered
- [ ] Action already taken is accurately stated
- [ ] Carrier submission is not described as completion
- [ ] Client action is clear
- [ ] Agency action is clear
- [ ] Carrier or third-party dependency is clear
- [ ] Every material action has an owner
- [ ] Expected completion timing is realistic
- [ ] Open requests have a next-update commitment
- [ ] No carrier timeline is guaranteed without confirmation
- [ ] Completion criteria are clear
- [ ] No unnecessary internal workflow details appear in the client message
- [ ] Response is concise
- [ ] Client should not need to ask what happens next

---

# Failure Conditions

The Skill should not be considered complete if:

- The response merely says the request was received
- The requested outcome is unclear
- The client is asked for information already available
- The agency says an action is complete when it was only submitted
- Client action is vague
- Carrier dependency is hidden
- Ownership is unclear
- No timing is provided
- No next-update commitment exists for an unresolved material request
- Unverified carrier timing is presented as guaranteed
- Internal operational jargon overwhelms the response
- Completion criteria are undefined
- The client would reasonably need to follow up to understand status

If any failure condition exists, revise before finalizing.

---

# Guardrails

## Do Not Fabricate Service Activity

Never claim that:

- A request was submitted
- A carrier was contacted
- A policy was changed
- A certificate was issued
- A claim was reported
- A payment was processed
- An endorsement was approved

unless the available information confirms that action occurred.

---

## Do Not Represent a Requested Change as Bound

A client request to change coverage does not establish that the change is effective.

Distinguish:

- Requested
- Submitted
- Approved
- Bound
- Processed

where applicable.

---

## Do Not Promise Third-Party Performance

Do not guarantee:

- Carrier turnaround
- Underwriter response
- Claims processing
- Lender response
- Vendor response

unless confirmed.

---

## Do Not Close Requests Prematurely

A task is not necessarily complete because the agency's initial action is done.

Confirm the intended client outcome.

---

## Do Not Create Coverage

Service communication must not imply coverage exists before authorized placement or endorsement.

---

## Do Not Cancel Coverage Without Proper Authority

Cancellation requests may require:

- Named-insured authorization
- Signed documentation
- Carrier requirements
- Effective-date confirmation

Follow applicable agency and carrier procedures.

---

## Do Not Provide Unsupported Coverage Advice

If a service request raises a coverage question requiring professional review, escalate appropriately.

---

## No Legal Advice

Requests involving contractual, regulatory, or legal issues may require further review.

Do not provide unsupported legal conclusions.

---

## Protect Confidential Information

Use only information necessary to process the request.

Do not unnecessarily expose:

- Driver license numbers
- Social Security numbers
- Financial account information
- Sensitive claim information
- Employee information
- Credentials
- Confidential internal notes

Use secure methods when appropriate.

---

## Preserve Human Accountability

This Skill supports the insurance professional.

The authorized insurance professional remains responsible for:

- Service execution
- Policy changes
- Coverage representations
- Carrier instructions
- Cancellation requests
- Client communication
- Documentation
- Compliance
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced commercial insurance account manager who is responsive, organized, and in control of the request.

The tone should be:

- Concise
- Professional
- Helpful
- Confident
- Direct
- Calm
- Client-centered
- Action-oriented

Avoid:

- Long explanations
- Internal jargon
- Vague promises
- Excessive apology
- Passive language
- Robotic acknowledgments
- Unnecessary technical detail
- Overpromising

The client should feel:

> They understood my request, they are handling it, and I know what happens next.

---

# Example

## Example Request

```text
Request:

Hi Sarah,

We purchased a new Ford F-350 yesterday and need it added to the policy. We are trading in the 2022 Chevrolet Silverado.

The dealership needs proof of insurance today.

The new truck VIN is 1FT8W3BT0RED12345.

Thanks,
Mike
```

---

## Example Output

### Service Assessment

**Request Type:** Vehicle Change / Evidence of Insurance  
**Urgency:** Time Sensitive  
**Status:** In Progress

### Internal Request Summary

**Client Requested:**
- Add new Ford F-350
- Remove 2022 Chevrolet Silverado
- Provide proof of insurance to dealership today

**Available Information:**
- New vehicle VIN supplied
- Requested timing supplied

**Items to Confirm:**
- Effective date should be confirmed as purchase date if not already established
- Existing vehicle record should be matched to confirm the correct Silverado being removed

**Agency Action:**
Submit the vehicle change and issue or obtain appropriate proof of insurance within agency/carrier authority.

---

### Suggested Subject Line

New Ford F-350 — Insurance Update in Progress

### Client Response

Hi Mike,

Thanks for sending the new truck information. We have the VIN for the Ford F-350 and are working on the vehicle change now.

We will add the new truck and remove the 2022 Chevrolet Silverado from the policy, subject to the carrier's processing requirements.

Our priority is getting the dealership the appropriate proof of insurance today. We will send that as soon as the change is processed or once we have the documentation needed to provide evidence within our authority.

Nothing further is needed from you right now unless we find that we need to confirm the exact Silverado being removed.

We'll keep this moving and update you today once the proof of insurance is ready.

Best,

Sarah

---

# Example 2 — Waiting on Client

## Request

```text
Please add our landlord as an additional insured and send them a certificate.
```

## Example Response

Hi [Client Name],

Absolutely—we can help with that.

To make sure we issue the certificate correctly, please send us the landlord's full legal name and address, along with the insurance requirements from the lease if available.

Once we have that information, we'll review the request and issue the certificate if it falls within the existing policy terms. If carrier approval or an endorsement is required, we'll handle that process and keep you updated.

Once you send the landlord information, we'll take it from there.

Best,

[Account Manager]

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are an experienced account manager responding to a client service request. Your goal is to provide a clear, efficient, and professional response that sets expectations and moves the request forward.
>
> Review the request below and create a structured response that demonstrates responsiveness and control of the situation.
>
> Request:
> [INSERT]
>
> Think from the client’s perspective—they want clarity, speed, and confidence that their request is being handled properly.
>
> Structure your response as:
>
> - A brief acknowledgment of the request
> - Action taken or what is required to move forward
> - Expected timeline for completion or next update
> - Clear next steps for the client (if applicable)
>
> Keep the message concise, direct, and easy to understand. Avoid unnecessary detail while ensuring nothing important is left unclear.

---

# Evolution From Prompt to Skill

The original prompt established the goal of creating a concise and professional client service response.

This Skill expands that prompt into a reusable Service Intelligence workflow by adding:

- Required inputs
- Recommended inputs
- Preferred source documents
- Source hierarchy
- Request Interpretation Standard
- Request Status Standard
- Evidence classification
- Urgency Classification Standard
- Request completeness review
- Information Reuse Standard
- Authority assessment
- Immediate-action framework
- Client dependency analysis
- Carrier / third-party dependency analysis
- Ownership Standard
- Completion timeline
- Next-Update Standard
- Service Completion Standard
- Completion criteria
- Short Response Version
- Internal follow-up actions
- Quality-control checklist
- Failure conditions
- Insurance-specific guardrails
- Example implementations

The purpose is to transform a service-response prompt into a reusable **Client Service Intelligence Skill**.

---

# Related Skills

Related Apeironix Skills include:

- [Commercial Insurance Post-Meeting Follow-Up](../05-post-meeting-follow-up/SKILL.md)
- [Commercial Insurance Policy Explanation in Plain English](../11-policy-explanation-plain-english/SKILL.md)
- [Commercial Insurance Coverage Explanation](../12-coverage-explanation/SKILL.md)
- [Commercial Insurance Client Situation Communication](../14-client-situation-communication/SKILL.md)
- Certificate Request Processing
- Policy Change Processing
- Endorsement Request Handling
- Billing Issue Resolution
- Claims Service Response
- Client Service Case Triage

Links should be added as those Skills are published.

---

# Suggested Invocation

```text
Prepare a Commercial Insurance Client Service Response.

Client:
[OPTIONAL]

Request:
[INSERT]

Current Status:
[OPTIONAL]

Action Already Taken:
[OPTIONAL]

Information Needed:
[OPTIONAL]

Carrier / Third-Party Dependency:
[OPTIONAL]

Expected Completion:
[OPTIONAL]

Next Update:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Request:
[INSERT]
```

---

# Version History

## 1.0.0

Initial public release.

Enhancements from the original Prompt #15 include:

- Request Interpretation Standard
- Request Status Standard
- Service-status classification
- Urgency Classification Standard
- Request completeness analysis
- Information Reuse Standard
- Authority assessment
- Client / agency / carrier ownership framework
- Ownership Standard
- Next-Update Standard
- Service Completion Standard
- Completion criteria
- Internal follow-up workflow
- Short Response Version
- Quality-control standards
- Failure conditions
- Insurance-specific guardrails
- Example implementations

---

# About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for:

- Judgment
- Relationships
- Client service
- Risk advisory
- Account management
- Service execution
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
