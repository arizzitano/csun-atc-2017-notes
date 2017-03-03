# Accessibility, Visual Design, and Front-End Development

Mitchell Evan, Sam Joehl; SSB BART - 3/2/2017

## Contrast
- Easy to flag non conformant
- Fix: text color, bg color, font size or weight
- Make sure to cover all possible UI states
- Selected/hover state, etc needs good contrast too

### Designing for Contrast
- Why is gray-on-gray so pervasive?
- Design trends inspired by vision of digital world
- Find examples of good high contrast work, share with designers
- Maybe I should start a mini newsletter?
- Bold text, illustration, shapes
- Nav links/tabs need distinguisher other than color (outline?)

### Developing for Contrast
- Iterative design as well as development
- Design leads a11y strategy, designer mainly responsible for contrast

## Keyboard
- Some people think it's binary - "just make it keyboard accessible"
- Tab order
- Focus management, in-page updates
- Tab, shift-tab, arrow, space
- Need visual focus indication on all tabbable elements and logical focus location at all times
- When to rely on browser's focus indicator? When to roll your own?

### How to do it?
- Shared responsibility
- Tab order: developer
- Visual focus indication: designer
- Select or activate: dev, a11y specialist
- Focus management: dev, a11y specialist
- Mobile first/responsive approach helps maintain logical focus order
- Small screens, screen readers, and tab nav linearize page content