# Spaghetti Recipe

You've been provided with a recipe for spaghetti as raw text, and you need 
to convert this recipe into a properly marked-up HTML file.

The recipe should have a primary heading of "Spaghetti Recipe", and it
should be divided into two sections, the ingredients and the instructions, 
with the headings "Ingredients" and "Instructions", respectively.

The ingredients are an unordered list with the following contents:  

  • Spaghetti
  • Marinara Sauce
  • Salt
  • Water

The instructions are an ordered list with the following contents:

  1. Bring water to a boil.
  2. Add spaghetti to boiling water.
    1. Add salt to taste.
    2. Cook for 10 minutes, stirring occasionally.
  3. Add marinara sauce to a pan, bringing to a simmer.
  4. Mix cooked spaghetti with marinara sauce.
  5. Enjoy!

Note that "Add salt to taste." and "Cook for 10 minutes, stirring
occasionally." are in a sub-ordered list under the second instruction.
  
Your HTML code should use proper semantic markup. However, you only need to
write the HTML that would go inside of a document's <body> tag; no need to 
worry about the <head> tag, the <html> tag, or the <!DOCTYPE> declaration.

# Hints

# [Hint_1]
There are two primary types of lists in HTML — <ul> and <ol> for unordered and 
ordered lists respectively.

# [Hint_2]
The only permitted children of lists are <li> elements. This means that even 
nested lists must be inside of a list item, usually along with the text describing 
that nested list.

# [Hint_3]    
These are some of the most common semantic grouping tags — <header>, <article>, 
<section>, <main>, <footer>, <aside>. Which seem most relevant here?
