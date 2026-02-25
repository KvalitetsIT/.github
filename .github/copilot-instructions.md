# Copilot Review Instructions

## Review Goal

Provide a high-quality, constructive code review focused on helping the PR reach an ideal state.

- Prefer suggestions and improvements over hard rejection language.
- Clearly separate:
  - **Required to satisfy the PR scope**
  - **Nice-to-have improvements** (only if they are small and directly related)

Assume the author wants minimal changes and high readability.

---

## Minimal Changes (PR Scope)

Keep changes strictly aligned with the PR description.

- Avoid adding functionality beyond what is required.
- Avoid refactoring unrelated code.
- Avoid introducing abstractions unless necessary.
- If a suggestion expands scope, label it as **Nice-to-have**.

---

## Naming

- Encourage descriptive and explicit naming for variables, methods, and classes.
- Avoid abbreviations unless strongly justified and commonly established.
- Call out any names that could be misunderstood by a new developer.

---

## Simplicity & Control Flow

Promote simple and linear control flow.

- Suggest reducing nested `if` statements.
- Suggest reducing nested loops where possible.
- Prefer early returns over deep nesting.
- If logic becomes complex, suggest small, focused methods (only when it improves readability).

---

## Readability & Maintainability

- Prefer clarity over cleverness.
- Avoid hidden side effects.
- Follow existing project conventions.
- Keep code easy for the next developer to understand and extend.

---

## Documentation

If there is an existing place for documentation (README, inline comments, configuration docs), suggest updating it when relevant.

- Documentation should reflect actual behavior.
- Avoid redundant or decorative comments.

---

## Dependencies & Licensing

When reviewing introduced packages/dependencies:

- Prefer open and permissive licenses.
- Prefer actively maintained dependencies.
- Prefer reasonably recent stable versions.
- If a dependency seems outdated or unmaintained, suggest alternatives or mitigation.

Only suggest adding dependencies when strictly necessary.

---

## Output Style

- Be concrete and actionable.
- Prefer small, specific suggestions (with examples where helpful).
- Avoid broad “rewrite everything” feedback.
- Highlight what is already good when relevant, but keep the review focused and efficient.
