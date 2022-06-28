# Class 4

## Assignment

[Wireframe and Design](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/)

For Lab, you’ll be building a site from scratch.
Think about what kind of page you want to design.
For now, focus mostly on the process. Take notes on the high-level process you’d want to follow to make a new site.

[Mozilla HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
If you’ve taken Code 101, this should be mostly review so skim.
If you have NOT taken Code 101, please read this chapter a little more carefully.

[Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
Note how these elements are common to the vast majority of web pages

Skim

[Mozilla HTML Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)
[Mozilla HTML Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

## Response

### Wireframing Article

- What is a wireframe?
  - skeleton design of a website, where things go, allows you to focus on the framework not the colors
- Wireframe Examples
  - whiteboards, pen and paper, eventually fancy schmancy software
  ![examples](https://dpbnri2zg3lc2.cloudfront.net/en/wp-content/uploads/old-blog-uploads/versions/samuel-student-wireframe---x----972-715x---.png)
- Considerations
  - pen vs digital is project dependant
  - different approaches can structure process, see reading
- Tools for Wireframing
  - this article mentions the following
    - __UXPin__: [UXPin](https://www.uxpin.com/)
    - __InVision__: [InVision](http://www.invisionapp.com/)
    - __Wireframe.cc__: [Wireframe.cc](https://wireframe.cc/)

- Steps for Wireframing
  1. Research
  2. Prepare
  3. Generate user flow map
  4. Draft
  5. Details
  6. Prototype

- Priniciples of Good Wireframing
  1. Clarity
  2. Confidence
  3. Simplicity is key

### Mozilla HTML Basics

- HTML basics
HTML (HyperText Markup Language) is the code that is used to structure a web page and its content.

- So what is HTML?
HTML is a markup language that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller, and so on. For example, take the following line of content:

The main parts of our element are as follows:

- The opening tag: consists of name, wrapped in opening and closing angle brackets.
- The closing tag: This is the same as the opening tag, except that it includes a forward slash
- The content: This is the content of the element, which in this case, is just text.
- The element: The opening tag, the closing tag, and the content together comprise the element.

Elements can also have attributes that look like the following:

- Attributes contain extra information about the element that you don't want to appear in the actual content.
- An attribute should always have the following:
  - A space between it and the element name (or the previous attribute, if the element already has one or more attributes).
  - The attribute name followed by an equal sign.
  - The attribute value wrapped by opening and closing quotation marks.

Nesting elements
You can put elements inside other elements too — this is called nesting. You do however need to make sure that your elements are properly nested

Empty elements
Some elements have no content and are called empty elements. Take the \<img> element that we already have in our HTML page:

Anatomy of an HTML document are the many element tags that exist, see articles for exaustive lists

Headings
Heading elements allow you to specify that certain parts of your content are headings — or subheadings.

Paragraphs
As explained above, \<p> elements are for containing paragraphs of text; you'll use these frequently when marking up regular text content:

Lists

Unordered lists are for lists where the order of the items doesn't matter, such as a shopping list. These are wrapped in a \<ul> element.
Ordered lists are for lists where the order of the items does matter, such as a recipe. These are wrapped in an \<ol> element.
Each item inside the lists is put inside an \<li> (list item) element.

Links
Links are very important — they are what makes the web a web! To add a link, we need to use a simple element — \<a> — "a" being the short form for "anchor". To make text within your paragraph into a link, follow these steps:

ex \<a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a>

### Semantic

Semantics
In programming, Semantics refers to the meaning of a piece of code

Semantics in JavaScript
In JavaScript, consider a function that takes a string parameter, and returns an \<li> element with that string as its textContent.

Semantics in CSS
In CSS, consider styling a list with li elements

Semantics in HTML
In HTML, for example, the \<h1> element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."

This will render it to look like a top level heading, but it has no semantic value, so it will not get any extra benefits as described above. It is therefore a good idea to use the right HTML element for the right job.

HTML should be coded to represent the data that will be populated and not based on its default presentation styling. Presentation (how it should look), is the sole responsibility of CSS.

Benefits of semantic markups:

- SEO Rankings
- Screen readers used by visually impaired users navigate a page
- Finding blocks of meaningful code
- Suggests to the developer the type of data that will be populated
- Semantic naming mirrors proper custom element/component naming

When approaching which markup to use, ask yourself,

- "What element(s) best describe/represent the data that I'm going to populate?"
  - Is it a list of data?; ordered, unordered?;
  - is it an article with sections and an aside of related information?
  - does it list out definitions?
  - is it a figure or image that needs a caption?
  - should it have a header/footer in addition to the global site-wide header/footer?

These are some of the roughly 100 semantic elements available. See Resource for examples

### Skimming

Lots of examples of syntax here, these are good places to dig around when looking for a new command or how to correctly add an element

[Homepage](https://briansward.github.io/reading-notes/)
