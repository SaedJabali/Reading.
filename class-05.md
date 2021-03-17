# Images

A picture can say a thousand words, and great images help make the difference between an
average-looking site and a really engaging one.

There are several things to consider when selecting and
preparing images for a site, but taking time to get them
**right** will make it look more attractive and professional.
We should do the following so they can be right :

* Include an image in your web pages using HTML.
* Pick which image format to use.
* Show an image at the right size.
* Optimize an image for use on the web to make pages load faster.

**Images** can be used to set the
tone for a site in less time than
it takes to read a description. 
And it should be 
* Be relevant
* Convey information
* Convey the right mood
* Be instantly recognisable
* Fit the color palette

### Adding Images

< img>
To add an image into the page
you need to use an < img>
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:

**src**
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site.

**alt**
This provides a text description
of the image which describes the
image if you cannot see it.

The text used in the alt attribute
is often referred to as alt text.
It should give an **accurate**
description of the image content
so it can be understood by
screen reader software (used by
people with visual impairments)
and search engines.

**title**
You can also use the title
attribute with the < img> element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.

The text used in the alt attribute
is often referred to as **alt text**.
It should give an accurate
description of the image content
so it can be understood by
screen reader software (used by
people with visual impairments)
and search engines.


### Height & Width of Images

**height**
This specifies the height of the
image in pixels.
**width**
This specifies the width of the
image in pixels.

#### The best places to put the image on are:

1. *before a paragraph*
The paragraph starts on a new
line after the image.

2. *inside the start of a paragraph*
The first row of text aligns with
the bottom of the image.

3. *in the middle of a paragraph*
The image is placed between the
words of the paragraph that it
appears in.

### Aligning Images

The align attribute was
commonly used to indicate how
the other parts of a page should
flow around an image. It has
been removed from HTML5
and new websites should use
CSS to control the alignment of
images.

* __Horizontally__

The align attribute can take
these horizontal values:
* left
This aligns the image to the left
(allowing text to flow around its
right-hand side).

* right
This aligns the image to the right
(allowing text to flow around its
left-hand side).

* __Vertically__

There are three values that the
align attribute can take that
control how the image should
align vertically with the text that
surrounds it:

* top
This aligns the first line of the
surrounding text with the top of
the image.

* middle
This aligns the first line of the
surrounding text with the middle
of the image.

* bottom
This aligns the first line of the
surrounding text with the bottom
of the image.




# Colors

### Foreground Color

1. Colors
The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:

* rgb values
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)

* hex codes
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80

* color names
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan.


2. Background-Color

**CSS** treats each **HTML** element as if it appears in a box, and the
background-color property sets the color of the background for that box.
You can specify your choice of background color in the same three ways you can specify
foreground colors: *RGB values, hex codes, and color names*.
If you do not specify a background color, then the background is transparent.
By default, most browser windows have a **white** background, but browser users
can set a background color for their windows, so if you want
to be sure that the background is white you can use the background-color property on the < body> element.

### Contrast
When picking *foreground* and *background* colors, it is important to ensure that there 
is enough contrast for the text to be legible.

![Contrast](https://coschedule.com/blog/wp-content/uploads/contrast-illustration.png).

### CSS 3: Opacity

**opacity**, **rgba**


CSS3 introduces the *opacity*
property which allows you to
specify the opacity of an element
and any of its child elements.
The value is a number between
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15%
opacity).

The CSS3 *rgba* property allows
you to specify a color, just like
you would with an RGB value,
but adds a fourth value to
indicate opacity. 
This value is known as an alpha value and is
a number between 0.0 and 1.0
(so a value of 0.5 is 50% opacity
and 0.15 is 15% opacity). The
rgba value will only affect the
element on which it is applied
(not child elements).

# Text

The properties that allow you to control
the appearance of text can be split into
two groups:

* Those that directly affect the font and its appearance
(including the typeface, whether it is regular, bold or italic,
and the size of the text)
* Those that would have the same effect on text no matter
what font you were using (including the color of text and
the spacing between words and letters).

< style>

font-weight: Light;

font-weight: Medium;

font-weight: Bold;

font-weight: Black;

font-style: normal;

font-style: italic;

font-style: oblique;

font-stretch:Condensed;

font-stretch:Regular;

font-stretch: Extended;

< /style>

When choosing a **typeface**, it is important to understand that a browser will usually
only display it if it's **installed** on that user's computer.

**Serif**
Serif fonts have extra details on
the end of the main strokes of
the letters.


**Sans-Serif**
Sans-serif fonts have straight
ends to letters and therefore
have a much cleaner design.

