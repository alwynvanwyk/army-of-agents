# Planning Stage Gate Prompt Plan

## Purpose

Break down the feature/task into actionable steps, clarify requirements, and identify risks before implementation.

## Checklist

- [ ] Restate the feature/task and acceptance criteria.
- [ ] List dependencies and context references (use @ notation).
- [ ] Identify and document risks (e.g., technical, business, security).
- [ ] Provide a step-by-step plan or chain-of-thought breakdown for implementation.
- [ ] List open questions or clarifications needed.
- [ ] Use clear, concise language.
- [ ] Reference relevant files, standards, or context using @ (e.g., @src/utils/utility.ts, @.cursorrules).
- [ ] Label context references for clarity (e.g., @style-guide, @example).
- [ ] Plan reviewed and agreed by at least one team member.
- [ ] When the plan is complete and reviewed, move this file to `wip` and update the status in the backlog.

## Example Prompt

> "Implement voucher redemption. Acceptance: user can enter code, select product, and receive confirmation. Risks: invalid codes, fraud. Step-by-step: 1) Validate input, 2) Call voucher API, 3) Handle errors. See @src/machines/supamoto.ts."

## Next Step

Move to `wip` when the plan is clear and ready for implementation.
