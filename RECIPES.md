# Small artifact recipes

These are optional practice examples, not tested time-to-competence promises. Scale them to your experience, permitted access, and available sessions. If you cannot yet define the task, checking that missing fact can be your first artifact.

Use synthetic or appropriately licensed public inputs. Keep credentials, employer data, client information, and private assessment answers out of repositories, screenshots, and unapproved tools.

## Python: transform a small CSV

- **Prerequisites:** a runnable Python environment, a small permitted CSV, and a way to inspect JSON. A standard-library-only version is a possible starting scope.
- **Result:** one short script, sample input, expected JSON, and a note explaining field handling.
- **Checks:** try a quoted comma, an empty value, and a missing required header. Compare output with known expected records; report errors rather than silently dropping a bad row.
- **Evidence to retain:** actual outputs, a failed or corrected assumption if one occurred, help used, and what you can explain or change independently. Do not manufacture failures to fill a quota.
- **Day-30 condition:** continue if the transformation serves the task and remains useful after checking, restart, and maintenance costs. Narrow or defer if those conditions do not hold.
- **Limit:** a small file conversion does not prove production reliability, scalability, or employability.

## SQL: answer one question with checked data

- **Prerequisites:** an approved query environment and a small dataset with a known expected answer. Do not bypass database permissions.
- **Result:** a saved query, the question it answers, expected rows or totals, and assumptions about the sample.
- **Checks:** include duplicates and NULLs. If joining tables, inspect unmatched rows and whether the join multiplies records. A multi-table join is not mandatory when a simpler query answers the question.
- **Evidence to retain:** query text, sample schema, expected and observed results, and any remaining uncertainty.
- **Day-30 condition:** continue if the query supports a real need, you can explain it, and access remains appropriate. Clarify access or try a smaller permitted sample if the environment prevents a meaningful check.
- **Limit:** passing on a sample does not establish correctness on company data, performance at scale, or authorization to deploy.

## Frontend: one usable interaction

- **Prerequisites:** a runnable local page and one intended user action. React is optional; existing HTML and JavaScript may be sufficient.
- **Result:** an input, an output, an empty or loading state where relevant, and one understandable error state.
- **Checks:** use keyboard navigation, a narrow viewport, and invalid input. Confirm that labels and error messages explain what someone can do next.
- **Evidence to retain:** the local demo, test cases, known limitations, and a note describing the behavior. Share a screen recording only if you can do so without exposing private information.
- **Day-30 condition:** continue if the interaction serves the intended task and can be inspected by an appropriate reviewer; otherwise clarify the need, narrow the interaction, or defer it.
- **Limit:** public hosting is not required. One page does not establish complete accessibility, security, or production readiness.

## AI-assisted work: review a variable output

- **Prerequisites:** an approved tool, permitted sample inputs, and criteria for checking the output. Do not submit sensitive data to an unapproved service.
- **Result:** a short task brief, a prompt or workflow note, representative inputs, and a review checklist. Model or tool access may involve costs; this recipe does not require buying a specific service.
- **Checks:** include a normal input and a difficult or incomplete one. Compare outputs with the stated criteria and record uncertainty, factual errors, or missing information when observed.
- **Evidence to retain:** the tool/model and date, settings where available, inputs, observed outputs, review effort, and changes you made. Repeating a prompt may produce a different answer.
- **Day-30 condition:** continue if the reviewed output improves the intended task after usage and checking costs are considered. Use another method or defer if the output cannot be checked appropriately.
- **Limit:** no fixed failure count or identical-output guarantee. A successful sample does not establish accuracy across tasks or permission for unsupervised use.

## Common Day-7 review

1. What did I attempt, and what can I inspect?
2. Did the check address the task, or only completion of a lesson?
3. What help, setup, access, and feedback affected the result?
4. What remains unverified?
5. Should I continue, narrow, clarify, defer, or stop this particular test?

Use [TEMPLATE.md](TEMPLATE.md) to record the review and [EXAMPLE.md](EXAMPLE.md) for a fictional worked comparison. Lessons, documentation, and AI assistance are allowed; explain their role rather than claiming unsupported independent competence.
