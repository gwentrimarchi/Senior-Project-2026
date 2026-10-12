# Sanbor Requirements & Application Scoping Options
*Draft — EMSDC / Sanbor Corporation senior project*

## Requirements, Explanations, and Deliverables

| Number | Requirement | Explanation | Example Deliverable |
|----|----|----|----|
| 1 | Identify likely points of contact at a named target company, by role (such as procurement, engineering) | Sanbor's sales team and manufacturer's reps identify target companies but not necessarily the specific people inside them who make or influence buying decisions.| A contact/role taxonomy and documented search strategy, tested against 2-3 real target companies (spec document + worked examples) |
| 2 | Surface a realistic path to reach each contact (shared connections, industry groups), not just contact info | Stakeholders emphasized that the challenge isn't only finding names but also establishing a business connection with them. | A relationship path framework, plus a mockup of a "path" view for one sample contact |
| 3 | Track or flag "buying triggers"| Sanbor's marketing team already does this manually by watching for signals of need. This requirement is about making that process more systematic or automatable. | A catalog of buying trigger signal types, based on how Sanbor/Jared's team finds them currently |
| 4 | Use Sanbor's existing target company list as a starting point, supplemented by new company discovery | Sanbor already maintains a list of companies it wants to work with. MVP would rely on this list as input. Ideally, we would provide a service that can help generate this list. | A data model/schema for company and contact records, with a sample populated spreadsheet from Sanbor's list |
| 5 | Provide a view of companies that may be looking for suppliers like Sanbor, with contacts | The inverse of Req 4. providing Sanbor with companies that are actively searching for suppliers such as Sanbor. | A dashboard with a "buyers looking for suppliers" view |
| 6 | Support visibility and outreach for named hard to reach targets (Honeywell), not only easy ones | Honeywell was specifically raised as a company that is both a target and notoriously hard to access.  Our solution should support these especially challenging cases. | A worked case study applying the contact discovery and relationship path methodology specifically to Honeywell |

### Open Requirement 1
What is the directionality of the solution? We're assuming that Sanbor should be able to use this to help find and connect with buyers, but should buyers also be able to use this to connect with Sanbor?

### Open Requirement 2
What are our data sources? public data and Drexel provided resources are the two proposed options currently

## Scoped Application Options

### Option A: Target List Enrichment & Contact Discovery Application
Takes Sanbor's existing target list and Jared's manual process, and automates the step where a company on the list becomes a specific person and a buying signal.

It plugs directly into a step that already exists in Sanbor's workflow, has at least one clear user in Jared's marketing team, and doesn't require resolving the open bi-directional or data source questions before work can start. It's the most central response to the core pain point in the stakeholder notes and realisitic to get develop in our timeframe.

### Option B: Relationship Path Finder
Once a contact is identified, this finds a realistic way to reach them.

It's narrower than Option A, but it depends on having a contact to start from, so it functions as a second-stage tool that would sit on top of Option A (or on top of Jared's existing manual list) rather than standing alone as a starting point.

### Option C: Buying Trigger Monitor
A lightweight tool that watches public signals from Sanbor's existing list of target companies. This would automatically flag "Buying Triggers" that Sanbor tracks manually now to lock in potential buyers.

It's the most self contained and data driven of the four options, since it only needs Sanbor's existing target list as input. That also makes it the easiest to demo as a working prototype.

### Option D: Hard Target Intelligence Brief Generator
Given a named "hard to reach company" (the Honeywell case), this compiles available public business intelligence into a brief that Sanbor's sales team could act on.

Rather than building the full pipeline, it's a research assistant tool focused on one target at a time. It's narrower in scope than Option A, easy to demo with a single real example (Honeywell), and directly addresses a specific hard case Jared mentioned, though it doesn't generalize into an ongoing system the way Option A does.