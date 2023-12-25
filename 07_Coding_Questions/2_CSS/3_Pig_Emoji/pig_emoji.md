# Pig Emoji

You're given an HTML file with the markup for a pig emoji.

Using only CSS, style the HTML to have the appearance of a pig emoji with the following characteristics:

  • The head should be a perfect circle with a width and height of 200px, a top margin 
    of 20px, and a background color of #ffc0cb.

  • The ears should be perfect circles, each with a width and height of 50px.
    They should be positioned behind the head and 10px inwards from the left
    and right edges of the head, respectively. They should also protrude above
    the head by 10px, and they should have the same background color as the
    head.
      
  • The eyes should be perfect circles, each with a width and height of 50px.
    They should be positioned 40px from the top of the head, and 30px from the
    left and right edges of the head, respectively. They should have a
    background color of white.

  • Each eye contains a pupil, which should be half the size of the eye with
    a border-radius of 50%. The pupils should be centered in their respective
    eye, and they should have a background color of black.

  • The nose should have a width of 100px and a height of 60px. It should be
    horizontally centered and positioned 30px from the bottom of the head.
    Additionally, it should have a border radius of 35% and a background color
    of #f57187.

  • The nose contains two nostrils, each with a height that's 50% of the
    height of the nose and a width that's 25% of the width of the nose. The
    nostrils should be vertically centered with horizontal space around them
    (twice as much space between them as from the edge of the nose).
    Additionally, they should have a border radius of 50% and a background
    color of black.
        
  • The head and both ears should each have a solid, black, 5px border, while the 
    nose and both eyes should each have a solid black, 2px border.
      
Your submission will be assessed based on how similar your `Browser Output` is to 
the `Expected Output`; it should be nearly identical.

# Hints

# [Hint_1]

  Try breaking the problem into small pieces and thinking about the individual
  shapes needed. Starting with the head and then moving down the DOM tree
  is likely the easiest approach.

# [Hint_2]

  When an element is set to `position: absolute, it will be positioned
  relative to its nearest positioned ancestor (e.g. a parent with `position: relative`).
  Can you use this to position the various elements based on the position of the head?

# [Hint_3]

  A `border-radius` of `50%` will create a perfect circle
  when an element has the same width and height.

# [Hint_4]

  The `:first-child` and `:nth-child()` pseudo-classes can be
  used to select specific children numbers. For example `.foo:first-child`
  will select elements with the class `foo` that are the first child
  of their parent.

# [Hint_5]
  
  Centering an element with position absolute can be tricky, but the easiest way
  will be to give it `left: 50%`, which moves the left edge of the
  element 50% of the way over. This can then be combined with
  `transform: translateX(-50%)` to account for the width of the element itself.
