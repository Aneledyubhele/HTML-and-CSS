**HTML-and-CSS**

What is HTML?

HTML (Hypertext Makeup Language) HTML is a language used to make web pages. It helps 
developers organize content like titles, paragraphs, and links. It uses tags enclosed in angle 
brackets to define different parts of a page. Opening tags start an element, and closing tags end 
it `'<p>,</p>', '<p>,</p>'`
CSS

CSS (Cascading Style Sheets) CSS is the design tool for web pages, determining colors, fonts, 
sizes, and animations. Even with mistakes, browsers try to make the page look good, making CSS 
like a resilient problem-solver for creating attractive web pages.

JavaScript

JavaScript is a special programming language that adds cool, interactive features to websites. It's 
like a superhero because it can do things HTML and CSS can't. But it's sensitive—if there's a 
problem, it might not work. Websites need to work on old computers and browsers, so they use 
HTML, CSS, and JavaScript together. Each does something different, and together they make 
websites strong and cool.

HTML Syntax

HTML is a language for organizing web pages using tags enclosed in < and > symbols. Tags 
come in pairs: opening and closing. Elements, like paragraphs, are defined with these tags, giving 
meaning to content. Elements can be nested within each other, creating a tree-like structure. The 
browser uses this structure to understand and display content. Proper nesting and closing tags 
are crucial for conveying meaning accurately.

HTML Paragraphs

To make text appear as separate paragraphs on a webpage, we use HTML tags 
called `<p>` and `</p>`. These tags indicate the beginning and end of each paragraph. Without 
these tags, the browser treats multiple lines of text as a single paragraph. By adding <p> before 
the first paragraph and `</p>` after each paragraph, the browser understands that they are distinct 
paragraphs.

HTML headlines

HTML Headlines help organize web content into sections. There are six levels of headlines, from 
h1 to h6, with h1 being the biggest. Each level has a different look and shows the importance of 
the content. It's important to choose the right headline level based on its meaning, not just how 
it looks. For example, h1 is usually for the main title, and h2 can be for a subtitle. Keeping 
headlines consistent helps people using screen readers understand the page better. While there 
aren't strict rules, using these headline levels well makes content easier to understand and 
improves the user experience.

HTML Bold and Italics

HTML offers four elements for emphasizing text: `"<i>"`, `"<em>"`, `"<b>"`, and `"<strong>"`. Each 
serves a distinct purpose. `"<i>"` and `"<em>" `are for italics, with `"<em>"` adding emphasis while 
`"<i>"` is used for titles or other non-emphasized text. Similarly, `"<b>"` and ` "<strong>"` create bold 
text, with `"<strong>"` indicating importance or urgency, while `"<b>"` is purely visual. It's important 
to ch oose the appropriate element based on the intended meaning of the emphasized text to 
convey semantic clarity and enhance user experience.

HTML have three types of lists: (unordered lists, ordered lists, and definition lists.)

1. Unordered Lists: Commonly used for lists without a specific order, like ingredients in a 
recipe. Each item is enclosed in `<li>` tags, and the entire list is wrapped in `<ul>` tags. The 
appearance of list markers is determined by the browser, but `<ul>` conveys the meaning, 
and CSS can later change its appearance.
2. Ordered Lists: Similar to unordered lists, but items have a specific order, like steps in a 
recipe. Enclosed in `<li>` tags, the list is wrapped in `<ol>` tags to display numbered steps, 
indicating a clear order.
3. Definition Lists: Used for key-value pairs, resembling dictionary entries. Each term is 
enclosed in `<dt>` tags, and its corresponding description is enclosed in `<dd>` tags. 
Multiple descriptions for a term are supported. The entire list is wrapped in `<dl>` tags. 
Unlike other lists, `<dt>` and `<dd>` tags are placed side by side without additional wrappers.

HTML provides elements for marking up quotes on webpages, including blockquotes and inline 
quotes.

1. Blockquotes: Used for longer quotes, blockquotes are enclosed in ` <blockquote>` tags 
and can contain any HTML elements. They are used to distinguish quoted content from 
the surrounding text and can be styled with CSS.
2. Inline Quotes: Enclosed in `<q>` tags, inline quotes are for shorter quotes within text. 
They automatically add appropriate quote marks and are useful for maintaining 
consistency across different languages and regions.
HTML attributes like datetime in the `<time>` element allow specifying dates and times in a 
machine-readable format. This is crucial for indicating the time of publication or other time related information on webpages.

HTML Date and Time Inputs

HTML simplifies dealing with dates and times using the `<time>` element and 
its datetime attribute. The `<time>` element is used to mark dates, times, or durations, while 
the datetime attribute specifies the machine-readable format of the date or time. By using this 
attribute, we can convey precise timing to computers, even specifying time zones if needed. This 
simplifies formatting and ensures consistency across different platforms.

HTML Code, pre and br

To display code on a webpage, HTML uses the `<code>` element, which changes the font to a 
fixed-width style. To show special characters like < or >, we use HTML entities like `&lt`; and `&gt;`. 
The `<br>` element creates line breaks, useful for poems or code formatting. For keeping irregular 
spacing, the `<pre> `element maintains spacing and line breaks. Combining `<pre> `and `<code>` is 
common for neatly formatted code blocks with indentation. These elements ensure code and text 
content look organized on webpages.

HTML Superscripts, Subscripts and Small Text

HTML provides elements for handling superscripts, subscripts, and small text to convey different 
meanings and levels of importance in content. Subscripts are characters set below the baseline, 
like in chemical formulas, while superscripts are characters set above the baseline, often used in 
mathematical formulas or footnotes. These can be marked up using 
the `<sub>` and  `<sup> `elements, respectively. Additionally, small text, indicating less prominence, 
can be marked with the `<small>` element, useful for fine print or less important details. These 
elements aid in conveying precise typography and meaning in HTML content.

HTML attributes

HTML attributes are like special instructions that we can add to elements to make them do more 
things on a webpage. Some attributes are just for certain elements, like the datetime attribute, 
which helps specify time in the time element. Others, called global attributes, can work with lots 
of different elements. Two important global attributes are class and ID. The class attribute gives 
elements names so we can style them with CSS, while the ID attribute gives elements unique 
names, useful for targeting them in CSS or JavaScript.
There are also cool attributes like "contenteditable" that let users edit webpage content right in 
the browser. However, saving those changes usually needs special coding on the backend. These 
attributes make websites more interactive and give us ways to use browser features and 
JavaScript tricks. Attributes like "lang" and "dir" help make content accessible to people who 
speak different languages. "lang" tells the browser what language the content is in, and "dir" tells 
it which way the text should flow. This is super important for international users.

ARIA Roles

ARIA Roles are crucial attributes added to HTML elements to aid assistive technologies in 
comprehending web content, enhancing accessibility for individuals with disabilities. Ensuring 
accessibility is vital as inaccessible websites can create obstacles for users and may breach 
regulations. ARIA Roles facilitate full utilization of complex web interfaces, such as app-like 
designs, by furnishing vital information to assistive technologies. For instance, in scenarios where 
CSS Grid is used creatively, resulting in individual letter reading by screen readers, ARIA labels 
can rectify the issue by providing accurate text representation while concealing unnecessary 
elements. This approach balances visual appeal with accessibility, making ARIA Roles 
indispensable for broadening web inclusivity and enabling seamless interaction for all users.

Formatting HTML

Fomatting involves managing whitespace, comments, letter case, element length, and self-closing 
tags. While HTML typically disregards extra spaces and line breaks, exceptions exist for certain 
elements like `<pre>`, `<code>`, and `<textarea>`, or with CSS adjustments. Comments aid readability 
but are ignored by browsers. The uppercase vs. lowercase debate in HTML has shifted towards 
lowercase for better readability, though browsers are unaffected. Element length reflects 
historical considerations for file size optimization, with newer elements favoring complete words 
for clarity. Self-closing tags, once emphasized, are now optional for older elements 
like `<img>` with formatting choices driven by readability and personal preference. Browsers 
accommodate diverse styles.

Unsual Characters

In HTML, certain symbols like <, >, and & have special meanings. If you want to display them as 
regular text instead of beinginterpreted as HTML code, you can use character entities. These 
entities are combinations of symbols like `"&copy;`" for © or `"&nbsp;"` for non-breaking spaces. 
They help ensure that your content appears as intended on webpages, even if you're using 
content management systems like WordPress or markdown. Non-breaking spaces are particularly 
useful for keeping words together or creating multiple spaces between words, ensuring proper 
formatting on your webpage.

HTML Links

Web links play a crucial role in our online experience, seamlessly connecting different parts of the 
internet. They enable us to navigate websites effortlessly, allowing us to access various pages 
with just a simple click. The concept of linking goes back to the 1980s when early computer 
visionaries imagined hypertext and hypermedia, which ultimately led to the creation of the web.
In HTML, creating a link is straightforward using the `<a>` (anchor) element, along with 
the href attribute specifying the URL destination. This attribute, abbreviated for Hypertext 
Reference, determines where the link directs users when clicked. Links can encompass text, 
images, or other elements, making it easy to navigate within web content.
URLs, also known as web addresses, can be either absolute or relative. Absolute URLs point 
directly to specific locations on the web, including the HTTP or HTTPS protocol, with HTTPS being 
the recommended choice for its enhanced security features. HTTPS stands for Secure Hypertext 
Transfer Protocol and ensures safer communication over the internet. Nowadays, modern 
browsers automatically include "https://" in URLs to enhance user safety while browsing.

HTML URLs Pathways

HTML URLs can be absolute or relative. Absolute URLs start from the website's root, while relative 
URLs are based on the current file's location. They're handy for linking within the same site, 
referencing files, and moving between servers. Understanding file organization is crucial. Relative 
URLs omit the domain but include the root indicator. Clean URL structures use folders and 
index.html files. Trailing slashes don't impact navigation. Crafting good URLs boosts user 
experience and SEO. In short, relative URLs offer flexibility and clean navigation within a website.

Navigation

Navigation menus on websites are typically structured using HTML elements such as "ul" for 
unordered lists and "li" for list items. The entire menu is enclosed in a "nav" element to signify its 
purpose. Adding CSS styling enhances its visual appearance. To make it accessible, roles like 
"navigation" and "aria label" are assigned, ensuring compatibility with screen readers.
Different types of menus, like breadcrumbs and footer links, may require different markup 
approaches. Breadcrumb trails, for instance, use an ordered list ("ol") but do not necessarily need 
the "navigation" role. Footer links are straightforward, merely being wrapped in a "footer" 
element without the need for a "nav" or list.
The choice of HTML elements and attributes depends on the specific requirements of each 
project, emphasizing the importance of considering semantic meaning and accessibility needs. 
There's no one-size-fits-all approach, and the optimal solution varies based on the context and 
desired rendering of elements.

HTML WORKING WITH GRAPHICS AND IMAGES

Images are very important on the website because make website looks nice and images are all over the place.
Images can added by using the image element as img`<img src = "image.jpg" alt="#" width="400" hieght="300">`

1.First, we have the source attribute (SRC), which tells the browser which image file to load. 
2.The alt attribute (ALT), which provides a text description of the image. 
3.The width and height attributes, which determine the size of the image. So, every image should have all four of these attributes.

Image Formats

GIF

GIFs are great for compressing illustrations that have large areas of the same color, but it falls short when it comes to photographs. It only supports 256 colors, and images can end up looking pixelated, unless you want that retro vibe. GIFs can have transparent areas, but the edges between transparent and solid parts can be jagged.

SVG
 
(Scalable Vector Graphics) files are ideal for creating logos, icons, and illustrations due to their vector-based nature, which allows them to be scaled to any size without losing quality, while maintaining a small file size. Unlike pixel-based formats like GIF, SVGs contain instructions for rendering the graphic, making them highly efficient and versatile.

JPG 

JPGs are widely used for compressing photos and are the default format for most digital cameras. When using JPG images on websites, it's important to resize and compress them to prevent slow loading times. Compressing JPGs involves reducing color information to strike a balance between image quality and file size. This can be done manually or with the help of online tools.

PNG

PNG is a modern format useful for transparent images, sometimes better than GIF or JPG in compression. Experiment with compression options to find the smallest file size. Expect newer formats for better compression. Consider size, format, and compression for faster downloads. HTML remains constant regardless of image format.

Responsive Images

Responsive images in CSS are designed to ensure that images display well across devices of varying screen sizes, from large desktop monitors to small mobile screens.High-resolution images can be a problem for users on slow networks or with limited data, as they're large in size, slow to download, and expensive to load.

HTML allows for different image versions to be delivered based on the device's screen size, pixel density, network speed, and other factors.

Figcaption and Figures

Figures and figcaptions are elements used in web design to associate captions with images or other visual content.

**SQL (Structured Query Language)**:
  - Tool for handling and defining data in databases.
  - Standardized in 1986, simplifying interaction with databases.
  - Provides a standardized way for databases to understand queries.
    
**Basics of SQL**:
  - A statement is the core of SQL, used to retrieve or modify data in databases.
  - Uses operators and uppercase keywords, ending with a semi-colon.
  - Statements can perform various tasks like asking questions, modifying data, creating, tweaking, or deleting tables.
    
**Pronunciation of SQL**:
  - Originally SEQUEL (Structured English Query Language), now commonly referred to as SQL.
  - Pronunciation can vary, with some still calling it SEQUEL.
    
**SELECT Statement:**
  - Fundamental SQL method for fetching data from a database.
  - Can retrieve non-database text by enclosing it in quotes and ending with a semicolon.
  - Parameters specify data retrieval from the database.
    
**Fetching Data from a Table:**
  - Accessed through "browse data," selecting a specific table (e.g., 'people').
  - Field names used in the table to request information.
    
**Enhancing SELECT Statement:**
  - Basic SELECT statement can be enhanced with additional conditions for precise data fetching.
  - Further query refinement discussed in subsequent chapters.
    
**Removing Table Data:**
  - Use the `delete` keyword to erase records from a table.
  - Specify the table where deletions should happen.
    
**Selective Deletion:**
  - Confirm deletion targets with a `select` statement.
  - Example: 'select * from people where id_number = 1001' checks details of a specific record before deletion.
  - Execute deletions with a specific condition, like 'delete from people where id_number = 1001'.
  - Multiple records can be removed at once based on conditions.
    
**CRUD Operations:**
  - Demonstrates CRUD operations - Creating, Reading, Updating, and Deleting data.
  - Execute these operations using DB Browser.

**Introduction to MongoDB:**
  - MongoDB is a popular document database known for its reliability and user-friendly nature.
  - It also includes CRUD operations, aggregations, and MongoDB drivers usage, providing valuable knowledge to developers.

**What is MongoDB?**
  - MongoDB is favored by web developers for its ease of use since 2009.
  - It allows working with data in a document format, making it consistent with applications.
  - MongoDB supports distributed systems, allowing for easy vertical and horizontal scaling.
    
**Insert Documents in MongoDB:**
  - Two Methods: There are 2 methods to insert documents into a MongoDB database.
  - `insertOne()`: To insert a single document, use the insertOne() method.
    - Inserts a single object into the database.
  - `insertMany()`: To insert multiple documents, use the insertMany() method.
    - Inserts an array of objects into the database in bulk.
 







