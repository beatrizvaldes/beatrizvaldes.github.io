# Intro to CSS

CSS (Cascading Style Sheets) allows you to create rules that specify how the content of an element should appear.
There are **block** and **inline elements**. Block level elements start in a new line, like <H1>. Inline elements flow within the text, like bold, links, etc. The key to understanding how CSS works is imagining there is an *invisible box* around every HTML element.

In this case, 
`p {
    font-family: Arial;

- p is a selector, indicate which element the rule applies to. 
- Font-family: Arial is a declaration, indicates how the elements referred to in the selector should be styled. Declarations are split into two parts, a property and a value, and are separated by a colon.

You can use external CSS (recomended) or internal CSS that's used inside the HTML sheet. We don't want to use that in a website that has more than one page.

We can find popular selectors [here](https://www.technetexperts.com/web/10-most-popular-css-selectors/)
