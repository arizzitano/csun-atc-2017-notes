# Bring Accessibility into the Development Lifecycle with CI Testing

Alastair Garrison, SSB Bart - 3/1/2017

## Testing Components
- Component-level acceptance tests
- Integration-level acceptance tests
- BDD: software should be built and tested in terms of desired behaviors

## User Stories
- Gherkin style: given x condition, when y condition, then outcome
- User stories are associated with code functions
- Requirements for the story are used to set conditions for test

## Process
- User story serves as input for dev
- Write code and tests based on the story requirements

## Accessibility testing libraries
- stand alone libs of a11y checks
- accessengine
- JS based
- May add JS script tag to the page
- In Cucumber, you write step definitions
- For mobile, "instrument" the code: include testing lib in non-production code

## Bringing a11y into BDD
- Smoke tests: WHEN i run a11y tests, THEN no tests will fail
- This works with simple stuff like axe
- Also check explicitly for a11y behaviors
