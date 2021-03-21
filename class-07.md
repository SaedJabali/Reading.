# Tables

**What's a Table?**

A table represents information in a *grid* format.
Examples of tables include financial reports, TV
schedules, and sports results.

## Basic Table Structure

**< table>**
The < table> *element* is used
to create a table. The contents
of the table are written out row
by row.

**< tr>**
You indicate the start of each
row using the opening < tr> tag.
(The tr stands for table row.)
It is followed by one or more
< td> elements (one for each cell
in that row).
At the end of the row you use a
closing < /tr> tag.

**< td>**
Each cell of a table is
represented using a < td>
element. (The td stands for table data.)
At the end of each cell you use a
closing < /td> tag.

< th>
The < th> element is used just
like the < td> element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table heading).

![Structure](https://lh3.googleusercontent.com/proxy/r5CdOzA-NfzPpP3PA5jt7fBqwzk_s5l5gesOMZ82fOOK9hEhJerrWaEeHt-R8OWYQr_fYu9Gb7w1OZnsptZ5Vpen4gxcb2DXm2Dmk-GjUhS1x4-NR52mzrk)


### Spanning Columns and Rows with HTML Tables


Most real-world **tables** have cells that stretch across two or more rows or column in the table. In the publishing world, these cells are said to straddle the related rows and columns. Often, the straddling cells contain information relevant to straddled rows and columns, such as a common heading or shared data.

In HTML, these straddling cells are known as spanning cells. You can create spanning cells across rows and columns (and both) using two attributes defined for the < td> and < th> tags. As you might expect, the colspan attribute creates a cell that spans two or more columns. The rowspan attribute creates a cell that spans two or more rows. You can use these attributes together, creating a cell that spans rows and columns simultaneously.

Simple spans


< table>

< tr>

  < th>< /th>

  < thcolspan="2">Fruit</th>

< /tr>



< tr>

  < th>< /th>

  < th>Oranges< /th>

  < th>Grapefruit< /th>

< /tr>



< tr>

  < th>Flavor< /th>

  < td>Sweet< /td>

  < td>Tart< /td>

< /tr>



< tr>

  < th>Size< /th>

  < td>Small< /td>

  < td>Large< /td>

< /tr>

< /table>

this will result a table contains

Fruit

Oranges	Grapefruit

Flavor...  	Sweet..   	Tart

Size....   	Small..   	Large


Notice that the first row of this table has only two cells. The first cell is empty, lining up with the empty cell in the beginning of the second row. The next cell has the colspan attribute set to 2, causing it to span the next two cells in the next row. You can verify this by seeing that the cell containing "Fruit" spans the two cells containing "Orange" and "Grapefruit."


### Long Tables

The < thead> tag is used to group header content in an HTML table.

The < thead> element is used in conjunction with the < tbody> and < tfoot> elements to specify each part of a table (header, body, footer).

Browsers can use these elements to enable scrolling of the table body independently of the header and footer. Also, when printing a large table that spans multiple pages, these elements can enable the table header and footer to be printed at the top and bottom of each page.

Note: The < thead> element must have one or more < tr> tags inside.

The < thead> tag must be used in the following context: As a child of a
< table> element, after any < caption> and < colgroup> elements, and before any < tbody>, < tfoot>, and < tr> elements.

# Functions, Methods, and Objects

The **this** Keyword

In a function definition, this refers to the "owner" of the function.

In other words, this.firstName means the firstName property of this object.

JavaScript **Methods**

JavaScript methods are actions that can be performed on objects.

A JavaScript method is a property containing a function definition.

To access an object method with the following syntax:

**objectName.methodName()**

You will typically describe fullName() as a method of the person object, and fullName as a property.

The fullName property will execute (as a function) when it is invoked with ().

To add a new method to an object:

person .name = function () {

  return this.firstName + " " + this.lastName;

};



