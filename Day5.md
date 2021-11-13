# Day 5 notes

## CSS

> - What is CSS

*CSS is a program that stylises HTML asthetically. The simple way of seeing it is CSS is like an **interir designer** choosing what paint, furniture, layout scheme, and everything else.*

*It allows you for personalize the wireframe of HTML to create a front-end page like Google or similar.*

> - How it works?

### 6 - Steps
1. *The browser will load the HTML*
2. *It converts the HTML into a DOM (Document Object Model). The DOM represents the document in the computer's memory.* 
3. * *The browser then fetches most of the resources that are linked to by the HTML document, such as embedded images and videos*
4. *The browser parses the fetched CSS, and sorts the different rules by their selector types into different "buckets", e.g. element, class, ID, and so on. Based on the selectors it finds, it works out which rules should be applied to which nodes in the DOM, and attaches style to them as required (this intermediate step is called a render tree).*
5. *The render tree is laid out in the structure it should appear in after the rules have been applied to it.*
6. *The visual display of the page is shown on the screen (this stage is called painting).*