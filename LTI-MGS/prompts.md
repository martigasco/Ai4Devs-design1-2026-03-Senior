**PROMPT 1**

You are a senior Product Manager and Product Engineer.

I need submission-ready Markdown content for the initial documentation of a startup product called LTI.

Context:
- LTI is a startup building an AI-native Applicant Tracking System (ATS).
- The goal is to help HR teams and hiring managers work faster and better together.
- The product should improve recruiter efficiency, collaboration, automation, and selected AI-assisted recruiting tasks.
- This is an initial version of the product, so keep it realistic for an MVP.
- Write everything in English.
- Do not overengineer.
- Do not describe speculative enterprise features unless clearly marked as future work.

Please generate a Markdown section for a document with these parts:

1. Brief description of the software LTI
2. Its value proposition
3. Its competitive advantages
4. Main functions of the system
5. A Lean Canvas for the business model

Requirements:
- Make the content concise, clear, and submission-ready
- Focus on a startup MVP, not a fully mature enterprise platform
- Separate core MVP capabilities from differentiators
- For the Lean Canvas:
  - first provide it as a Markdown table
  - then provide it as a Mermaid diagram
- Use proper Markdown headings
- Keep the tone professional and practical

Return only the Markdown content for these sections.

**PROMPT 2**

You are a senior software analyst.

I am documenting the first version of LTI, an AI-native Applicant Tracking System.

I need submission-ready Markdown content for the section about the 3 main use cases of the system.

Please do the following:

1. Select the 3 most important use cases for the LTI MVP
2. For each use case, provide:
   - Name
   - Goal
   - Primary actor
   - Secondary actors
   - Preconditions
   - Main flow
   - Alternative flows
   - Postconditions
   - Why this use case matters for the MVP
3. For each use case, generate an associated UML use case diagram in PlantUML

Requirements:
- Choose use cases that represent the core business value of an ATS
- Keep them realistic for a startup MVP
- Prefer clarity over completeness
- Use consistent actors such as Recruiter, Hiring Manager, Candidate, and external services where needed
- Make the PlantUML syntax valid
- Return everything as clean Markdown
- Use one subsection per use case, followed by its diagram code block

Return only the Markdown content for this section.

**PROMPT 3**

You are a senior software architect.

I am documenting the initial version of LTI, an AI-native Applicant Tracking System.

I need submission-ready Markdown content for the data model section.

Please generate:

1. A short introduction to the data model
2. The main entities required for the MVP
3. For each entity, a table with:
   - Attribute name
   - Type
   - Description
4. The main relationships between entities
5. Important status fields or enums where relevant
6. A Mermaid ER diagram covering the MVP data model

Requirements:
- Keep the model realistic and aligned with an ATS MVP
- Focus on relational database modeling
- Do not include unnecessary enterprise complexity
- Include the most important entities for job openings, candidates, applications, interviews, users, collaboration, and AI assistance if justified
- Keep the Mermaid diagram readable and valid
- Use proper Markdown headings

Return only the Markdown content for this section.

**PROMPT 4**

You are a senior software architect.

I am documenting the initial version of LTI, an AI-native Applicant Tracking System.

I need submission-ready Markdown content for the high-level system design section.

Please generate:

1. A short explanation of the recommended architectural style for LTI v1
2. The main system components and their responsibilities
3. External integrations
4. Main data flows
5. Key non-functional considerations:
   - scalability
   - security
   - reliability
   - observability
6. A high-level architecture diagram in Mermaid

Important:
- Recommend a realistic architecture for a startup MVP
- Avoid overengineering
- If modular monolith is the best option, explain why
- Include AI-related components only where they add clear product value
- Keep the diagram understandable and submission-ready

Return only the Markdown content for this section.

**PROMPT 5**

You are a senior software architect.

I am documenting the initial version of LTI, an AI-native Applicant Tracking System.

I need submission-ready Markdown content for the C4 section.

Please generate:

1. A brief explanation of the chosen scope
2. A C4 System Context diagram
3. A C4 Container diagram
4. A C4 Component diagram that goes deeper into one important container of your choice

Requirements:
- The selected container should be central to the MVP
- Keep the diagrams consistent with the previously defined high-level architecture
- Use Mermaid if possible, but if C4 is clearer in PlantUML, use PlantUML
- Keep the output readable and practical
- Add a short explanation below each diagram

Return only the Markdown content for this section.

**PROMPT 6**

I have generated the main sections of the LTI initial documentation.

Please merge them into a single clean Markdown document called `LTI-initials.md`.

Requirements:
- Keep the original meaning
- Remove duplication
- Improve coherence between sections
- Preserve all diagram code blocks
- Add a title
- Add a table of contents
- Use this section order:

1. Introduction
2. LTI Overview
3. Value Proposition and Competitive Advantages
4. Main Functions
5. Lean Canvas
6. Main Use Cases
7. Use Case Diagrams
8. Data Model
9. High-Level System Design
10. C4 Model
11. Assumptions and Open Questions
12. Conclusion

Attached you have the md files for all the generated sections