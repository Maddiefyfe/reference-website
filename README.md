# reference-website
1.	Naming convention for all filenames, paths and folders
2.	Best practices for commit messages
3.	What is HTML?
HTML stand for Hypertext Markup Language and is used to depict the content of websites. It contains three main sections, the head, body, and footer. HTML contains several elements, and these elements are used to properly display a website. Each separate web page has its own HTML file, for example, an About, Contact, and Main page of a website would each have their own HTML file. 
4.	Proper syntax for HTML tags
Each tag used to define the purpose of the text that’s inside of it follow a particular syntax. It begins with an opening tag, which is also the tag name, and ends with a close tag. For example, a paragraph tag would look like <p> </p> (the slash indicates that it is a closing tag). The element content, or the words viewed on screen, is placed inside the tags. These 3 factors make up the element. 
5.	Explain or demonstrate commonly used html tags/elements:

headings: h1-h6 - 

Headings are used to mark headings according to their importance. h1 is most important, and only one can be contained within an HTML file. h6 is the least important, and the smallest. 

p - 
p is a paragraph tag, and paragraphs must always start on a new line. 

lists: ul, ol, dl - 
ul stand for unordered list, ol stands for ordered list, and dl stands for description list. ul and ol contain li, or list items, and dl contains both dt (term or name) and dd (description of term). HTML configures these lists and gives them certain properties which can be altered using CSS. 

a - 
a is an anchor element. The opening a indicates where a link starts, and the closing a indicates where a link ends, meaning it creates a hyperlink. It must also contain a href attribute, meaning its value will equal a URL. 

img - 
img is an image tag. Images are not embedded in a website, rather are linked to by the HTML document. An img tag must also contain “alt” or an alternative tag which indicates the contents of the image, or what it is depicting. 

figure (img & figcaption) - 
Both an img and figcaption can be placed within a figure. The img tag is used as how it is described above, and the figcaption tag is used to lay a caption over the image as it is displayed on the website. 

q - 
q is used to mark quotations found within other elements, such as a paragraph tag. 

blockquote - 
blockquote is used to indicate large, stand-alone quotes. It may be placed within a figure tag.

cite - 
A cite tag marks the source of a quotation. 

em - 
em is a phrasing element that adds emphasis to text. They are typically italic. 

strong - 
strong is used to add a lot of emphasis to a text and declares it to be of strong importance or urgency. They are typically given a bold font weight.

b - 
b is a keyword. It is used to make a term boldfaced but is not given any special or urgent importance. 

i - 
i is used to indicate another language, technical term, or title. It is used to describe semantics.

small - 
small is used to make certain letters, words, or sentences smaller compared to the surrounding text.

6. Explain block Elements and also explain the list of block elements and why they are used from below:

html - 
html is used to represent the root of an HTML document. All other elements must be contained within the <html> tag, as it is the bases for the entire webpage. 
  
head - 
head is an element that contains metadata about the HTML document. This can include the title, language, stylesheets, and default fonts. 
  
body -
body is used to contain all content of an HTML document. There can only one body tag used per HTML page. 
  
header - 
header is used to contain all introductory content. It is usually at the top of the page, and can contain navigation, logo, or company name. They can also be placed within sections or articles in an HTML document to introduce the content contained within them. 
  
nav - 
nav is used to provide navigation links to content that is either inside the current HTML document or to other pages. 
  
main - 
The main tag is used to indicate the main content of a page. It may only be used once per page, and it tells the browser exactly where the main content is located. 
  
section - 
The section tag is used to indicate a part of the document that is related. It contains related content within itself, and usually also contains a heading. 
  
article
An article tag is similar to a section tag in that it contains related content, however, it is used to represent self-contained items on an HTML document. Meaning, it can be independently distributed or reused. (ex. Blog post, magazine article, etc.). 
  
div - 
div is a block element that groups elements together. It has no affect on layout until it is styled using CSS. 
  
aside - 
aside is used to group content that is only indirectly linked to the main content on an HTML document. It may frequently be presented as a sidebar on a website. 
  
footer - 
A footer tag is located at the bottom of an HTML document. It may contain copyright information, terms and services, etc. 
  
span - 
span is an inline element that is used to markup part of a text or part of the document. 
  
small - 
small is used to make certain letters, words, or sentences smaller compared to the surrounding text.

7. Explain why accessibility is important and also explain the accessibility properties like:
  
Accessibility is an extremely important factor to keep in mind when creating and designing and HTML document. As the internet has become a major aspect of billions of people lives, it is essential that it can be used by any person, regardless of their disabilities. By making a website accessible, it ensures that all users have an easy experience using and accessing any information found on the website. 
  
landmark roles
  
ARIA, (Accessible Rich Internet Application) is a specification laid out by the Web Accessibility Initiative. ARIA has a set of landmark roles that help users who use screen readers easily find and jump to content within the webpage. These landmark roles include:
  
header role= “banner”
  
Added to the primary header to indicate the element as the masthead. 
  
nav role= “navigation”
  
Added to the top nav link to indicate the element is the primary navigation.
  
main role= “main”
  
Added to the main section in HTML, defines the content within to be the main section of the page.
  
aside role= “complimentary”
  
Added to an aside to indicate the content is related to the main content.
  
footer role= “contentinfo”
  
Added to the footer element to define it as information about the main content.

aria labels - 
  
aria labels provide the user with a non-visible label that will only be announced by screen readers. These labels are added to links to describe to the user what they will be clicking on. 
  
image alternative texts - 
  
The alt attribution allows the web developer to add description to images that are not visible on the completed webpage. This text will be read by a screen reader to describe to the user what the image depicts. 

  What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
  
8. CSS stands for Cascading Style Sheets. It is the language we use to control the appearance of the HTML document and how it is presented on the web. A CSS file can be created within a code editor and saved as style.css. To attach the file to the HTML, it must be placed with the <head> of the document using the <link> element. The href attribute is used to point to the location of the css file, and the ref attribute is used to define it as a stylesheet. 
  
The code would look like such:
link rel=“stylesheet” href=“css/style.css”
  
9. What is the difference between CSS ruleset, property and value (write explanation and an example code) 
  
A CSS rule consists of a selector and declaration block where properties are styled. 
Ruleset: A ruleset contains a selector and one or more declarations surrounded by {}. A selector identifies which part of the HTML code is being transformed, and a declaration assigns a value to a property within that selector. An entire ruleset may look something like this:
  
p {
  
background-color: purple;
  
}
  
Property: A property is the type of design you wish to add to the HTML code. In the above example, background-color would be the property.
  
Value: A value would be an accepted value for the property selected. In the above example, purple would be the value of background-color.

10. Why do we use border-box property in CSS?
A border-box allows padding and border to be included in an elements width and height. Without border-box, the padding and border are added onto the width of the box, making it bigger. With border-box, the padding and border are within the set limits of the box. 
  
html {
  
box-sizing: border-box;
  
}
*, *::before, *::after {
  
box-sizing: inherit;
  
}
  
Should be added to the top of every CSS file. 
  
  11. Explain different type of ways we can add spacing to an element
  
The padding and margin properties can be used to add spacing to an element. 
  
  
12. What is the main difference between margin and padding?
  
Margin is defined as the space around an element and padding is defined as the distance between the elements content and a border that may be placed around it. Padding is directly outside the content, and it pushes the edge of the box away from the content. Margin is outside of the box completely, and it is a transparent layer that pushes other boxes away. 

