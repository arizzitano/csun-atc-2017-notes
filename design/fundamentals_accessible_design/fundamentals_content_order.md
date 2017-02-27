# Content Order

## Why important?
- What happens if you view the page without CSS? Page should appear in correct order
- AT order can be dramatically different from visual order
- Can be really hard to reach desired location
- Tab shouldn't dramatically shift location in page

## Design
- Annotate design comps
- Indicate desired order to developers to prevent implementation problems
- Problem: 2 column layout
- Indicate focus order as well as visual order
- Match focus and visual order unless an exception is intentional
- This must extend to responsive layouts
- DIFFERENCES between mobile and desktop should generally NOT cause differences in focus order

## Implementation
- NEVER USE TABLES - ordered row by row, not col by col
- Don't space things out with whitespace characters

## Style guide
- Layout templates & style guides make things easier for developers
- Follow template conventions, don't bend them to your will
- If you solve an order problem, add it to pattern library

## Exercise
- [Content Order Exercise](content_order_exercise.JPG)
