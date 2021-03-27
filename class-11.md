# Images

You can *control* the size of an image using the width and height properties in **CSS**, just like you can for any other box.
*Specifying* image sizes helps pages to load more *smoothly* because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.


### Aligning images Using CSS

Rather than using the < img> element's align attribute, web page authors are increasingly using the float property to align images. 
There are two ways that this is commonly achieved:

1. The float property is added
to the class that was created to
represent the size of the image.
2. New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.

**By default**, images are inline elements.
 This means that they flow within the surrounding text.
In order to center an image, it should be turned into a blocklevel
element using the display property with a value of block.
Once it has been made into a block-level element, there are
two common ways in which you can horizontally center an image:

1. On the containing element,
you can use the text-align
property with a value of center.
2. On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.



**Background Images**


The background-image property allows you to place an image behind any HTML
element. This could be the entire page or just part of the page.


**Repeating Images**

* repeat

The background image is
repeated both horizontally and
vertically

* repeat-x

The image is repeated
horizontally only

* repeat-y

The image is repeated vertically
only.

* no-repeat

The image is only shown once.

**Background Position**

When an image is not being
repeated, you can use the
background-position
property to specify where in the
browser window the background
image should be placed.