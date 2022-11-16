# Class 5 notes - CSS

**CSS** (Cascading Style Sheets) is used to style a web page.

- A CSS rule opens with a selector.
- Inside curly braces `{}` will be **declarations** consisting of **property** and **value** pairs.
- The following example uses `<h1>` as the selector and `color` and `font-size` as properties.

>Example:  
`h1 {`<br>
    `color: red;`<br>
    `font-size: 5em;`<br>
`}`

## Types of Selectors

- **Universal selector** `*` matches elements of any type.
- **Type selector** `elementname` matches elements by node name.
- **Class selector** `.classname` matches elements based on the contents of their `class` attribute.
- **ID selector** `#idname` matches an element based on the value of the element's `id` attribute.
- **Attribute selector** `[attr=value]` based on the presence or value of a given attribute.

### Grouping selectors

**Selector list** `A, B` specifies that both `A` and `B` are selected.

>Example: `span {`<br>
    `border: red 2px solid;` <br>
`}`<br>
`div {`<br>
    `border: red 2px solid;`<br>
`}`<br>
can instead be written as: `span, div {`<br>
    `border: red 2px solid;`<br>
`}`

## CSS Reset

A reset stylesheet is used to reduce browser inconsistencies in formatting.