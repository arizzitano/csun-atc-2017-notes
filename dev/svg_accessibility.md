# SVG Accessibility

Chaals McCathie Nevile, Léonie Watson - 3/2/2017

## History
- has been around since late 90s, used on early mobile devices
- "all" browsers support, no real spec
- standalone document
- bg image
- img element

## Accessible Name
- gets an exposed role of image/diagram
- can explicitly set role="img"
- SVG title: first one exposed as accessible name
- Multiple titles NEED aria
- <desc>: provide detailed description
- May need aria-describedby for multiple descs

## Text
- Available to assistive tech as plain text
- Links: <a xlink:href="#foo"> - inconsistent behavior
- Tabindex works in all browsers

## Defining objects
- <defs> elem
- You can reuse it with <use>

## Charts
- A bar chart is a table, so use role="table"
- Use role="rowgroup, rowheader, cell, etc", aria-level

## Zoom and pan
- Need to make sure legend/key is always accessible to users
- onzoom event
- currentScale property
- vector-effect="non-scaling-stroke"
- you can also use css. media queries work in svgs too
- good idea to use css to highlight focus area

## Animation
- <animate> elems
- specify id, where to move it, what to do with it, etc
- Can name another animation, hook into its beginning or end
- Can trigger based on user interaction
- id.click
- 27s
- id.end+13s
- don't use accesskey. it doesn't work!
- You can explain them with aria-live. it just works :)
- it doesn't work in ie or edge :((((
- easy to produce!!

## W3C
- work underway to reorganize spec with a11y focus
- needs volunteers
