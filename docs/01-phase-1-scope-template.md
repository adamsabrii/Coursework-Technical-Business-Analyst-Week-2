# Phase 1 Scope Template

Use this to define a disciplined Smart-Recovery first release.

## In scope

List the capabilities you believe should be built in Phase 1.

Starter examples:
- identity verification
- account summary and eligible actions
- promise-to-pay capture
- eligible payment-plan selection
- rules-based routing to agents
- portal outcome reporting

Additions:
- real-time payment status updates
    - when a customer makes a payment and is processed this should automatically reflect on their account and visible to the agents without sifting through communications with payments department
- client profile lookup with interaction history
    - agents should be able to quickly verify client information and their contact history with related information
- automated customer notifications for simple follow-ups
    - after a customer is contacted there should be an automatic notification system (possibly email) that will follow-up on their repayments
- automated agent alerts for phone-up contact
    - when a customer is due for a phone up, account data should reflect this status and the related agent should be notified to make the call.
- agent-customer assignment with alerts for case updates
    - as part of the logging process and agent should be identifiable for that activity
    - agents will be made aware if their case has been resolved, they have transferred it to another agent.

## Out of scope

Be explicit.

Starter examples:
- hardship assessment
- bespoke repayment negotiation
- legal escalation workflow
- major core-platform replacement
- advanced personalisation

Additions:
- data migration from legacy database
    - although, the database is old and may require some modernisation it will require large amounts of upfront investment and will not directly benefit the in time or revenue savings.
- system for tracking agent performance via agent profiles
    - this would help encourage improved agent performance, however; it's productivity benefits are minimal and would be considered an optimisation capability for Phase 2.
- AI-driven case escalation handling
    - as it is a complex task the requires some human judgement, automation here is quite difficult when this isn't the main concern of the stakeholders.
- advanced self-serve features
    - this requires human judgement with variations case by case, therefore making it difficult for automation at this point.

## Assumptions

Record what must be true for this scope to work.

Examples:
- legacy data needed for account summary is accessible enough for Phase 1
- eligibility rules can be agreed without full policy redesign
- operations will support a limited pilot or phased rollout

Additions:
- email and other communications channels are accessible enough to build customer profiles with existing history
- client account data is sufficient to populate profiles without significant cleaning first
- IT team can support integration work within the Phase 1 timeline
- case ownership is attributable

## Dependencies and constraints

Note the most important delivery and operating constraints.

Examples:
- legacy system data availability
- compliance approval for messages and audit trail
- agent workflow alignment for routed cases

Additions:
- cannot modify the legacy database schema
- stakeholder agree on prioritsations before Phase 1 begins
- agent adoption has to be achievable without extensive retraining

## Why this scope is credible

Write 1-2 paragraphs linking the chosen scope to:
- Week 1 top-ranked opportunities
- measurable value
- delivery feasibility
- change and adoption risk


The main two automation opportunities priorities are a self-serve portal, which automates the process of handling straightforward cases, and an
internal agent portal, which automates the process of recovering customer information and interaction history. Scope seeks to automate all straightforward cases to view account balance, make payments, capture promise-to-pay and payment plan selection. The portal would necessarily be able to verify the user's identity and even if the user gets routed to an agent to handle more complex cases, an portal outcome is reported. For the internal agent portal the scope seeks to provide the capability to be connected to a centralised system which allows the agent to quickly see client interaction history. The interaction history would include which agents have worked on the case, with a description on what occurred. This would be connected to a notification system that can inform customers about their repayments through automated email reminder or notify agents to make and phone-in follow-up. Directionally speaking, the scope will recover agent time that can be spent handling complex cases that cannot be automated. The automated cases alone will bring revenue uplift in able to retrieve repayments with minimal effort. For the agent portal, there will be less time per account, fewer missed follow-ups and fewer repeated contacts. Directly addressing the delays in case handling.

The feasibility of delivery rests on the legacy data being sufficiently complete to populate profiles without significant cleansing, communication channels being accessible enough to support the notification system, and IT being able to support integration work within the Phase 1 timeline. The constraint of the schema of the database is that the scope must be designed around the existing database structure rather than improving it. Importantly, success replies on stakeholder agreement on prioritisation  before build begins to avoid decisions bleeding into delivery. On adoption, the greater risk is that since agents have entrenched workarounds built out of necessity, the portal needs to be demonstrably faster from day one or behaviour will not change. The case assignment system also depends on accounts being cleanly ownable, if it's not clear which agent a case belongs to, that problem needs resolving before the system can do its job.


