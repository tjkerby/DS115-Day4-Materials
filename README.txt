DS 115 Day 4: Academic Pathways

CONTENTS
slides/day4.qmd: Editable Quarto slides with presenter notes.
slides/day4.css: Small additions scoped to Day 4.
slides/assets/major-overlap.svg: Adapted Venn diagram with updated course labels.
day4-slides.html: Standalone Reveal.js slides for opening in a browser.
day4-slides.pdf: Static PDF review and sharing copy.
day4-teaching-guide.html: Timing, activity guidance, answer keys, and sources.
theme.scss and slides/_metadata.yml: Copies of the existing course defaults.

ADD TO THE EXISTING COURSE
1. Copy slides/day4.qmd, slides/day4.css, and slides/assets/major-overlap.svg
   into the corresponding locations in the existing slides folder.
2. Keep the existing theme.scss and slides/_metadata.yml.
3. Add this link to index.qmd:
   - [Day 4 - Academic Pathways](slides/day4.html)
4. Run:
   quarto render slides/day4.qmd
   quarto render index.qmd
5. Publish with your existing course workflow.

The materials have not been added to or published from your repository.

USE AS A STANDALONE QUARTO PROJECT
The supplied _quarto.yml, theme.scss, and slides/_metadata.yml allow rendering
the source without first adding it to the course. Run quarto render.

BROWSER SLIDES
Open day4-slides.html in a browser. Arrow keys advance slides. Press S for
presenter notes, O for overview, and F for fullscreen. Some browsers require
serving the file from a local HTTP server for the presenter view. The standalone
copy embeds its style and Reveal.js assets and does not need a CDN.

The standalone HTML and PDF are review copies built from the same source.
The PDF is separately typeset from the slide content, so minor layout
differences from the Quarto presentation are possible. Quarto and browser
rendering were unavailable in the preparation environment.
Quarto rendering in the existing course remains the normal publishing route.

TEACHING
The main lecture has 28 slides plus 3 reference slides. The guide provides a
50-minute sequence with the seven DS requirement areas, a live tour of five
programs, an updated Venn diagram, and brief MAP sheet, MyMAP, and advising
demonstrations. The instructor recommends DS as a starting point for undecided
students and emphasizes learning and experience beyond the major choice.
Follow current Canvas instructions for the graduation plan and advisor/TA assignment.

REQUIREMENTS
The DS link is the instructor-supplied 2025-2026 catalog. The other four program
links open the current catalog. The Venn diagram shows selected core courses,
not complete requirements or all elective overlap. ML allows STAT 201 instead
of STAT 121. Students should use their own catalog year and degree audit.
The guide explains source-year differences and legacy course labels in the MAP sheet.
