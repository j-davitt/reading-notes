
# Class 4 notes - HTML Structure

## Wireframing

### Key Principles

>- Maintain Clarity
>- Gain User Confidence
>- Simplicity is Key

`Wireframing` is a practice used to define and plan the information hierachy of the design for a website, app, or product. Allows you to plan the layout and interaction of your interface.

### Best Tools for Wireframing

- Pen and paper
- UXPin
- InVision
- Wireframe.cc

### Steps to Make a Wireframe

1. **Do your research** - Understand your audience and research competitors
2. **Prepare research for quick reference**
3. **Map out user flow** - Ensure users are self sufficient
4. **Draft and Sketch** - Build the skeleton
5. **Add detail and start testing** - Add detail to elements and collect feedback from colleagues
6. **Start turning wireframes into prototypes**

## HTML Basics

Main parts consist of:

1. **Opening tag:** Name of the element wrapped in angle brackets **<>**. States where the element begins.
2. **Closing tag:** Same as opening tag except it contains a forward slash. States where the element ends.
3. **Content:** Content of the element.
4. **The Element:** The openeing tag, closing tag, and content together.

>Example: `<p>Example Text</p>`

**Attributes** contain extra information about an element. Attributes that set a value always have:

1. A space between it and the element name.
2. The attribute name followed by an equal sign `=`.
3. The attribute value wrapped by opening and closing quotation marks.

>Example: `<p class="editor-note">Example Text</p>`

**Nesting** is placing elements inside other elements. This can be used for many things including bolding text.

>Example: `<p>Example <strong>text</strong></p>`

**Images** are embedded using `<img>` with `src` containing the path to the image and `alt` containing descriptive text.

>Example: `<img src="images/pic1.jpg" alt="description of image">`

The **Heading** element allows you to specify headings or subheadings `<h1> - <h6>`.

**Lists** are wrapped in `<ul></ul>` for unordered lists and `<ol></ol>` for ordered lists. Each item will be wrapped in `<li></li>`.

>Example: <br>`<ul>`
    <br>`<li>Item 1</li>`
    <br>`<li>Item 2</li>`
    <br>`<li>Item 3</li>`
 <br> `</ul>`

 **Links** are made with `<a href="url">link name</a>`
 