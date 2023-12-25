# Sign-Up Form

Implement a sign-up form in HTML with the following six input fields, each
with an appropriate label:

  1. `Username`, a required text input field
  2. `Password`, a required password input field
  3. `Email`, a required email input field
  4. `Phone Number`, an optional telephone input field
  5. `Date of Birth`, an optional date-picker input field
  6. `I agree to the TOS`, a required checkbox input field

There should also be a `Sign Up` button at the bottom of the form. When
clicked on (and if all required fields have been filled), the button should
submit the form using default browser behavior.

Note that submitting the form in your `Browser Output` or in the `Expected Output` 
will result in a broken page being displayed; this is normal behavior, since these 
outputs are rendered in iframes.

You only need to write the HTML that would go inside of a document's <body> tag; 
no need to worry about the `<head>` tag, the `<html>` tag, or the `<!DOCTYPE>` 
declaration.

# Hints

# [Hint_1]
All of these inputs can use the `input` tag, with different `type`  attributes to 
determine the input type.

# [Hint_2]   
A `required` boolean attribute can be used for required form inputs.

# [Hint_3] 
A `button` tag or an `input` tag with `type="submit"` will automatically submit 
their parent forms.  
  