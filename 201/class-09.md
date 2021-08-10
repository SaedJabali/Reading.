# Forms

An HTML *form* is used to **collect** user input. The user input is most often sent to a server for *processing*.

### Form Controls

**ADDING TEXT**

* Text input *(single-line)*
Used for a single line of text such
as email addresses and names.

* Password input
Like a single line text box but it
masks the characters entered.

* Text area (multi-line)
For longer areas of text, such as
messages and comments.

**Making Choices**

* Radio buttons
For use when a user must select
one of a number of options.

* Checkboxes
When a user can select and
unselect one or more options.

* Drop-down boxes
When a user must pick one of a
number of options from a list.

**Submitting Forms**

* Submit buttons
To submit data from your form
to another web page.

* Image buttons
Similar to submit buttons but
they allow you to use an image.

**Uploading Files**

* File upload
Allows users to upload files
(e.g. images) to a website.

![Forms](https://opentechschool.github.io/python-flask/core/images/form-input.png)    ![Forms](https://lh3.googleusercontent.com/proxy/JxHTXTsnKYyZDIIJRUTDiV8tpknLkjaRfFfTKQ_YI89bx-gcLNROJEXIudLHvvY_qnmckiKJXHpmcdaD7vXoR-tlOAosix3yxOMnuS6_y6xL5Zj1tL1mt-4Ty4geiw4bNohmPdut0Rc39Ko6)


### Form Structure

**< form>**
Form controls live inside a
< form> element. This element
should always carry the action
attribute and will usually have a
method and id attribute too.

**action**
Every < form> element requires
an action attribute. Its value
is the URL for the page on the
server that will receive the
information in the form when it
is submitted.

**method**
Forms can be sent using one of
two methods: get or post.


# CSS styling

### list-style

**Type**

*Unordered Lists*

For an unordered list you can use
the following values:

* none
* disc
* circle
* square

*Ordered Lists*

For an ordered (numbered) list
you can use the following values:

* decimal

 1 2 3

* decimal-leading-zero

 01 02 03

* lower-alpha

a b c

* upper-alpha

A B C

* lower-roman

i. ii. iii.

* upper-roman

I II III

**Image**

The list-style-image property *replaces* the list-item marker with an image.

**Position**

The list-style-position property *specifies* the position of the list-item markers (bullet points).

**List Shorthand**

The list-style CSS shorthand property *allows* you to set all the list style properties at once.

### Table Properties

* width 

to set the width of the table

* padding

to set the space between the border of each table cell and its content.

* text-transform

to convert the content of the table headers to uppercase.

* letter-spacing, font-size

to add additional styling to the content of the table headers.

* border-top, border-bottom

to set borders above and below the table headers.

* text-align

to align the writing to the left of some table cells and to the right of the others.

* background-color

to change the background color of the alternating table rows.

* :hover 

to highlight a table row when a user's mouse goes over it.

# JavaScript Events

HTML events are *things* that happen to HTML elements.

When JavaScript is used in HTML pages, JavaScript can *react* on these events.

**What can JavaScript Do?**

1. Event handlers can be used to handle and verify user input, user actions, and browser actions:

* Things that should be done every time a page loads.
* Things that should be done when the page is closed.
* Action that should be performed when a user clicks a button.
* Content that should be verified when a user inputs data.

2. Many different methods can be used to let JavaScript work with events:

* HTML event attributes can execute JavaScript code directly.
* HTML event attributes can call JavaScript functions.
* You can assign your own event handler functions to HTML elements.
* You can prevent events from being sent or being handled.