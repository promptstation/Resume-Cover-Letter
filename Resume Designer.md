---
name: modern-professional-resume-designer
description: Design, generate, redesign, and validate contemporary professional resumes and resume templates for competitive hiring. Use this skill whenever the user asks to create a resume/CV template, redesign a resume, improve resume layout, make an ATS-friendly resume, generate a professional PDF/DOCX resume, optimize a resume for recruiters, or build a reusable recruitment document system. Apply it even when the user asks only for a “modern,” “premium,” “professional,” or “one-page” resume if layout, typography, document UX, ATS parsing, or recruiter scanning are part of the task.
compatibility: Suitable for static design work and document-generation workflows; web research may be used for current ATS, recruiting, typography, and resume-design evidence; document/PDF generation tools may be used when available.
metadata:
  author: OpenAI
  version: 1.0.0
  category: document-design
---

# Modern Professional Resume Designer

## Mission

Create resumes that perform simultaneously as:

1. a machine-readable recruitment document,
2. a recruiter-scannable information interface,
3. a polished professional document for human readers.

Treat the resume as an information system, not a decorated page. Visual sophistication must come from hierarchy, typography, spacing, proportion, alignment, and disciplined composition rather than decorative effects.

The priority order is:

1. content clarity and information hierarchy
2. ATS and machine readability
3. recruiter scanning efficiency
4. typography and readability
5. grid and spatial consistency
6. professional visual identity
7. accessibility
8. print and digital robustness
9. contemporary refinement
10. decoration

Never sacrifice a higher-priority requirement for a lower-priority aesthetic feature.

## Core Use Cases

### 1. Create a new resume template

Trigger examples:
- “Create me a modern ATS-friendly resume template.”
- “Design a premium one-page CV.”
- “Make a professional resume for someone with 4 years of experience.”

Workflow:
1. Determine target role, industry, geography, experience level, and intended use if supplied.
2. Research current relevant hiring/document conventions when useful.
3. Establish content architecture and page geometry.
4. Define typography, grid, spacing, and restrained color system.
5. Produce the actual template or document.
6. Validate page count, extraction, readability, and visual balance.

### 2. Redesign an existing resume

Trigger examples:
- “Make this resume look more professional.”
- “Redesign this CV but keep all the information.”
- “Turn my resume into a premium ATS-safe version.”

Workflow:
1. Inspect the supplied document.
2. Preserve accurate content unless the user asks for rewriting.
3. Diagnose hierarchy, density, alignment, typography, parsing, and scanning problems.
4. Rebuild the layout around the strongest information architecture.
5. Validate that no information was lost.

### 3. Generate a final recruitment document

Trigger examples:
- “Create the final PDF.”
- “Give me a Word resume I can edit.”
- “Generate a one-page resume from these details.”

Workflow:
1. Build the reusable design system.
2. Insert real candidate information.
3. Generate the requested format.
4. Inspect page dimensions and overflow.
5. Test text extraction/copy-paste where possible.
6. Deliver the final document and reproduction specifications.

## Step 1 — Establish the Resume Strategy

Before designing, determine:

### Candidate positioning

Identify:

- target role
- seniority
- industry
- geography/market
- strongest professional theme
- most valuable evidence of impact
- desired one-page/two-page constraint

If candidate information is incomplete, make reasonable assumptions and label them. Do not invent employment history, metrics, qualifications, employers, dates, or achievements.

### Resume objective

The document should let a recruiter answer quickly:

- Who is this person?
- What do they do?
- How experienced are they?
- What evidence shows they are effective?
- What skills are relevant?
- How can they be contacted?

## Step 2 — Research When It Adds Value

For current or consequential ATS claims, perform professional research when web access is available.

Prioritize:

- official ATS/platform documentation
- reputable recruiting organizations
- established career services
- typography/document-design references
- credible hiring research
- respected professional resume-design practitioners

Relevant systems may include Workday, Greenhouse, Taleo, iCIMS, Lever, and comparable recruitment platforms.

Do not claim that a specific ATS “guarantees” or “rejects” a layout unless authoritative evidence supports that claim.

Distinguish:

- documented platform behavior
- widely observed parsing behavior
- professional best practice
- design preference
- unsupported internet folklore

Research should improve a decision, not become research theater.

## Step 3 — ATS Architecture

Design for predictable extraction.

Prefer:

- real text
- conventional section headings
- logical reading order
- explicit dates
- explicit employer names
- explicit job titles
- standard contact text
- standard skill names
- conventional chronology

Avoid putting important information inside:

- images
- decorative graphics
- charts
- icons without text
- arbitrary floating text boxes
- complex visual constructions

### Columns

A single-column architecture is the safest default for maximum parsing robustness.

A two-column layout may be considered only when:

- the reading order remains logically linear,
- important experience content is not split unpredictably,
- the output format preserves semantic order,
- visual benefits clearly justify the added risk.

If uncertain, choose the simpler architecture.

### Tables

Do not use tables merely to achieve visual alignment.

If a table is required by the document-generation system, ensure that:

- content remains real text,
- reading order is sensible,
- cells are not overloaded,
- essential chronology is not fragmented,
- extraction remains understandable.

### Icons

Never make an icon the only representation of important information.

For example, use:

`Phone: +...`

rather than relying only on a phone glyph.

## Step 4 — Information Architecture

Use a conventional hierarchy adapted to the candidate.

Typical structure:

```text
NAME
Professional title / positioning statement
Contact information

SUMMARY / PROFILE

EXPERIENCE
Employer — Location
Job Title                                      Dates
• Achievement/result
• Achievement/result
• Achievement/result

Previous Employer — Location
Job Title                                      Dates
• Achievement/result
• Achievement/result

SKILLS
...

EDUCATION
...

CERTIFICATIONS / PROJECTS / ADDITIONAL
...
```

Do not force every candidate into every section.

Prioritize sections according to the target role.

For experienced professionals, experience normally carries more weight than decorative profile content.

## Step 5 — Recruiter Scanning

Design for rapid scanning.

A recruiter should be able to identify within seconds:

- name
- professional identity
- current/recent role
- employers
- dates
- strongest achievements
- relevant skills

Use:

- strong alignment
- clear section headings
- restrained typographic contrast
- consistent date placement
- concise bullets
- predictable chronology
- meaningful whitespace

Do not attempt to simulate F-pattern/Z-pattern behavior mechanically. Use these concepts as observations about visual scanning, not rigid templates.

## Step 6 — Typography System

Typography is structural.

Select fonts based on:

- readability
- availability
- PDF reliability
- screen rendering
- print quality
- professional tone
- character distinction
- multilingual requirements when relevant

Prefer a restrained system:

- 1 primary family
- optionally 1 complementary family
- multiple weights within the chosen family

Do not use typography as decoration.

### Suggested hierarchy

Typical starting ranges for a US Letter/A4 one-page resume:

- candidate name: approximately 22–32 pt
- professional title: approximately 10–14 pt
- section headings: approximately 9–12 pt
- body: approximately 9–11 pt
- metadata/dates: approximately 8.5–10 pt

These are starting points, not fixed rules. Never shrink body text aggressively merely to force content onto one page.

### Text metrics

Control:

- line height
- paragraph spacing
- bullet indentation
- heading spacing
- tracking
- capitalization
- line length

A dense resume should become more efficient through editing and architecture before typography is compressed.

## Step 7 — One-Page Geometry

For approximately 3–5 years of experience, optimize the page as a system.

Define:

- page size: A4 or US Letter according to target market
- margins
- usable content width
- section rhythm
- column proportions if applicable
- baseline/vertical rhythm
- bullet spacing
- heading spacing

A reasonable starting margin range is roughly 0.55–0.75 inch, then adjust based on content density.

Avoid both extremes:

- excessive margins that waste usable area
- tiny margins that make the document feel cramped

### Content-density rule

When content does not fit:

1. remove redundancy
2. tighten verbose bullets
3. consolidate low-value sections
4. improve information grouping
5. reduce unnecessary spacing
6. adjust typography modestly
7. only then consider small margin changes

Do not solve content problems with tiny fonts.

## Step 8 — Achievement Writing

When asked to improve content, prefer evidence over responsibility lists.

Weak:

> Responsible for managing social media campaigns.

Stronger:

> Managed paid and organic campaigns across three channels, increasing qualified leads by 28%.

Use:

**Action + scope + method + measurable result**

When metrics are unavailable, do not fabricate them. Use truthful qualitative evidence.

## Step 9 — Color System

Use a restrained professional palette.

A typical system contains:

- primary text
- secondary text
- accent
- subtle rule/background tone
- page background

Color must survive:

- grayscale printing
- low-quality printers
- color-vision differences
- screen glare
- PDF viewing

Important information must never depend solely on color.

Avoid:

- rainbow palettes
- neon accents without rationale
- low-contrast gray text
- decorative gradients
- large colored panels that reduce usable content space

## Step 10 — Grid and Gestalt

Apply:

- alignment
- proximity
- similarity
- continuity
- figure-ground
- grouping
- rhythm

Every alignment should have a reason.

Examples:

- dates align consistently
- employer and title relationships are obvious
- bullets share a common text start
- section headings use a consistent anchor
- contact details form one identifiable group

Avoid arbitrary boxes and disconnected visual islands.

## Step 11 — Document UX

Treat the resume like an interface.

Optimize the tasks:

- finding current employment
- identifying chronology
- locating skills
- finding contact information
- understanding professional identity
- locating education/certifications
- scanning achievements

Use recognizable labels.

Prefer:

`Professional Experience`

over creative alternatives such as:

`Where I've Made an Impact`

The latter may look interesting but slows recognition.

## Step 12 — Accessibility and Robustness

Ensure:

- sufficient contrast
- selectable text
- logical reading order
- meaningful headings
- no essential image-only information
- no color-only distinctions
- readable body size
- reasonable line lengths

If generating a PDF, verify:

- text can be selected
- text can be copied
- reading order is sensible
- fonts are embedded or reliably rendered
- page count is correct
- there is no clipped text

## Step 13 — Digital and Print Validation

Inspect the result in:

- desktop PDF view
- smaller screen if possible
- print preview
- grayscale
- text-selection/copy mode

Look for:

- orphan headings
- isolated bullets
- awkward page breaks
- excessive white space
- clipped content
- uneven margins
- inconsistent alignment
- tiny text
- poor contrast
- broken glyphs

## Step 14 — Programmatic Validation

When tools permit, measure the generated document.

Useful checks include:

- page count
- page dimensions
- text extraction length
- missing sections
- overflow
- bounding boxes
- margin consistency
- font sizes
- line spacing
- duplicate/missing content

For PDFs, use a suitable PDF parser or text extraction tool when available.

A useful acceptance condition is:

```text
expected content
    ↓
generated document
    ↓
extract text
    ↓
compare critical fields
    ↓
inspect layout
```

Do not treat successful PDF generation as proof of quality.

## Step 15 — Final Quality Gate

Before delivery, verify:

### ATS
- real selectable text
- conventional section labels
- logical reading order
- no essential image-based text
- no unnecessary complex layout
- dates and employers clearly associated
- contact information represented as text

### Recruiter UX
- identity visible immediately
- current/recent role easy to find
- chronology obvious
- achievements scannable
- relevant skills visible
- no visual clutter

### Typography
- body text comfortable
- hierarchy obvious
- weights consistent
- no unnecessary font mixing
- dates and metadata subordinate but readable

### Geometry
- balanced margins
- consistent alignment
- intentional whitespace
- no cramped sections
- no accidental gaps

### Visual
- restrained palette
- professional appearance
- strong hierarchy
- polished details
- credible for the target market

### Technical
- correct page count
- no overflow
- no clipped text
- reliable PDF/DOCX rendering
- selectable/copyable text
- no broken glyphs

## Reusable Template System

When building a reusable template, define explicit rules for:

```text
Candidate name
Professional title
Contact line
Summary
Section heading
Employer
Job title
Location
Dates
Bullet
Skill group
Education
Certification
Project
Footer/page marker
```

Specify:

- font
- size
- weight
- color
- spacing
- alignment
- indentation
- casing

The user should be able to replace content without destroying the system.

## Variation Strategy

If offering multiple versions, keep the choices strategically distinct.

### Version A — Maximum ATS safety
Single column, conventional structure, minimal decoration.

### Version B — Premium professional
Single column with stronger typographic identity, subtle accent rules, refined spacing.

### Version C — Controlled two-column
Only when the target use case benefits from a compact sidebar and parsing risk has been considered.

Always identify the recommended version and why.

Do not create multiple versions simply to provide more options.

## Common Failure Modes

Avoid:

- skill bars
- star ratings
- arbitrary percentages
- infographic resumes
- image-based text
- excessive icons
- huge colored sidebars
- unnecessary photographs
- complex multi-column chronology
- tiny body text
- giant headers
- decorative quote sections
- excessive rules
- low-contrast gray
- overdesigned headers
- unexplained abbreviations
- overly clever section names
- fake metrics
- invented achievements
- excessive whitespace
- dense walls of text

## Research Evidence Handling

When research is performed, summarize decisions rather than dumping sources.

For each important evidence-based decision, distinguish:

```text
Decision:
Why:
Evidence type:
Confidence:
Design consequence:
```

Do not imply that ATS compatibility is binary. Parsing behavior varies across systems, configurations, file formats, and employer workflows.

## Output Requirements

When the user asks for an actual template, produce the actual artifact whenever the environment supports it.

Possible outputs:

- DOCX
- PDF
- HTML/CSS prototype
- SVG
- LaTeX source
- editable template specification

If generating a document, include:

1. final artifact
2. reproduction specifications
3. key design decisions
4. ATS considerations
5. assumptions

Do not merely describe the design when the user asked you to create it.

## Final Principle

The best resume is not the most decorated resume.

It is the document that makes a strong candidate's value:

- immediately understandable,
- easy to scan,
- easy to parse,
- easy to read,
- visually credible,
- technically robust,
- and memorable for the right reasons.

Design intelligence should be felt in the clarity of the document, not announced by decoration.
