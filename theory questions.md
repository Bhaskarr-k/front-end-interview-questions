# what is HTML?
- HTMl stands for hyper text markup langauge.it is a standared text formating for developing web pages released in 1993.
- HTML is a language that  is interpreted by browser and it tells the browser what to display and how to display.
- HTML is an importent language to learn if anyone wants to work in the development domain .
- HTMl introduced and developed by Tim Burners lee year of 1990.
# can we display a web page inside a web page or ls nesting web pages possible?
- yes we can display a web page inside another HTML web page. HTMl provides a tag **<iframe>** using which we can achieve this functionality.
- <iframe src = "url of the web page to embed">
# what are tags and attributed in HTML?
- tags are primary content of the HTML that defines how the content will be structured and formatted where as Attributes are used along with the HTML tags to define the charectristics of the element.
- for example <p align="center">interview questions</p> inthis align is the attribute using which we will align paragraph to show in the center of the view.
# what are void elements in HTML?
- HTMl elements which do not have closing tags or do not need to be closed are voied elements .
- for example <br/> ,<img/>, <hr/>
# what is the advantage of collapsing white space?
- in HTML a blank sequence of whitespace charecters is trated as a single space charecter, because the browser collaps multiple spaces into a single space charecter and this helps a developer to indent lines of text without worrying about multiple spaces and maintain readability and understandability of HTML codes.
# what are the HTML entities?
- in HTML some charecters are reverse like '<''>' etc. 
- to use rhese charecters in our web page we need to use the charecter entities called HTML entities.
- below a are few mapping between the reversed charecter and its respective entity charecter to be used.
- |charecter    |entity name     |   entity number  |
  |-------------|----------------|------------------|
  |   <         |  &less than;          |   &#60;          |
  |    >        |  &greater than  |    &#62;       |
  |&            |  &amp;        |     &#38;        |
# what are diffrent types of lists in HTML?
- in java script there are 3 types of lists
-  ordered list 
   unordered list 

   description list

## ordered list:
- An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.

- The list items will be marked with numbers by default:
## unorderd list:
- An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.

- The list items will be marked with bullets (small black circles) by default:

- Example:
- <ul>
     <li>Coffee</li>
     <li>Tea</li>
     <li>Milk</li>
- </ul>

## HTMl description list:
- HTML also supports description lists.

- A description list is a list of terms, with a description of each term.

- The <dl> tag defines the description list, the <dt> tag defines the term (name), and the <dd> tag describes each term:
- example:
- <dl>

    <dt>Coffee</dt>

    <dd>- black hot drink</dd>

    <dt>Milk</dt>

    <dd>- white cold drink</dd>

</dl>

# whar are the "class" attribute in html?
- the class attribute is used to specify the class name for an HTML element.
- multiple elements in HTML can have the same class value.
- also it is mainly use to assciate the styles wiritten in the stylesheet with the HTML elements.
#  what is the diffrence between the **id** attribute and the **class** attribute if HTML elements?
- multiple elements in HTML can have the same clas value, where as a value of id attribute of one element cannot be associated with another HTML element.
# define multiple form data?
- mulitpart form data is one of the values of the enctype attribute.
- 


