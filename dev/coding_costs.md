# Coding Costs: Nudging Your Developers

Tatiana Iskandar, Jesse Beach, Facebook - 3/1/2017

## How to optimize a11y expert time?
- Processes and tools for a11y
- Nothing required
- a11y team < 10 people
- 30k react components (!!!!!!!!)
- Grow team IMPACT, not size

## Dev Productivity
- Simple errors (low level stuff)
- Integrate guides with developer tools
- Question: what about typescript?

## JS
- Default props
- Strong typing for JS: flowtype.org. Annotate JS with type
- React warns against invalid aria attributes
- Linting/aria attrs

## Testing
- Manual tests (the fewest)
- e2e tests
- integration tests
- unit tests
- linting rules (the most, base of automation pyramid)

## Linting
- Contextual feedback before code gets COMMITTED (pre commit hooks)
- Lint for things like specific handlers, wrong roles, etc
- Linter errors show up in IDE
- Question: where is their linter config?

## Stuff to use
- eslint-plugin-jsx-a11y (evcohen/eslint-plugin-jsx-a11y)
- ARIA Query (a11yance/aria-query)
- Link rule violations to documentation

## How to fix existing issues in code?
- Codemodding (fix all similar problems at once)
- Use lint tools to find existing errors
- Write script to fix the errors in code
- facebook/jscodeshift
- makes sense for large codebases, like facebook

## How to deal with review bottlenecks?
- auto-subscribe to a11y diffs
- tag-team reviews, build up group of experts
- praise authors

## Components
- Inaccessible interactions can be traced to inaccessible component
- Engineers may not know a component exists
- They tend to start new ones from scratch
- FB components unstyled and purely functional
- Abstract away aria specifics so devs can use them without having to know
- Abstract components + behaviors
- Facebook: ui component explorer (internal only)

## Dealing with Regressions
- Support champions
- Provide docs (wiki)
- Guides for debugging, aria, SRs, etc
- Provide support
- a11y rallies: collaborate with product team and fix as many issues as possible
- empowers devs to act as a11y advocates for their teams

## Automate teaching moments
- Document criteria
- Categorize tasks based on tags/descriptions
- Milo Bot performs maintenance on tasks, applies tags, subscribes people, provides specific explanation, etc
- IDK if we need this, might be overkill.

## Awareness
- Product devs need to know about a11y problems
- Need to know about a11y in general
- Bootcamp: 6-8 week training for new hires (holy crap)
- Give new hires easy a11y tasks
