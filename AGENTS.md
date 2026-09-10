## Purpose

This tool is designed to support early-career professionals by giving them quick, reliable access to the most common career questions and practical guidance whenever they need it. It is intended to serve as a reusable, on-demand resource for career planning, decision-making, and professional growth.

The project is intentionally built to be flexible and expandable so the tool can evolve over time. As the product matures, new topics, scenarios, and career stages can be added to better support users beyond the initial early-career audience.

---

## 1. Core Workflow (Spec-Driven Development)

* **Plan First:** Before making changes, identify the page section or content area being updated and confirm the intended outcome in plain language.
* **Review Source Data:** Use only the real profile details provided for the mentor or educator. Do not invent credentials, schools, years of experience, or teaching history.
* **Propose Changes:** For substantive edits, describe the planned file changes and content updates before writing code.
* **Scope Discipline:** Keep edits focused on the relevant page, layout, content, or styling. Avoid unrelated refactors or framework adoption unless explicitly requested.

## 2. Technical Environment & Commands

* **Language/Stack:** Plain HTML5, CSS3, and vanilla JavaScript for a small static site.
* **Build Commands:** No build step is required. Open `index.html` directly in a browser or serve the directory locally with a simple static server such as:
  * `python3 -m http.server 8000`
  * `npx serve .`
* **Preview Workflow:** Validate changes by opening the page in a browser and checking that layout, spacing, text hierarchy, and responsiveness are correct.
* **Design Aesthetic:** Use a clean, accessible academic palette with warm neutrals, navy, cream, and teal accents; maintain high contrast and readable typography.

## 3. Style and Quality Constraints

### Platform Overview
This platform is a career guidance tool designed for tech sector professionals at entry-level and mid-level career stages. The platform features multiple mentor personas with distinct voices and teaching styles, allowing users to select the mentor type that best fits their learning style and career needs.

### Design System & Brand

#### Brand Colors

**Primary Colors:**
- MX Black: #000000
- MX White: #FFFFFF
- MX Blue/Gray Background: #F5F8FC

**Gradient Colors:**
- Primary Gradient: Purple (#9B3FDF) → Blue (#0075FF) → Cyan (#00C3FF) → Turquoise (#00DAD9)

**Secondary/Accent Colors:**
- MX Purple: #9B3FDF
- MX Blue 1: #0075FF
- MX Blue 2: #00C3FF
- MX Turquoise: #00DAD9

#### Typography

**Typeface:** Inter (system font family)

**Font Weights Available:**
- Light
- Regular
- Bold

**Heading Styles:**
- Use Inter Bold for emphasis and section headers
- Maintain clear visual hierarchy with consistent sizing across responsive breakpoints

**Body Text:**
- Regular: Inter Regular for primary content
- Bold: Inter Bold for emphasis within body text
- Maintain readable line-height for accessibility (1.5 or greater for body text)

#### Brand Voice

The platform's voice reflects these core characteristics:

**Bold:** We advocate for clear, confident guidance that empowers professionals.
- DO: Use active voice, make declarative statements, be confident in recommendations
- DON'T: Use overly long or complex sentences, hedge statements with unnecessary qualifiers

**Genuine:** We provide honest, data-driven guidance grounded in real experience.
- DO: Support advice with examples and evidence, be straightforward and clear
- DON'T: Make unsupported claims, use vague language

**Grounded:** We simplify complex career concepts and avoid jargon when possible.
- DO: Use consistent industry terminology, keep language accessible and simple
- DON'T: Use excessive adjectives, add unnecessary embellishment

**Friendly:** We approach mentorship with empathy, positivity, and inclusivity.
- DO: Be constructive and supportive in tone, use inclusive language and pronouns
- DON'T: Be dismissive or point out others' failures, alienate any reader

#### Writing Style

**Grammar & Punctuation:** Follow AP Style by default, with flexibility for clarity and accessibility.

**Point of View:** Use first and second person ("we," "us," "you," "your") to create direct connection with users. Avoid third person when possible.

**Inclusive Language:** Use gender-neutral pronouns (they/them, etc.) and avoid gendered assumptions. Ensure all examples reflect diverse experiences and backgrounds.

**Active Voice:** Prefer active voice to make guidance feel direct and actionable. Avoid passive constructions unless necessary for clarity.

**Other Details:**
- Use Oxford comma in lists for clarity
- Contractions are acceptable and encouraged for conversational tone
- Use one space after periods
- Avoid "&" unless space constraints require it; use "and" instead

### Mentor Personas

#### Career Stages
- **Entry-Level:** Professionals new to the tech industry (0-2 years), navigating onboarding, foundational skills, and early career decisions
- **Mid-Level:** Professionals with 3-7 years of experience, focused on growth, specialization, and career advancement decisions

#### Mentor Archetypes
*Pending research and definition. Each archetype will have a distinct teaching style, personality, and voice while supporting the platform's core values of clarity, honesty, and empathy.*

**To Define:**
- Specific mentor types/archetypes that resonate with entry-level and mid-level tech professionals
- Teaching style characteristics for each archetype
- Voice and tone adjustments for each mentor (if any) relative to platform voice
- Whether mentors should use platform voice as a foundation or develop independent voices

### Framework & Accessibility Constraints

* **Framework Constraint:** Keep the project lightweight and semantic. Do not add React, Tailwind, Bootstrap, or other frameworks unless the user explicitly asks for them.
* **Project Structure:** Prefer simple, clear files such as `index.html`, `style.css`, and `script.js`. Keep CSS organized by section or component when the file grows.
* **Accessibility:** Use semantic HTML, meaningful headings, sufficient contrast, and responsive layouts for mobile, tablet, and desktop. Ensure color choices meet WCAG AA standards for contrast.
* **Content Rules:** All content—platform and mentor-provided—should reflect the platform's voice and values: clear, honest, grounded, and friendly. Use professional, accurate, and non-generic language.

## 4. Expectations for AI Agents

* Prefer small, precise edits over broad rewrites.
* Preserve the existing structure unless a change explicitly requires a layout update.
* When editing text, keep the content truthful, polished, and aligned with the mentor profile.
* Favor maintainability and readability over cleverness or unnecessary abstraction.
