

# What is HTML?
- HTML stands for hyper text markup langauge 
- it is used to create and structure web pages.
- it provides the basic framework for web content by using **elements(taga)** tags to define diffrent parts of a web page, such as **headings**,**paragraphs**,**links**,**images**.
- The first version of HTML was written by Tim Berners-Lee in 1993
# What are the different versions of HTML?
- HTML has evolved over time, introducing new features and improvements. Below are the major versions of HTML:

## HTML 1.0 (1993)
- The first official version of HTML.
- Very basic, supporting only simple elements like headings, paragraphs, and links.
- No styling or complex features.
## HTML 2.0 (1995)
- Standardized the basic features of HTML 1.0.
- 
- Still lacked support for complex layouts and styling.

## HTML 3.2 (1997)
- Introduced tables (<table>), image alignment, and JavaScript.
- First version officially supported by W3C.
- Introduced the font  tag for styling (now obsolete).

## HTML 4.01 (1999)
- Introduced CSS support for styling.
- Improved forms with new attributes.
- Allowed scripting languages like JavaScript.
- Provided three versions:
-**Strict**: No deprecated elements.
- **Transitional**: Allowed older elements.
- **Frameset**: Allowed the use of frameset for dividing web pages.
# XHTML (2000)
- A stricter version of HTML 4.01, following XML rules.
- Required properly nested tags and lowercase tag names.
- 
- More structured but less flexible than HTML.
## HTML5 (2014 - Present)
The latest and most powerful version of HTML.
Introduced:
Semantic elements (article, section, nav, header, footer, etc.).
Multimedia support (video, audio).
Canvas API for graphics and animations.
New form elements (date, email, number).
Better mobile compatibility and responsive design.
### Comparison of Key Features
- HTML 1.0	Basic text, images, and links
- HTML 2.0	Forms, basic tables
- HTML 3.2	Tables, scripting, improved images
- HTML 4.01	CSS support, scripting, better forms
- XHTML	Stricter syntax, follows XML
- HTML5	Multimedia, semantic tags, mobile-friendly

# What is the difference between HTML and HTML5?
### html:
- Requires third-party plugins (e.g., Flash)
- Uses external plugins (e.g., Flash, Silverlight)
- No dedicated semantic tags
- Requires JavaScript for validation
- Not mobile-friendly
- Limited support for APIs
- No built-in offline support
- Slower, requires additional plugins

### html5:
- Native support for audio and video elements
- Supports canvas and svg for graphics and animations
- Introduces new tags like header, footer, article, section for better structure
- Native support for validation (required, email, number, etc.)
- Designed for responsiveness and mobile compatibility
- Supports new APIs (Geolocation, Web Storage, WebSockets, etc.)
- Provides Web Storage & Cache API for offline use

# What are the key features of HTML5?
-  New semantic elements
- Multimedia suppport(Audio&Video)
- canvas&SVG for graphics
- improved form controls and validation
- web storage(loal&session storage)
- Geolocation API.
- Webstacks for real-time environment
- Responsive web design and mobile optimization
- offline web applications
# What is the structure of an HTML document?
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
    <link rel="stylesheet" href="styles.css"> <!-- External CSS -->
</head>

<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <main>
        <section>
            <h2>About Us</h2>
            <p>This is a simple HTML page structure.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>

    <script src="script.js"></script> <!-- External JavaScript -->
</body>

</html>


# What is the purpose of the <DOCTYPE> declaration?
- the doctype declaration in HTML specifies the Document definition that web page adhere to 
- it helps web browers determine how to render the page correctly.
### purpose of <doctype>:
- ensures the broswer renders the page in **standards mode** following modren web standards.
- without it browser may enter **quirks mode** where they attempt to nimic older non-standard behaviour for compatibility 
### defines the HTML version:
- specifies which verison of HTML the doucment followes.
- in modren web development <doctype> is use for HTML5

# What is the difference between block-level and inline elements?
- in HTML elements are categorized block level or inline based on how they behave in the document flow.
### block level elements:
- block level elements stsrt on a new line and take up the full width availble.
- always start on a anew line- take up the full width of the parent container
- can contain other block level or inline elements- respect height and wdith properties
- **common block level elements**
- <div>,<p>,<section><article><header>
### inline elements:
- inline elements od not start on a new line and only tke up as much width as necessary
- stay on the same line as surronding text for elements- take up only as much width as their ocntent requires
- cannot contain block level eelementes 
- heigh and width properties have no effect
- **common inline elements**
- <span><a><strong><em><img>
# What is the difference between <div> and <span>?
- both **div** and **span** are container elements in HTML but they serve diffrent purpose in structuring and styling content
### div:
- a div is a block level element use to group ohter elements together
- it takes up the full width of its container and starts on a new line
- commonly used folayout structturing and grouping related content.
### span:
- a span is an inline element use to wrap a portion of text or other inline elements for styling purposes
- it only takes up as much widht as its its conent requires

# What are HTML attributes?

- What is the difference between the <section>, <article>, and <div> elements?
- How do you create a hyperlink in HTML?
- What is the difference between absolute and relative URLs?
- What is the purpose of the <meta> tag?
- What is the difference between <strong> and <b>, and between <em> and <i>?
- What are semantic HTML elements? Give some examples.



- What are HTML forms and what are the different form elements?
- How do you create a table in HTML?
- What are the different input types in HTML5?
- What is the difference between id and class attributes?
- What is the alt attribute in the <img> tag used for?
- What is the difference between the <label> tag and the for attribute?
- What are the new form elements introduced in HTML5?
- What is the difference between localStorage, sessionStorage, and cookies?
- What is the purpose of the <canvas> and <svg> elements?
- What is the difference between <iframe>, <embed>, and <object>?
- What is the use of the data-* attribute in HTML5?
- How do you make an image responsive in HTML?
- How do you create a dropdown list in HTML?
- What is the difference between <ol>, <ul>, and <dl>?
- What is lazy loading in HTML? How do you implement it?
Advanced HTML Interview Questions
How does the browser render an HTML page?
What are web components?
What is the Shadow DOM?
What is the difference between the <template> and <slot> elements?
How can you improve HTML performance?
What is the difference between defer and async attributes in the <script> tag?
How does accessibility (ARIA) work in HTML?
How do you handle cross-browser compatibility in HTML?
What is Progressive Web App (PWA), and how does HTML contribute to it?
What are custom data attributes in HTML, and how can they be used in JavaScript?
What are microdata and structured data in HTML?
What is Content Security Policy (CSP) in HTML?
What is the role of autocomplete in form inputs?
What is the difference between <noscript> and <script>?
What are iframes, and what are the security concerns associated with them?


What are HTML forms and what are the different form elements?
How do you create a table in HTML?
What are the different input types in HTML5?
What is the difference between id and class attributes?
What is the alt attribute in the <img> tag used for?
What is the difference between the <label> tag and the for attribute?
What are the new form elements introduced in HTML5?
What is the difference between localStorage, sessionStorage, and cookies?
What is the purpose of the <canvas> and <svg> elements?
What is the difference between <iframe>, <embed>, and <object>?

What is the difference between <iframe>, <embed>, and <object>?
What is the use of the data-* attribute in HTML5?
How do you make an image responsive in HTML?
How do you create a dropdown list in HTML?
What is the difference between <ol>, <ul>, and <dl>?
What is lazy loading in HTML? How do you implement it?