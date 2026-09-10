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

* **Framework Constraint:** Keep the project lightweight and semantic. Do not add React, Tailwind, Bootstrap, or other frameworks unless the user explicitly asks for them.
* **Project Structure:** Prefer simple, clear files such as `index.html`, `style.css`, and `script.js`. Keep CSS organized by section or component when the file grows.
* **Accessibility:** Use semantic HTML, meaningful headings, sufficient contrast, and responsive layouts for mobile, tablet, and desktop.
* **Content Rules:** The site should reflect a mentor-focused, supportive, growth-oriented educational voice. Use professional, accurate, and non-generic language.
* **Resume Source Data:** Name: Carrie Johnson | Role: Mentor / Teacher | Focus: STEM education and student-centered coaching | Philosophy: Growth-focused mentorship that builds confidence, curiosity, and practical skills | Experience: educator and mentor experience tailored to real project context.

## 4. Expectations for AI Agents

* Prefer small, precise edits over broad rewrites.
* Preserve the existing structure unless a change explicitly requires a layout update.
* When editing text, keep the content truthful, polished, and aligned with the mentor profile.
* Favor maintainability and readability over cleverness or unnecessary abstraction.
