# Images

## Alternative Text
- alt attribute (WHEN NEEDED): easy to learn, difficult to master
- Other benefits: SEO, low-band, text browsers, etc

## Informative Images
- Photos, icons, screenshots, logos, simple diagrams
- Images that convey important content
- These require an alternative format
- How do you convey something like a painting?
- What about a logo?

## Linked Images
- Need alt text!! Otherwise SR user doesn't know where it goes
- Alt text should focus on purpose of link
- Text needs to describe what image link DOES, not what it SHOWS

### Icon Fonts?
- Hard to make totally robust + accessible.
- SVG is the way to go.
- Icon fonts usually have useless text value associated. Need aria attr or alt text.
- Opera Mobile does not render icon fonts
- Developers use letters (font icon characters) -- need to hide with aria-hidden. Show text label in accompanying span for SR users

## Complex Images?
- Charts/graphs need alt text (how???)
- Comic strips
- longdesc???

## Sometimes alt text is not needed
- Captcha (alternative means of output)
- Redundant/duplicate content (when image already has an accompanying label)
- Decorative images (e.g. bg images) - doesn't convey important information

## Exercise
- [Alt text exercise](images_exercise.JPG)
