# Rainbow Circles

You're given an HTML file with three nested divs, each with a unique ID.

Using only CSS, style the HTML to have the appearance of six concentric
colored circles.

From outside to inside, the circles should have the following characteristics:

  • 300px by 300px, #ff0000
  • 250px by 250px, #ffa500
  • 200px by 200px, #ffff00
  • 150px by 150px, #008000
  • 100px by 100px, #0000ff
  • 50px by 50px, #800080

While there are a variety of ways to achieve this desired output, for the purpose 
of this problem all colors should be achieved using background colors and/or box 
model properties.

Your submission will be assessed based on how similar your `Browser Output` is to 
the `Expected Output`; it should be nearly identical.

# Hints

# [Hint_1]
Consider the different box-model properties that can be helpful to solve this problem. Which properties allow for adding colors with CSS?

# [Hint_2]
Since there are 6 colors and only 3 divs, some of the colors will need to come from borders.

# [Hint_3]
Start from the innermost circle, alternating between using `background-color` and 
`border` to create the colors.

# [Hint_4]
A `border-radius` of `50%` can be used to create a perfect circle. 
