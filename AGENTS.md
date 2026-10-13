# BIO 340 General Genetics Educational Apps

## Project purpose

This repository contains public preparation materials and interactive learning tools for Dr. Jessie Ebie's BIO 340 General Genetics course. The site is published with GitHub Pages at:

https://jessieebie.github.io/bio-340-genetics/

The intended audience is primarily BIO 340 students. The tone should be human, supportive, welcoming, and honest about the demands of an upper-level genetics course. Avoid language that sounds punitive, discouraging, or machine-generated.

## Repository structure

- `index.html` is the main resource hub.
- `pre-course-review/index.html` is the interactive preparation and prerequisite review tool.
- `course-success/index.html` is the course success guide presented as an accessible, collapsible question-and-answer page.
- `lac-operon/lac-operon-teaching-simulation.html` is the Lac Operon Simulation. Preserve its behavior when making broader site changes.
- `resources/BIO-340-Genetics-Preparation-Guide.pdf` is the downloadable preparation guide.
- `resources/BIO-340-Course-Success-Guide.pdf` is the downloadable course success guide.

The two Word source documents currently live one directory above this repository:

- `../BIO 340 Genetics Preparation Guide with Interactive Review.docx`
- `../BIO 340 Course Success Guide.docx`

The matching working PDFs are also stored one directory above the repository. The Word documents are the editable sources. The PDFs in `resources/` are the public website copies.

## The preparation guide and review tool

The preparation materials answer the question, “Is there anything I can study before the class starts to help me prepare?” They help students recall introductory biology concepts and basic math skills used in genetics. They are not intended to outline everything students will learn in BIO 340 or reteach complete introductory biology units.

Important content areas include:

- Basic probability, fractions, decimals, percentages, the sum rule, the product rule, and independent events
- DNA and RNA structure, transcription, translation, proteins, amino acids, monomers, polymers, and biologically important bond types
- Mitosis and meiosis, the number of cells produced, chromosome-number changes, homologous chromosomes, and related introductory concepts

The interactive tool uses a question bank so students can repeat practice. Questions should have one unambiguously correct answer unless the interface is explicitly designed for multiple selections. State units or whether an answer should be a decimal, fraction, or percentage whenever ambiguity is possible. Students may try a question up to three times and may request the answer and explanation. Feedback should explain the reasoning needed for that specific question, not give generic study advice.

The preparation webpage links to OpenStax Biology 2e as an optional reference. It also explains that typed questions are matched to prepared explanations and are not sent to a chatbot.

## The course success guide

The success guide covers realistic expectations, learning strategies, support hours, course resources, planning, and asking for help. It should not repeat the full syllabus. Direct students to the current syllabus and Canvas course for official policies and details.

Key points include:

- BIO 340 is a four-credit course completed in 7.5 weeks, and the average student should plan for about 24 hours of work per week.
- It is an upper-level survey course in a large field. It is challenging and manageable with steady engagement and active practice.
- Genetics requires reasoning and problem solving, not recognition or memorization alone.
- Learning includes a period of not knowing yet. Confusion and revision are normal parts of the process.
- Students should use support hours for both learning and professional connection. They may ask about meeting at another time if posted support hours do not work.
- Students should work through the Modules in Canvas instead of relying only on the Canvas To Do list, which can omit ungraded supporting materials.
- The course has built-in flexibility described in the syllabus. Outside that flexibility, deadlines are firm.
- Some policies, resources, and support options are specific to Dr. Ebie's sections. Keep this distinction concise and direct students to their instructor's current syllabus and Canvas course.

When `course-success/index.html` is embedded in Canvas, the note about section-specific policies and the back-to-main-menu link are hidden. They remain visible on the standalone page.

## Writing and visual style

- Write naturally. Avoid em dashes, unnecessary colons, stock AI phrasing, and overly polished promotional language.
- Use “Dr. Ebie” or “Dr. Jessie Ebie” where an instructor name is needed.
- Keep all visible text and document fonts black unless white text is required on a dark background.
- Use grayscale for document shading. Website colors may use the established maroon and gold palette as long as contrast requirements are met.
- Use the copyright footer `© 2026 Dr. Jessie Ebie` on public pages and documents where appropriate.
- Keep the main-page course title on one line when space permits and allow it to reflow on small screens.
- Preserve the established card layout, typography, spacing, and responsive behavior unless a redesign is explicitly requested.
- Instructor-only Canvas embed controls should be visually secondary and placed on their own line so students do not mistake them for learning activities.

## Accessibility requirements

All webpages, Word documents, and PDFs should be accessible and screen-reader friendly.

For webpages:

- Use one descriptive `h1` and a logical heading hierarchy.
- Use semantic landmarks, buttons, links, lists, form controls, and fieldsets where appropriate.
- Give controls clear accessible names and preserve keyboard operation.
- Provide visible focus indicators.
- Do not communicate meaning through color alone.
- Maintain WCAG 2.1 AA color contrast.
- Respect `prefers-reduced-motion`.
- Make layouts reflow without horizontal scrolling on small phone screens.
- Keep touch targets usable on mobile devices.
- Use live regions for copy-confirmation or changing quiz feedback when needed.

For Word and PDF guides:

- Use native Word heading styles and native bulleted lists.
- Use accessible Word tables only when a table is genuinely useful. Identify header rows, avoid merged cells when possible, and add alternative text or a description when needed.
- Keep reading order logical and link text descriptive.
- Add document title, author, subject, and keywords deliberately. Do not include references to AI, ChatGPT, Codex, LibreOffice, or automated generation in visible text or metadata.
- Export final PDFs with Microsoft Word, not LibreOffice.
- Verify that PDF text is selectable, headings and lists are tagged, links work, reading order is logical, and document properties are correct.

## Document workflow

1. Edit the existing Word source rather than rebuilding it from scratch so styles, spacing, headers, footers, bullets, and accessibility settings are preserved.
2. Use Microsoft Word for editing when Word-specific behavior or PDF export matters.
3. Inspect the Word document visually after changes, including page breaks, table widths, headers, footers, link color, and grayscale shading.
4. Check document properties and remove stale or misleading metadata.
5. Export the PDF from Microsoft Word.
6. Inspect the exported PDF visually and check its tags, reading order, links, and metadata.
7. Replace the corresponding PDF in `resources/` only after verification.
8. Update the matching webpage when document wording changes so the website and PDF do not contradict each other.

## Website workflow

- Keep the site dependency-free unless a dependency is clearly necessary. Current pages are self-contained HTML, CSS, and JavaScript.
- Use relative links for navigation within the site and absolute GitHub Pages URLs only in generated Canvas embed code.
- Do not remove or rename a public URL without updating every link and embed snippet that uses it.
- Do not alter the Lac Operon Simulation while working on another resource unless the request specifically requires it.
- Test standalone and embedded behavior. Embedded pages should not show the back-to-main-menu link.
- Test at desktop and narrow mobile widths.
- Before committing, run `git diff --check`, inspect the exact diff, and confirm there are no unrelated changes.
- Commit focused changes with a clear message. Push only the intended files to the `main` branch, then verify that GitHub Pages received the update.

## Safety and preservation

- The repository may contain user changes. Never discard, reset, or overwrite unrelated work.
- Do not replace Word files with regenerated approximations.
- Do not delete source documents, PDFs, screenshots, or other files unless their ownership and purpose are clear. Temporary files created during the task should be removed when the task is complete.
- Treat course policies in the current syllabus and Canvas course as authoritative. Do not infer or invent policies from older materials.
- Review all genetics questions and explanations for scientific accuracy and ambiguity before publishing.
