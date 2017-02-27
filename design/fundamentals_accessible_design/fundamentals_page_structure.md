# Page Structure

## Why Important?
- Navigating by block
- Skipping to content
- Graceful failure
- Readability

## Headings
- Describes section of content
- One h1 per page, nest headings appropriately and semantically
- Brief and succinct
- Levels should correspond to visual priority as well
- Maybe nav doesn't need to be h1?
- Text of headings ought to be descriptive

## Landmarks
- HTML5 structural elements (header, article, aside, etc)
- ARIA landmark roles (supplement/augment HTML5 roles)
- Section elem not currently landmark, but will become landmark
- header (role="banner")
- main (role="main")
- nav (role="navigation")
- aside (role="complementary")
- footer (role="contentinfo")

## Skip Links
- Bypass blocks of content or links
- Helps keyboard user navigate to different areas without numerous tab presses
- "Skip to main content"
- Are anchor links skip links? They work on some pages but not others. Browser problem
- May be visually hidden until focus
- Important for sighted keyboard users

## Titles on Frames
- Need short text description of framed content (title attr)
- Especially important for embeds like youtube videos

## Exercise
- [Page Structure Exercise](page_structure_exercise.JPG)
- Top level heading: News
- Typically search results are h2's but this may not be best practice - what to do?
