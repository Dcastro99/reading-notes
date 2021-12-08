# **Basics of HTML, CSS & JS**

>## *Chapter 2: “Text”*

### Headings & Paragraphs

- There are 6 sizes of headings lable as < H1> through < H6> and they will appearform largest to smallest.
- to build paragraphs we place them in < p> and < /p> the actual paragraph will live within these tags

### Bold, italic, & emphasis

- To bold a word or statement you can place them between < b> and < /b> tags

- For words to appear italic we place them in < i> and < /i>

- < br /> allows you to break lines inside a paragraph

- < hr /> creates a line that'll separate two lines

- < em> makes a word stand out which usually looks italic

>## Chapter 10 “Introducing CSS”

- CSS styles the HTML file. You can attach CSS in two differnt ways.  you can use a < link> tag to tell the browser where to find the CSS file used on the page. A < link> will always have a *herf* a *type* and a *rel*  

- You can also include CSS within the page and that mean you'd use a < style> tag. This will sit inside the < head>. You can use < style> attribute on most elements.
*ex* <b>< p style" = color:blue;">

- CSS cascades so it will read top to bottome of the page. If two selectors are the same it'll use the last.

>## Chapter 2 "Basic JavaScript instructions"

- JavaScript is fucntions that become interative in a webpage. These functions are called statements. 

- *Variable* = is a place where a script can storre temporary information.

- *let* delares the variable

- *variable name* is the identifier of the variable.
*ex* (let UserName = ) (*let*) will be the variable key word (*UscerName*) will be the variable name. Followed by a variable value.

- <u>Data types:</u> *numeric*, *string*, *boolean*. These are three examples of data type. 
  - Numeric: use of numers
  - string: use of letters or charaters
  - boolean: value is true/false
- overall it allows interation between the user and the website. An example would be when you input your name in a feild. Thats a javaScript code.

>## Chapter 4 "Decisions and Loops"

- ### *Comparisson operators*

  - == (is equal to)
  - != (is NOT equal to)
  - === (Strict equal to)
  - !== (strict NOT equal to)
  - <u><</u> (less than)
  - <u>></u> (greater than)
  - <u>>=</u> (Greater than or equal to)
  -<u><=</u> (less than or equal to)

-if & if else statements are fun since they have different outcomes depending on whats inputted.
*ex* if (number >= 5){answer("too high, try again")}
else { answer ("that's correct!")}