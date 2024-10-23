# CSS - Cascading Stylesheets (Style)

## 3 ways to style with CSS

- Inline -> putting the style on the element itself
  - not recommended (last resort)
  - old way
  - only used if you cannot use the other two ways

- Internal -> using style tags inside the HTML file
  - Selector - what elements do you want to style?
  - Rule - how do you want to style those elements?
    - key - style application
    - value - what you want the style application to be
  - styles one page
  - not recommended

- External -> link in the head
  - Selector - what elements do you want to style?
  - Rule - how do you want to style the elements?
  - can be used on multiple HTML pages

- Specificity - more specific a selector is, the more priority it is given
  - inline is the most specific
  - id
  - classes
  - elements is the least specific
  - order only matters when the rules have the same specificity

- Box Model - everything is a box
  - content - everything inside
  - padding - space between the border and content
  - border - the edge of what is shown for the element
  - margin - space between elements

- Selectors
  - id
  - class
  - elements

- Optional
  - Size units
    - px
    - percentages
    - pt
    - rem
    - em
  - Display: Block vs Inline vs Inline-Block
  - Tables 