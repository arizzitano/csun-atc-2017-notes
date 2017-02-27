# Fundamentals of Accessible Design
Caitlin Geier, Matthew Isner, Dennis Lembree
Deque Systems
2/27/2017

## Visual Information

### Color
- Color as information: good for people w cognitive disabilities
- Need alternative means of presenting this information for people who are colorblind

#### Ways to test for color contrast issues
- Photoshop/Illustrator: proof setup
- Colblinder
- Nocoffee extension for chrome

### Links
- What is and isn't a link?
- Early web: blue=link, purple=visited, easy to tell what's what.
- Now people use CSS for everything. Color, underline, border, hover state, bg image, etc
- Does it look like a link (based on your knowledge of the web)?
- Screen reader users can hear it's a link
- Difference b/w link and body text?
- Can you tell where it goes?
- Should skip links be treated differently?
- Deque: thicker left border on content section to indicate focus, only for skip links

### Visual Focus
- Focus indicator is visual marker that calls attn to element on web page which keyboard has in focus.
- Most browsers: medium/light blue outline :focus
- DO NOT DO outline=0
- Must be visible for all interactive elements, different from surroundings, can be same as hover

### Visual Characteristics
- Don't direct people to i.e. "click the big green button"
- Better to use text, descriptive name, type of element
- Pattern libraries are your friend!!
- Consistent link design, visible focus, use of color, language, etc.
- Good examples of pattern libraries: ebay mind, salesforce lightning design, us web design standards, style tiles
- Pattern libraries rarely work for everyone out of the box
