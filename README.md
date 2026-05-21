# Fieldwork: The Convergence

A science-fiction final exam for graduate qualitative methods classes. Students enter a fictional fieldsite, hit the same methodological dilemmas they would meet in real fieldwork, and write their way through. The story-world is set in 2100. The dilemmas are real.

## What this is in plain terms

You assign your students a final exam. Each gets a personalised scenario as a researcher deployed to one of four non-human frontiers: a beaver colony on a boreal river, a sperm whale pod, a forest mycelial network, or an alien collective-resonance society. Fieldwork starts. Things get complicated. The student writes their reasoning. Their mission log is the artefact you grade.

The point is cognitive distance. A scenario about an alien species you have never met lets a student think through positionality, reflexivity, and empathy without the threat of getting their own thesis fieldwork wrong on paper. The methodological tension is still real. They will go back to course readings under fictional conditions and defend their choices in writing the way they will one day defend choices in real research.

## Try the demo first

Play it in your browser: **[DoopsintheWind.github.io/fieldwork-convergence](https://DoopsintheWind.github.io/fieldwork-convergence/demo/convergence_demo.html)**. Or open `demo/convergence_demo.html` locally after cloning.

Type a name, pick a frontier, click through a sample two-part exam, and see one of the sixteen consequences land. The demo covers two frontiers (Beaver and Kaia) with one path each. It shows the shape of the experience without you having to imagine it.

## What is in this repository

```
README.md                  · this file
LICENSE                    · MIT license for code (the demo HTML/CSS/JS)
LICENSE-CONTENT            · CC BY 4.0 license for all written content and the demo images
DISCLAIMER.md              · fiction, science, cultural-representation, content-warning, and no-warranty statements

world_lore.md              · year 2100 frame, ESSA, the four frontiers in overview
kaia.md                    · Kaia frontier briefing + the real science behind it
deep_speakers.md           · Deep Speakers (sperm whale) frontier + the science
root.md                    · Root Network (mycelial) frontier + the science
beavers.md                 · Beaver frontier (boreal watersheds) + the science

scenarios_kaia.md          · example exam scenarios on the Kaia frontier
scenarios_deep.md          · example exam scenarios on the Deep Speakers frontier
scenarios_root.md          · example exam scenarios on the Root Network frontier
scenarios_beaver.md        · example exam scenarios on the Beaver frontier

sample_debrief_letter.md   · one example of the post-exam in-world letter
readings.md                · qualitative methods + frontier-science reading list
note_from_claude.md        · a short note from Claude about working on this

demo/                      · a playable HTML demo of the exam
demo/SPEC.md               · the content spec the demo was built from
demo/convergence_demo.html · the playable HTML demo
demo/images/               · the images used by the demo

.gitignore
```

## Content notes for instructors

The exam material engages difficult themes that are part of the qualitative-methods territory it asks students to think through. None of it is gratuitous, but all of it is worth knowing about before you assign. The list below flags the heaviest content by frontier so you can preview which scenarios fit which cohort.

- **All frontiers.** Eco-grief and climate-driven ecosystem collapse shape the 2100 backdrop. Institutional surveillance, whistleblower dynamics, and researcher culpability for harm appear in every frontier's scenarios.
- **Deep Speakers.** Historical and ongoing human harm to whales, including sonar damage to acoustic communities. Scenario 2 includes a branch in which the student-researcher conducts a non-consensual acoustic intervention; the framing condemns the choice.
- **Beaver.** Collateral harm to non-human young (kits losing winter food caches). The scenarios stage local-versus-institutional knowledge politics through fictional characters and place-based knowledge.

Three practical suggestions for adopters.

1. **Intake form.** Ask students on the pre-exam intake whether there are themes they would prefer not to engage with, and honour the request without requiring disclosure of why.
2. **Preview scenarios fully.** The demo shows lower-charge branches. Read the full scenario files before assigning.
3. **Debrief beyond the in-world letter.** The debrief letter (`sample_debrief_letter.md`) closes the narrative loop. If a scenario lands hard for a student, a short non-fictional check-in and a reminder of your institution's student counselling resources at grading time may matter more than the letter.

## How to actually run this in your course

No game engine. No coding. You need three things.

1. A way to give each student a personalised scenario before the exam window.
2. A way for students to write their responses (an LMS text box is fine).
3. A way to grade what they write.

### Step 1. Read the world

Start with `world_lore.md`, then read the four frontier files (`kaia.md`, `deep_speakers.md`, `root.md`, `beavers.md`) in any order. Each pairs the story with the real science. After reading, you should be able to talk about each frontier with a colleague.

### Step 2. Read one scenario end to end

Pick any `scenarios_*.md` file and read one full scenario. Every scenario has the same shape. A briefing, a Part 1 narrative ending in four decision choices, and four Part 2 branches that each develop one of the choices.

### Step 3. Decide what to give your students

Two options.

**Option A. Use the scenarios as written.** Assign one, or let students pick. They read the briefing, write Part 1 with their choice and justification, and submit. You then send Part 2. They write their second response and submit the mission log.

**Option B. Personalise the scenarios with Claude (or another LLM).** This is the version this exam was piloted with. Ask each student to share their thesis topic and the methodological challenges they expect to find hardest. Then sit with Claude and build a scenario per student that pulls on those worries. Keep one of the four frontiers, tilt the dilemma toward what the student needs to think about. See the next section for the workflow.

### Step 4. Grade

The mission log is qualitative writing. Grade it the way you grade other reflective writing in your course. There is no rubric in this repository, on purpose. Build the rubric that fits what you want to test.

### Step 5. Send a debrief letter

After grading, send each student a short letter (one page or less) in the voice of a fictional participant from their scenario, telling them what their fieldwork meant to the community they researched. `sample_debrief_letter.md` is one example. Ask Claude to draft it from the student's mission log, then revise by hand so the voice lands clean. Students remember the letter more than the exam.

## Working with Claude on the personalised version

The exam works best when each student gets a scenario built for them. Doing this by hand for a whole class is hard. Working with Claude makes it possible for one instructor.

A workflow that works:

1. Read the world files yourself first. Claude can write inside this world, but you have to know whether the draft is staying inside it.
2. Give Claude the student's thesis topic and the methodological challenges they named in your pre-exam intake form.
3. Ask Claude to draft a Part 1 briefing with four choices that pull on those challenges, set on one of the four frontiers.
4. Read the draft. Push back. Ask Claude to sharpen the dilemma, make the choices less symmetrical, or specify the participants further. Revise. This step is the work.
5. When Part 1 is good, ask Claude to draft Part 2 crises branching from each Part 1 choice.
6. Stress-test it. Ask Claude to play a student taking the exam, and see whether it surfaces what you wanted.
7. Keep notes on what worked. You are the editor. Claude is the partner.

Iterative co-design, not one-prompt-and-done. The pay-off is every student getting a different exam without you hand-writing each one from scratch.

## What you can do with these materials

All written content (the world files, the scenarios, the readings list, the sample debrief letter, the demo spec) and the demo images in `demo/images/` are licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

You can:
- Use the materials in your own teaching, including at a tuition-charging institution.
- Adapt the materials, rewrite them, mix them with your own.
- Translate them into other languages.
- Quote from them in articles, conference papers, talks, or training materials.
- Generate variations using AI tools and use the results in your course.
- Use the demo images freely in your slides, syllabi, course pages, and presentations.
- Build something commercial on top of the materials. CC BY 4.0 allows commercial use.

You must:
- Give attribution. The suggested citation is below. Where space allows, include a link to the original repository.
- If you adapt, say so. A short "Adapted from..." line is enough.

You do not need to:
- Ask permission first.
- Share your adaptations back (though I would love to see them).
- Pay anything.

The HTML, CSS, and JavaScript code in `demo/` is licensed separately under the **MIT License**. The same freedoms apply, with the same attribution requirement.

## A note on fiction

This is a work of fiction. ESSA, the Sovereignty Compact, the Integration Alliance, the Maritime Cooperative, the Consensus Federation, the Mycelial Signal Project, the Convergence Ethics Panel, all named research stations, all named characters, and all in-world institutions, events, and dialogue are products of the author's imagination. Any resemblance to actual persons, living or dead, or to actual events, is purely coincidental. Where the lore files reference real scientific research, those references credit the original authors and are listed in `readings.md`.

Where a scenario names a kind of community knowledge or local practice, this is worldbuilding for an exam exercise. It is not a representation of what any specific real community has said, done, or believed. Adopters teaching the scenarios in places where local knowledge traditions exist around the topics depicted are welcome to substitute locally relevant characters and settings.

For the full disclaimer (fiction, scientific authority, cultural representations, content warnings, educational purpose, no endorsement, no warranty), see `DISCLAIMER.md`.

These materials are released in the author's personal capacity and do not represent the positions of any employing institution, funding body, or co-author.

## A note on the images

The images in `demo/images/` were generated by Dinara Pisareva using Adobe Firefly under a paid Adobe subscription, which grants user ownership and permits commercial use of outputs. These specific outputs are released to adopters under CC BY 4.0 terms, to the extent any rights exist. Because AI-generated outputs may not be subject to copyright in all jurisdictions, the CC BY 4.0 grant operates as a permission from Dinara Pisareva not to assert claims over your use. You can use, share, and adapt them with attribution.

## A note on the science

The four frontiers are pedagogical objects, not biology. The Kaia are invented. The Deep Speakers borrow heavily from real sperm whale culture research (Whitehead, Rendell, Gero, Hersh, Sharma). The Root Network borrows from work on forest mycelial signalling (Simard, Babikova, Adamatzky, Tero) and acknowledges the live debate over how far that work can be taken (Karst et al. 2023). The Beaver Frontier borrows from beaver ecosystem-engineering research (Rosell, Brazier, Polvi and Wohl, Goldfarb). Each frontier file marks which claims are science-backed and which are speculative extensions for the world-building.

## Suggested citation

> Pisareva, D. (2026). *Fieldwork: The Convergence*. CC BY 4.0. https://github.com/DoopsintheWind/fieldwork-convergence

## Contact

If you adapt this exam, I would love to see what you build. Open an issue on this repository.
