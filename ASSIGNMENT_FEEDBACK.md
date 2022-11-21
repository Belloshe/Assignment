Hi Bella!

Nice work! I know you missed a fair bit of the early classes and this is a pretty good job.

The main issue is the contact form - see the notes below. It should be a relative quick fix.

The other main isse is the separate CSS detailed below. I suggest using "style.css" as a general file with thee header, naviggation and footer styling, them delete all the duplicate styles from the other css files.

You have most things covered, but unfortunately the contact form is a required element for the assignment.

Could you please make the suggested changes, then push the changes to github and let me know so I can take another look?

*************************************

CRITERIA FOR GRADING

*************************************

GODKÄNT:
-------------------------------------

3 separate pages: ✅

A header with a page title on every page: ✅

A navigational menu every page with links to the other pages: ✅

Contact form:
    Email: ✅
    Message: ✅
    Required: ❌
    Mail to: ❌
    On clicking the Submit button the form should open up my default email client and fill the email with the inputs. Your form is missing an "action", and the inputs aren't being added - check this link for a guide on how to fix it: https://www.w3schools.com/html/tryit.asp?filename=tryhtml_form_mail

    Also the inputs should be "required" an if you try to submit you should see a message - add the word "required" as an attribute to the input.

RWD:
    Desktop: ✅
    Mobile: ✅

External CSS: ✅

-------------------------------------

VÄLGODKÄNT:
-------------------------------------

Current page indication in the menu: ❌
  Add a class to the relevent menu item on each page.

Responsive Image: ✅
 Excellent.

RWD:
  Media Query: ✅
  Flex/Grid: ✅

Separate CSS: ❌ ✅
  It's great that you have separate CSS files, but a lot of the styling is the same in every file. 
  
  The idea behind separate files is that you have common styling - eg the header, or footer, or navigtion inside a "general" or "header" an "footer" file, then include that file on every page in the <head> section. You can import as many CSS files as you like in an html file.

  Semantic: ✅

Semantic Element naming: ✅
  A few of things like <div class="h"> in home.html but very well done.

Code Style:
  HTML: ✅
    Ddirectory names insidde projects should always be lower case - html instead of HTML
  CSS: ✅ ❌
    Lots of empty lines - in CSS have one and only one empty line bwteem selectors and NO empty lines inside the { } blocks.