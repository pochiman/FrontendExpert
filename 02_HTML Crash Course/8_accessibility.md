# 8 - Accessibility

Accessible web development leads to a better user experience for all and, ultimately, to a more inclusive internet. In that spirit, let us look at some of the best practices to follow and some markup elements to include when designing with accessibility in mind.

# Key Terms

# [Accessibility]

  Building applications usable by as many people as possible.
  Oftentimes this means utilizing semantic HTML and ensuring the
  application works properly with various assistive technologies.

# [Accessibility_Tree]

  A tree representation of the page focusing on information specific to
  accessibility. Each node in this tree contains information such as the
  `role`, `state`, `name` and `description`.

  The accessibility tree is created from the DOM tree and kept in sync with
  it. Assistive technologies such as screen readers interact with the accessibility
  tree rather than directly with the DOM.

  Learn more: https://developer.mozilla.org/en-US/docs/Glossary/Accessibility_tree

# [WAI-ARIA]

  The "Web Accessibility Initiative - Accessible Rich Internet Applications" specification
  for accessible HTML created by the World Wide Web Consortium (W3C). Oftentimes
  referred to as just ARIA, this contains a set of HTML attributes that can be
  added to provide extra information to the `accessibility tree`.
  
  ARIA attributes are usually grouped into three main categories:

  • `Roles`: What the element is doing, used to define the purpose of the element.
     These can be broken down into a few main subgroups:

      • `Landmark`: Major content areas, navigational landmarks.
      • `Structure`: Document structure information.
      • `Widget`: Interactive elements.
      • `Window`: Sub-windows in the browser.
      • `Live Region`: Regions with dynamically changing content.

  • `Properties`: Extra meaning and characteristics of the element, such as labels.
  • `States`: Current state of the element, such as if it is disabled.

  Learn more: https://developer.mozilla.org/en-US/docs/Learn/Accessibility/WAI-ARIA_basics
