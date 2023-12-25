# Blog Post

You've been provided with a blog post as raw text, and you need to convert
this post into a properly marked-up HTML file.
  
The post should have a primary heading of `Introducing AlgoCoin` with a tagline of
`The future of decentralized meme currency is here.`.

The post should be treated as an article with two sections, titled `What is AlgoCoin` 
and `Where Do I Start?`, respectively. Each section should have a paragraph of text 
(the text directly below the respective section title in the starting code), and the
sections should be divided by a horizontal rule.

In the first section, the text `proof-of-inverted-binary-tree consensus algorithm` 
should be marked up as strong text, and `Web 4.0` should be emphasized. In the second 
section, the word `AlgoExpert` should be a link to https://algoexpert.io, and it 
should open in a new tab.

Finally, the post should have a footer at the bottom with the text 
`Copyright 3022 AlgoCoin. All rights reserved.`.

Your HTML code should use proper semantic markup. However, you only need to write 
the HTML that would go inside of a document's <body> tag; no need to worry about the 
<head> tag, the <html> tag, or the <!DOCTYPE> declaration.

# Hints

# [Hint_1]
These are some of the most common semantic grouping tags — <header>, <article>, 
<section>, <main>, <footer>, <aside>. Which seem most relevant here?

# [Hint_2]
Since a blog post is a standalone piece of content, the most appropriate semantic 
grouping tag to wrap it is the `article`. Then inside of the blog post, `header`, 
`section` and `footer` can be used for the various sections.

# [Hint_3]
The `target="_blank"` attribute can be added to anchor tags to open links in new tabs.
