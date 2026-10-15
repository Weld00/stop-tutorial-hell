# Worked example: Python, SQL, or the existing spreadsheet?

**Fictional example.** These circumstances, observations, and numbers were invented to demonstrate the template. They are not customer results or a recommendation for every learner.

This applies the four-step protocol in [README.md](README.md); [RECIPES.md](RECIPES.md) contains other small task ideas.

## Situation and checked facts

An operations coordinator wants to reconcile two weekly CSV exports and identify missing order IDs. A checked result would help the team review exceptions. They can protect two one-hour sessions and one two-hour session each week; this is this person's schedule, not a minimum learning requirement.

They can use a prepared, synthetic sample with known missing and duplicate IDs. A local Python environment is already available. Access to the company's reporting database is still awaiting approval. The coordinator already knows basic spreadsheet lookups and some Python loops.

**Important unknown:** is the spreadsheet process actually the bottleneck? If it already meets the need reliably, learning another tool may not be the next useful step.

## Compare the options

| Route | What can be tested now? | Important limitation |
| --- | --- | --- |
| Existing spreadsheet | Reconcile the sample, check known exceptions, and measure the actual effort. | A working sample does not establish that the workbook handles every future export. |
| Python | Read the sample files with the standard-library CSV module and compare IDs. | A short script needs checking and instructions; a working demo is not a production process. |
| SQL | Ask about approved database access and inspect a permitted schema example. | A tutorial database does not establish permission to query company data. |

## Provisional focus

Start by checking the existing spreadsheet on the same sample. Only spend the remaining sessions on a small Python comparison if there is a concrete limitation to investigate. Keep SQL deferred until the access question is answered or a different task makes it relevant.

This is not “Python beats SQL.” It is a choice about the task and conditions currently available. If the coordinator did not know enough to attempt a script, the first test would need a smaller prerequisite or a different route.

## First-week test

1. Prepare synthetic files with four known missing IDs, one duplicate, and an empty-ID case. Write the expected result.
2. Run the existing spreadsheet approach and inspect whether it finds those cases. Record corrections and total checking time.
3. If a limitation remains, try one small Python version on exactly the same sample. Explain its matching logic and compare results, including duplicate and empty IDs.

Use permitted sample data only. Do not upload company exports to an unapproved tool or publish them in this repository.

## Fictional Day-7 review

The spreadsheet found the missing IDs but the coordinator had to correct a blank-ID assumption. A first Python version also mishandled blanks. After a focused correction, both approaches matched the expected sample output.

That result does **not** prove that the script saves time, that all edge cases are covered, or that the coordinator has learned Python. It supports one smaller next step: repeat the comparison on another permitted sample and include checking and restart time.

## If continuing through Day 30

- **Week 2:** repeat on a second synthetic sample and write down assumptions.
- **Week 3:** change a column name and test missing, duplicate, and empty IDs again. Record how each route fails and recovers.
- **Week 4:** package the more useful approach with instructions and limits. Ask an appropriate reviewer whether another test is justified before any real workflow use.

Keep the spreadsheet if it remains the better fit. Continue Python only if the observed benefit justifies its checking and maintenance costs. Revisit SQL when the task and approved access support it; do not invent an access deadline.

## Next decision

Choose between continuing, narrowing, clarifying, deferring, or stopping this specific test based on the new observations. No claim about a career transition, income, job readiness, or permanent skill preference follows from this exercise.
