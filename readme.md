#HTML/CSS	 Fundamentals
-----
##The Big Picture
**HTML (HyperText Markup Language)** is the underlying structure for a web page. It's comparable to the human body in that it has a head and a body. Between the `<head></head>` tags is where we store information about the site, such as the title. Tags are the way we speak (or type, rather) HTML to the computer. Computers only understand a certain language if you use the proper [**syntax**](http://www.webopedia.com/TERM/S/syntax.html). Tags are part of the HTML syntax. You'll see plenty of them as we dig deeper.

After the `<head>` area of the document comes the `<body>`. The body tag also has a closing tag, closing tags are denoted by the forward slash that comes before the tag name, i.e., `</body>`. Almost all HTML tags will need a closing tag, although some do not, we'll cover those in more detail later on.

When we place content between opening and closing tags, we are **wrapping** the content with those tags, i.e., `<title>This is a Title</title>`. Here we have wrapped the title of the site "This is a Title" in opening and closing title tags.

Overall, HTML is plain looking, similar to a typical word document. This is where CSS comes in. We use **CSS (Cascading Style Sheets)** to make it look visually appealing, this process is referred to as **styling**. 
> CSS is designed primarily to enable the separation of document content from document presentation [(1)](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

Styling makes use of **selectors** to select an element from the page and give it some formatting. We'll explore CSS further, but first let's talk a little more about HTML. I'll be reviewing each of the elements from the following lists and demoing them so you can follow along visually.

Each of the items below is linked to its documentation on the [Mozilla Developer Network](https://developer.mozilla.org/en-US/) website. You may come across w3schools in your Google searches, although there is some good information on this website, it is typically looked down upon due to having outdated information and not always using best practices, try to use MDN over w3schools whenever possible, it helps to prefix your search with "mdn". This mainly applies to HTML, CSS, and JavaScript (JS) syntax searches, most everything else can be found elsewhere on Google or on [StackOverflow](http://stackoverflow.com/).

##HTML Skeleton
- [doctype](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5/Introduction_to_HTML5)
- [html](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/html)
- [head](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head)
- [body](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body)

##HTML Fundamental Elements
- [p](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p)
- [header](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header)
- [footer](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer)
- [h1-h6](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)
- [ul](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
- [li](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li)
- [div](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)
- [span](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span)

Great, you should now have a basic understanding of what it takes to build a web page in HTML. Now let's dive into what we need to make things look pretty.

##CSS Basics
- [id (#) vs class(.) and specificity](https://css-tricks.com/specifics-on-css-specificity/)
- [width px && %](https://developer.mozilla.org/en-US/docs/Web/CSS/width)
- [height px && %](https://developer.mozilla.org/en-US/docs/Web/CSS/height)
- [background-color](https://developer.mozilla.org/en-US/docs/Web/CSS/background-color)
- [background-image](https://developer.mozilla.org/en-US/docs/Web/CSS/background-image)
- [color](https://developer.mozilla.org/en-US/docs/Web/CSS/color)
- [font-size](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size)
- [text-align: center;](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align)
- [line-height](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height)
- [box-model (margin, padding, border)](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
- [float](https://developer.mozilla.org/en-US/docs/Web/CSS/float)
- [clear](https://developer.mozilla.org/en-US/docs/Web/CSS/clear)


##Connecting your CSS to your HTML Sheet 
- Inline CSS is possible, but it’s better to keep it external using the [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link) tag. This allows us to follow convention for separation of concerns or [SoC](https://en.wikipedia.org/wiki/Separation_of_concerns)
- Example of linking CSS: `<link href="styles.css" type="text/css">`

####Resources
-------------
[What is HTML](http://www.yourhtmlsource.com/starthere/whatishtml.html)

[What is HTML anyway?](http://www.goodellgroup.com/tutorial/chapter1.html)

[What is CSS](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_Started/What_is_CSS)

1. [CSS Definition](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)