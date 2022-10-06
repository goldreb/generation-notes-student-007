# What is HTML

..._HyperText Markup Language_ 
...tells the browsers how to structure the web pages you visit.

### Element 
- is part of a webpage
- may contain a data item or a chunk of text or an image
- typical element includes an opening tag with some **attribute**, enclosed text content, and a closing tag

### Element Anatomy
![Element Anatomy](/HTML/html_img/anatomy_element.jpg)



| Anatomy of Element Explanation |                              |     |
| ---                            |---                           |---  |
| `opening tag`                  | consist of the name of the element | `(ex. <p>, <h1>)`|
| `content tag`                  | the content of the element      |    |
| `closing tag`                  | same as opening tag except it includes forward slash before the element      |    ` (ex. </p>. </h1>) ` |


### Nested Elements
- elements that can be nested inside another element 
`(ex. <p><strong>**nested**</strong></p>) `
### Empty Elements
- elements with no content.
- consist of a single tag  
` (ex. <br>, <img>, <meta>, <link>) `

### Attributes
- contain information about the element that won't appear in the content.
![attribute image](/HTML/html_img/anatome_attribute.jpg)

` An attribute should have:`
- space between it and the element name. 
- attribute name followed by equal sign.
- wrapped with opening and closing qoutatin marks 

## HTML Structure
![html structure](/HTML/html_img/html_structure.jpg)

> `<!DOCTYPE>` - doctype is needed in the HTML for everything else to work. 

> `<html></html>` - this element wraps all the content on the page.

> `<head></head>` - acts as a container for everything you want to include on the HTML page.

> `<meta charset="utf-8">` - represents metadata that cannot be represented by other HTML meta related elements. `charset` attributes sets the character set for your document to UTF-8, which inlcudes most characters from the vas majority of human written language.

> `<title></title>` - sets the title of the page, it will appear in the browser tab.

> `<body></body>` - contains all the content that display on the page.

