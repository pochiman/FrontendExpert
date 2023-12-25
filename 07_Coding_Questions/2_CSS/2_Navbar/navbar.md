# Navbar

You're given an HTML file for the top navigation bar of a website. The navigation 
bar consists of two unordered lists, containing three and two list items, respectively.

Style this navigation bar as follows:

  • The navigation bar should be a horizontal bar, spanning the entire width
    of its parent; all of its list items should be displayed in a single row.

  • The first unordered list (containing Product, Testimonials, and Pricing)
    should appear on the far left side of the navigation bar. The second
    unordered list (containing Team and Contact Us) should appear on the far
    right side of the navigation bar.

  • The navigation bar should have a background color of #6e072d and a white font color.

  • The unordered lists should have no margin or padding. However, the
    individual list items should have vertical padding equal to their font
    size and horizontal padding equal to their font size multiplied by 1.5;
    their font size should be 18px.

  • Hovering over a list item should change its background color to #b90e4d 
    and the mouse cursor to a pointer.
  
  • There should be a solid, white, 2px border separating the list items. However this border    
    shouldn't appear on the right side of Pricing or on the left side of Team.

  • The individual list items shouldn't have bullet points next to them.

Your submission will be assessed based on how similar your `Browser Output` is to the 
`Expected Output`; it should be nearly identical.

# Hints

# [Hint_1]
Use the `list-style-type` property to remove the default bullet points on list items.

# [Hint_2]
Since this layout is 1 dimensional (a single row), we recommend solving this problem with Flexbox.

# [Hint_3]
A combination of the `:not` and `:last-of-type` pseudo classes can be used to place the borders on the correct elements.
