# 2 - HTML Basics

In order to build a solid foundation, we need to start with some basics. Let's begin!

# Key Terms

# [HTML]

  HyperText Markup Language is the primary language of the web, containing
  the content and structure of a website.

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML

# [Tag]

  The primary method of marking up content using HTML. Tags use the syntax
  <tagname>content</tagname>.

  For example, paragraphs use the `p` tag, so we could create the paragraph
  "Hello World" with <p>Hello World</p>.

  The left side tag, such as <p>, is referred to as the `opening tag`. The right side tag, such as </p> is referred to as the `closing tag`. Everything inside of the tags is the `content`, which
  will actually be rendered on the page. The combination of the opening tag, content
  and closing tag are referred to as a complete `element`.

  Some tags don't have any content, so we call these `empty tags` or `self-closing` tags. These either use the opening tag syntax or <tagname />.

  For example, horizontal rules use the `hr` tag, so we could create a
  horizontal rule with either `<hr>` or `<hr />`.

# [Attribute]

  Extra information provided to HTML elements, similar to function parameters.
  
  Attributes use the syntax <tagname attribute="value">content</tagname>. The
  attribute name will always come after the tag name, with a space in between
  them. The quoted value will then be separated from the attribute name by an
  equals sign. For example, we can create an input of type "checkbox" with
  <input type="checkbox" />.

  A small number of attributes are booleans rather than strings. Any value for
  a boolean attribute will be treated as `true`, so all of the following
  checkboxes would be `disabled`.

  <input type="checkbox" disabled="disabled" />
  <input type="checkbox" disabled="true" />
  <input type="checkbox" disabled />

  <!--
    This is still disabled, since the attribute is set.
    Of course we don't recommend this though as it is quite confusing to read.
  -->
  <input type="checkbox" disabled="true" />

# <!DOCTYPE html>
  The required first line of every HTML file for telling the browser what version
  of html to use. A doctype of `html` will use the modern HTML5 standard.
  While a page will usually render properly without a doctype declaration, they should
  still always be included as some older browsers will not render pages following
  the modern specification without it (this is sometimes called "quirks" mode).

# <head> </>
  The tag containing metadata about the HTML document
  (i.e. anything that isn't displayed on the page). The <head> 
  of the HTML file should be the first tag within the <html> tag.

  The <title> is the only required tag within the <head>. This tag gives the page a title, which is used
  for the name of the tab in most browsers, and it gets used for search
  results in many search engines.

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head

# <body> </>
  The tag containing the content of the webpage.
  The <body> of the HTML file should be the second
  tag within the <html> tag, just below the <head>.

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body
