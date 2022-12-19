NESTED ORDERED AND UNORDERED LIST:

An ordered list is a list of items in which the order of the items is significant. Ordered lists are usually represented with numbers or letters.

An unordered list is a list of items in which the order of the items is not significant. Unordered lists are usually represented with bullet points.

We can nest an ordered or unordered list inside another ordered or unordered list by using the appropriate HTML tags. 

--> ordered list (ol) would create a list with the following structure:

1.Item 1
2.Item 2
3.Subitem 1
4.Subitem 2
5.Item 3

We can nest unordered lists in the same way, using the <ul> tag instead of the <ol> tag.

It's also possible to nest an ordered list inside an unordered list, or vice versa.

-->Unordered list (ul) would create a list with the following structure:

.Item 1
.Item 2
    .Subitem 1
    .Subitem 2
.Item 3

--------------------------------------------------------------------------------------------------------------------------------

SEMANTICS TAGS:

Semantic tags are HTML tags that provide meaning to the content they enclose. They are used to structure and organize the content of a webpage, making it easier for humans and machines to understand. These tags can help search engines and assistive technologies understand the structure and content of your web page, which can improve accessibility and SEO.

There are several semantic tags that can be used to create the layout of a webpage, including:

<header>: This tag represents the header of a webpage or section of content. It is typically used to contain the site logo, navigation menu, and other elements that are common to the top of all pages.

<nav>: This tag represents a section of the webpage that contains navigation links.

<main>: This tag represents the main content of the webpage.

<article>: This tag represents a standalone piece of content, such as a blog post or news article.

<section>: This tag represents a generic section of content within the webpage.

<aside>: This tag represents content that is tangentially related to the main content of the webpage, such as a sidebar.

<footer>: This tag represents the footer of a webpage or section of content. It is typically used to contain copyright information, contact details, and other elements that are common to the bottom of all pages.

By using these semantic tags, you can create a clear and well-structured layout for your webpage. This makes it easier for users to understand and navigate the content, and also helps search engines understand the content and its relationships to other pages on the web.

--------------------------------------------------------------------------------------------------------

TEXT FORMATTING TAGS:

There are several HTML tags that can be used to format text on a webpage. Some common text formatting tags include:

<strong>: This tag makes the enclosed text bold.

<em>: This tag emphasizes the enclosed text by rendering it in italics.

<sup>: This tag renders the enclosed text as superscript (smaller text that is slightly raised above the line).

<sub>: This tag renders the enclosed text as subscript (smaller text that is slightly lowered below the line).

<mark>: This tag highlights the enclosed text.

<del>: This tag strikes through the enclosed text.

<code>: This tag is used to represent a piece of code. It typically renders the text in a monospaced font and preserves whitespace.

<pre>: This tag is used to represent preformatted text. It preserves whitespace and typically renders the text in a monospaced font.

Here is an example of how these tags can be used:

--> <p>This is a <strong>bold</strong> paragraph. This is an <em>emphasized</em> paragraph. This is a <sup>superscript</sup> paragraph. This is a <sub>subscript</sub> paragraph. This is a <mark>highlighted</mark> paragraph. This is a <del>deleted</del> paragraph. This is a <code>code</code> paragraph. This is a <pre>preformatted</pre> paragraph.</p>

--------------------------------------------------------------------------------------------------------------
IMAGE, AUDIO AND VIDEO

To add images, audio, and video to an HTML page, you can use the following tags:

<img>: displays an image on the page
<audio>: plays an audio file on the page
<video>: plays a video file on the page
Here is an example of how you can use these tags:


<!-- Display an image -->
<img src="image.jpg" alt="A description of the image">

<!-- Play an audio file -->
<audio src="audio.mp3"></audio>

<!-- Play a video file -->
<video src="video.mp4"></video>
The src attribute specifies the location of the file, and the alt attribute provides a text description of the image for users who are unable to see it.

You can also use the controls attribute to add controls to the audio and video elements, allowing users to play, pause, and adjust the volume.


<audio src="audio.mp3" controls></audio>
<video src="video.mp4" controls></video>