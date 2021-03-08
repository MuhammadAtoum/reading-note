# CSS allows you to create rules that specify how the content of
an element should appear. For example, you can specify that
the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one
headings should be in a blue, italic, Times typeface.

# CSS allows you to create rules that control the
way that each individual box (and the contents
of that box) is presented.

## Using CSS, you could add a
border around any of the boxes,
specify its width and height, or
add a background color. You
could also control text inside
a box — for example, its color,
size, and the typeface used.

# Example Styles

### Boxes

Width and height
Borders (color, width, and style)
Background color and images
Position in the browser window

### Text

Typeface
Size
Color
Italics, bold, uppercase,
lowercase, small-caps

### Specific

There are also specific ways
in which you can style certain
elements such as lists, tables,
and forms.

# example

* body {
font-family: Arial, Verdana, sans-serif;}
h1, h2 {
color: #ee3e80;}
p {
color: #665544;}

* body {
font-family: arial;
background-color: rgb(185,179,175);}
h1 {
color: rgb(255,255,255);}


# Foreground Color

The color property allows you to specify the color of text inside an element. You can specify any
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
DarkCyan

*We look at these three different*
ways of specifying colors on the
next double-page spread.


* RGB Values
Values for red, green, and blue
are expressed as numbers
between 0 and 255.

* Hex Codes
Hex values represent values
for red, green, and blue in
hexadecimal code.


* Color Names
Colors are represented by
predefined names. However,
they are very limited in number.

# hsl, hsla

The hsl color property has been introduced in CSS3 as an alternative way to specify colors.
The value of the property starts with the letters hsl, followed by individual values inside
parentheses for:
## hue
This is expressed as an angle
(between 0 and 360 degrees).
## saturation
This is expressed as a
percentage.
## lightness
This is expressed as a
percentage with 0% being white,
50% being normal, and 100%
being black.
The hsla color property allows
you to specify color properties
using hue, saturation, and
lightness as above, and adds a
fourth value which represents
transparency (just like the rgba
property). The a stands for:
## alpha
This is expressed as a
number between 0 and 1.0.
For example, 0.5 represents
50% transparency, and 0.75
represents 75% transparency.
