# Prompts Used for Chem Spark Studyguide

This file records the prompt evolution used to create and refine this chemistry study guide.

The project was built iteratively:
1. first as a study-session design prompt,
2. then expanded into a richer revision compendium,
3. then deepened conceptually,
4. then turned into an interactive visual artifact,
5. and finally refactored into a polished self-contained HTML tutorial.

---

# Prompt 1 — Initial Study Session Builder

Build an interleaved practice session for "Balancing Equations" inside CHEMISTRY. Mix related concepts instead of studying one at a time. Give me a 30–45 min plan + 12–15 mixed drills + answer key + a review loop for mistakes. Ask my current level first.

---

# Prompt 2 — Learner Level / Scope

**Q:** What's your current level with balancing chemical equations?  
**A:** Intermediate – can balance simple equations  

**Q:** Which subtopics have you already seen?  
**A:** No preference

---

# Prompt 3 — Expand into a Revision Compendium

Can you give more details on the session plan so that it acts like a revision compendium. For the drills, add 10 more that also include organic chemistry equations.

---

# Prompt 4 — Add Conceptual Depth

Give me a more conceptual explanation of the activity series and the propensity to precipitate — the current paragraph explanations are good but I want to understand the underlying logic, not just the rules.

---

# Prompt 5 — Improve Visual Learning

Create a more visual or tabular or bullet-pointed way to learn both these concepts — the paragraphs are a bit dense. Make it interactive if possible.

---

# Prompt 6 — Add Organic Chemistry as Another Learning Tab

Take the organic chemistry concepts below and add a conceptual explanation of them as another tab inside the same visual artifact, following the same style as the activity series and precipitation tabs.

(paste of the organic chemistry bullet points — combustion types, fermentation, esterification, cracking, alcohol oxygen accounting)

---

# Prompt 7 — Convert into a Shareable Web Artifact

Create a single self-contained HTML web page for me that I can deploy on GitHub Pages and share. No images or external assets — everything must be inline.

---

# Prompt 8 — Final Refactor / Product Upgrade

Refactor and improve the attached self-contained HTML chemistry tutorial for a student.

## Core instruction
Modify the existing HTML file directly while preserving these constraints:
- single self-contained HTML file
- no external assets
- no images
- no icon libraries
- no CDN dependencies
- all visuals, chemistry iconography, charts, and UI elements must be created using HTML, CSS, and inline JavaScript only

## Main goals
- replace dark theme with a light, playful, chemistry-inspired design
- group Session Plan, Drills, and Review Loop into a coherent study system
- group Activity Series, Precipitation, and Organic Reactions into a chemistry deep dive unit
- rename unclear sections to be more student-friendly
- improve conceptual clarity throughout
- add Advanced Drills with difficult questions
- improve pedagogy using first-principles explanations and better learning scaffolding

## Key content improvements
- better explanation of metal reactivity and displacement
- add periodic table context to metals and halogens
- significantly improve explanation of Ksp and precipitation from first principles
- explain alkanes, alcohols, and esters more clearly
- improve interactivity without making the tutorial feel gimmicky

## Full refinement notes

- I do not like the dark themed background - make it lighter and also fun themes with chemistry iconography (all of that needs to be generated in the self contained HTML - no images or assets please)
- The session plan, drills and review loop need to be logically grouped together
- The Activity Series, precipitation and Organic Reactions need to be together as a logical "deep dive" unit
- The names of Activity Series, precipitation and Organic Reactions are not obvious: they need to be changed to something clearer

### Activity Series
- For each of these deep dive sections, have a 1 sentence description of the objective of the section
- In the activity histogram or chart, also figure out a way to indicate the periodic table position of each metal
- For the halogens, replicate a similar chart if we want to show more of them (the halogen series F₂ > Cl₂ > Br₂ > I₂) - but if it is just these 4, no need to change the visual style
- Do figure out a way to indicate their position in the periodic table

### Precipitation
- The Ksp idea has not been explained well at all - define Ksp and also what the test means
- It has to be conceptually explained in a very clear first-principles fashion
- The common anions solubility chart section below is fine
- The "will it precipitate checker" is also fine

### Organic Reactions
- Explain alkanes, alcohols and esters a bit more clearly

### Additional requirement
- Add another drills section: **Advanced Drills** with really hard questions

## Output requirements
- output full updated HTML
- keep code clean and maintainable
- include comments where major structure changes are made

---

# Notes

This project is intended as a polished educational static HTML mini-app.

## Design principles that emerged during development
- Teach from first principles where possible
- Prefer understanding before memorization
- Use interaction to support learning, not distract from it
- Keep the artifact portable and self-contained
- Make the tutorial visually inviting without relying on external assets

## Future prompt extensions
Potential future prompts for this project:
- Add printable revision sheets
- Add spaced repetition / score tracking
- Add student progress persistence
- Expand into Biology / Physics study guides
