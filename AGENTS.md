# AGENTS.md

## Project
My personal portfolio: one static web page built only from resume.md.
Plain HTML and CSS. A few lines of JavaScript only if really needed.
No framework, no build step, no npm. It is hosted free on GitHub Pages,
so index.html must stay in the root of this folder.

## Files
- resume.md: the ONLY source of facts about me. Read it before every task.
- index.html: the page (semantic HTML: header, main, section, footer)
- style.css: all the styles
- Do not create any other files unless I ask.

## Content rules (most important)
- Use only facts written in resume.md. Never invent companies, projects,
  numbers, dates, skills, awards, links or testimonials.
- If resume.md has no facts for a section, leave that section out.
  No placeholder text ("Lorem ipsum", "Coming soon", "Add your project here").
- Keep my numbers and results exactly as written in resume.md.
- Never use the em dash character in any text (page, README, resume.md).
  Use a comma, colon or full stop instead.
- Never put a phone number, home address, date of birth or any ID number
  on the page, even if one is in resume.md.
- Email, LinkedIn and GitHub links only if they are in resume.md.

## Design rules
- Mobile first: it must look right on a 360px-wide phone and on a laptop.
- System font stack, body text 16px or larger, good contrast.
- Works in light and dark mode (prefers-color-scheme).
- No external CSS or JS libraries, no CDN links, no web fonts,
  no images I did not put in this folder.
- Section order, only where facts exist: Hero (name, one-line headline,
  links), About, Experience, Projects, Skills, Education, Contact.

## Never
- Never add a dependency, framework or build tool without asking me first.
- Never invent anything about me. If you need a fact, ask me.
- Never delete resume.md or this file.

## When you finish
- List every section you made and, for each fact, the resume.md line it came from.
- Tell me how to open index.html in my browser to check it.
