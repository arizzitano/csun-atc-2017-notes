# Inclusive Data Visualizations: Charts, Graphs, and Dashboards

Jennifer Gauvreau, Michael Bennett, Elizabeth Whitmer; CGI - 3/1/2017

https://drive.google.com/file/d/0B5PHZFnvjwEqZlZkT2oxODZkWTg/view

## Planning for data vis

### Select appropriate type
- What's the data?
- What are you trying to communicate?
- Using the mst appropriate chart type is a key first step for determining usability
- may be an iterative process

### a11y Guidance
- Information and communication technology (ICT)
- Select most accessible option that _also meets your business need_
- Fully accessible first, then next best thing
- Provide additional redundancies where tech falls short
- Check Voluntary Product Assessment Template - not required, but a good idea  to have
- Request demo or trial

## Improving usability

### Best practices
- Certain chart types have their own strengths and weaknesses
- What are you showing? Comparison, distribution, trend, etc
- Order values when comparing by timestamp or value
- Always include axis labels!!!
- Use readable labels - example: angle at 45 degrees
- Does the axis need to start at 0?
- Accessibility and usability have a significant overlap

## Accessibility concerns
- Data visualization is inherently not 508 compliant
- Visual nature doesn't mean charts can't be accessible
- Entire experience needs to be keyboard operable
- Is the UI accessible to motor impaired users?
- Does it rely on color alone?
- Can the UI be customized by low-vision users?

### Blind Users
- Rely on other senses to obtain information
- Hearing and touch (SR and braille display hardware)
- Can braille hardware show a graph? or just text?

#### How to improve?
- Define Meaningful Text Equivalents
- Data set: each data point is important
- Easiest equivalent is adjacent data table
- Needs to be comparable in scope and detail
- Can also provide downloadable export
- For a trend, individual data points are not important. Trend can be described instead
- Allow user to toggle between chart and data view - saveable preference
- Data table is not enough! Still make every effort to make chart as accessible as possible

### Motor impaired users
- Difficulty performing tasks that utilize smaller hand muscles
- Hand/finger strength, hand/eye coordination
- Non mouse users
- Everything must be keyboard accessible
- Don't rely on hover! (this also applies to mobile)

#### How to improve?
- Instead of hover text, include text in x axis labels?
- Include data table beneath chart with all data values
- (Not mentioned, but... could you make descriptions keyboard navigable?)

### Low vision users
- Vision impaired but not blind
- Zoom in on content to make larger
- Scales text size
- Screen magnification software

#### How to improve?
- Designs to reflow content for easy readability (RWD)
- Text needs sufficient contrast
- Scalable text and containers
- Proximity of metadata
- Don't display unique information on hover
- Text resizing can break labels and other text
- Watch out for overlaps! Recalculate tick positions (?)

### Color Blind Users
- Protanopia (red)
- Deuteranopia (green)
- Tritanopia (blue)

#### How to improve?
- Avoid using only color to convey meaning
- Think of black and white printers also
- Use tools to help analyze
- Can still use color meaningfully but a redundancy must also exist
- Text labels
- Distinguishable textures or patterns
- Monochromatic color schemes are great but still need text redundancy
- http://colorbrewer2.org for color palettes
