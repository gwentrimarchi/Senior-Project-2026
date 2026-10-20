# FootInTheDoor Project Plan

**Course:** CI 491

---

## Project Background

The Eastern Minority Supplier Development Council (EMSDC) is a regional affiliate of the National Minority Supplier Development Council. It certifies minority-owned business enterprises (MBEs) and connects them with large corporations that want to buy from diverse suppliers. Its mission is to help these MBEs go beyond being eligible suppliers and become selected ones.

Sanbor Corporation, an EMSDC-affiliated manufacturer, is the partner company for this project. Sanbor's sales team and manufacturer's representatives maintain a list of companies they want to do business with. Its marketing team manually monitors those companies for "buying triggers," which are signs that a company may soon need a supplier like Sanbor.

Sanbor faces four main challenges in turning that list into business:

1. **Identifying relevant contacts:** Each company on the target list must be translated into actionable contact information. Sanbor frequently lacks visibility into which individuals in procurement, engineering, or supply chain hold or influence purchasing authority.

2. **Establishing credible outreach paths:** A name and email address alone are insufficient, as unsolicited outreach to large organizations is rarely successful. Sanbor requires a credible path to each contact, such as a mutual connection, an industry association, or an existing EMSDC relationship.

3. **Monitoring buying triggers:** Monitoring companies manually is labor-intensive and inconsistent, increasing the likelihood of missing the period when a company is actively seeking suppliers.

4. **Engaging hard-to-reach companies:** Certain strategically important companies are particularly difficult to engage. Honeywell was identified as both a priority target and one of the most challenging companies to reach.

## Statement of Work

### Small Scope Option

Build a website with a user-friendly interface tailored to EMSDC and Sanbor's needs. The website will allow users to access information collected about the prospective customers (businesses) they have shared with the project team.

### Expanded Scope Option

Build the same database needed for the small-scope option, but also develop AI capabilities to research, summarize, classify, and prioritize companies.

Potential features include:

- Identification of relevant departments and publicly listed contacts.
- Research and summarization of company information.
- Classification of potential buying triggers.
- Scoring companies based on how promising they are for Sanbor.
- Source references to help users verify collected information.

## Resources

- Public databases and information sources.
- Drexel-provided databases.
- Sanbor-provided databases.
- Potential tools and libraries for the AI track, including PyTorch, NumPy, and pandas.

## Assumptions

- The project team will be provided with relevant information and datasets.
- The team will have access to appropriate public and Drexel-provided research resources.
- The final scope will depend on data availability, technical feasibility, and stakeholder feedback.

---

## Project Schedule

### Q1: Research and Planning

#### October 19–26, 2026 — Understand Sanbor's Customer Base

- Identify the types of buyers, industries, and organizations Sanbor currently serves.
- Gather details to establish a baseline for customer patterns and habits.
- Analyze purchasing patterns, common customer needs, and communication methods.
- Meet with the Sanbor representative and request biweekly check-ins.

#### October 26–November 2, 2026 — Identify the Ideal Prospective Customer

- Identify the characteristics of an ideal prospective customer.
- Identify promising lead characteristics, including industry, company size, operational needs, and purchasing requirements.
- Meet with EMSDC to review the project plan before submission.

#### November 2–9, 2026 — Identify Sanbor's Competitive Advantages

- Document Sanbor's products, capabilities, and value propositions.
- Identify characteristics that differentiate Sanbor from competing suppliers.

#### November 9–23, 2026 — Research Target Companies

- Research the provided list of target companies.
- Compile company profiles, locations, industries, operations, and potential business needs.

#### November 23–December 7, 2026 — Identify Contacts and Buying Triggers

- Identify relevant contacts within target companies.
- Research potential buying triggers that indicate upcoming supplier needs.
- Document possible outreach paths and relevant business relationships.

#### December 7–21, 2026 — Review Internal Data and Design the Database

- Define data sources, lead-scoring criteria, and interface requirements.
- Analyze available Sanbor customer sales records to identify existing relationships and purchasing patterns.

#### December 21, 2026–January 1, 2027 — Consolidate Findings and Finalize the Development Plan

- Organize collected research into a structured dataset.
- Identify information gaps and areas requiring additional research.
- Finalize the technical approach and minimum viable product (MVP) requirements.

### Q2: Development and Implementation

#### January 4–17, 2027 — Finalize Requirements and System Design

- Finalize platform requirements based on feedback from Sanbor and EMSDC.
- Determine the core MVP features, including company profiles, contact information, source tracking, search, and filtering.
- Select programming languages, frameworks, database technology, and development tools.
- Create initial website wireframes and establish the overall system architecture.

#### January 18–31, 2027 — Implement the Database Structure

- Implement the database structure.
- Import and organize company information collected during Q1.
- Standardize company names, remove duplicate entries, and identify incomplete or inconsistent records.
- Develop a process for tracking source URLs, research dates, and confidence in collected information.
- Begin developing backend functionality to retrieve and update company information.

#### February 1–14, 2027 — Build the Website Interface

- Build the website interface for Sanbor and EMSDC to access company intelligence.
- Develop individual company profile pages displaying business information, contacts, and research findings.
- Implement database search, filtering, and sorting functionality.
- Create navigation and layouts that allow users to compare companies and review supporting evidence.
- Connect the website interface to the centralized database.
- Conduct initial usability checks.

#### February 15–28, 2027 — Investigate and Implement AI Capabilities

*Conditional on approval of the expanded project scope.*

- Investigate appropriate AI tools or existing language models for researching and summarizing company information.
- Develop methods for extracting information from approved public sources.
- Implement the lead-scoring method developed in Q1.
- Include source references and confidence indicators to help users verify AI-generated findings.

#### March 1–13, 2027 — Test Core Features and Demonstrate the Prototype

- Test company profile retrieval, search, filtering, and data display.
- Verify that stored information is linked to the correct company and source references work properly.
- Compare automated summaries and classifications against their original sources.
- Identify technical issues, missing data, and implementation limitations.
- Demonstrate the preliminary platform to project stakeholders and collect feedback.

### Q3: Refinement, Testing, and Delivery

#### March 29–April 11, 2027 — Refine the Platform

- Complete remaining development tasks based on the Q2 prototype and stakeholder feedback.
- Refine the website interface to improve usability.
- Improve database consistency, search functionality, and company research presentation.
- Finalize AI-assisted summaries, classifications, and lead-scoring functionality, if applicable.
- Ensure the platform distinguishes verified information from uncertain or unavailable findings.

#### April 12–25, 2027 — Conduct System and Methodology Testing

- Test primary user workflows, including searching for companies, reviewing profiles, and identifying relevant contacts.
- Evaluate AI-generated summaries, buying-trigger classifications, and lead rankings, if applicable.
- Evaluate the effectiveness and limitations of the research methodology.

#### April 26–May 9, 2027 — Demonstrate the Platform and Incorporate Feedback

- Demonstrate the platform to Sanbor and EMSDC representatives.
- Gather feedback on interface usability, company profile usefulness, contact relevance, and identified opportunities.
- Determine whether the platform helps Sanbor prioritize prospective customers and develop informed outreach strategies.
- Implement high-priority improvements based on stakeholder feedback.
- Refine lead-scoring criteria to reflect Sanbor's business priorities.
- Retest updated features.

#### May 10–16, 2027 — Evaluate Project Outcomes

- Assess the completeness and accuracy of collected company information.
- Evaluate whether the platform identifies relevant contacts, potential buying triggers, and promising business opportunities.
- Document public data limitations and challenges involving hard-to-reach companies.
- Summarize project outcomes and identify areas for future development.

#### May 17–23, 2027 — Complete Documentation and Prepare the Final Demonstration

- Complete technical documentation describing system architecture, database design, technologies, and implementation.
- Document the research methodology, data sources, AI components, lead-scoring criteria, and system limitations.
- Prepare recommendations for maintaining the database, updating company information, and expanding the platform.
- Develop the final project demonstration.
- Conduct a final review of deliverables with the project team.

#### May 24–June 1, 2027 — Finalize and Deliver the Platform

- Perform final system checks and resolve remaining critical issues.
- Verify that the database and website operate as expected and source references are accessible.
- Deliver the completed FootInTheDoor platform to stakeholders.
- Present the project's goals, methodology, implementation, results, future improvements, and limitations.

---

## Risks and Mitigation Strategies

### 1. Data Quality

**Risk:** Public data on contacts and buying triggers may be incomplete or out of date.

**Mitigation:**

- Cross-check information across sources.
- Track source URLs and research dates.
- Flag uncertain records for manual review.

### 2. External Platform Restrictions

**Risk:** Platforms such as LinkedIn restrict automated access and may change their terms or APIs during the project.

**Mitigation:**

- Use only permitted data sources and access methods.
- Design the system so data sources can be replaced.
- Avoid relying on a single external source.

### 3. Privacy and Legal Concerns

**Risk:** Collecting personal contact information raises privacy and legal concerns.

**Mitigation:**

- Limit collection to relevant business information.
- Review the approach with the faculty advisor.
- Follow applicable privacy requirements and source terms of use.

### 4. Hard-to-Reach Target Companies

**Risk:** Companies such as Honeywell may have limited public information available.

**Mitigation:**

- Use Honeywell to evaluate the limits of the research methodology.
- Investigate alternative permitted sources and credible outreach paths.
- Document information gaps and research limitations.
- Use findings to identify improvements to the platform.

---

## Project Deliverables

- A centralized database of prospective customers.
- Structured company profiles containing relevant business information.
- Publicly available business contact information and source references.
- A user-friendly website for searching, filtering, and reviewing company intelligence.
- AI-assisted research, summaries, classifications, and lead scoring, if the expanded scope is approved.
- Technical documentation covering system architecture, database design, technologies, and implementation.
- Documentation of research methodology, data sources, limitations, and recommendations for future development.
- A final demonstration and presentation for Sanbor and EMSDC stakeholders.
