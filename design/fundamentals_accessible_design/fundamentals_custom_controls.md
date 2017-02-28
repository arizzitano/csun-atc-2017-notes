# Custom Controls

## What is it?
- Non-native control, not part of spec, not out of box
- Often impossible for AT or keyboard users to use
- All the good styling in the world won't make it usable for AT users
- Role, name, value, state - design must hand this off to developer
- Try very hard to use native controls, until you can't.

## Role
- What is it?
- Look at available roles in aria spec
- What role does this particular control have?
- Some controls may have a complex hierarchy of different roles

## Name
- What's it called?
- Unique identity that distinguishes it from other controls with similar functionality

## Value
- What data does it contain?
- May be either inherent or entered by user
- Changes in response to user input

## State
- Temporary/ephemeral
- "expanded" "selected" etc
- Like React state
- Designer should pass this over to developer - back and forth process

## Accessibility Tree
- Accessibility inspector: comes with XCode on mac
- Contains browser/OS representation of these custom controls

## Exercise
- [Modal Dialog Exercise](custom_controls_exercise_1.JPG)
- [Combobox Exercise](custom_controls_exercise_2.JPG)
