![gh](https://www.freetutorialsplus.com/css-tutorial/images/css-illustration.png)
# CSS #
*"Pseudo-element" redirects here. For pseudoelement symbols in chemistry, see Skeletal formula § Pseudoelement symbols.
For the use of CSS on Wikipedia, see Help:Cascading Style Sheets.
For other uses, see CSS (disambiguation).*

> Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language such as HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.

CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics, enable multiple web pages to share formatting by specifying the relevant CSS in a separate .css file which reduces complexity and repetition in the structural content as well as enabling the .css file to be cached to improve the page load speed between the pages that share the file and its formatting.

Separation of formatting and content also makes it feasible to present the same markup page in different styles for different rendering methods, such as on-screen, in print, by voice (via speech-based browser or screen reader), and on Braille-based tactile devices. CSS also has rules for alternate formatting if the content is accessed on a mobile device.

The name cascading comes from the specified priority scheme to determine which style rule applies if more than one rule matches a particular element. This cascading priority scheme is predictable.

The CSS specifications are maintained by the World Wide Web Consortium (W3C). Internet media type (MIME type) text/css is registered for use with CSS by RFC 2318 (March 1998). The W3C operates a free CSS validation service for CSS documents.

In addition to HTML, other markup languages support the use of CSS including XHTML, plain XML, SVG, and XUL. >

# Getting Started with CSS #
** In this tutorial you'll learn how easy it is to add style and formatting information to the web pages using CSS. But, before we begin, make sure that you have some working knowledge of HTML.

If you're just starting out in the world of web development, start learning from here »

Without further ado, let's get started with the Cascading Style Sheets (CSS).**

 # Including CSS in HTML Documents #
CSS can either be attached as a separate document or embedded in the HTML document itself. There are three methods of including CSS in an HTML document:


- [x] 
Inline styles — Using the style attribute in the HTML start tag. 
- [x] Embedded styles — Using the < style> element in the head section of a document. 

- [x] External style sheets — Using the <link> element, pointing to an external CSS file.

![at](https://mdn.mozillademos.org/files/12189/css-as-authored.png)
 # Inline Styles #
**Inline styles are used to apply the unique style rules to an element by putting the CSS rules directly into the start tag. It can be attached to an element using the style attribute.

The style attribute includes a series of CSS property and value pairs. Each "property: value" pair is separated by a semicolon (;), just as you would write into an embedded or external style sheets. But it needs to be all in one line i.e. no line break after the semicolon, as shown here:**

> "<h1 style="color:red; font-size:30px;">This is a heading</h1>
>
>" <p style="color:green; font-size:22px;">This is a paragraph.</p> >

>" <div style="color:blue; font-size:14px;">This is some text content.</div> >

# CSS Color #
Setting Color Property
The color property defines the text color (foreground color in general) of an element.

For instance, the color property specified in the body selector defines the default text color for the whole page. Let's try out the following example to see how it works:

>
body {
    color: #ff5722;
}

# Defining Color Values #
Colors in CSS most often specified in the following formats:

- [x] a color keyword - like "red", "green", "blue", "transparent", etc.
- [x] a HEX value - like "#ff0000", "#00ff00", etc.
- [x] an RGB value - like "rgb(255, 0, 0)"

CSS3 has introduced several other color formats such as HSL, HSLA and RGBA that also support alpha transparency. We'll learn about them in greater detail in CSS3 color chapter.

For now, let's stick to the basic methods of defining the color values:

# Color Keywords #
CSS defines the few color keywords which lets you specify color values in an easy way.

These basic color keywords are: aqua, black, blue, fuchsia, gray, green, lime, maroon, navy, olive, purple, red, silver, teal, white, and yellow. The color names are case-insensitive.

[css referce](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)


![ghaliaaa](https://www.techfry.com/images/articles/css/css02.jpg)

