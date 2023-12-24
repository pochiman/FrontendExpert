# 2 - Essential HTML Tags

More common than the common housefly, these HTML tags are virtually ubiquitous and can be found populating nearly every webpage.

# Key Terms

# <p> </>
  The paragraph tag, usually used for blocks of text (although they can
  contain other elements that are part of the paragraph, such as images).

  For example:

  <p>Hello World!</p>

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p

# Heading Tags </>
  HTML tags represented by <h1> through <h6>. <h1> is the top level heading, while 
  <h2> is a secondary subheading and so on. For example:

  <h1>Main Heading</h1>
  <h2>Secondary Heading</h2>

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements

# <img> </>
  The image tag. This is an empty tag, and it should always include two
  primary attributes: 

  • `src`: The path to the image, either relative or absolute.
  • `alt`: Alternative text to be used with screen readers or any time the image cannot be displayed.
  
  <img src="img/dog.png" alt="dog" />

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img

# <ul> </>
  The unordered list tag, used for a list where the order does not matter.
  By default, most browsers will show this as a bulleted list.

  The unordered list should contain any number of <li> tags. For example:

  <ul>
      <li>AlgoExpert</li>  
      <li>SystemsExpert</li>  
      <li>MLExpert</li>  
      <li>FrontendExpert</li>
  </ul>

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul

# <ol> </>
  The ordered list tag, used for a list where the order matters.
  By default, most browsers will show this as a numbered list.

  The ordered list should contain any number of <li> tags. For example:

  <ol>
      <li>Step 1</li>
      <li>Step 2</li>
      <li>Step 3</li>
  </ol>  

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol

# <li> </>
  The list item tag, used for individual elements in both unordered and ordered lists.
  
  List items can also contain other lists to create nested lists. For example:

  <ol>
      <li>Step 1</li>
      <li>
        Step 2:
        <ol>
          <li>Substep 1:</li>
          <li>Substep 2:</li>
        </ol>
      </li>
      <li>Step 3</li>    
  </ol>

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li

# <pre> </>
  The preformatted text tag. This tag preserves whitespace, which can be useful
  when indentation and newlines need to be preserved. For example: 

<pre>
    *
   ***
  *****
 *******
*********
   | |
</pre>

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/pre

# <br> </>

  The line break tag. This is an empty tag used to create a line break in text,
  such as for the introduction of an email or new lines in a poem. However, this
  tag should not be used just for spacing out elements as that can be accomplished
  with CSS. For example:

  <p>
      Dear User, <br />
      We hope you are enjoying FrontendExpert!
  </p>

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/br

# <hr> </>      

  The horizontal rule tag. This is an empty tag used to create a thematic break between
  content, drawn as a horizontal line by default. For example:

  <p>Part 1</p>
  <hr />
  <p>Part 2</p>

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/hr

# <a> </>
  The anchor tag, used for linking to other pages. This tag should include an `href` 
  attribute with the path to the page being linked (absolute or relative). For example:

  <a href="https://algoexpert.io">AlgoExpert</a>

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a

# <em> </>

  The emphasis tag, usually rendered as italics by default in the browser.
  For example:
  
  <p>I <em>need</em> to study!</p>

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em

# <strong> </>
  The strong tag, usually rendered as bold by default in the browser.
  For example:

  <p><strong>Note:</strong> This is important!</p>

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong
