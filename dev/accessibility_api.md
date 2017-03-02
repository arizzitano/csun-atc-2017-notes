# Introduction to the Accessibility API

David MacDonald, CanAdapt

http://davidmacd.com/slides/csun/CanAdapt-what-is-the-accessible-API.pdf

## History
- Text-only OSs easy for screen readers to use
- GUIs made it more complex
- Microsoft drove a lot of SR development
- Different AAPIs for apple, windows, linux

## Accessibility Tree
- Subset of the DOM, trims out things that aren't necessary
- Talks to accessibility API
- To see it use https://www.paciellogroup.com/resources/aviewer/
- You can inspect objects on windows system
- The best way is to just use a screen reader

### Fields
- AccRole
- AccName
- AccValue
- AccDescription
- AccState
- AccDefaultAction
- AccParent
- There's also UIAutomation

### Examples
- aria can badly mess it up! Different names can supercede each other
- don't do more with aria than you're comfortable with
- checkbox: no value just state

### How it works
- User tabs
- Form field gets focus
- hits a11y tree
- returns name to OS
- screen reader reads the name

## Why use ARIA?
- provide simple interactive controls like radio buttons and dropdowns
- custom components like menus
- non native interactive controls
- use native stuff when possible!
- just use a dang select menu or a real button element
- announce important changes to the content (aria-live)
- aria 2.1: change of content
- add structure to a page
- don't let stuff that you hide from sighted people be visible to blind people
