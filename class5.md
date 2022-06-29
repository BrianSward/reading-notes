# Reading Class 5

## Assignment

Read

[What is CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

Read and Experiment

[How to Add CSS](https://www.w3schools.com/css/css_howto.asp)

[CSS Color](https://www.w3schools.com/cssref/pr_text_color.asp)

Skim

[CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

[Myers Web Reset Stylesheet](https://meyerweb.com/eric/tools/css/reset/)

Submission Instructions
Share what you’ve learned by copying and pasting the full text of your new rendered web page into the ‘Reply’ below. Include the live url of the new page below your pasted text.

## Response

### What is CSS?

- What is CSS?

__CSS (Cascading Style Sheets)__ allows you to create great-looking web pages. Using CSS, you can control exactly how HTML elements look in the browser.

- What is CSS for?

CSS is a language for specifying how documents are presented to users.

    _Note: A browser is sometimes called a user agent_

- CSS can be used for very basic document text styling
- It can be used to create a layout
- It can even be used for effects such as animation

- CSS syntax

CSS is a rule-based language where declarations, which take the form of property and value pairs, specify the properties. A CSS stylesheet will contain many such rules, written one after the other.

    _Note: You can find links to all the CSS property pages (along with other CSS features) listed on the MDN CSS reference_

- CSS is broken down into modules

- CSS has specifications which are published by standards organizations (such as the W3C, WHATWG, ECMA, or Khronos).

New CSS features are developed or specified by the CSS Working Group. CSS is constantly developing. A website built in 2000, using the limited CSS available then, should still be usable in a browser today!

- as CSS is implimented it is usually supported by all browsers simu support information, BUT ALWAYS CHECK ALL BROWSERS. There are tables which show compatibility.

### How to add CSS

Three Ways to Insert CSS

- __External__ CSS - With an external style sheet, you can change the look of an entire website by changing just one file!

- __Internal CSS__ - An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the <style> element, inside the head section.

- __Inline__ CSS - An inline style may be used to apply a unique style for a single element.

    _Note: An inline style loses many of the advantages of a style sheet (by mixing content with presentation). Use this method sparingly._

- __Multiple Style Sheets__ If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used. 

- __Cascading Order__ What style will be used when there is more than one style specified for an HTML element? So, an inline style has the highest priority, and will override external and internal styles and browser defaults.

### CSS Color

CSS color Property is how we set the text-color for different elements:

- Definition and Usage

The color property specifies the color of text.

    Default value: not specified
    Inherited: yes
    Animatable: yes. Read about animatable
    Version: CSS1
    JavaScript syntax: object.style.color="#0000FF"

CSS Syntax
    color: color|initial|inherit;

Property Values
|Value|Description|
|---|---|
|color |Specifies the text color. Look at [CSS Color Values](https://www.w3schools.com/cssref/css_colors_legal.asp) for a complete list of possible color values.|
|initial|Sets this property to its default value.|
|inherit|Inherits this property from its parent element.

### Skimming Assignments

#### CSS Reference

[CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

"Use this CSS reference to browse an alphabetical index of all of the standard CSS properties, pseudo-classes, pseudo-elements, data types, functional notations and at-rules. You can also browse key CSS concepts and a list of selectors organized by type. Also included is a brief DOM-CSS / CSSOM reference."

#### Myers Web Reset Stylesheet

[Myers Web Reset Stylesheet](https://meyerweb.com/eric/tools/css/reset/)

Not fully sure what I'm reading here but it seems like you will want to reset your CSS at times and this is a comprehenive and seemingly accepted way to do it; although the usefulness of this is lost on me at this nacent stage of understanding

[Homepage](https://briansward.github.io/reading-notes/)
