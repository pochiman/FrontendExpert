# Purchase Form

You're given an HTML file with the markup for a purchase form, similar to
the actual purchase form on AlgoExpert.
  
Using only CSS, style the purchase form to have the following
characteristics:

  • The `#wrapper` should have 12px of padding, a border radius of
    12px, and a background color of #e0e0e0.

  • The ordered list should be styled as a stepper component:

    • This stepper should be horizontally centered with no padding, but it
      should maintain its default vertical margin.

    • Each list item in the stepper should have its corresponding item number above 
      its text content, and this number should be inside of a circle with a white 
      background color, a width of 30px, 8px of bottom margin, a font-size of 24px, 
      and a solid, black, 4px border. The number inside of the circle should be 
      horizontally and vertically centered, and the circle should be horizontally
      centered above the text content.

    • The number-circle for the list item with the `selected` class should have white 
      text and a background color of #279600.

    • Between each pair of adjacent number-circles should be a 4px-tall black 
      horizontal line. These divider lines should be vertically centered with
      respect to the number-circles, and they should sit exactly between the
      circles, just touching their edges.
  
  • The unordered list should be styled as follows:

    • The unordered list should maintain its default margin, but it should
      have no padding.

    • Each list item in the unordered list represents a single product
      offering and should have 12px of padding, 12px of vertical margin, a
      height of 40px, a border-radius of 8px, bold font, and a white background color.

    • The labels should have 4px of left margin and a text color based on
      the list-item class, following this mapping:

      • .blue-product: #626ee3

      • .red-product: #890023

      • .orange-product: #f37f1b

      • .green-product: #11967e

    • Each product-offering list item should also have a solid, 5px left
      border of the same color as its text.
        
  • The "Continue" button should be aligned to the right side of the `#wrapper`, 
    with 12px of padding, a font size of 16px, a border radius of 8px, a background 
    color of #02203c and a white text color.

For convenience, the starting code includes variables with most of the specified 
pixel values and colors.

Your submission will be assessed based on how similar your `Browser Output` is to 
the `Expected Output`; it should be nearly identical.

# Hints

# [Hint_1]

  This problem has a lot of smaller components. Try taking those one at a time,
  starting with whichever section feels simplest to you.

# [Hint_2]

  The `list-style-type: none;` declaration can be used to remove
  the default bullets and numbers from list items.

# [Hint_3]

  The `:before` and `:after` pseudo elements can be
  used to add extra children to an element. Can you use these to create the
  circles and divider lines?

# [Hint_4]

  To treat the elements inserted by `:before` and `:after`
  as "normal" elements, they need to be given content and a display property.
  Oftentimes `content: "";` and `display: block;` will be
  used here, but of course this can be changed to fit the needs of the problem.

# [Hint_5]

  The `counter-increment: {name};` declaration can be used to create
  a counter and increment it with each element selected by a ruleset. This counter
  can then be used as content with `content: counter({name})`, replacing `{name}` 
  with any name.

# [Hint_6]

  If flex items all have a `flex-basis` of 100% and default
  grow/shrink values, they will stretch to fill the space of the container evenly.
