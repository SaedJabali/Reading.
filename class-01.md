## Overview
_Hypertext Markup Language (HTML)_ is the __language__ that describes the contents and __structure__ of webpages.
HTML code consists of HTML elements. An HTML element may contain text and/or other elements. This makes HTML code hierarchical. An HTML element consists of a start tag, followed by the element content, followed by an end tag. A start tag is of the form < elementName> and an end tag is of the form < /elementName>. Both the start and the end tags contain the element name (elementName).
The following example shows a < title> element; the start tag is < title>, the end tag is < /title>, and the contents is the text Web Mapping:

< title>Web Mapping< /title>

Some HTML elements are empty, which means that they consist of only a start tag, with no contents and no end tag. The following code shows an < hr> element, which is an example of an empty element:

__< hr>__

An element may have one or more attributes. Attributes appear inside the start tag and are of the form attributeName="attributeValue". The following code section shows an example of an < img> element, with an attribute called src. The value of the attribute, in this example, is "images/image.jpg". Note that < img>, like < hr>, is an empty HTML element, which is why it does not have an end tag.
__< img src="images/image.jpg">__

## Block vs. inline
While learning about the various HTML elements, it is important to keep in mind that HTML elements are divided into __two__ general types of behaviors:
* Block-level elements
* Inline elements

A block-level element, or simply a block element, is like a paragraph. Block elements always start on a new line in the browser window. Examples of block elements include:

* Headings < h1>
* Paragraphs < p>
* Bullet-point lists < ul>
* Numbered lists < ol>

It is helpful to imagine block elements as horizontal boxes. Box width is determined by the width of the browser window, so that the box fills the entire available space. Box height is determined by the amount of content. For example, a paragraph fills the entire available page width, with variable height depending on the amount of text.
An inline element is like a word within a paragraph. It is a small component that is arranged with other components inside a container. Inline elements appear on the same line as their neighboring elements. Examples of inline elements include:

* Links < a>
* Bold text < b>
* Italic text < i>
* Images < img>


## How Websites Are Created

All websites use __HTML__ and __CSS__, but content management systems, blogging software, and                       e-commerce platforms often add a few more technologies into the mix. 
_Small_ websites are often written just using HTML and CSS.

_Larger websites_ — those that are updated regularly and use a content management system (CMS), blogging tools, or e-commerce software — often make use of more complex technologies on the web server, but these technologies are used to produce HTML and CSS that is then sent to the browser.

 **So**, if your site uses these technologies, you will be able to use your new HTML and CSS knowledge to take more control over how your site looks.
Larger, more complex sites like these may use a database to store data, and programming languages such as PHP, ASP.\.Net, Java, or Ruby on the web server, but you do not need to know these technologies to improve what the user sees. The skills you will learn in this book should be enough to help you on that road.



## How Pages Use Structure

__Basic sections of a document__

Webpages can and will look different from one another, but they all tend to share similar standard __components__, unless the page is displaying a Fullscreen video or game, is part of art project, or is just badly structured:

##### header:
Usually, a big strip across the top with a big heading, logo, and perhaps a tagline. This usually stays the same from one webpage to another.
##### navigation bar:
Links to the site's main sections; usually represented by menu buttons, links, or tabs. Like the header, this content usually remains consistent from one webpage to another — having inconsistent navigation on your website will just lead to confused, frustrated users. Many web designers consider the navigation bar to be part of the header rather than an individual component, but that's not a requirement; in fact, some also argue that having the two separate is better for accessibility, as screen readers can read the two features better if they are separate.

##### main content:
A big area in the center that contains most of the unique content of a given webpage, for example, the video you want to watch, or the main story you are reading, or the map you want to view, or the news headlines, etc. This is the one part of the website that will vary from page to page!

##### sidebar:
Some peripheral info, links, quotes, ads, etc. Usually, this is contextual to what is contained in the main content (for example on a news article page, the sidebar might contain the author's bio, or links to related articles) but there are also cases where you will find some recurring elements like a secondary navigation system.

##### footer:
A strip across the bottom of the page that generally contains fine print, copyright notices, or contact info. It is a place to put common information (like the header) but usually, that information is not critical or secondary to the website itself. The footer is also sometimes used for SEO purposes, by providing links for quick access to popular content.

A "typical website" could be structured something like this:


![Typical Website](sample-website.png)


## The Evolution of HTML

1. HTML 4 Released 1997
2. 	XHTML 1.0 Released 2000
3. 	HTML5 Released 2000



**HTML5 Layout**


__HTML5__ offers a set of _markup_ elements that allow you to _create_ a structured layout for web pages. These elements are often termed as __Semantic__ Markup because they convey their meaning and purpose clearly to the developer and to the browser.

__Semantic Markup__

Semantic markup expresses its meaning and purpose clearly to the developers and to the browser. Web developers frequently use the __< div>__ element to layout their web pages. However, a __< div>__ element by itself __does not__ convey what it is representing in a web page. A < div> element may wrap a navigational menu, or it may house a list of blog posts, but merely using < div> does not convey much information to the developers or to the browsers. Usually, CSS classes applied to < div> elements reveal some information about their intended purpose. For example, consider the following markup:

< div class="header">...< /div>

In the above markup it is the header CSS class that gives you an idea as to what the < div> might be doing. In the absence of this CSS class, however, there is no way to easily identify what the < div> might be doing. This is because < div> is a general-purpose element. It has no specific documented responsibility. It simply marks a division or section of the web page but does not dictate what can go inside that section.
HTML5 includes a set of markup elements that overcome this difficulty. These new elements have meaningful names so that just by looking at these elements you get a clear idea about their content. These semantic elements of HTML5 are listed below (this is not an exhaustive list):

* < header>
* < footer>
* < section>
* < article>
* < aside>
* < nav>

![HTML layout](layout.png)

The above figure shows a typical arrangement of various elements. Note that their exact location on a page is purely dependent on the layout. For example, the < aside> element can be placed on the left-hand side of the < section> or even above or below it.

## Who is the Site For?

Every website should be designed for the target audience—not just for yourself or the site owner. 
It is therefore __very important__ to understand who your target audience is. Who is the Site For?

### Target Audience: individuals

1. What is the age range of your target audience?
2. Will your site appeal to more women or men? What is the mix?
3. Which country do your visitors live in?
4. Do they live in urban or rural areas?
5. What is the average income of visitors?
6. What level of education do they have?
7. what is their marital or family status?
8. What is their occupation?
9. How many hours do they work per week?
10. How often do they use the web?
11. What kind of device do they use to access the web?

### Target Audience: Companies

1. What is the size of the company or relevant department?
2. What is the position of people in the company who visit your site?
3. Will visitors be using the site for themselves or for someone else?
4. How large is the budget they control?
