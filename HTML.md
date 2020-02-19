## introduction
**How People Access the Web ?**
Before we look at the code used to build websites it is important to consider the different ways in which people access the web and clarify some terminology.
1. Browsers
2. Web Servers
3. Screen readers
4. Devices

**How Websites Are Created ?**
All websites use HTML and CSS, but content management systems, blogging software, and e-commerce platforms often add a few more technologies into the mix.

**How the Web Works?**
When you visit a website, the web server hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server.

## CH. 1 structure
**How Pages Use Structure**
Think about the stories you read in a newspaper: for each story, there will be a headline, some text, and possibly some images. If the article is a long piece, there may be subheadings that split the story into separate sections or quotes from those involved. The structure is very similar when a news story is viewed online.

**Structuring Word Documents**
The use of headings and subheadings in any document often reflects a hierarchy of information. For example, a document might start with a large heading, followed by an introduction or the most important information.

**HTML Describes the Structure of Pages**
To describe the structure of a web page, we add code to the words we want to appear on the page.

**HTML Uses Elements to Describe the Structure of Pages**
Each element has an opening tag and a closing tag.
Tags act like containers. They tell you something about the information that lies between their opening and closing tags.

**Attributes Tell Us More About Elements**
Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.

**Body, Head & Title**
`<body>`
Everything inside this element is shown inside the main browser
window.
`<head>`
Before the `<body>` element you will often see a `<head>` element.
This contains information about the page (rather than
information that is shown within the main part of the browser window that is highlighted in blue on the opposite page).
You will usually find a `<title>` element inside the `<head>`element.
`<title>`
The contents of the `<title>` element are either shown in the
top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page.


## Ch. 8 extra markup

**The Evolution of HTML**
Since the web was first created, there have been several different versions of HTML.
- HT ML 4 Released 1997.
- XHT ML 1.0 Released 2000.
- HT ML5 Released 2000.
In order to help web page authors move to this new syntax, two main flavors of XHTML 1.0 were created:
1. Strict XHTML 1.0, where authors had to follow the rules
to the letter.
2. Transitional XHTML 1.0, where authors could still use presentational elements (such as <center> and <font>).

**Comments in HTML**
If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters:
`<!-- comment goes here -->`.

**ID Attribute**
Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character). It is important that no two elements on the same page have the same value for their id attributes.

**Class Attribute**
Every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a document, you will want a
way to identify several elements as being different from the other elements on the page.

**Block Elements**
Some elements will always appear to start on a new line in the browser window. These are known as block level elements.
Examples of block elements are
`<h1>`, `<p>`, `<ul>`, and `<li>`.

**Inline Elements**
Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements.
Examples of inline elements are
`<a>`,`<b>`, `<em>`, and `<img>`.

**Grouping Text & Elements In a Block**
The `<div>` element allows you to group a set of elements together
in one block-level box.
In a browser, the contents of the `<div>` element will start on a new line, but other than this it will make no difference to the presentation of the page.

**Grouping Text & Elements Inline**
The `<span>` element acts like an inline equivalent of the `<div>`
element. It is used to either:
1. Contain a section of text where there is no other suitable
element to differentiate it from its surrounding text.
2. Contain a number of inline elements.
You will usually see that a class or id attribute is used with
`<span>` elements:
- To explain the purpose of this `<span>` element
- So that CSS styles can be applied to elements that have specific      
  values for these attributes.

**IFrames**
An iframe is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame.
One common use of iframes is to embed a Google Map into a page. The
content of the iframe can be any html page.
An iframe is created using the
`<iframe>` element. There are a few attributes that you will need to know to use it:
`src`
The src attribute specifies the URL of the page to show in the frame.
`height` 
The height attribute specifies the height of the iframe in pixels.
`width`
The width attribute specifies the width of the iframe in pixels.

**Information About Your Pages**
The `<meta>` element lives inside the `<head>` element and contains information about that web page. It is not visible to users but fulfills a number of purposes such as telling search engines about your page, who created it, and whether or not it is time sensitive. The `<meta>` element is an empty element so it does not have a closing tag. It uses attributes to carry the information. The most common attributes are the name and content attributes, which tend to be used together.

Some defined values for this attribute that are commonly
used are:
_description_
This contains a description of the page. This description is commonly used by search engines to understand what the page is about.
_keywords_
This contains a list of comma separated words that a user might search on to find the page.
_robots_
This indicates whether search engines should add this page to their search results or not.
_author_
This defines the author of the web page.
_pragma_
This prevents the browser from caching the page.
_expires_
Because browsers often cache the content of a page, the expires option can be used to indicate when the page should expire (and no longer be
cached).

## CH. 17 HTML5 layout
**Traditional HTML Layouts**
For a long time, web page authors used `<div>` elements to group together related elements on the page (such as the elements that form a header, an article, footer or sidebar). Authors used class or id attributes to indicate the role of the `<div>` element in the structure of the page.

**New Html 5 Layout Elements**
HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them. They are still subject to change, but that has not stopped many web page authors using them already.


**Headers & Footers**
The `<header>` and `<footer>` elements can be used for:
1. The main header or footer that appears at the top or bottom of every page on the site.
2. A header or footer for an individual `<article>` or `<section>` within the page.

**Navigation**
The `<nav>` element is used to contain the major navigational blocks on the site such as the primary site navigation.

**Articles**
The `<article>` element acts as a container for any section of a page that could stand alone and potentially be syndicated. This could be an individual article or blog entry, a comment or forum post, or any other
independent piece of content. If a page contains several articles
(or even summaries of several articles), then each individual article would live inside its own `<article>` element. The `<article>` elements can even be nested inside each other.

**Asides**
The `<aside>` element has two purposes, depending on whether it is inside an `<article>` element or not. When the `<aside>` element is used inside an `<article>` element, it should contain information that is related to the article but not essential to its overall meaning.
When the `<aside>` element is used outside of an `<article>` element, it acts as a container for content that is related to the entire page.

**Sections**
The `<section>` element groups related content together, and typically each section would have its own heading. Because the `<section>` element
groups related items together, it may contain several distinct
`<article>` elements that have a common theme or purpose. Alternatively, if you have a page with a long article, the `<section>` element can be used to split the article up into separate sections.

**Heading Groups**
The purpose of the `<hgroup>` element is to group together a set of one or more `<h1>` through `<h6>` elements so that they are treated as one single heading.

**Figures**
It can be used to contain any content that is referenced from the main flow of an article (not just images).The `<figure>` element should also contain a `<figcaption>` element which provides a text decription for the content of the `<figure>` element.

**Sectioning Elements**
the `<div>` element will remain an important way to group together related elements, because you should not be using these new elements that you have just met for purposes other than those explicitly stated.
Where there is no suitable element to group a set of elements, the `<div>` element will still be used. In this example, it is used as a wrapper for the entire page.

**Linking Around Block-Level Elements**
HTML5 allows web page authors to place an `<a>` element around a block level element that contains child elements. This allows you to turn an entire block into a link. This is not a new element in HTML5, but it was not seen as a correct usage of the `<a>` element in earlier versions of HTML.

**Helping Older Browsers Understand**
Older browsers that do not know the new HTML5 elements will automatically treat them as inline elements. Therefore, to help older browsers, you should include the line of CSS on the left which states which new elements should be rendered as block-level elements.


## CH. 18 process & design
**Who is the Site For?**
Every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is.

**Why People Visit YOUR Website**
Now that you know who your visitors are, you need to consider why they are coming. While some people will simply chance across your website, most will visit for a specific reason.
Your content and design should be influenced by the goals of your users.

**What Your Visitors are Trying to Achieve**
It is unlikely that you will be able to list every reason why someone visits your site but you are looking for key tasks and motivations. This
information can help guide your site designs.

**What Information Your Visitors Need**
You know who is coming to your site and why they are coming, so now you need to work out what information they need in order to achieve their goals quickly and effectively.

**How Of ten People Will Visit Your Site**
Some sites benefit from being updated more frequently than others. Some information (such as news) may be constantly changing, while other content remains relatively static.

**Site Maps**
Now that you know what needs to appear on your site, you can start to organize the information into sections or pages.
The aim is to create a diagram of the pages that will be used to structure the site. This is known as a _site map_ and it will show how those pages can be grouped. To help you decide what information should go on each page, you can use a technique called _card sorting_.

**WireFrames**
A wireframe is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.

**Getting your message across using design**
The primary aim of any kind of visual design is to communicate. Organizing and prioritizing information on a page helps users understand
its importance and what order to read it in.
- content.
- Prioritizing.
- organizing.
- visual hierarchy.
- grouping.
- similarity.

**Visual hierarchy**
Most web users do not read entire pages. Rather, they skim to find
information. You can use contrast to create a visual hierarchy that gets
across your key message and helps users find what they are looking for.
- size.
- color. 
- style.
Visual hierarchy refers to the order in which your eyes perceive what
they see. It is created by adding visual contrast between the items being displayed. Items with higher contrast are recognized and processed first.
- Images
Images create a high visual contrast and often attract the eye first. They can be used to draw attention to a specific message within the page.

**grouping and Similarity**
When making sense of a design, we tend to organize visual elements
into groups. Grouping related pieces of information together can make a
design easier to comprehend. Here are some ways this can be achieved.
- proximity.
- closure.
- Continuance.
- White Space.
- color.
- borders.
- Consistency.
- headings.

**Designing Navigation**
Site navigation not only helps people find where they want to go, but also helps them understand what your site is about and how it is organized. Good navigation tends to follow these principles:
- Concise.
- clear.
- Selective.
- context.
- Interactive.
- Consistent.