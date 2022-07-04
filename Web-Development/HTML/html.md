# HTML Tutorial

> In this tutorial, we will learn how to write HTML.


<br /><br />


## HTML Introduction

> HTML is a markup language used to create web pages. HTML describe the structure of a web page and the most inportant part, HTML is NOT a programming language.


<br /><br />


## Starting with HTML

> If you want to start with HTML, you should know the following: How to create a HTML page. If you didnt know how to do it yet, you are free to jump to [How to create a HTML page](/Web-Development/How-to-create-a-Web-Page.md) and start learning.


<br /><br />


## HTML Basics

> Now that you should know how to create a HTML page, you can start learning HTML.

<br />

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


## HTML Elements

> An HTML element is a piece of HTML that is used to create a web page.  A HTML element consists of a tag and some content.

Code:

```
<h1>Content</h1>
```

Output:

<h1>Content</h1>

> Some HTML elements dont have no content and don't have a closing tag. This is Elements are called empty elements.

Code:

```
<br>
```

Output:

<br>  

(The `<br>` tag, produces a line break in text.)


## HTML Attributes

> An HTML attribute is a piece of information that is associated with an HTML element. It provide additional information about the element. An Attribute is always in the start tag.

### The src Attribute

> The `src` attribute is used to define the source of the image. There are two possible src attributes. The Absolute and the Relative. The Absolute attribute links to an external image (Not on your filesystem). The Relative attribute links to an image in the same directory (In your filesystem).

Code:

```
<img src="Image.png">
```

Output:

<img src="Image.png">

#### Absolute Attribute

Code:

```
<img src="http://www.example.com/Image.png">
```

Output:

<img src="http://www.example.com/Image.png">

#### Relative Attribute

Code:

```
<img src="/HTML/Images/Image.png">
```


### The href Attribute

> The `href` attribute is used to link to another page. The `<a>` tag is used to create a hyperlink.

Code:

```
<a href="http://www.example.com">This link links you to the example.com Website</a>
```

Output:

<a href="http://www.example.com">This link links you to the example.com Website</a>

### The Alt Attribute

> The `alt` requires the `<img>` tag. The `Alt` attribute is used to display an alternate text for an image, if the image cannot be displayed. If the image cant be displayed the user can see the text and know what image should be displayed instead. The user cna also hover over the image and see the text.

Code:

```
<img src="Image.png" alt="This is an image">
```

Output:

<img src="Image.png" alt="This is an image">

### CSS Attributes

> The CSS Attributes can also be set in a CSS file. For better viseibility, you should use the a specific CSS file.

#### The width and height Attributes

> The width and the height Attributes set the width and height of an image.

Code:

```
<img src="Image.png" width="200" height="200">
```

Output:

<img src="Image.png" width="200" height="200">

#### The style Attribute



## HTML Headings

## HTML Paragraphs

## HTML Styles