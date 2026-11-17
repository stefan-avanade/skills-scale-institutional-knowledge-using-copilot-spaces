# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Project Sponsors / Business Owners

### Role Summary
Project Sponsors or Business Owners provide executive-level accountability for the business need, expected outcomes, and resources for an initiative.

### Responsibilities
- Champion the business case and confirm alignment with organizational priorities
- Secure or coordinate required funding, capacity, and decision-maker support
- Make or escalate material scope, priority, and investment decisions
- Review progress against intended business outcomes and resolve escalated barriers

### Goals
- Deliver measurable business value
- Ensure the initiative has appropriate authority and resources
- Make timely decisions when delivery trade-offs require sponsor input

### Typical Communication
- Sponsor checkpoints and milestone reviews
- Decision and escalation updates from the Project Manager
- Outcome reviews with the Product Manager and stakeholders

### Collaboration with Existing Roles
- Align with the Product Manager on desired outcomes, success measures, and priority changes
- Partner with the Project Manager on governance, resources, escalations, and milestone decisions
- Consult Developers and QA/Testing through the delivery leads when business decisions affect feasibility, scope, or acceptance
- Provide stakeholders with a clear path for approvals and decisions

---

## Business Analysts

### Role Summary
Business Analysts connect stakeholder needs to clear, actionable requirements and business processes that the delivery team can validate.

### Responsibilities
- Elicit, analyze, and document business needs, workflows, assumptions, and constraints
- Translate needs into requirements and support measurable acceptance criteria
- Maintain traceability between stakeholder needs, backlog items, and delivered outcomes
- Identify requirement gaps, conflicts, and process impacts early

### Goals
- Ensure the team builds a shared understanding of the problem and expected behavior
- Reduce ambiguity, rework, and missed requirements
- Make requirements testable and aligned with business outcomes

### Typical Communication
- Stakeholder interviews and requirements workshops
- Backlog refinement and acceptance-criteria reviews
- Process maps, requirement notes, and decision records

### Collaboration with Existing Roles
- Work with the Product Manager to refine needs, scope, priorities, and acceptance criteria
- Coordinate with the Project Manager to schedule discovery, track decisions, and surface dependencies
- Clarify requirements with Developers and QA/Testing so implementation and verification reflect intended behavior
- Validate that stakeholder needs are represented and raise unresolved conflicts to the Product Manager or Sponsor

---

## UX/UI Designers and Researchers

### Role Summary
UX/UI Designers and Researchers investigate user needs and shape accessible, usable experiences that support the product's intended outcomes.

### Responsibilities
- Plan and conduct user research or usability evaluation appropriate to the initiative
- Create and maintain user flows, interaction designs, prototypes, and interface specifications
- Identify usability and accessibility considerations and communicate design requirements
- Use research and feedback to recommend experience improvements

### Goals
- Make products useful, understandable, and accessible to their intended users
- Validate design assumptions before and during implementation
- Keep user needs visible alongside business and technical constraints

### Typical Communication
- Research readouts and design reviews
- Prototypes, design specifications, and usability findings
- Collaboration in backlog refinement and acceptance-criteria reviews

### Collaboration with Existing Roles
- Partner with the Product Manager to connect user research and design decisions to product outcomes and priorities
- Coordinate with the Project Manager on discovery and design milestones and communicate risks to the plan
- Work with Developers to explain designs, review implementation, and resolve feasibility trade-offs
- Work with QA/Testing to include usability and accessibility expectations in validation
- Share relevant findings with Stakeholders while protecting user research privacy and context

---

## Technical Leads / Architects

### Role Summary
Technical Leads or Architects guide technical design and integration decisions so the solution is maintainable, secure, and feasible within project constraints.

### Responsibilities
- Establish or clarify technical direction, architecture, and engineering standards
- Identify technical dependencies, integration points, and implementation risks
- Support Developers with design decisions and complex technical issues
- Advise on non-functional requirements such as reliability, performance, and security

### Goals
- Deliver a coherent, maintainable solution that meets technical and product needs
- Identify architectural risks and dependencies early
- Enable consistent engineering decisions across components and teams

### Typical Communication
- Technical design documents and architecture reviews
- Engineering planning and dependency discussions
- Risk and trade-off updates with delivery and product leads

### Collaboration with Existing Roles
- Guide and support Developers without taking over their implementation ownership
- Work with the Product Manager to assess technical options and clarify trade-offs against product priorities
- Coordinate with the Project Manager on sequencing, cross-team dependencies, estimates, and technical risks
- Partner with QA/Testing to make solutions testable and address quality attributes
- Explain material technical implications to Stakeholders through the Product Manager or Project Manager

---

## DevOps / Release Managers

### Role Summary
DevOps or Release Managers coordinate the systems and operational steps needed to build, deploy, monitor, and, when needed, roll back a release.

### Responsibilities
- Coordinate release plans, deployment readiness, and environment dependencies
- Maintain or operate build and deployment automation in collaboration with engineering
- Confirm monitoring, rollback, and release verification plans are ready
- Surface deployment constraints and operational risks before release

### Goals
- Make releases repeatable, observable, and low risk
- Ensure teams can detect and respond to deployment issues
- Improve coordination between development and operational readiness

### Typical Communication
- Release plans and readiness checkpoints
- Deployment pipeline and environment updates
- Go/no-go, monitoring, and post-deployment status reports

### Collaboration with Existing Roles
- Work with Developers to ensure build, configuration, and deployment needs are understood
- Coordinate with QA/Testing on environment availability, smoke tests, and release verification
- Partner with the Project Manager on release timing, readiness, risks, and stakeholder communications
- Align with the Product Manager and Stakeholders on release scope and timing, and with Operations/Support on handoff and monitoring

---

## Operations / Support Representatives

### Role Summary
Operations or Support Representatives bring service-readiness and customer-support needs into delivery and provide a feedback path after release.

### Responsibilities
- Identify operational requirements, support workflows, and service dependencies
- Prepare support documentation, knowledge transfer, and escalation paths
- Advise on monitoring, incident response, and service-readiness needs
- Share customer feedback and recurring operational issues with the delivery team

### Goals
- Ensure teams can support and operate delivered capabilities
- Reduce avoidable customer impact and time to resolve incidents
- Feed operational learning into product and process improvements

### Typical Communication
- Operational-readiness and handoff reviews
- Support documentation and incident or service updates
- Feedback summaries in backlog refinement and retrospectives

### Collaboration with Existing Roles
- Coordinate with the Project Manager on readiness milestones, handoffs, dependencies, and escalations
- Work with the Product Manager to prioritize support insights and operational needs in the backlog
- Partner with Developers and QA/Testing on diagnostics, supportability, and incident follow-up
- Align with DevOps/Release Managers on deployment monitoring, rollback, and release handoff
- Keep Stakeholders informed of material service impacts through agreed communication channels

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign or combine roles according to project size and context, while keeping decision ownership and handoffs explicit.
