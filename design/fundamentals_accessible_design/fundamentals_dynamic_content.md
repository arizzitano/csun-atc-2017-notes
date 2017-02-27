# Dynamic Content

## What is it?
- New content isn't obvious to SR users
- Modal interactions can be difficult
- Form validation can be useless (e.g. calling out errors)

## Remote Updates
- Require immediate user action (assertive)
- Provide general information (polite)
- Doesn't have to mean "far away"
- aria-live region

## Modals
- While open, hide bg page
- Constrain focus within modal
- User needs to interact only with modal - shouldn't be able to touch anything else on the page
- When dismissed return focus to trigger
- esc keypress should ALWAYS dismiss the modal

## Client Side Form Validation
- Don't validate on blur
- Validate on form submission or keypress
- Programmatically associate validation messages with form fields

## Widgets that just keep moving
- Carousel, feed, etc.
- Need mechanism to pause, stop, or hide

## Exercise
- Accessible carousel example: check out http://csun.edu
- [Dynamic Content Exercise](dynamic_content_exercise_1.md)
