# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [ ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_
//...............................
A “screen reader” is a software application that converts the text displayed on a computer screen into synthesized speech. Text-to-speech capabilities are a vital component of AI assistants such as Apple’s Siri and Amazon’s Alexa, which “talk” with users by converting their replies into digital speech. Screen readers are a specific use case of text-to-speech technology that improve accessibility for people with visual disabilities.
Source: https://www.boia.org/blog/why-screen-readers-are-essential-for-website-accessibility
//...........................

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
//....
<img>
//.....

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
//...
<ul> , <li> , <a>
//....

c) You want to sell designer hats. You need to receive orders from the user.
//....

The <form> tag is used to get user input, by adding the form elements. Different types of form elements include text input, radio button input, submit button, etc.
//....

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
//...
It is not possible to nest a <button> with an <a> element as it isn’t valid HTML5. According to HTML5 specification, the <a> tag must not have any interactive content descendant.

The HTML <a> element can be wrapped around entire lists, paragraphs, sections, and so on, as long as it does not contain an interactive content (e.g., buttons or other links).
//....

## Q5 - What is the most generic tag you can use?
//...
<div> and the link tag.
//...

## Q6 - What do the following achronyms stand for?

a) `a`
//..
anchor
//..

b) `ol`
//...
The <ol> tag defines an ordered list.
//...

c) `ul`
//...
The <ul> tag defines an unordered (bulleted) list.
//...


d) `li`
//..
The <li> HTML element is used to represent an item in a list. 
//...

e) `tr`
//...
The <tr> HTML element defines a row of cells in a table.
//...

f) `th`
//...
The <th> tag defines a header cell in an HTML table.
//...

g) `td`
//...
 The <td> HTML element defines a cell of a table that contains data. It participates in the table model.
 //...

## Q7 - Usually, `td` elements are children of what kind of elements?
//...
<tr>
//...

## Q8 - What is the difference between td and th?
//...
 TH is used for table header cells while TD is used for table data cells. This distinction gives user agents a means to render such cells distinctly, for instance by using a larger or heavier font for header cells.
 //...

## Q9 - Which tag makes the text appear bigger: h1 or h3?
//...
The heading elements are H1, H2, H3, H4, H5, and H6 with H1 being the highest (or most important) level and H6 the least.
//...

## Q10 - In which situation can you use self closing tags?
//...
Typically, the self-closing tag makes use of a “/” character in order to effectively close out a beginning tag enclosed in sideways carets.
//...

## Q11 - What is autofilling and why is it important?
//...
The AutoComplete supports the autofill behavior with the help of autofill property. Whenever you change the input value, the AutoComplete will autocomplete your data by matching the typed character. Suppose, if no matches found then, AutoComplete doesn’t suggest any item. It's important because Autocomplete allows the browser to predict the value.
//...

## Q12 - Which attributes are always present in an img element?
//..
The src attribute is required, and contains the path to the image you want to embed. The alt attribute holds a text description of the image, which isn't mandatory but is incredibly useful for accessibility
//...

## Q13 - Which attribute is always present for an anchor tag?
//...
The Anchor element. The <a> HTML element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address. 
//...
