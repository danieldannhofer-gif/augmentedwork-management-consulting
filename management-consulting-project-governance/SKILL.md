---
name: "management-consulting-project-governance"
description: "Establish governance structures, decision rights, and oversight mechanisms for projects and programs. Use when setting up project governance, defining decision-making authority, or creating oversight frameworks."
---
# Project Governance

Establish governance structures, decision rights, and oversight mechanisms to ensure projects deliver intended outcomes, manage risks, and maintain alignment with strategic objectives.

## Trigger

User runs `/management-consulting-project-governance` or asks about project governance, decision rights, or oversight structures.

## Inputs

Gather the following from the user:

1. **Project context**:
   - Project type and scope
   - Strategic importance
   - Budget and timeline
   - Stakeholders involved

2. **Current state**:
   - Existing governance (if any)
   - Current decision-making processes
   - Pain points or issues

3. **Requirements**:
   - Regulatory or compliance requirements
   - Organizational standards
   - Specific governance needs

4. **Constraints**:
   - Organizational structure
   - Resource availability
   - Cultural considerations

## Governance Framework

### Governance Levels

**Three Levels of Governance**:

1. **Strategic Governance** (Steering Committee/Executive Level)
   - **Purpose**: Ensure alignment with business strategy and objectives
   - **Focus**: Strategic direction, resource allocation, major decisions
   - **Frequency**: Monthly or quarterly
   - **Authority**: Approve scope changes, budget adjustments, major risks

2. **Tactical Governance** (Project Management Level)
   - **Purpose**: Ensure effective project execution
   - **Focus**: Planning, monitoring, issue resolution, resource management
   - **Frequency**: Weekly or bi-weekly
   - **Authority**: Day-to-day decisions, task prioritization, minor adjustments

3. **Operational Governance** (Team Level)
   - **Purpose**: Ensure quality and efficiency of work
   - **Focus**: Task execution, quality assurance, collaboration
   - **Frequency**: Daily or as needed
   - **Authority**: Task-level decisions, quality checks, process improvements

### Governance Structure

**Typical Governance Bodies**:

1. **Steering Committee**
   - **Members**: Executive sponsor, project sponsor, key stakeholders, external advisors (if needed)
   - **Chair**: Executive sponsor or most senior stakeholder
   - **Responsibilities**:
     - Approve project charter and scope
     - Allocate resources and budget
     - Review progress and make strategic decisions
     - Escalate issues beyond project manager authority
     - Ensure alignment with business strategy
     - Approve major changes (scope, budget, timeline)
     - Resolve cross-functional conflicts
   - **Meeting Cadence**: Monthly or as needed
   - **Reporting**: High-level status, strategic issues, decisions needed

2. **Project Management Office (PMO)**
   - **Members**: Project manager, program manager (if applicable), PMO lead
   - **Responsibilities**:
     - Develop and maintain project management standards
     - Provide project management tools and templates
     - Monitor project health and performance
     - Identify and resolve cross-project dependencies
     - Report to steering committee
     - Mentor project managers
     - Ensure consistency across projects
   - **Meeting Cadence**: Weekly or bi-weekly
   - **Reporting**: Project status, issues, risks, resource needs

3. **Project Team**
   - **Members**: Project manager, workstream leads, team members
   - **Responsibilities**:
     - Execute project tasks
     - Monitor progress and quality
     - Identify and escalate issues
     - Collaborate across workstreams
     - Report to project manager
   - **Meeting Cadence**: Weekly (team), daily (stand-ups if Agile)
   - **Reporting**: Task progress, blockers, deliverables

**Governance Structure Example**:
```
[Executive Leadership]
       ↓
[Steering Committee] — Strategic oversight, major decisions
       ↓
[PMO / Program Manager] — Cross-project coordination
       ↓
[Project Manager] — Day-to-day management
       ↓
[Workstream Leads] — Workstream execution
       ↓
[Team Members] — Task execution
```

### Decision Rights Framework

**Decision Categories**:

1. **Strategic Decisions** (Steering Committee)
   - Project approval and funding
   - Major scope changes
   - Significant budget adjustments
   - Resource allocation across projects
   - Risk acceptance for major risks
   - Go/no-go decisions at key milestones

2. **Tactical Decisions** (Project Manager)
   - Project planning and scheduling
   - Task prioritization
   - Resource allocation within project
   - Minor scope adjustments
   - Issue resolution within authority
   - Vendor selection (within budget)

3. **Operational Decisions** (Workstream Leads/Team Members)
   - Task execution approach
   - Quality assurance
   - Daily problem-solving
   - Process improvements
   - Tool selection (within guidelines)

**Decision Rights Matrix**:

| Decision Type | Steering Committee | PMO | Project Manager | Workstream Lead | Team Member |
|---------------|-------------------|-----|-----------------|----------------|--------------|
| Approve charter | A | C | R | I | I |
| Allocate budget | A | C | R | I | I |
| Change scope | A | C | R | I | I |
| Prioritize tasks | C | C | A | R | I |
| Resolve issues | C | R | A | C | R |
| Quality checks | I | I | C | A | R |

**Key**:
- A = Approve (final authority)
- R = Recommend (provide input and recommendation)
- C = Consult (must be consulted before decision)
- I = Inform (must be informed after decision)

### Governance Documents

1. **Project Charter**
   - **Purpose**: Authorize the project and define high-level parameters
   - **Contents**:
     - Project name and sponsor
     - Business case and objectives
     - Scope (in scope and out of scope)
     - Key deliverables
     - Success criteria
     - High-level timeline and budget
     - Key stakeholders
     - Assumptions and constraints
     - Risks and mitigation
   - **Approval**: Steering committee

2. **Governance Framework Document**
   - **Purpose**: Define how the project will be governed
   - **Contents**:
     - Governance structure and roles
     - Decision rights and authority levels
     - Escalation paths
     - Meeting cadence and agendas
     - Reporting requirements
     - Change control process
     - Risk management approach
   - **Approval**: Steering committee

3. **Decision Log**
   - **Purpose**: Track key decisions and their rationale
   - **Contents**:
     - Decision date
     - Decision description
     - Decision maker
     - Rationale
     - Impact
     - Related documents
   - **Maintenance**: Updated after each governance meeting

4. **Issue and Risk Register**
   - **Purpose**: Track and manage issues and risks
   - **Contents**:
     - Issue/Risk ID
     - Description
     - Category
     - Impact and likelihood
     - Owner
     - Status
     - Mitigation actions
     - Target resolution date
   - **Maintenance**: Updated regularly (weekly or as issues arise)

### Meeting Cadence and Agendas

**Steering Committee Meeting**:
- **Frequency**: Monthly or quarterly
- **Duration**: 60-90 minutes
- **Attendees**: Steering committee members
- **Agenda**:
  1. Project status overview (10 min)
  2. Strategic issues (20 min)
  3. Major decisions needed (20 min)
  4. Risk review (10 min)
  5. Open discussion (10 min)
  6. Action items and next steps (10 min)

**PMO Review Meeting**:
- **Frequency**: Bi-weekly or monthly
- **Duration**: 45-60 minutes
- **Attendees**: PMO, project managers
- **Agenda**:
  1. Project health dashboard (15 min)
  2. Cross-project dependencies (15 min)
  3. Resource allocation (10 min)
  4. Process improvements (10 min)
  5. Action items (10 min)

**Project Status Meeting**:
- **Frequency**: Weekly
- **Duration**: 30-60 minutes
- **Attendees**: Project manager, workstream leads, key team members
- **Agenda**:
  1. Progress since last meeting (10 min)
  2. Upcoming deliverables (10 min)
  3. Issues and blockers (15 min)
  4. Resource needs (5 min)
  5. Action items (10 min)

**Daily Stand-up (Agile)**:
- **Frequency**: Daily
- **Duration**: 15 minutes
- **Attendees**: Team members
- **Agenda**:
  1. What did I do yesterday?
  2. What will I do today?
  3. What blockers do I have?

### Reporting Framework

**Report Types**:

1. **Executive Dashboard** (Steering Committee)
   - **Frequency**: Monthly
   - **Contents**:
     - Overall project health (Red/Yellow/Green)
     - Key milestones status
     - Budget vs. actual
     - Major risks and issues
     - Upcoming decisions needed
   - **Format**: 1-page visual dashboard

2. **Project Status Report** (PMO/Project Manager)
   - **Frequency**: Weekly or bi-weekly
   - **Contents**:
     - Progress against plan
     - Deliverables completed
     - Upcoming deliverables
     - Issues and blockers
     - Risks and mitigation
     - Resource status
     - Budget status
   - **Format**: 2-3 page report with visuals

3. **Workstream Status** (Workstream Leads)
   - **Frequency**: Weekly
   - **Contents**:
     - Task progress
     - Deliverables status
     - Issues and blockers
     - Resource needs
     - Upcoming tasks
   - **Format**: 1-page summary

**Reporting Best Practices**:
- Tailor to audience (executive vs. operational)
- Focus on exceptions and issues
- Use visual indicators (Red/Yellow/Green)
- Provide context, not just data
- Highlight decisions needed
- Keep it concise

### Change Control Process

**Purpose**: Manage changes to scope, timeline, or budget in a controlled manner.

**Process**:
1. **Identify Change**: Anyone can identify a potential change
2. **Document Change**: Complete change request form
   - Description of change
   - Reason for change
   - Impact on scope, timeline, budget
   - Risk assessment
   - Recommended action
3. **Assess Change**: Project manager assesses impact
   - Detailed impact analysis
   - Resource requirements
   - Timeline implications
   - Cost implications
   - Risk assessment
4. **Approve Change**: Appropriate authority based on change size
   - Minor changes: Project manager
   - Moderate changes: PMO
   - Major changes: Steering committee
5. **Implement Change**: Update plans and communicate
   - Update project plan
   - Update budget
   - Communicate to stakeholders
   - Document in change log

**Change Request Form**:
```
**Change Request**

**Requestor**: [Name, Date]
**Project**: [Name]

**Change Description**:
[Detailed description of the proposed change]

**Reason for Change**:
[Why this change is needed]

**Impact Assessment**:
- Scope: [Increase/Decrease/No change]
- Timeline: [Increase/Decrease/No change] — [New end date]
- Budget: [Increase/Decrease/No change] — [New budget]
- Resources: [Impact on resources]
- Risks: [New risks or changes to existing risks]

**Recommended Action**:
[Approve/Reject/Modify]

**Approval**:
- Project Manager: [Name, Date]
- PMO: [Name, Date] (if required)
- Steering Committee: [Name, Date] (if required)
```

### Escalation Process

**Purpose**: Ensure issues are resolved at the appropriate level.

**Escalation Path**:
1. **Team Level**: Attempt to resolve within team
2. **Workstream Level**: Escalate to workstream lead
3. **Project Level**: Escalate to project manager
4. **PMO Level**: Escalate to PMO for cross-project issues
5. **Steering Committee**: Escalate to steering committee for strategic issues

**Escalation Criteria**:
- **Time**: Issue not resolved within [X] days
- **Impact**: Issue affects multiple workstreams or projects
- **Authority**: Issue beyond current authority level
- **Risk**: Issue poses significant risk to project success

**Escalation Form**:
```
**Issue Escalation**

**Escalated By**: [Name, Date]
**Project**: [Name]
**Workstream**: [Name]

**Issue Description**:
[Detailed description of the issue]

**Impact**:
- Scope: [High/Medium/Low]
- Timeline: [High/Medium/Low]
- Budget: [High/Medium/Low]
- Quality: [High/Medium/Low]

**Actions Taken**:
[What has been tried to resolve the issue]

**Recommended Resolution**:
[What is recommended to resolve the issue]

**Escalation To**: [Name, Role]
```

## Governance for Different Project Types

### Agile Projects
- **Governance**: Lightweight, empowering
- **Decision Rights**: Pushed to teams
- **Meeting Cadence**: Daily stand-ups, sprint reviews, retrospectives
- **Reporting**: Burndown charts, velocity metrics
- **Change Control**: Flexible, iterative

### Waterfall Projects
- **Governance**: Structured, controlled
- **Decision Rights**: Centralized
- **Meeting Cadence**: Phase reviews, stage gates
- **Reporting**: Gantt charts, milestone tracking
- **Change Control**: Formal, documented

### Transformation Programs
- **Governance**: Multi-layered, coordinated
- **Decision Rights**: Distributed with clear escalation
- **Meeting Cadence**: Multiple levels (steering, program, project)
- **Reporting**: Portfolio dashboard, interdependency tracking
- **Change Control**: Program-level oversight

### Research and Development
- **Governance**: Flexible, innovative
- **Decision Rights**: Expert-driven
- **Meeting Cadence**: Regular check-ins, milestone reviews
- **Reporting**: Progress against hypotheses, learning logs
- **Change Control**: Adaptive, experimental

## Output Format

### Governance Framework Document

**Executive Summary**:
- Project overview
- Governance objectives
- Key governance bodies
- Decision rights summary

**Governance Structure**:
- Organizational chart
- Roles and responsibilities
- Reporting lines

**Decision Rights**:
- Decision categories
- Authority levels
- Escalation paths

**Meeting Cadence**:
- Meeting schedule
- Attendees
- Agendas
- Reporting

**Processes**:
- Change control process
- Issue escalation process
- Risk management process
- Reporting framework

**Templates**:
- Project charter template
- Change request form
- Issue escalation form
- Status report templates

### Governance Setup Checklist

- [ ] Steering committee established
- [ ] PMO established (if needed)
- [ ] Project manager assigned
- [ ] Workstream leads identified
- [ ] Decision rights defined
- [ ] Escalation paths established
- [ ] Meeting cadence set
- [ ] Reporting framework defined
- [ ] Change control process documented
- [ ] Issue escalation process documented
- [ ] Governance framework approved
- [ ] Kickoff meeting conducted

## After Governance Setup

Ask: "Would you like me to:
- Create governance charters for each body?
- Develop meeting agendas and templates?
- Set up a governance dashboard?
- Train stakeholders on governance processes?"

## Usage

**Load this skill when the user:**
- Needs to establish project governance
- Wants to define decision rights and authority
- Needs to create oversight frameworks
- Wants to improve project oversight

**Trigger phrases/keywords:**
- project governance
- governance framework
- decision rights
- steering committee
- PMO
- project oversight
- governance structure
- project management office

**DO NOT load when:**
- Request involves connector tools or local filesystem operations
- Task requires git operations
