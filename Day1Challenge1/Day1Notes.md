# Percentages vs Fixed Widths

 * HTML is responsive by default
 * Body is normally the viewport

# Percentages on the child

 * Overflow is a feature - CSS tries to avoid losing/hiding information by default
 * Percent 'units' are always a percent of the parent's measurement
   So if the parent is `200px` wide, and we set the child to have `width: 50%`, the child will be rendered `100px` wide

# Why it's a good idea to avoid heights

They cause problems such as wrapped text overflowing off the bottom

Again, any non-responsiveness is caused by rules we added

Other options for setting height:
 * set a padding
 * what about min-height?

`em` are based on the font size of the element

# Challenge 1 Goals:

1. Limit text to midpoint
2. Prevent text from overflowing on narrow screens