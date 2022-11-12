# HTML
HTML:-

HyperText Markup Language.

---HTML is the standard markup language for creating Web pages

---HTML describes the structure of a Web page

---HTML consists of a series of elements

---HTML elements tell the browser how to display the content

---HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

e.g.,

<!DOCTYPE html>    -------- declares the document is an HTML5 document.
<html>             --------root element of HTML page
<head>             --------meta information of HTML page
<title>Page Title</title>  --title page for HTML page
</head>
<body>             -------defines documents body,all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.

<h1>My First Heading</h1>  ---heading
<p>My first paragraph.</p> ---paragraph

</body>
</html>

Q.HTML Elements.?

HTML element is defined by a start tag, some content, and an end tag:

syntax:-<tagname> Content</tagname>

e.g.,<h1>My First Heading</h1>

Nested elements:-HTML page contains nested elements like (<html>, <body>, <h1> and <p>):

Q.HTML Attributes.?

HTML attributes provide additional information about HTML elements.

---All HTML elements can have attributes

---Attributes provide additional information about elements

---Attributes are always specified in the start tag

---Attributes usually come in name/value pairs like: name="value"

a)Href attribute:-

The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link:

e.g.,<a href="https://www.w3schools.com">Visit W3Schools</a> 

b) Src attribute:-

The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:

e.g.,<img src="img_girl.jpg"> 

c) height and width attributes:-

The <img> tag should also contain the width and height attributes, which specify the width and height of the image (in pixels):

e.g.,<img src="img_girl.jpg" width="500" height="600">

d) alt attributes:-

The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.

e.g.,<img src="img_girl.jpg" alt="Girl with a jacket">

e)Style attribute:-

The style attribute is used to add styles to an element, such as color, font, size, and more.

e.g.,<p style="color:red;">This is a red paragraph.</p>

f)title attribute:-

The title attribute defines some extra information about an element.

e.g.,<p title="I'm a tooltip">This is a paragraph.</p>

Q.HTML Tags:-

HTML tags are like keywords which defines that how web browser will format and display the content. With the help of tags, a web browser can distinguish between an HTML content and a simple content. HTML tags contain three main parts: opening tag, content and closing tag. But some HTML tags are unclosed tags.

--All HTML tags must enclosed within < > these brackets.

--Every tag in HTML perform different tasks.

--If you have used an open tag <tag>, then you must use a close tag </tag> (except some tags)

syntax:-<tag> content </tag>

Q.Anchor tag:-

The HTML anchor tag defines a hyperlink that links one page to another page. It can create hyperlink to other web page as well as files, location, or any URL. The "href" attribute is the most important attribute of the HTML a tag. and which links to destination page or URL

href attribute of HTML anchor tag
The href attribute is used to define the address of the file to be linked. In other words, it points out the destination page.

<a href = "..........."> Link Text </a>

Q.HTML Lists.?

HTML Lists are used to specify lists of information. All lists may contain one or more list elements. There are three different types of HTML lists:

1.Ordered List or Numbered List (ol) --- displays elements in numbered format. 

2.Unordered List or Bulleted List (ul) ----displays elements in bulleted format

3.Description List or Definition List (dl) ---displays elements in definition form like in dictionary. 
