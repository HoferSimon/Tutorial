# HTML Tutorial

> In this tutorial, we will learn how to write HTML.


<br />
<br />


## Introduction

> HTML is a markup language used to create web pages. HTML describe the structure of a web page and the most inportant part, HTML is NOT a programming language.


<br />
<br />


## Starting

> If you want to start with HTML, you should know the following: How to create a HTML page. If you didnt know how to do it yet, you are free to jump to [How to create a HTML page](/Web-Development/How-to-create-a-Web-Page.md) and start learning.


<br />
<br />


## Basics

> Now that you should know how to create a HTML page, you can start learning HTML.

> If you start with a new HTML page, you always start with the following structure:

<!DOCTYPE html>
<html>
    <head>
        <title>My first html page</title>
    </head>
    <body>
        <h1>My first html page!</h1>
        <p>HTML is not a programming language</p>
    </body>
</html>

> - The `<!DOCTYPE html>` tag is used to define the type of document. It is always the first tag in the HTML file.
> - The `<html>` tag is used to define the start of the HTML document. It is always the second tag in the HTML file.
> - The `<head>` tag is used to define the start of the head section. In this section, you can add meta data, links to stylesheets, and scripts.
> - The `<title>` tag is used to define the title of the page.
> - The `<body>` tag is used to define the start of the body section. In this section, you can add content.
> - The `<h1>` tag is used to define the start of the heading.
> - The `<p>` tag is used to define the start of the paragraph.


<br />
<br />


## Elements

> An HTML element is a piece of HTML that is used to create a web page.  A HTML element consists of a tag and some content.

Code:

```
<h1>Content</h1>
```

Output:

<h1>Content</h1>

> Some HTML elements don't have content and don't have a closing tag. This is Elements are called empty elements.

Code:

```
<br>
```

(The `<br>` tag, produces a line break in text.)


<br />
<br />


## Attributes

> An HTML attribute is a piece of information that is associated with an HTML element. It provide additional information about the element. An Attribute is always in the start tag.

<br />

### The src Attribute

> The `src` attribute is used to define the source of the image. There are two possible src attributes. The Absolute and the Relative. The Absolute attribute links to an external image (Not on your filesystem). The Relative attribute links to an image in the same directory (In your filesystem).

Code:

```
<img src="Image.png">
```

<br />

#### Absolute Attribute

Code:

```
<img src="http://www.example.com/Image.png">
```

<br />

#### Relative Attribute

Code:

```
<img src="/HTML/Images/Image.png">
```

<br />

### The href Attribute

> The `href` attribute is used to link to another page. The `<a>` tag is used to create a hyperlink.

Code:

```
<a href="http://www.example.com">This link links you to the example.com Website</a>
```

Output:

<a href="http://www.example.com">This link links you to the example.com Website</a>

<br />

### The Alt Attribute

> The `alt` requires the `<img>` tag. The `Alt` attribute is used to display an alternate text for an image, if the image cannot be displayed. If the image cant be displayed the user can see the text and know what image should be displayed instead. The user cna also hover over the image and see the text.

Code:

```
<img src="Image.png" alt="This is an image">
```

Output:

<img src="Image.png" alt="This is an image">

<br />

### CSS Attributes

> The CSS Attributes can also be set in a CSS file. For better viseibility, you should use the a specific CSS file.

<br />

#### The width and height Attributes

> The width and the height Attributes set the width and height of an image.

Code:

```
<img src="Image.png" width="200" height="200">
```

<br />

#### The style Attribute

> The style Attribute is used to add styles to an element. For exaple color, size, font, etc.

Code:

```
<p style="color:red; font-size:20px;">This is a red text</p>
```

Output:

<p style="color:red; font-size:20px;">This is a red text</p>


<br />
<br />


## Headings

> Headings are used to display the title of a page or subtitles. The `<h1>` tag is used to define the start of the heading. There are 6 different headings. The `<h1>` tag is used for the largest heading. The `<h6>` tag is used for the smallest heading.

> Why do we use headings? Search engines use headings to index the content of a page. Headings are also used to separate sections of a page.

Code:

```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

Output:

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>


<br />
<br />


## Paragraphs

> HTML Paragraphs are used to create paragraphs. The `<p>` tag is used to define the start of the paragraph.

Code:

```
<p>This is a paragraph</p>
```

Output:

<p>This is a paragraph</p>


<br />
<br />


## Styles

> The style Attribute is used to add styles to an element. For exaple color, size, font, etc.

> You should use the style Attributes just for small style changes. For example, if you want to change the color of a text, you should use the style Attribute. If you want to style a whole section of a page, you should use a CSS file.

> The style Attribute is played in the start tag. The style Attribute has the following format:

Code:

```
<tagname style="property:value;">
```

<br />

### Text Color

> You can change the color of a text element. With the `color:yourcolor` attribute.

Code:

```
<p style="color:red;">This is a red text</p>
```

<br />

### Background Color

> You can change the background color. With the `background-color:yourcolor` attribute.

Code:

```
<p style="background-color:red;">This is a red text</p>
```

<br />

### Font

> You can change the font. With the `font-family:yourfont` attribute.

Code:

```
<p style="font-family:Arial;">This is a Arial text</p>
```

<br />

### Text Size

> You can change the size of a text. With the `font-size:yourtextsize` attribute.

Code:

```
<p style="font-size:20px;">This is a 20px text</p>
```


<br />


## Formatting Text
<br />

> You can change the format of a text for a specific purpose.

> For example: <b>, <strong>, <i>, <em>, <mark>, <small>, <del>, <ins>, <sub>, <sup>.

<br />

### `<b>` and `<strong>` Element

> The `<b>` and `<strong>` element is used to make text bold.

Code:

```
<b>This text is bold</b>

or

<strong>This text is bold</strong
```

Output:

<b>This text is bold</b>

or

<strong>This text is bold</strong>

<br />

### `<i>` and `<em>` Element

> The `<i>` and `<em>` element is used to make text italic.

Code:

```
<i>This text is italic</i>

or

<em>This text is italic</em>
```

Output:

<i>This text is italic</i>

or

<em>This text is italic</em>

<br />

### `<mark>` Element

> The `<mark>` element is used to mark text.

Code:

```
<mark>This text is mark</mark>
```

Output:

<mark>This text is mark</mark>

<br />

### `<small>` Element

> The `<small>` element is used to make text smaller.

Code:

```
<small>This text is small</small>
```

Output:

<small>This text is small</small>

<br />

### `<del>` Element

> The `<del>` element is used to mark deleted text.

Code:

```
<del>This text is strikethrough</del>
```

Output:

<del>This text is strikethrough</del>

<br />

### `<ins>` Element

> The `<ins>` element is used to mark inserted text.

Code:

```
<ins>This text is inserted</ins>
```

Output:

<ins>This text is inserted</ins>

<br />

### `<sub>` Element

> The `<sub>` element is used to mark subscripted text.

Code:

```
<sub>This text is subscripted</sub>
```

Output:

<sub>This text is subscripted</sub>

<br />

### `<sup>` Element

> The `<sup>` element is used to mark superscripted text.

Code:

```
<sup>This text is superscripted</sup>
```

Output:

<sup>This text is superscripted</sup>


<br />
<br />


## Colors

> You can change the color of an element with predefined colors name, with RGB, HEX, HSL, RGBA or HSLA.

<br />

### Color Name

> You can specify a color by using there name.

Code:

```
<p style="color:red;">This is a red text</p>
```

<br />

### RGB

> You can specify a color by using RGB.

Code:

```
<p style="color:rgb(255,0,0);">This is a red text</p>
```

<br />

### HEX

> You can specify a color by using HEX.

Code:

```
<p style="color:#ff0000;">This is a red text</p>
```

<br />

### HSL

> You can specify a color by using HSL.

Code:

```
<p style="color:hsl(0,100%,50%);">This is a red text</p>
```

> You can specify a color by using RGBA.

Code:

```
<p style="color:rgba(255,0,0,0.5);">This is a red text</p>
```

<br />

### HSLA

> You can specify a color by using HSLA.

Code:

```
<p style="color:hsla(0,100%,50%,0.5);">This is a red text</p>
```


<br />


## Tables
<br />

> Tables are used to display data in a structured way.

Code:

```
<!DOCTYPE html>
<html>
<head>
</head>
<body>

<h2>Table</h2>

<table>
  <tr>
    <th>Name</th>
    <th>Email</th>
    <th>Phone Number</th>
  </tr>
  <tr>
    <td>Simon</td>
    <td>simon@gmail.com</td>
    <td>1112223333</td>
  </tr>
  <tr>
    <td>Daniel</td>
    <td>daniel@gmail.com</td>
    <td>4445556666</td>
  </tr>
  <tr>
    <td>Markus</td>
    <td>markus@gmail.com</td>
    <td>7778889999</td>
  </tr>
</table>

</body>
</html>
```

Output:

<!DOCTYPE html>
<html>
<head>
</head>
<body>

<h2>Table</h2>

<table>
  <tr>
    <th>Name</th>
    <th>Email</th>
    <th>Phone Number</th>
  </tr>
  <tr>
    <td>Simon</td>
    <td>simon@gmail.com</td>
    <td>1112223333</td>
  </tr>
  <tr>
    <td>Daniel</td>
    <td>daniel@gmail.com</td>
    <td>4445556666</td>
  </tr>
  <tr>
    <td>Markus</td>
    <td>markus@gmail.com</td>
    <td>7778889999</td>
  </tr>
</table>

</body>
</html>


<br />


## Lists
<br />

> Lists are used to display data in a structured way. Lists can be ordered or unordered.

Code:

```
<!DOCTYPE html>
<html>
<body>

<h2>List</h2>

<ul>
  <li>1. Task</li>
  <li>2. Task</li>
  <li>3. Task</li>
</ul>  

</body>
</html>
```

Output:

<!DOCTYPE html>
<html>
<body>

<h2>List</h2>

<ul>
  <li>1. Task</li>
  <li>2. Task</li>
  <li>3. Task</li>
</ul>  

</body>
</html>


<br />
<br />


## Comments

> Comments are used to add notes to a page. Comments are not displayed in the browser.

Code:

```
<!-- This is a comment -->
```


<br />
<br />


## Head

> The `<head>` element contains the head of the document.

> In the head, you can add meta tags, links, etc.

Code:

```
<!DOCTYPE html>
<html>
    <head>
        <p>This is the header.</p> 
    </head>
    <body>
    </body>
</html>
```

<br />

### Title

> The title element contains the title of the document.

Code:

```
<!DOCTYPE html>
<html>
    <head>
        <title>This is the title.</title>
    </head>
    <body>
    </body>
</html>
```

<br />

### Meta Tags

> Meta tags are used to specify information about the HTML document.

<br />

#### Charset

> The charset attribute specifies the character of the document. This provides that there arent strange character in the text.

Code:

```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
    </head>
    <body>
    </body>
</html>
```

<br />

#### Viewport

> The viewport attribute specifies the size of the browser window.

Code:

```
<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
    </body>
</html>
```

<br />

### Links

> Links are used to link to other pages. For example your CSS file.

Code:

```
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="yourstyle.css">
    </head>
    <body>
    </body>
</html>
```