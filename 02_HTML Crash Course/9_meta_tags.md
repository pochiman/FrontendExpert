# 9 - Meta Tags

Metadata is special information about your webpage that can be used by search engines and web browsers to do cool stuff. But where do you define this data?

# Key Terms

# <meta> </>
  An HTML tag for providing extra metadata about a webpage. Most meta tags will 
  use a `name` and `content` pair for the type of metadata and its value.

  These are some of the more common metadata tags:

  <!-- Sets the character encoding to utf-8 -->
  <meta charset="utf-8" />

  <!-- Allows for custom responsive CSS, rather than the default scaling behavior of small devices -->
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <!-- Sets the page author -->
  <meta name="author" content="Conner Ardman" />

  <!-- Sets the page description -->
  <meta name="description" content="Ace the frontend interviews!" />

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta

# Favicon
  Also called a `favorite icon`, the icon for a webpage. Browsers usually
  show these in a variety of places, such as next to the tab name. Favicons 
  are created using the <link> tag. For example:

  <link rel="icon" href="favicon.png" />

# <base> </>
  A tag for setting the document base URL, which will be used for all relative links
  on the page. For example:
    
  <!-- This line goes in the <head> -->
  <base href="https://algoexpert.io" />

  <!-- This would go to https://algoexpert.io/frontend -->
  <a href="/frontend">FrontendExpert</a>

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/base
