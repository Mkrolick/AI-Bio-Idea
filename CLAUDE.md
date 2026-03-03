# Fast Biology Ideas - Agent Instructions

## Mission
Generate highly original, technically tractable ideas for speeding up wet-lab biology experiments. Ideas will be submitted to the Fast Biology Bounties competition (deadline: March 15th, 2026).

## Judging Criteria (from the competition)
1. **Originality** - Novel approaches, not rehashes of existing ideas
2. **Technical Tractability** - Concrete, feasible approaches with clear implementation paths
3. **Clarity** - Well-articulated proposals

## What NOT to propose
- General/hand-wavey statements about wet-lab automation
- Cloud labs as a category
- "Physical intelligence" buzzwords
- Broad automation platforms without specific technical mechanisms

## What TO propose
- Concrete technical approaches to speed up specific methods (PCR, cloning, protein synthesis, etc.)
- Novel combinations of existing technologies
- Exploiting underused organisms or biochemical properties
- New instrumentation or chemistry approaches

## Ralph Loop Workflow

When running in a ralph loop, follow this cycle each iteration:

1. **Read `TODO.md`** - Check the global task list for the next uncompleted task
2. **Pick the highest-priority unchecked item** or continue work on an in-progress item
3. **Read the relevant `research/<path>/checks.md`** to understand validation criteria
4. **Do the work** - Research, write, refine, or validate
5. **Update progress** - Check off completed items in the relevant checks.md
6. **Append to `progress.log`** - Record what was done this iteration and key learnings
7. **Update `TODO.md`** - Mark completed tasks, add new tasks discovered during work
8. **Assess convergence** - If all research paths have passing checks and polished proposals, output the completion signal

## Completion Signal
When ALL of the following are true, output exactly: `<promise>FAST_BIOLOGY_COMPLETE</promise>`
- All research paths have all checks marked `[x]` in their checks.md
- All ideas in `submissions/` have been reviewed and scored above threshold
- TODO.md has no remaining unchecked high-priority items

## Research Path Structure
Each research path lives in `research/<topic-name>/` and contains:
- `hypothesis.md` - The core idea being explored
- `literature.md` - Relevant papers, prior art, and references
- `analysis.md` - Technical feasibility analysis
- `checks.md` - Validation checklist (must all pass before idea is promoted)
- `notes.md` - Working notes, dead ends, and learnings

## Commands
- Search the web for papers and prior art
- Read and write markdown files
- Use the Bash tool for calculations or data processing
- Do NOT modify README.md (competition description, read-only reference)

## File Conventions
- All research notes in markdown
- Use `- [x]` for completed items, `- [ ]` for pending
- Append to progress.log, never overwrite
- Proposals in `submissions/` are the polished final output
