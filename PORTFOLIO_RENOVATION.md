# Portfolio Renovation Notes

## Vision

Renovate the portfolio into an interactive virtual version of the CV rather than a static resume page. The site should feel polished, visual, and exploratory, with each experience represented through an interactive or animated project view.

## Core Goals

- Build the portfolio layout first, before committing to detailed animations.
- Make each experience visually show the related project or workflow in some meaningful way.
- Use high-quality visual animation as a central feature, especially for workflow-heavy experiences.
- Keep the experience grounded in the CV, but make it feel more like navigating real work than reading bullet points.

## Chosen Layout Direction

Use the PDF resume as the information architecture, not as a literal visual template. The website should be CV-inspired and recruiter-friendly at first glance, then expand into technical project depth for people who want to inspect workflows and implementation details.

The first implemented layout is a single-page interactive CV:

- Hero / identity section with role positioning and primary actions.
- Sticky CV navigator for `Experience`, `Projects`, `Skills`, `Education`, and `Contact`.
- Experience timeline where each role becomes a project chapter.
- Project/workflow panels inside each experience, with the financial documents workflow treated as the first flagship animation candidate.
- Skills layer grouped like the resume: Programming, AI & ML, LLM & Agents, Infrastructure & Data.
- Compact education, languages, mindset, and contact sections.

The current visual panels are placeholders. They reserve space and establish hierarchy before detailed animations are designed.

## Interaction Ideas

- Each CV experience can become its own visual section or project card.
- Selecting an experience should reveal a richer visual explanation of the work.
- Workflow-based projects should use animated schemas that show flow, system architecture, and stack usage.
- Animations should communicate the technical process clearly while also being visually impressive.

## Example: Financial Documents Workflow

Initial animation concept:

- The full stack/schema stays visible as a fixed visual map.
- A document icon starts at a `Dashboard` item.
- The document moves to a `Parse` step.
- The document transforms into `Pages`.
- The pages transform into `Chunks`.
- The chunks move into a `Vector Store`.
- An `Agent` appears or becomes active.
- The agent calls tools connected to the workflow.

The goal is for the animation to show both the data flow and the technology stack, making the architecture understandable without relying only on text.

## Open Questions

- Which experiences deserve full workflow animations versus simpler visual treatments?
- What stack should the renovated portfolio use?
- How detailed should each project section be compared with the PDF resume?
- What details should be added for each experience before designing its final animation?

## Next Step

Gather more details for the first flagship animation, starting with the financial documents workflow: exact steps, stack components, agent tools, UI states, and what should move or transform on screen.
