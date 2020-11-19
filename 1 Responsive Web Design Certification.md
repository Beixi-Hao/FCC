# 1 Responsive Web Design Certification

[TOC]



## 1.1 Basic HTML and HTML5						28 

### 1.1.0   Introduction to Basic HTML and HTML5

   HTML - Hyper Text Markup Language

- describe the structure of a web page
- uses a special syntax or notation to organize and give information about the page to the browser
- HTML specification - W3 Consortium
- latest version HTML5
- elements usually have opening and closing tags that surround and give meaning to content

### 1.1.1   Say Hello to HTML Elements

Most HTML elements have an opening tag and a closing tag

opening tags:

`<h1>`

closing tags:

`</h1>`

- [x] change the contents in the `h1` element

### 1.1.2   Headline with the h2 Element

build an HTML5 cat photo web app

```html
<h2> </h2>
```

this elements tells the browser about the structure of your website

```html
<h1> - main headings
<h2> - sub headings
<h3>
<h4>
<h5>
<h6>
```

- [x] Add an `h2` tag under the `h1`tag

### 1.1.3   Inform with the Paragraph Element

`p` element are the preferred element for paragraph text on websites

p - paragraph

```html
<p> </p>
```

! as a convention, all HTML tags are written in lowercase

- [x] create a `p` element below the `h2` element

### 1.1.4   Fill in the Blank with Placeholder Text

*lorem ipsum* text - placeholder text by typesetters since the 16th century

Cicero of Ancient Rome

- [x] replace the text inside the `p` element with kitty ipsum text

------



### 1.1.5   Uncomment HTML

**commenting**

- a way to leave comments for other developers within your code without affecting the resulting output that is displayed to the end user
- a convenient way to make code inactive without having to delete it entirely

`<!-- -->`

- [x] Uncomment `h1`, `h2`, and `p` elements

### 1.1.6   Comment out HTML

- [x] comment out `h1` element and `p` element, but not `h2` element

------



### 1.1.7   Delete HTML Elements

- [x] delete `h1` element to simplify the view

### 1.1.8   Introduction to HTML5 Elements

`main`

`header`

`footer`

`nav`

`video`

`article`

`section`

- gives a descriptive structure to your HTML

- SEO - Search Engine Optimization 

- accessibility

- [x] create a second `p` element
- [x] create a `main` element and nest the 2 `p`element inside the `main` element

### 1.1.9  Add Images to Your Website

`img` element

point to a specific image's URL using the `src` attribute

```html
<img src="https://www.freecatphotoapp.com/your-iamge.jpg">
```

- `img` elements are <u>self-closing</u>
- all `img` elements **must** have an `alt` attribute
  - for screen readers to improve accessibility 
  - is displayed if the image fails to load
    - if the image is purely decorative, using an empty `alt` attribute is the best practice
    - should not contain special characters unless needed

```html
<img src="https://www.freecatphotoapp.com/your-iamge.jpg" alt="A business cat wearing a netktie.">
```

- [x] within the existing `main` elements, insert an `img` element before the `p` element
- [x] set the `src` attribute
- [x] give the `alt` attribute with applicable text

------



### 1.1.10 Link to External Pages with Anchor Elements

anchor element `a` - link to content outside of your web page

needs:

- a destination web address - `href` attribute
- anchor text

```html
<a href="https://freecodecamp.org">this links to freecodecamp.org</a>
```

- [x] create an `a` element

### 1.1.11 Link to Internal Sections of a Page with Anchor Elements

create internal links to jump to different sections within a webpage

to create an internal link:

1. assign a link's `href` attributes to a hash symbol `#` + the value of the `id` attribute for the element that you want to internally link to
2. add the same `id` attribute to the element you are linking to

`id` -  an attribute that uniquely describes an element

```html
<a href="#contacts-header">Contacts</a>
...
<h2 id="contacts-header">Contacts</h2>
```

- [x] change the external link to an internal link to jump to the bottom

### 1.1.12 Nest an Anchor Element within a Paragraph

nest links within other text elements

```html
<p>
  Here's a <a target="_blank" href="http://freecodecamp.org"> link to freecodecamp.org   </a> for you to follow. 
</p>
```

`_blank` specifies to open the link in a new tab

- [x] nest the existing `a` element within a new `p` element

### 1.1.13 Make Dead Links Using the Hash Symbol

add `a` elements to your website before you know where they will link

changing the behavior of a link using `JavaScript`

- [x] replace the `href` attribute value with a `#` hash symbol to create a dead link

`href="#"`

### 1.1.14 Turn an Image into a Link

make elements into links by nesting them within an `a` element

```html
<a href="#">
    <img src="https://bit.ly/fcc-running-cats" alt="Three kittens running towards the camera">
</a>
```

- [x] place the existing images within an `a` element

------

### 1.1.15 Create a Bulleted Unordered List

```html
<ul>
    <li>milk<\li>
    <li>cheese</li>
</ul>
```

- [x] create an unordered list

### 1.1.16 Create an Ordered List

ordered list = numbered list

<ol>
    <li>Garfield</li>
    <li>Sylvester</li>
</ol>

- [x] create an ordered list

------

### 1.1.17 Create a Text Field

create a web form

`input` elements are a convenient to get input from user

```html
<input type="text">
```

`input` elements are **self-closing**

- [x] create an `input` element of type `text`

### 1.1.18 Add Placeholder Text to a Text Field

placeholder text - displayed in `input` element before your user has inputted anything.

```html
<input type="text" placeholder="this is placeholder text">
```

- [x] set the `placeholder` value of your text `input`

------

### 1.1.19 Create a Form Element

build web forms that actually submit data to a server

```html
<form action="/url-whee-you-want-to-submit-form-data"></form>
```

- [x] nest the existing `input` element inside a `form` to the `action` attribute of the `form` element

### 1.1.20 Add a Submit Button to a Form

add a `submit` button to the form

clicking the button - send the data from the `form` to the URL specified with `form`'s `action` attribute

```html
<button type="submit">this button submits the form</button>
```

<button type="submit">this button submits the form</button>

- [x] add a button

### 1.1.21 Use HTML5 to Require a Field

require specific form fields so that user will not be able to submit form until he or she has filled them out

ex:

make a text input field required, add attribute `required` 

```html
<input type="text" required>
```

- [x] make text `input` a `required` field

------

### 1.1.22 Create a Set of Radio Buttons

*radio buttons* for questions where you want the user to only give you one answer out of multiple options

`input` type - radio

- each radio buttons can be nested within its own `label` element - automatically associate the radio button input with the label element surrounding it

- all related radio buttons should have the same `name` attribute to create a radio button group
  - select any single radio button will automatically deselect the other buttons within the same group ensuring only 1 answer is provided by the user

```html
<label>
    <input type="radio" name="indoor-outdoor">Indoor
</label>
```

best practice - set a `for` attribute on the `label` element - with a value that matches the value of the `id` attribute of the `input` element

allows assistive technologies to create a linked relationship between the label and the child `input` element

```html
<label for="indoor">
    <input id="indoor" type="radio" name="indoor-outdoor">Indoor
</label>
```

- [x] add a pair of radio buttons to the form, each nested within its `label` element

### 1.1.23 Create a Set of Checkboxes

Forms commonly use *checkboxes* for questions that may have more than 1 answer

`input` type - checkboxes

- each checkboxes can be nested within its own `label` element - automatically associate the checkbox input with the label element surrounding it

- all related checkbox inputs should have the same `name` attribute
- best practice - explicitly define the relationship between a checkbox `input` and its corresponding `label` by setting the `for` attribute on the `label` element to match the `id` attribute of the associated `input` element

```html
<label for="loving">
    <input id="loving" type="checkbox" name="personality">Loving
</label>
```

- [x] add a set of 3 checkboxes, each nested within its `label` element

### 1.1.24 Use the value attribute with Radio Buttons and Checkboxes

when a form gets submitted, the data is sent to the server and includes entries for the options selected

inputs of type `radio` and `checkbox` report their values from the `value` attribute

```html
<label for="indoor">
    <input id="indoor" value="indoor" type="radio" name="indoor-outdoor">Indoor
</label>
<label for="outdoor">
    <input id="outdoor" value="outdoor" type="radio" name="indoor-outdoor">Outdoor
</label>
```

when the user submits the form with the `indoor` option selected

the form data will include the line `indoor-outdoor=indoor`



if the `value` attribute is omitted, the submitted form data uses the default value, which is `on`

`indoor-outdoor=on` NOT useful

`value` attribute needs to be set to something to identify the option

- [x] give each of the `radio` and `checkbox` inputs the `value` attribute

### 1.1.25 Check Radio Buttons and Checkboxes by Default

set a checkbox or radio button to be checked by default using `checked` attribute

```html
<input type="radio" name="test-name" checked>
```

- [x] set the 1st of your radio buttons and the 1st of your checkboxes to both be checked by default

------

### 1.1.26 Nest Many Elements within a Single div Element

the `div` element

- division element
- a general purpose container for other elements

- the most commonly used

```html
<div> </div>
```

- [x] nest lists all within a single `div` element

------

### 1.1.27 Declare the Doctype of an HTML Document

a few elements that give overall structure to the page, and should be included in every HTML document



At the top of document

- tell the browser which version of HTML your page is using
- latest HTML5

```html
<!DOCTYPE html>
<html>
    <!-- Your HTML code goes here -->
</html>
```

`<!DOCTYPE ...>` 

... is the version of HTML

ex. HTML5 `<!DOCTYPE html>`

!DOCTYPE is important

`html` is not case sensitive



the rest of HTML code needs to be wrapped in `html` tags

- [x] Add a `DOCTYPE` tag, `html` tag, and `h1` element

### 1.1.28 Define the Head and Body of an HTML Document      	

add another level of organization in HTML document within the `html` tags with the `head` and `body` elements

`head` - any markup with information about page

- metadata elements
  - `link`
  - `meta`
  - `title`
  - `style`

`body` - any markup with the content of the page (what displays for a user)

```html
<!DOCTYPE html>
<html>
    <head>
        <!-- metadata elements -->
    </head>
    <body>
       <!-- page contents -->
    </body>
</html>
```

- [x] Edit the markup so there's a `head` and a `body`

## 1.2 Basic CSS							   					44 

### 1.2.0 Introduction to Basic CSS
1.2.1 Change the Color of Text
Passed
Use CSS Selectors to Style Elements
Passed
Use a CSS Class to Style an Element
Passed
Style Multiple Elements with a CSS Class
Passed
Change the Font Size of an Element
Passed
Set the Font Family of an Element
Passed
Import a Google Font
Passed
Specify How Fonts Should Degrade
Passed
Size Your Images
Passed
Add Borders Around Your Elements
Passed
Add Rounded Corners with border-radius
Passed
Make Circular Images with a border-radius
Passed
Give a Background Color to a div Element
Passed
Set the id of an Element
Passed
Use an id Attribute to Style an Element
Passed
Adjust the Padding of an Element
Passed
Adjust the Margin of an Element
Passed
Add a Negative Margin to an Element
Passed
Add Different Padding to Each Side of an Element
Passed
Add Different Margins to Each Side of an Element
Passed
Use Clockwise Notation to Specify the Padding of an Element
Passed
Use Clockwise Notation to Specify the Margin of an Element
Passed
Use Attribute Selectors to Style Elements
Passed
Understand Absolute versus Relative Units
Passed
Style the HTML Body Element
Passed
Inherit Styles from the Body Element
Passed
Prioritize One Style Over Another
Passed
Override Styles in Subsequent CSS
Passed
Override Class Declarations by Styling ID Attributes
Passed
Override Class Declarations with Inline Styles
Passed
Override All Other Styles by using Important
Passed
Use Hex Code for Specific Colors
Passed
Use Hex Code to Mix Colors
Passed
Use Abbreviated Hex Code
Passed
Use RGB values to Color Elements
Passed
Use RGB to Mix Colors
Passed
Use CSS Variables to change several elements at once
Passed
Create a custom CSS Variable
Passed
Use a custom CSS Variable
Passed
Attach a Fallback value to a CSS Variable
Passed
Improve Compatibility with Browser Fallbacks
Passed
Inherit CSS Variables
Passed
Change a variable for a specific area
Passed
Use a media query to change a variable

## 1.3 Applied Visual Design							52 

## 1.4 Applied Accessibility		  					22

## 1.5 Responsive Web Design Principles	4

## 1.6 CSS Flexbox               								17

## 1.7 CSS Grid                 									22

## 1.8 Responsive Web Design Projects		5