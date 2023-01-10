# Study Guide

## Resources

- ✅ **Study Guide: Flexbox**: https://codepen.io/squalrus/pen/rNrNKXd?editors=1100
- ✅**Study Guide: CSS Grid**: https://codepen.io/squalrus/pen/MWBwJap?editors=1100
- ✅ https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- ✅ https://css-tricks.com/snippets/css/complete-guide-grid/
- ✅ https://learn.microsoft.com/en-us/training/paths/accessibility-fundamentals/
- ✅ https://learn.microsoft.com/en-us/training/paths/react/
- ✅ Convert https://www.halcyonvestment.com/
- ✅ Create https://carrainbow.quest/
- ✅ Read https://12daysofweb.dev/

## Flexbox ✅

### `display`

Set to `flex` for the parent to control the layout and spacing of the child items.

### `flex-direction`

Sets the direction the items flow along the main axis. `row` is default, `row-reverse`, `column`, and `column-reverse`.

### `flex-wrap`

Sets whether the child items will wrap. `nowrap` is default, `wrap` and `wrap-reverse`. Defines the cross axis.

### `flex-flow`

Shorthand for `flex-direction` + `flex-wrap`. Shorthand that describes both the main and cross axes.

### `justify-content`

Sets how the child items are spaced along the main axis. `flex-start` is the default, `flex-end`, `center`, `space-between`, `space-around`, and `space-evenly`.

### `align-items`

Sets how the child items are spaced vertically along the cross axis. `flex-start` is the default, `flex-end`, `center`, `stretch`, and `baseline`.

### `align-content`

Sets the "rows" of child items positioning within the parent. `flex-start` is default, `flex-end`, `center`, `stretch`, `space-between`, and `space-around`.

### `gap`

Sets the spacing between child elements.

### `order`

Item property that assigns the visual order of the item. Defaults to the source order and all share `0` if not specified.

### `flex-grow`

Item property that grows the space the item occupies proportionately to the others.

### `flex-shrink`

Item property that shrinks the space the item occupies proportionately to the others.

### `flex-basis`

Item property that sets the default size of an element before the remaining space is distributed.

### `flex`

Item property shorthand for `flex-grow` + `flex-shrink` + `flex-basis`.

### `align-self`

Item property that overrides the alignment of the item, same values as `align-items`.

## CSS Grid ✅

### `display`

Set to `grid` to create a grid layout, or to `inline-grid` to create an inline grid layout.

### `grid-template-columns`

Establishes the column layout based on the numbers/values provided.

### `grid-template-rows`

Establishes the row layout based on the numbers/values provided.

### `grid-template-areas`

Leverages `grid-area` to define a grid template.

### `grid-template`

Shorthand for `grid-template-rows` + `grid-template-columns` + `grid-template-areas`. Values can be `none`, `grid-template-rows / grid-template-columns`.

### `column-gap`

Sets the size of the vertical grid lines (gutters).

### `row-gap`

Sets the size of the horizontal grid lines (gutters).

### `gap`

Shorthand for `row-gap` and `column-gap`.

### `justify-items`

Align the grid items along the horizontal axis. `start`, `end`, `center`, and `stretch`.

### `align-items`

Align the grid items along the vertical axis. `start`, `end`, `center`, `stretch`, and `baseline`.

### `place-items`

Shorthand for `justify-items` and `align-items`. `align-items / justify-items`.

### `justify-content`

Aligns the grid items within the grid container on the horizontal (row) axis. `start`, `end`, `center`, `stretch`, `space-around`, `space-beteen`, and `space-evenly`.

### `align-content`

Aligns the grid items within the grid container on the vertical (column) axis. `start`, `end`, `center`, `stretch`, `space-around`, `space-beteen`, and `space-evenly`.

### `place-content`

Shorthand for `justify-content` and `align-content`. `align-content / justify-content`.

### `grid-auto-columns`

Defines the implicit column size for an element placed outside the defined grid.

### `grid-auto-rows`

Defines the implicit row size for an element placed outside of the defined grid.

### `grid-auto-flow`

Defines how to organize items that aren't explicitly placed on the grid. `row`, `columns`, and `dense`.

### `grid`

Shorthand for setting `grid-template-rows`, `grid-template-columns`, `grid-template-areas`, `grid-auto-rows`, `grid-auto-columns`, and `grid-auto-flow`.

### `grid-column-start`

Item property to set the column starting position.

### `grid-column-end`

Item property to set the column ending position.

### `grid-row-start`

Item property to set the row position start.

### `grid-row-end`

Item property to set the row position end.

### `grid-column`

Shorthand for `grid-column-start / grid-column-end`.

### `grid-row`

Shorthand for `grid-row-start / grid-row-end`.

### `grid-area`

Gives a name to be referenced by the grid container template.

### `justify-self`

Item property that sets the horizontal alignment for the item. `start`, `end`, `center`, and `stretch`.

### `align-self`

Item property that sets the horizontal alignment for the item. `start`, `end`, `center`, and `stretch`.

### `place-self`

Shorthand for `justify-self` and `align-self`.

## Accessibility ✅

## Responsive Design

## DevTools

## CSS

- style a <progress> bar
- ensure icons are visible in forced-colors mode
- make a card layout friendly to both left-to-write and right-to-left writing modes
- handle for round avatars of different sizes and different transparencies
- develop a grid of logos that appears uniform in size even with different uploaded logo sizes and transparencies
- change the color of list bullets/numbers
- define accessible focus styles
- create and apply a color scheme that adapts for dark and light modes
- modify the size, color, and position of text underlines
- embellish a headline using pseudo elements
- crop an image into an irregular shape and apply a modified color effect
- "cut out" an icon from the element it is attached to (the page background is visible around it)
- ensure light text over a light image (like in a page header) is legible
- swap a navigation bar logo from left to centered position depending on viewport size
- apply an animation that adheres to prefers-reduced-motion
- smooth scroll to an anchor and adjust the anchor's scroll position below the top of the viewport
- adapt font sizes, padding, and margin without media queries
- add an icon to links that are external to your URL, or that lead to a downloadable resource (ex. pdf, doc)
- re-arrange a grid layout based on container size
- write styles for a blog/news article that considers spacing relationships between different content element types (ex. h2 followed by a p, - blockquotes), hierarchy relationships (feature image vs. in-content image vs. figure), and embellishments (ex. hr, strong, code)
- give a label a style when the input that follows it is invalid
- change the color of radio buttons and checkboxes, adapting to light or dark modes

## JS / React
