# Web Design Skill

## Design source selection
For a greenfield web UI, prefer:
- shadcn/ui primitives and patterns
- Tailwind CSS
- a consistent token system
- an established frontend design skill when available

For an existing app, preserve its established design system unless the task explicitly changes it.

## Process
1. Inspect existing UI/components.
2. Identify reusable primitives.
3. Define visual tokens.
4. Build responsive structure.
5. Implement accessible states.
6. Test critical flows in a real browser when available.
7. Review desktop + mobile behavior.

## Quality bar
A production UI must account for:
- responsive breakpoints
- keyboard navigation
- focus states
- semantic structure
- contrast
- loading/empty/error states
- form validation
- reduced-motion considerations where relevant
- maintainable component boundaries

Do not create decorative UI without product purpose.
