---
name: professional-resume-template-evaluator
description: Rigorously evaluate, rank, and improve professional resume/CV templates as integrated information-design systems. Use this skill whenever a user asks to assess, compare, score, audit, rank, redesign, or optimize a resume template, CV layout, resume PDF, DOCX, screenshot, image, or portfolio-style career document for ATS compatibility, recruiter scanability, typography, one-page geometry, visual hierarchy, accessibility, professional credibility, or modern hiring performance. Inspect the actual artifact when provided and research ATS/recruitment/design evidence when conclusions require current or technical verification.
compatibility: Best used with access to document parsing, OCR/image inspection, web research, and file-analysis tools when available. Supports PDF, DOCX, images, screenshots, and comparable resume artifacts.
metadata:
  author: OpenAI
  version: 1.0.0
  category: document-design
---

# Professional Resume Template Evaluator

## Mission

Evaluate resumes as **information-design systems**, not merely attractive pages. The strongest result balances three audiences simultaneously:

1. **Humans** — recruiters and hiring managers must understand the candidate quickly.
2. **Machines** — recruitment systems must be able to extract, associate, index, and search the content reliably.
3. **The candidate/brand** — the document must communicate credibility, competence, relevance, and appropriate personality.

Do not reward decoration that harms extraction or comprehension. Do not recommend blandness merely because it is safer. The objective is the strongest practical balance between visual quality, machine readability, recruiter usability, accessibility, and hiring-context appropriateness.

## Core Use Cases

### 1. Template audit
Trigger when a user provides a resume template and asks whether it is good, professional, ATS-friendly, readable, modern, or effective.

### 2. Template comparison/ranking
Trigger when the user provides two or more resume templates and asks which is better. Apply the same scoring framework to every candidate and normalize assumptions before ranking.

### 3. Template optimization/redesign guidance
Trigger when the user wants concrete changes. Identify the highest-leverage structural issues first, then typography, visual system, and micro-refinements.

### 4. Artifact-level technical audit
Trigger when a PDF/DOCX/screenshot/image is supplied and the user wants technical confidence. Inspect the actual artifact rather than judging from a description alone.

## Evidence Discipline

Separate conclusions into three evidence levels:

- **Verified fact** — directly observable in the artifact, documented by a reliable source, or reproducibly tested.
- **Established convention** — broadly accepted professional practice with credible support but not universal technical law.
- **Design inference** — reasoned prediction about likely recruiter behavior, parsing, or visual impact.

Never turn a design inference into a claim of guaranteed ATS behavior.

When ATS behavior is discussed, remember that ATS products and configurations differ. Discuss likely risk, not certainty. Avoid phrases such as “100% ATS-proof,” “works with every ATS,” or “this ATS definitely rejects it” unless direct authoritative evidence exists for the exact behavior.

## Workflow

### Step 1 — Establish the evaluation target

Identify:

- artifact type: PDF, DOCX, image, screenshot, template, etc.
- intended role/industry if known
- career level if known
- intended geography if relevant
- intended submission channel if known
- whether ATS compatibility, visual quality, or both are priorities
- whether the user wants evaluation only or actionable redesign guidance

If critical information is missing, make a reasonable assumption and label it. Ask a clarifying question only when the missing information could materially change the ranking.

### Step 2 — Inspect the actual artifact

If a file or image is provided, inspect it before forming conclusions.

For documents, examine where possible:

- page dimensions
- text extraction order
- text-layer integrity
- headings
- columns
- tables
- text boxes
- floating objects
- headers/footers
- embedded images
- icons
- shapes
- hyperlinks
- font metadata
- font embedding
- spacing
- margins
- section structure
- copy/paste behavior

For visual artifacts, inspect:

- alignment
- visual hierarchy
- contrast
- typography
- grid
- spacing
- density
- grouping
- color
- graphical elements
- scanning paths
- page balance

Do not infer invisible document structure solely from a screenshot if the underlying file is available.

### Step 3 — Reverse-engineer the information system

Map the intended logical structure:

```text
Identity
→ Contact
→ Position / Professional Summary
→ Experience
→ Education
→ Skills
→ Supporting Sections
```

Then compare that logical sequence against the artifact's visual and machine-readable order.

Explicitly identify cases where visual order differs from extraction order.

### Step 4 — Analyze machine readability

Audit:

- text extraction order
- column order
- tables
- text boxes
- floating elements
- grouped objects
- headers/footers
- icons replacing labels
- graphics containing text
- unusual glyphs
- embedded fonts
- OCR dependence
- contact extraction
- employer/title association
- dates
- section-heading recognition
- skills extraction
- copy/paste behavior
- searchability

For each material risk, explain:

**Design decision → technical mechanism → likely consequence → severity → recommended fix.**

Do not simply say “columns are bad.” Explain whether the particular column implementation creates ambiguous reading order and how that could affect extraction.

### Step 5 — ATS compatibility assessment

Evaluate separately from visual attractiveness.

Use these risk categories:

**Low Risk** — likely to preserve logical text and section relationships across common workflows.

**Moderate Risk** — may work in many systems but introduces ambiguity or platform-dependent behavior.

**High Risk** — materially increases the chance of extraction, indexing, association, or workflow problems.

Consider:

- standard section labels
- text accessibility
- reading order
- columns
- tables
- text boxes
- icons
- graphics
- headers/footers
- contact fields
- dates
- PDF structure
- DOCX structure
- keyword visibility
- searchable text
- copy/paste

Where possible, distinguish technical evidence from industry advice.

### Step 6 — Typography audit

Assess:

- family
- availability
- embedding
- rendering
- weight
- size
- line height
- tracking
- hierarchy
- legibility
- character distinction
- cross-platform behavior
- print behavior

Ask whether the type system is appropriate to the candidate's industry and career level.

Evaluate typography as both a visual system and a machine-readable text system.

### Step 7 — One-page geometry

Treat the page as a constrained system rather than a container to be filled.

Measure or estimate:

- page dimensions
- margins
- usable width/height
- column ratios
- gutters
- vertical rhythm
- line density
- section spacing
- heading spacing
- whitespace distribution
- content-to-whitespace ratio

Use **3–5 years of experience** as a default stress-test case when no other career level is supplied.

Determine whether the design can realistically support a strong one-page resume without:

- shrinking body text excessively
- crushing line height
- removing important content
- reducing margins to impractical levels
- producing visual clutter

Also test conceptual resilience at 1–2, 3–5, and 5–10 years of experience when relevant.

### Step 8 — Hierarchy and scanning

Assess the document as a recruiter interface.

Determine how quickly a reader can identify:

1. who the candidate is
2. target role/profile
3. recent relevant experience
4. measurable achievements
5. skills
6. evidence of relevance

Analyze:

- left-edge anchors
- heading entry points
- employer/title prominence
- date visibility
- bullet rhythm
- alignment
- section transitions
- stopping points
- information scent

Do not mechanically label every resume as F-pattern or Z-pattern. Identify the actual scanning model encouraged by the design.

### Step 9 — Grid and composition

Reverse-engineer:

- grid
- margins
- columns
- gutters
- alignment lines
- baseline relationships
- section widths
- vertical rhythm
- repeated modules

Apply relevant Gestalt principles:

- proximity
- similarity
- continuity
- closure
- common region
- figure-ground
- alignment
- repetition
- contrast
- scale
- visual weight

Identify whether relationships are encoded clearly or merely suggested through decoration.

### Step 10 — Color and accessibility

Evaluate:

- primary/secondary/accent colors
- saturation
- contrast
- hierarchy
- print behavior
- grayscale performance
- color-vision accessibility
- industry fit

Determine whether color communicates hierarchy or competes with content.

A resume must remain understandable if color is removed.

### Step 11 — Recruiter UX

Treat the page as a task-oriented interface with limited attention.

Evaluate:

- discoverability
- scanability
- cognitive load
- navigation
- consistency
- comprehension speed
- decision efficiency
- visual prioritization
- error/friction potential

The template should help the recruiter answer the six core questions without hunting through the page.

### Step 12 — Historical and contemporary design analysis

Identify relevant influences when useful, such as:

- Swiss/International Typographic Style
- modernism
- minimalism
- editorial design
- corporate identity
- information design
- digital product design
- contemporary document design

Do not praise historical or modern styling merely because it is fashionable. Explain the functional value of the influence.

### Step 13 — Market and ATS research

Research current practices when the question is time-sensitive, technical, disputed, or industry-specific.

Prioritize:

1. official ATS/vendor documentation
2. established recruitment-industry research
3. academic/technical research
4. recognized design institutions/publications
5. typography/UX authorities
6. established hiring organizations and recruiters
7. credible industry analysis

When researching Workday, Taleo, Greenhouse, or another ATS, avoid extrapolating a behavior documented for one system to every system.

Explicitly mark disagreements among sources.

### Step 14 — Industry adaptability

Classify the template as:

- Universal
- Corporate
- Creative
- Technical
- Executive
- Industry-specific

Assess fit for:

- finance
- technology
- consulting
- marketing
- design
- engineering
- healthcare
- academia
- operations
- sales
- management
- executive roles
- creative industries

Explain modifications required for different contexts.

### Step 15 — Failure-mode attack

Actively try to break the template.

Look for:

- extraction-order failures
- association failures
- excessive density
- weak hierarchy
- contrast problems
- typography failures
- alignment drift
- color dependence
- print problems
- accessibility barriers
- recruiter scanning friction
- industry mismatch
- information overload
- wasted space

Do not stop after finding reasons the design works.

## Scoring Framework

Use a weighted 100-point model. Adjust weights only when the user's stated purpose clearly warrants it, and explain the adjustment.

Default weighting:

| Dimension | Weight |
|---|---:|
| ATS / machine compatibility | 18 |
| Information hierarchy | 12 |
| Recruiter scanability | 12 |
| Typography | 10 |
| Layout / grid | 10 |
| One-page geometry / density | 10 |
| Human readability | 8 |
| Visual design / composition | 7 |
| Accessibility | 5 |
| Professional credibility | 5 |
| Market relevance | 3 |
| **Total** | **100** |

Also report these normalized scores out of 100:

- Overall Score
- ATS Compatibility
- Human Readability
- Recruiter Scanability
- Typography
- Layout/Grid
- One-Page Geometry
- Visual Design
- Accessibility
- Professional Credibility
- Market Relevance

Explain the reasoning for every major score. Do not allow visual attractiveness to overwhelm machine readability and usability.

### Classification

Use:

- **Elite:** 90–100
- **Excellent:** 85–89
- **Strong:** 78–84
- **Good:** 70–77
- **Average:** 60–69
- **Weak:** 50–59
- **Poor:** 35–49
- **Unsuitable:** below 35

These bands are an evaluation rubric, not an objective industry certification.

## Critical-Priority System

Separate findings into:

### Critical Issues
Problems that could materially damage parsing, readability, accessibility, or recruiter comprehension.

### High-Priority Improvements
Changes with substantial expected benefit.

### Medium-Priority Improvements
Meaningful refinements that do not alter the core system.

### Low-Priority Refinements
Micro-level aesthetic or polish improvements.

Never give cosmetic refinements equal prominence to structural or ATS problems.

## Recommendation Logic

End with exactly one of:

- **KEEP AS-IS**
- **KEEP WITH MINOR REFINEMENTS**
- **REDESIGN SELECTED AREAS**
- **MAJOR REDESIGN REQUIRED**
- **REJECT / REPLACE**

Use the strongest evidence discovered to justify the decision.

If the template is already excellent, preserve successful decisions. Do not invent criticism merely to make the report look rigorous.

## Final Report Structure

Use this structure unless the user asks for another format:

# Resume Template Evaluation

## 1. Overall Ranking
- Classification
- Overall score
- Final recommendation

## 2. Executive Verdict
A concise professional judgment explaining the biggest strengths and weaknesses.

## 3. Scorecard
Provide the weighted score and the normalized category scores.

## 4. Detailed Analysis
Cover the dimensions most relevant to the artifact, including machine readability, typography, geometry, hierarchy, scanning, grid, color, composition, UX, accessibility, and professional credibility.

## 5. ATS Risk Assessment
Show Low / Moderate / High risk areas and explain the technical reason.

## 6. Recruiter Scanability Assessment
Describe the likely scan path and information priorities.

## 7. One-Page Geometry Assessment
Explain capacity, density, margins, and failure points.

## 8. Typography Assessment
Explain family, hierarchy, readability, embedding, and rendering considerations.

## 9. Grid and Layout Assessment
Explain the underlying spatial system and any alignment problems.

## 10. Color and Accessibility
Explain hierarchy, contrast, grayscale, and accessibility.

## 11. Gestalt and Composition
Explain grouping, rhythm, balance, and visual weight.

## 12. Market / Trend Assessment
Explain contemporary relevance and industry fit.

## 13. Critical Problems
Rank the most consequential problems.

## 14. Recommended Changes
For every recommendation use:

**Change:** what to alter.

**Reason:** why it matters.

**Risk solved:** what problem it addresses.

**Expected effect:** what should improve.

## 15. What Should Not Be Changed
Protect the strongest successful decisions so redesign does not destroy what already works.

## 16. Ideal Target Specification
Describe the target system for:

- page geometry
- typography
- hierarchy
- grid
- color
- ATS safety
- accessibility
- density
- visual personality

## 17. Final Professional Verdict
State the final recommendation and strongest supporting evidence.

## Research Citation Rules

When external research is used:

- cite claims that depend on external sources
- prefer primary/official sources for technical ATS behavior
- identify the date/context of time-sensitive evidence
- distinguish documentation from anecdotal recruiter practice
- explain conflicts rather than silently choosing one source

For an artifact-only visual review, do not manufacture citations. Clearly identify which conclusions come directly from inspection.

## Artifact Handling Rules

### PDF
Inspect both the rendered appearance and text layer when possible. A visually perfect PDF can still have a problematic extraction order.

### DOCX
Inspect document structure, paragraph order, tables, text boxes, headers/footers, floating objects, and font embedding/availability where tools permit.

### Screenshot/image
Evaluate visual design thoroughly, but explicitly state that invisible document structure, text-layer integrity, and true ATS extraction cannot be verified from an image alone.

### Multiple files
Evaluate each artifact independently before comparing them. Normalize assumptions about career level, role, and content volume.

## Anti-Patterns

Avoid:

- “It looks professional” without evidence
- “ATS-friendly” as a binary label
- assuming every ATS parses identically
- treating all columns as automatically unsafe
- treating all graphics as automatically harmful
- recommending serif/sans-serif choices as universal rules
- confusing aesthetic minimalism with information clarity
- excessive compression to force one page
- vague recommendations such as “make it cleaner”
- criticizing successful design decisions without a reason
- citing template marketplaces as technical ATS authorities
- claiming recruiter behavior as universal
- allowing trendiness to dominate usability

## Quality Gate

Before finalizing, verify:

- actual artifact inspected when available
- machine-readability and visual quality evaluated separately
- ATS claims appropriately qualified
- scores are internally consistent with findings
- critical issues are prioritized
- recommendations are actionable
- strong existing decisions are protected
- missing evidence is disclosed
- current research is cited when necessary
- final recommendation follows from the score and evidence

## Core Principle

The best resume template is not the prettiest template and not the safest-looking template.

It is the template that makes the candidate's evidence **easy for machines to extract, easy for recruiters to scan, easy for humans to read, and credible for the target professional context** — while using visual design to clarify information rather than compete with it.
