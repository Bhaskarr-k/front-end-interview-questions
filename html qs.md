

# What is HTML?
- HTML stands for hyper text markup langauge 
- it is used to create and structure web pages.
- it provides the basic framework for web content by using **elements(taga)** tags to define diffrent parts of a web page, such as **headings**,**paragraphs**,**links**,**images**.


# what is the diffrence between **id** and **class** in HTML?
## id:
- the id selector uses the id selector of an HTML element to select a specific element.
- the id of an element is unique wihtin a page, so the id selector is used to select one unique element.
- to select an element with a specific id, write a hash(#) charecter, followed by the id of the element.
- id name cannot start with a number
## class:
- the class selector selects HTML elements with a specific class attribute
- to select elements with a specific class, write a period(.) charecter followed by the class name.
### diffrence between class and id?
- **id** is unique, used for one element and **class** can be reused for multiple elements.
# what are the semantic HTML elements?
- A semantic element clearly describes its meaning to both browser and developer.
- semantic elements exact meaning of **elements with a meaning**
- EX: <img>,<table>,<article>,<section>
# how do you make a web page accessible?
- use semantic HTML
- Add alt to images
- use lables for form elements
- add aria attributes if neeeded
- ensure good heading structure
- use lang attribute
# what is the use of meta tags?
- the meta tags defines a metadata about an HTML documnet. metadata is data information about data
- meta tag always go inside the head element, and are typically used to specify charecter set, page description, keywords, author of the document, and viewpirt settings
- metadata will not be displayed on the page but is machine prasible
- metadata is used by browsers search engines keyowrds and other web services
- there is a method to let web designers take control over the viewport through the meta tag 
# what is the diffrence between section and div and article?
- the **article** element is an HTML element tag is used to a self contained piece of content that can be independently distributed or reused. 
- it is **typically used used for blog posts, news articles or user generated content**
- the **section** element is used to group related content together. it represents a thematic grouping of content within a document. it can be used to page into diffrent sections chapters, or tabbed content.
- the **div** element is a generic container used to group other HTML elements together. it does not carry any semantic menaing on its own, unlike article and secction and div is typically used for styling or manipulating content using css or javascript. 
# what is the diffrence betwen relative and absloute and fixed and sticky positioning?
- **static**: this is the defualt value all elements are in order as they appear in the doucment.
- **realtive**: this element is positioned relative to its normal position
- **absolute**: the lement is positioned absolutely to its first postioned parent
- **fixed**:the element is positioned relted to the browser window
- **sticky**: the element is postioned based on the users scrol position
# how does flexbox work? explain main concepts like justify content and align items?
- flexbox makes it easier to align , space, and distribute elements inside a **flex container** expecially when the size of the items is unknown or dynamic
## main concepts:
- justify content:
- align items:
- flex-direction:
- flex-wrap:
# what is the diffrence between em, rem, px,and %?
- **px**: fixed size: absolute unit, doesnt scale with svreen or parent size
- **em**: parent elements font size: relative to the size of the parent
- **rem**: root elements font size: relative to the root (html) font size
- **%parent element size**: used for width, height, padding 
# What is specificity in CSS and how is it calculated?
- specificity is the set of rules the browser uses to decide which css rule wins when multiple rules target the same element
- specifity is like 4 part score
- **a**: inline styles- highest priority
- **b**: id selectors- powerful
- **c**: class, attribute, pseudo class- medium
- **d**: element and pseudo elements- lowest
# how can you center a div both horizentally and vertically?


⚙️ JavaScript Questions
What is the difference between var, let, and const?

Explain event bubbling and event delegation.

What are arrow functions and how are they different from regular functions?

What are promises and async/await in JavaScript?

What is hoisting in JavaScript?


⚛️ React.js (if you're applying for React roles)
What are components in React? Difference between functional and class components?

What is the Virtual DOM and how does React use it?

What are props and state?

What are React hooks? Explain useState and useEffect.

How does conditional rendering work in React?






