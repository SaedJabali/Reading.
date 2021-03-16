# Links

Links are the *defining feature* of the web because they allow you to move from one web page to another — enabling the very idea of *browsing* or *surfing*.

### Types of Links

* Links from one website to another.
* Links from one page to another on the same website.
* Links from one part of a web page to another part of the same page.
* Links that open in a new browser window.
* Links that start up your email program and address a new email to someone.

**Links** are created using the *< a>* element. Users can click on anything between the opening *< a>* tag and the closing *< /a>* tag. You specify which page you want to link to using the href attribute.

The text *between* the opening < a> tag and closing < /a> tag
is known as link text. Where possible, the link text should
explain where visitors will be taken if they click on it (rather
than just saying "click here").

To *write* good link text, you can think of **words** people might use when *searching* for the
page that you are *linking* to.
(For example, rather than write "places to stay" you could use something more specific such as "hotels in New York.").

**< a>**
Links are created using the < a> element which has an attribute
called **href**. 
The value of the href attribute is the page that you want people to go to when they *click* on the link.
Users can click on anything that appears **between** the opening < a> tag and the closing < /a> tag and will be taken to the page specified in the href attribute. 
When you link to a different website, the value of the href attribute will be the full web address for the site, which is known as an **absolute** URL.

**Absolute URLS**
*URL* stands for Uniform Resource Locator.
Every web page has its own URL.
This is the web *address* that you would type into a browser if you wanted to
visit that specific page.
An absolute URL starts with the domain name for that site, and can be followed by the path
to a specific page. If no page is specified, the site will display the homepage.

When you are *linking* to other pages *within* the *same* site, you do not need to specify the
domain name in the URL. 
You can use a *shorthand* known as a *relative* URL.

**Relative URLs**

| Relative Link Type               |  Example               |
|-----------------------------------|------------------------------  |
| **Same Folder** To link to a file in the same folder, just use the file name. (Nothing else is needed.)   |       To link to music reviews from the music homepage: < a href="reviews.html">Reviews< /a> |
| **Child Folder** For a child folder, use the name of the child folder, followed by a forward slash, then the file name. |To link to music listings from the homepage: < a href="music/listings.html">Listings< /a> |
| **Grandchild Folder** Use the name of the child folder, followed by a forward slash, then the name of the grandchild folder, followed by another forward slash, then the file name.| To link to DVD reviews from the homepage:< a href="movies/dvd/reviews.html"> Reviews< /a> |
|**Parent Folder** Use ../ to indicate the folder above the current one, then follow it with the file name.| To link to the homepage from the music reviews: < a href="../index.html">Home< /a> |
| **GrandParent Folder** Repeat the ../ to indicate that you want to go up two folders (rather than one), then follow it with the file name. | To link to the homepage from the DVD reviews: < a href="../../index.html">Home< /a> |

### Email Links

**mailto**: To create a link that starts up the user's email program and
addresses an email to a specified email address, you use the < a>
element. 
However, this time the value of the href attribute starts
with mailto: and is followed by the email address you want the
email to be sent to.
 On the right you can see that an email link looks just like any other link but, when it is clickedon, the user's email program will open a new email message and address it to the person
specified in the link.

< a href="mailto:jon@example.org">Email Jon< /a>


This **example** is of a web page about film.

< html>

< head>

< title>Links< /title>

< /head>

< body>

< h1 id="top">Film Folk< /h1>

< h2>Festival Diary< /h2>

< p> Here are some of the film festivals we
will be attending this year.< br />Please
< a href="mailto:filmfolk@example.org">
contact us< /a> if you would like more
information.< /p>

< h3>January< /h3>

< p>< a href="http://www.sundance.org">
Sundance Film Festival< /a>< br />
Park City, Utah, USA < br />
20 - 30 January 2011< /p>

< h3>February< /h3>

< p>< a href="http://www.tropfest.com">
Tropfest< /a>< br />
Sydney, Australia< br />
20 February 2011< /p>

<!-- additional content -->

< p>< a href="about.html">About Film Folk< /a>< /p>

< p>< a href="#top">Top of page< /a>< /p>

< /body>

< /html>



### Key Concepts in Positioning Elements

**Building Blocks** CSS treats each HTML element as if it is in its
own box. This box will either be a *block-level* box or an *inline box*.

**Block-level** elements start on a new line Examples include:
< h1> < p> < ul> < li>

**Inline elements** flow in between
surrounding text Examples include:
< img> < b> < i>

![elements](https://media.gcflearnfree.org/content/5e82363212da9215e057b928_03_30_2020/block_vs_inline_diagram.png)

**Containing Elements**
If one block-level element sits inside another block-level element then the outer box is
known as the containing or parent element.

### Controll ing the Position of Elements

CSS has the following positioning *schemes* that allow you to control
the layout of a page: **normal flow**, **relative positioning**, and **absolute positioning**.
You specify the positioning scheme using the position
property in CSS.
You can also float elements using the float property.

* Normal flow
Every block-level element
appears on a new line, causing
each item to appear lower down
the page than the previous one.
Even if you specify the width
of the boxes and there is space
for two elements to sit side-byside,
they will not appear next
to each other.
This is the default
behavior (unless you tell the
browser to do something else).

* Relative Positioning
This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed. 
This
does not affect the position of
surrounding elements; they stay
in the position they would be in
in normal flow.

* Ab solute positioning
This positions the element
in relation to its containing
element.
 It is taken out of
normal flow, meaning that it
does not affect the position
of any surrounding elements
(as they simply ignore the
space it would have taken up).
Absolutely positioned elements
move as users scroll up and
down the page.


# FUNCTIONS & METHODS

**Function** — a set of instructions that perform a task.
**Method** — a set of instructions that are associated with an object.

*Functions* are like recipes. They can execute a set of instructions on data or variables and return the result. The beauty of functions is that they are recyclable. That is, the function can be used repeatedly *without* having to *write* the same code again.

// Define a function that prints a string
function welcomeMessage() {
  console.log('Welcome to JavaScript');
}
// Call the function
welcomeMessage();

In the example above, the welcomeMessage function is used to display Welcome to JavaScript in the console. Let’s walk through this code step-by-step:

* The function keyword indicates the start of a function.
* The word that follows (welcomeMessage) is the function’s name.
* The empty parentheses after welcomeMessage indicate that there are no parameters, or inputs, for the function.
* The code between the opening ({) and closing (}) curly braces is a set of instructions. This code will only execute when the function is called.
* To call a method, you need the function’s name, a pair of parentheses, and a semicolon. In this example, the function is called with welcomeMessage();.


**Methods**
A method, like a function, is a set of instructions that perform a task. The difference is that a method is associated with an object, while a function is not. Let’s explore some of JavaScript’s built-in methods.

var str = 'CodeCADEMY';
var str1 = str.toLowerCase();
var str2 = str.toUpperCase();

The variable str in the example above stores the string ‘CodeCADEMY’. The .toLowerCase() and .toUpperCase() methods in the example above are called on str. Let’s talk through each line:

* On the second line, the .toLowerCase() method is called on the str variable, which returns the lowercase string 'codecademy'.
* On the third line, the .toUpperCase() method is called on the str variable, which returns the uppercase string 'CODECADEMY'. Notice, periods are used to call a method on an object, as in str.toLowerCase();.

# 6 Reasons for Pair Programming

1. Greater efficiency
It is a common misconception that pair programming takes a lot longer and is less efficient. In reality, when two people focus on the same code base, it is easier to catch mistakes in the making.

2. Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.

3. Learning from fellow students
Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of.

4. Social skills
Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key.

5. Job interview readiness
A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen.

6. Work environment readiness
Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product.