# Backlog Stage Gate Prompt Plan

## Purpose

Define requirements and context for new prompts/tasks before planning or implementation.

## Checklist

- [ ] Clearly state the task or feature to be addressed.
- [ ] Include acceptance criteria or success conditions.
- [ ] Provide any relevant background or links to related tasks.
- [ ] List any constraints (e.g., technical, business, integration).
- [ ] Include stakeholder feedback or approval section.
- [ ] Use clear, concise language.
- [ ] Avoid implementation details—focus on "what" not "how".
- [ ] When ready, create a new prompt file in `planning` and link related backlog items.
- [ ] Reference relevant files, standards, or context using `@` (e.g., `@src/utils/utility.ts`, `@.cursorrules`).
- [ ] Label context references for clarity (e.g., `@style-guide`, `@example`).

## Example Prompt

> "Design a REST API endpoint for user registration. The endpoint should accept email and password, validate input, and return a JWT on success. Acceptance: passes all unit tests and input validation. Constraints: must comply with GDPR and fit within 160 USSD characters. Stakeholder Feedback: Product Owner approved. See @src/routes/user.ts and @.cursorrules for standards."

## Next Step

Move to `planning` when requirements are clear and agreed upon.
