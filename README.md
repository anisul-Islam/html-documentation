# HTML Documentation

- [HTML English Video Tutorial](https://youtu.be/TWUf6eSi2K8)
- [Learn HTML by building a project](https://youtu.be/mgO9ObbVeJ8)
- [html complete course Bangla (Beginner to Advanced)](https://youtube.com/playlist?list=PLgH5QX0i9K3oHBr5dsumGwjUxByN5Lnw3)

![html course plan](images/html.png)

## Table of Contents

- [Beginner Level](#beginner-level)

    1. [Introduction to HTML](#1-introduction-to-html)
      - [How website works](#10-how-website-works)
      - [What is HTML & Why HTML?](#11-what-is-html--why-html)
      - [History of HTML](#12-history-of-html)
      - [Advantages and disadvantages of HTML](#13-advantages-and-disadvantages-of-html)
      - [Setup Environment](#14-setup-environment)
      - [Basic Structure of HTML Document](#15-basic-structure-of-html-document)

    2. [Basic Tags, Styling, Debugging](#2-basic-tags-styling-debugging)
      - [Tag, Attribute](#21-tag-attribute)
      - [Basic HTML Tags](#22-headings-paragraph-line-breaks-horizontal-rule)
      - [Styling HTML Elements](#23-styling-html-elemnts)
      - [Entity, comment, Symbol, Color](#24-entity-comment-symbol-color)
      - [Debugging](#25-debugging)

    3. [Text Formatting Tags](#3-text-formatting-tags)
    4. [Lists](#4-lists)
    5. [Links and Navigation](#5-links-and-navigation)
    6. [Image and iframe](#6-image-and-iframe)
    7. [Table](#7-table)
    8. [Form Basic](#8-form-basics)
    9. [Semantic HTML](#9-semantic-html)
    10. [Demo for basic HTML](#10-demo-for-basic-html)
    11. [Assignment for basic HTML](#11-assignment-for-basic-html)

- [Intermediate Level](#intermdiate-level)

  1. [Meta Tag and SEO](#31-meta-tags--seo)
  2. [Adding font-awesome icon & google font](#32-adding-font-awesome-icon--google-font)
  3. [Advanced Table](#33-advanced-table)
  4. [Advanced Form](#34-advanced-form)
  5. [Send form data to your email](#35-send-form-data-to-your-email-using-third-party-api)
  6. [Multimedia Elements in HTML](#36-multimedia-elements-in-html)
  7. [Send form data to your email](#35-send-form-data-to-your-email-using-third-party-api)
  8. [HTML5 Elements](#38-html5-elements)

- [Advanced Level](#advanced-level)


3. [Advanced HTML](#3-advanced-html)

   - [Multimedia - audio, video](#31-multimedia---audio-video)
   - [Web accessibility](#34-web-accessibility)
   - [Graphics](#35-graphics)
   - [HTML5 API](#36-html5-api)
   - [HTML Templates and Web Components](#37-html-templates-and-web-components)

## Beginner Level

### 1. Introduction to html

In this chapter we will discuss what is HTML, why do we need HTML, advantages and disadvantages of HTML, History of HTML, environment setup for HTML, basic structure of HTML

#### 1.0 How website works?

- client, server model
- http request + http response
- web design - html, css, js, js libraries/frameworks
- give a demo for this

#### 1.1 What is HTML & Why HTML

- HTML stands for HyperText Markup Language
- It is not a **programming language** but markup language where tags are responsible for defining the elements and layout of a webpage, including headings, paragraphs, images, links, and more.

#### 1.2 History of HTML

- Tim Berners-Lee created HTML in 1990
- HTML 1.0 - 1990
  HTML 2.0 - 1993
  HTML 3.0 - 1995 (Not fully implemented)
  HTML 3.2 - 1997
  HTML 4.0 - 1997
  HTML 4.01 - 1999
  HTML5 - 2014 (Ongoing development with subsequent versions like HTML5.1, HTML5.2, etc.)

#### 1.3 Advantages and disadvantages of HTML

- Advantages of HTML:

1. **Easy to Learn**: HTML has a simple and straightforward syntax, making it easy for beginners to learn and understand.

2. **Platform Independent**: HTML is platform-independent and can be used on any operating system or device that has a web browser.

3. **Wide Browser Support**: HTML is supported by all major web browsers, ensuring compatibility and accessibility across different platforms.

- Disadvantages of HTML:

1. **Limited Styling Options**: HTML has limited styling capabilities compared to CSS (Cascading Style Sheets). While HTML can define basic styles, more complex and detailed styling is better achieved using CSS.

2. **Lack of Interactivity**: HTML on its own is static and lacks interactivity. To add dynamic behavior or functionality to web pages, additional technologies such as JavaScript or server-side languages are required.

3. **Browser Compatibility Issues**: Different web browsers may interpret HTML code differently, leading to potential compatibility issues. Developers must test and ensure cross-browser compatibility.

4. **Security Risks**: HTML alone does not provide built-in security features. Web developers must implement security measures and follow best practices to protect against vulnerabilities, such as cross-site scripting (XSS) attacks.

#### 1.4 Setup Environment

- Editor: VScode / Notepad++ / Sublime
- Browser: Google Chrome / Firefox
- Version Control: GitHub

Setting up a development environment for HTML involves choosing the right tools and configuring them properly to streamline your web development process. Here’s a step-by-step guide to get you started:

##### Step 1: Choose a Text Editor or IDE

A good text editor or Integrated Development Environment (IDE) is essential for writing HTML. Here are some popular options:

1. **Visual Studio Code (VS Code)**:
   - Lightweight and highly customizable.
   - Supports extensions for various languages and tools.

2. **Sublime Text**:
   - Fast and lightweight.
   - Supports many plugins for added functionality.

3. **Atom**:
   - Open-source and highly customizable.
   - Has a large community and many packages available.

4. **WebStorm**:
   - A powerful IDE specifically for web development.
   - Offers many built-in features for HTML, CSS, and JavaScript.

##### Step 2: Install Your Chosen Text Editor or IDE

###### Visual Studio Code (VS Code)

1. **Download**:
   - Go to the [VS Code website](https://code.visualstudio.com/).
   - Download the installer for your operating system.

2. **Install**:
   - Run the installer and follow the instructions to install VS Code.

##### Step 3: Install Extensions

To enhance your development environment, install extensions that help with HTML, CSS, and JavaScript development. Here are some recommended extensions for VS Code:

1. **HTML Boilerplate**:
   - Provides basic HTML templates.

2. **Live Server**:
   - Launches a local development server with live reload feature.

3. **Prettier - Code formatter**:
   - Formats your code for better readability.

###### Installing Extensions in VS Code

1. Open VS Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
3. Search for the desired extensions and click **Install**.

##### Step 4: Set Up a Project Folder

1. **Create a Project Folder**:
   - Create a folder on your computer where you will store your project files. For example, `html-project`.

2. **Open the Project Folder in VS Code**:
   - Open VS Code.
   - Go to `File` > `Open Folder` and select your project folder.

##### Step 5: Create Your First HTML File

1. **Create a New File**:
   - In VS Code, go to `File` > `New File` or press `Ctrl+N`.

2. **Save the File**:
   - Save the file as `index.html` in your project folder by going to `File` > `Save As` and typing `index.html`.

3. **Add Basic HTML Boilerplate**:
   - Type `html:5` and press `Tab` to automatically generate a basic HTML boilerplate using Emmet.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Hello, World!</h1>
</body>
</html>
```

##### Step 6: Set Up Live Server

1. **Open Live Server**:
   - With your `index.html` file open, right-click on the editor and select `Open with Live Server`.
   - Alternatively, click on the **Go Live** button at the bottom right of the status bar.

2. **View Your Page**:
   - Your default web browser should open, displaying your `index.html` file. Any changes you make to the file will automatically reload in the browser.

##### Step 7: Version Control with Git

1. **Install Git**:
   - Download and install Git from the [official Git website](https://git-scm.com/).

2. **Initialize a Git Repository**:
   - Open a terminal in VS Code by pressing `Ctrl+`` (backtick) or going to`View` > `Terminal`.
   - Initialize a new Git repository in your project folder:

     ```bash
     git init
     ```

3. **Add Files and Commit**:
   - Add your files to the repository and commit your changes:

     ```bash
     git add .
     git commit -m "Initial commit"
     ```

4. **Set Up a Remote Repository**:
   - Create a new repository on GitHub, GitLab, or Bitbucket.
   - Link the local repository to the remote repository:

     ```bash
     git remote add origin https://github.com/yourusername/yourrepository.git
     git push -u origin main
     ```

##### Step 8: Learning Resources

1. **MDN Web Docs**:
   - Comprehensive resource for learning HTML, CSS, and JavaScript.
   - [MDN Web Docs](https://developer.mozilla.org/)

2. **W3Schools**:
   - Tutorial website for learning web technologies.
   - [W3Schools](https://www.w3schools.com/)

3. **FreeCodeCamp**:
   - Free coding curriculum with a focus on web development.
   - [FreeCodeCamp](https://www.freecodecamp.org/)

#### 1.5 Basic Structure of HTML Document

- HTML document has 2 important part: head, body
- In the following example a basic structure of a HTML document

  ```html
  <!DOCTYPE html>
  <html>
    <head>
      TITLE, META TAG ETC.
    </head>
    <body>
      CONTENT OF THE WEBPAGE
    </body>
  </html>
  ```

- Always use `<!DOCTYPE html>` to tell the browser what type of document to expect; remember it is not a tag, just a declaration
- Every HTML document must have `<html>` pair tag and Inside `<html>` tag we use `<head>` and `<body>` as the example shows above.
- Inside head tag we use meta tag, set title etc.
- Inside body tag we write everything that we want to display on web page.

### 2. Basic Tags, Styling, Debugging

#### 2.1 Tag, Attribute

- Tag is the heart of html; HTML document is mainly built with tag.
- Tag Syntax: `<keyword>` ; Inside the angular brackets we need to write predefined keywords to use html tag.
- Small / capital letters both can be used when writing html tag; however small letter is prefered.
- Example: `<p> This is a paragraph </p>`
  In the example, `<p>` is an opening tag, `</p>` is a closing tag and `This is a paragraph` is called content. In between the starting tag to end tag we have content. Everything from starting tag to end tag is called Element

##### Types of Tag

- There are 2 types of html tag: Pair/container tag and empty tag
- Pair tag has starting and ending; However, empty tag has no closing tag.
- Some of the example of pair tag and empty tags are given below:

  ```html
  <!-- Some examples of Pair/Container Tag -->
  <html>
    ...
  </html>
  <head>
    ...
  </head>
  <body>
    ...
  </body>
  <p>...</p>
  <h1>...</h1>
  <script>
    ...
  </script>
  <style></style>
  ....

  <!-- Some examples of Empty Tag -->
  <meta />
  <link />
  <br />
  <hr />
  <img />
  <input />
  ...
  ```

##### Attribute

- Attribute helps tag to extend its capabilities
- In the following example, `<img/>` is tag; src, height, width are the attributes

  ```html
  <img src="anis.jpg" height="200" width="200" />
  ```

- Attribute Syntax: `attributeName="attributeValue"`

#### 2.2 Headings, Paragraph, Line breaks, Horizontal rule

```html
<body>
  <!--6 heading tags-->
  <h1>This is a h1</h1>
  <h2>This is a h2</h2>
  <h3>This is a h3</h3>
  <h4>This is a h4</h4>
  <h5>This is a h5</h5>
  <h6>This is a h6</h6>

  <!--to create a paragrap use p tag-->
  <p>This is a paragraph. I am writing a paragraph here.</p>

  <!--to create a horizontal rule use hr tag-->
  <hr size="2" />
</body>
```

- output of the text-formatting tags is below:
  ![headings](images/headings.png)

- There are 6 HTML heading levels. `<h1>` is the largest level and `<h6>` is the smallest level.
- by default, heading tags and paragraph tag create new line (block level element)
- `<hr size="2"/>` here `<hr/>` is an empty tag responsible for creating horizontal rule and size attribute set the heights of the horizontal rule in pixel

#### 2.3 Styling html elemnts

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <style>
      body {
        background-color: #222;
      }
      h1 {
        /* color: white; */
        /* color: #fff; */
        color: rgb(255, 255, 255);
        text-align: center;
      }
    </style>

    <title>Document</title>
  </head>
  <body>
    <h1>Bangladesh is my motherland. I miss Bangladesh a lot.</h1>
    <p style="color: green;">I also miss my family</p>
  </body>
</html>
```

- From the example, you can see that for styling html elements inside the html documents we can use style tag or style attribute
- style attribute in HTML: style="property: value; property: value..." (from the example you can see that `<p>` tag has style attribute where paragraph color is set as green)
- style tag in HTML: `<style> ... </style>` tag must be used inside the head tag as shown in this example. In this example you can see that `<h1>` and `<body>` tag has styling property like color, text-align, background-color.
- To set color of an html element we can use color name / hexadecimal color code / rgb color / hsl code as a value of color property as shown in this example for h1 tag.

#### 2.4 Entity, comment, Symbol, Color

##### Comment syntax example

```html
<!-- This is a comment -->
```

##### Entity syntax example

```html
&copy; &lt; &gt; &gt; &hearts; &nbsp;
```

- First example shows the example of a html comment
- second example shows an example of entity
- To create an entity first write & then give a keyword and then give a semicolon
- `&copy;` will create copyright symbol
- `&lt;` will create less than symbol
- `&gt;` will create greater than symbol
- `&hearts;` will create hearts symbol

##### Sources for adding symbol, icons and emoji

- Unicode character website: <https://unicode-table.com/en/>
- W3School emoji link: <https://www.w3schools.com/charsets/ref_emoji.asp>
- iconfinder icon link: <https://www.iconfinder.com/>

- Pick image from [unsplash](https://unsplash.com/)
- Choose color from

  - [colorhunt](https://colorhunt.co/)
  - [imagecolorpicker](https://imagecolorpicker.com/)
  - [htmlcolorcodes](https://htmlcolorcodes.com/)

#### 2.5 Debugging

- Inspect Element: Within the browser developer tools, the "Inspect Element" feature allows you to examine and modify the HTML structure in real-time. You can navigate through the document tree, view CSS styles, and experiment with changes to identify and fix layout or formatting issues.
- Use Comments: Insert comments (`<!-- ... -->`) within your HTML code to temporarily remove or isolate sections of code that might be causing issues. This helps you narrow down the problematic area and identify the source of the problem.
- After writing your html code you can check the validity on this website <https://validator.w3.org/>

### 3. Text Formatting tags

- Text Formatting tags: Applying formatting to text using tags like strong, em, u, s, sup, sub, blockquote, and code.

```html
<body>
  <!-- b(bold) and strong tag are quite similar -->
  <b>This is a bold text</b> <br />
  <strong>This is a strong text</strong> <br />

  <!-- i(italic) and em(emphasize) tag are quite similar -->
  <i>This is a italic text</i> <br />
  <em>This is a emphasize text</em> <br />

  <!-- u(underline) -->
  <u>This is a italic text</u> <br />

  <!--tags can be used inside one another-->
  <b>bold. <i> italic and bold</i></b> <br />

  <mark>Important task should be highlighted</mark> <br />
  <!-- del (deleted) -->
  <del>This is a deleted text</del> <br />

  <!-- sup (superscript), sub(subscript) -->
  H<sub>2</sub>O <br />
  (a+b)<sup>2</sup> <br />

  <!-- pre tag helps to show text as you want to formatted -->
  <pre>
      This is a
        life changing documentation
      Read,learn, enjoy
        ofcourse share with others
  </pre>

  <abbr title="google is a search engine">Google</abbr>
  <address>Anisul Islam 192 anis road, London United Kingdom</address>

  <h2>What our customer thinks?</h2>
  <blockquote>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed varius</p>
    <footer>John Doe</footer>
  </blockquote>

  <code> console.log("hello"); </code>
</body>
```

output of the text-formatting tags is below:
![text formatting](images/text-formatting.png)

- The `<blockquote>` tag is used to enclose a block of quoted text. It is commonly used to represent quotations, excerpts, or highlighted text. The `<p>` element inside the `<blockquote>` represents the quoted text, and the `<footer>` element provides attribution or the source of the quote.

- The `<code>` tag is used to define a section of code or programming instructions. It is commonly used for displaying code snippets or highlighting code within a paragraph.

### 4. Lists

#### Lists in HTML with Attributes

Lists in HTML are used to group related items together. HTML provides various types of lists to represent different kinds of information: ordered lists, unordered lists, and definition lists. Each type of list has attributes that can modify its behavior or appearance. Here’s a detailed explanation of each type with relevant attributes:

##### 1. Ordered Lists (`<ol>`)

Ordered lists are used when the order of the items is important. Each item in an ordered list is numbered automatically by the browser.

**Attributes**:
- `type`: Specifies the type of numbering (e.g., "1" for numbers, "A" for uppercase letters, "a" for lowercase letters, "I" for uppercase Roman numerals, "i" for lowercase Roman numerals).
- `start`: Specifies the starting number of the list.
- `reversed`: Reverses the order of the list items.

**Syntax**:

```html
<ol type="A" start="3" reversed>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
```

**Example**:

```html
<ol type="I" start="5">
  <li>Install Visual Studio Code</li>
  <li>Install necessary extensions</li>
  <li>Create a new project folder</li>
  <li>Create an index.html file</li>
  <li>Write HTML content</li>
</ol>
```

In this example, the list items are numbered starting from V (5) in uppercase Roman numerals.

##### 2. Unordered Lists (`<ul>`)

Unordered lists are used when the order of the items does not matter. Each item in an unordered list is typically marked with a bullet point.

**Attributes**:
- `type`: Specifies the type of bullet (e.g., "disc", "circle", "square" - note that this attribute is deprecated and not recommended for use).

**Syntax**:

```html
<ul type="circle">
  <li>Milk</li>
  <li>Bread</li>
  <li>Eggs</li>
</ul>
```

**Example**:

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

In this example, the list items are marked with default bullet points.

##### 3. List Items (`<li>`)

The `<li>` element is used to define each item in both ordered and unordered lists. It can also have attributes to modify its behavior.

**Attributes**:
- `value`: Specifies the value of the list item in an ordered list.

**Syntax**:

```html
<ol>
  <li value="10">Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```

**Example**:

```html
<ol>
  <li value="10">Step 10</li>
  <li>Step 2</li>
  <li>Step 3</li>
</ol>
```

In this example, the first list item will start with the number 10, followed by 2 and 3.

##### 4. Nested Lists

Lists can be nested inside each other to create sub-lists. This is useful for representing hierarchical data.

**Syntax**:

```html
<ul>
  <li>Item 1
    <ul>
      <li>Sub-item 1.1</li>
      <li>Sub-item 1.2</li>
    </ul>
  </li>
  <li>Item 2</li>
</ul>
```

**Example**:

```html
<ul>
  <li>Frontend Development
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
    </ul>
  </li>
  <li>Backend Development
    <ul>
      <li>Node.js</li>
      <li>Express.js</li>
      <li>Databases
        <ul>
          <li>MySQL</li>
          <li>MongoDB</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>
```

In this example, the main list contains items related to frontend and backend development, and each of these items contains nested lists.

##### 5. Definition Lists (`<dl>`)

Definition lists are used to represent a list of terms and their definitions. Each term is enclosed in a `<dt>` (definition term) element, and each definition is enclosed in a `<dd>` (definition description) element.

**Syntax**:

```html
<dl>
  <dt>Term 1</dt>
  <dd>Definition for Term 1</dd>
  <dt>Term 2</dt>
  <dd>Definition for Term 2</dd>
</dl>
```

**Example**:

```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language, the standard language for creating web pages.</dd>
  <dt>CSS</dt>
  <dd>Cascading Style Sheets, used to style HTML elements.</dd>
  <dt>JavaScript</dt>
  <dd>A programming language used to create dynamic and interactive effects on web pages.</dd>
</dl>
```

In this example, the terms "HTML", "CSS", and "JavaScript" are defined with their respective descriptions.

#### Summary

- **Ordered Lists (`<ol>`)**: Use for items that have a specific order. Items are numbered. Attributes include `type`, `start`, and `reversed`.
- **Unordered Lists (`<ul>`)**: Use for items that do not have a specific order. Items are marked with bullet points. Attributes include `type` (deprecated).
- **List Items (`<li>`)**: Define individual items in both ordered and unordered lists. The `value` attribute specifies the value of the list item in an ordered list.
- **Nested Lists**: Create hierarchical structures by nesting lists inside each other.
- **Definition Lists (`<dl>`)**: Use for terms and their definitions. Contains `<dt>` for terms and `<dd>` for definitions.

#### example

  ```html
  <body>
    <h3>Web development front end skills</h3>
    <ol>
      <li>HTML</li>
      <li>GitHub</li>
      <li>Figma</li>
      <li>CSS</li>
      <li>Tailwind CSS / Bootstrap</li>
    </ol>

    <dl>
      <dt>Google</dt>
      <dd>Google is a search engine</dd>
    </dl>
  </body>
  ```

  output of the list code
  ![list](images/list.png)

### 5. Links and Navigation

Links are a fundamental aspect of web navigation, enabling users to move from one webpage to another or to different sections within a page. HTML uses anchor tags (`<a>`) to create hyperlinks. Here’s an in-depth look at links and navigation:

#### Anchor Tags (`<a>`)

The anchor tag (`<a>`) is used to define hyperlinks in HTML. The content inside the anchor tag is typically clickable and directs the user to another location when clicked.

**Syntax**:

```html
<a href="URL">Link Text</a>
```

**Example**:

```html
<a href="https://www.example.com">Visit Example.com</a>
```

In this example, the text "Visit Example.com" is a clickable link that directs the user to `https://www.example.com`.

#### Absolute vs. Relative Links

Links can be either absolute or relative, depending on how they reference the target URL.

**Absolute Links**:

An absolute link provides the full URL, including the protocol (http or https), domain name, and path. Absolute links are used to link to external websites or resources.

**Syntax**:

```html
<a href="https://www.example.com/page.html">Example Page</a>
```

**Example**:

```html
<a href="https://www.google.com">Go to Google</a>
```

In this example, clicking the link will take the user to Google's homepage.

**Relative Links**:

A relative link provides a path relative to the current document or the root of the website. Relative links are commonly used to link to other pages within the same website.

**Syntax**:

```html
<a href="page.html">Example Page</a>
```

**Example**:

```html
<a href="about.html">About Us</a>
<a href="/contact.html">Contact</a>
<a href="../index.html">Home</a>
```

- `about.html` links to a page in the same directory as the current document.
- `/contact.html` links to a page at the root level of the website.
- `../index.html` links to a page one directory level up from the current document.

#### Link Attributes

Anchor tags can include various attributes that define the link's behavior and provide additional information. The most commonly used attributes are `href`, `target`, and `title`.

**1. `href` Attribute**:

The `href` (Hypertext REFerence) attribute specifies the URL of the page the link goes to. Without this attribute, the `<a>` tag will not function as a hyperlink.

**Syntax**:

```html
<a href="URL">Link Text</a>
```

**Example**:

```html
<a href="https://www.example.com">Visit Example.com</a>
```

**2. `target` Attribute**:

The `target` attribute specifies where to open the linked document. Common values include:

- `_self`: Opens the link in the same tab or window (default behavior).
- `_blank`: Opens the link in a new tab or window.
- `_parent`: Opens the link in the parent frame.
- `_top`: Opens the link in the full body of the window.

**Syntax**:

```html
<a href="URL" target="_blank">Link Text</a>
```

**Example**:

```html
<a href="https://www.example.com" target="_blank">Visit Example.com in a new tab</a>
```

In this example, clicking the link will open `https://www.example.com` in a new browser tab.

**3. `title` Attribute**:

The `title` attribute provides additional information about the link, typically displayed as a tooltip when the user hovers over the link.

**Syntax**:

```html
<a href="URL" title="Tooltip Text">Link Text</a>
```

**Example**:

```html
<a href="https://www.example.com" title="Go to Example.com">Visit Example.com</a>
```

In this example, hovering over the link will display the tooltip "Go to Example.com".

#### Putting It All Together

Here’s an example that combines all the elements discussed:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Links and Navigation</title>
</head>
<body>
    <h1>Navigation Links</h1>
    <p>
        <a href="https://www.example.com" target="_blank" title="Go to Example.com">Visit Example.com</a>
    </p>
    <p>
        <a href="about.html" title="Learn more about us">About Us</a>
    </p>
    <p>
        <a href="/contact.html" title="Get in touch with us">Contact</a>
    </p>
    <p>
        <a href="../index.html" title="Return to homepage">Home</a>
    </p>
</body>
</html>
```

#### previous doc

- Linking to other pages within the website and external websites.
- Creating hyperlinks using the `<a> ... </a>` tag and understanding attributes like href, target, and rel.

  - Inside `<a>` link `href="url"` attribute is used where we give the address where we want to visit based on click
  - Inside `<a>` link `target="_blank"` attribute is used to open a new tab for the visited page/site
  - As shown in the following example we can send email by clicking the link for that we have to use `href="mailto:EMAIL_ADDRESS_HERE"`
  - As shown in the following example we can call somone by clicking the link for that we have to use `href="tel:PHONE_NUMBER_HERE"`

  ```html
  <body>
    <h3>Contact Me</h3>
    <a href="http://www.studywithanis.com" target="_blank">website</a> <br />
    <br />
    <a href="https://www.youtube.com/c/anisulislamrubel" target="_blank"
      >YouTube</a
    >
    <br />
    <br />
    <a href="tel:0017444044000" target="_blank">Call me</a> <br />
    <br />
    <a href="mailto:anisul2010s@yahoo.co.uk" target="_blank">Mail Me</a>
  </body>
  ```

  output of the html link code
  ![link](images/link.png)

### 6. Image and iframe

Images are an essential part of web pages, adding visual appeal and context to the content. In HTML, images are inserted using the `<img>` tag. Here's a detailed explanation of how to work with images in HTML, including inserting images, using image attributes, and linking images.

#### Inserting Images (`<img>`)

The `<img>` tag is used to embed images in an HTML document. This tag is an empty element, meaning it does not have a closing tag.

**Syntax**:

```html
<img src="image_url" alt="description">
```

**Example**:

```html
<img src="https://www.example.com/image.jpg" alt="Example Image">
```

In this example, an image from `https://www.example.com/image.jpg` is displayed, and "Example Image" is used as alternative text.

#### Image Attributes

The `<img>` tag supports several attributes that define the source of the image, provide alternative text, and control the display of the image.

**1. `src` Attribute**:

The `src` (source) attribute specifies the path to the image file. This can be a relative URL, an absolute URL, or a data URL.

**Syntax**:

```html
<img src="image_url">
```

**Example**:

```html
<img src="https://www.example.com/logo.png">
```

**2. `alt` Attribute**:

The `alt` (alternative text) attribute provides a textual description of the image. This text is displayed if the image cannot be loaded and is also used by screen readers to describe the image to visually impaired users. Providing descriptive alt text improves accessibility and SEO.

**Syntax**:

```html
<img src="image_url" alt="description">
```

**Example**:

```html
<img src="https://www.example.com/logo.png" alt="Company Logo">
```

**3. `width` and `height` Attributes**:

The `width` and `height` attributes specify the dimensions of the image in pixels. Setting these attributes can help ensure that the layout of the page remains consistent even if the image takes time to load.

**Syntax**:

```html
<img src="image_url" width="width_value" height="height_value">
```

**Example**:

```html
<img src="https://www.example.com/logo.png" alt="Company Logo" width="200" height="100">
```

In this example, the image is displayed with a width of 200 pixels and a height of 100 pixels.

#### Image Linking

Images can also be used as hyperlinks. To create a clickable image, wrap the `<img>` tag inside an anchor (`<a>`) tag.

**Syntax**:

```html
<a href="link_url">
  <img src="image_url" alt="description">
</a>
```

**Example**:

```html
<a href="https://www.example.com">
  <img src="https://www.example.com/logo.png" alt="Company Logo" width="200" height="100">
</a>
```

In this example, clicking on the image will take the user to `https://www.example.com`.

#### Putting It All Together for Image

Here’s an example that combines inserting images, using image attributes, and creating clickable images:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Images in HTML</title>
</head>
<body>
    <h1>Images in HTML</h1>

    <!-- Inserting an Image -->
    <p>Here is an example of an image:</p>
    <img src="https://www.example.com/image.jpg" alt="Example Image">

    <!-- Using Image Attributes -->
    <p>This image has specified width and height:</p>
    <img src="https://www.example.com/logo.png" alt="Company Logo" width="200" height="100">

    <!-- Image Linking -->
    <p>Click on the image to visit Example.com:</p>
    <a href="https://www.example.com">
      <img src="https://www.example.com/logo.png" alt="Company Logo" width="200" height="100">
    </a>
</body>
</html>
```

#### Summary for Image

- **Inserting Images (`<img>`)**: Use the `<img>` tag to embed images in HTML.
- **`src` Attribute**: Specifies the path to the image file.
- **`alt` Attribute**: Provides alternative text for the image, improving accessibility and SEO.
- **`width` and `height` Attributes**: Define the dimensions of the image in pixels.
- **Image Linking**: Wrap the `<img>` tag in an `<a>` tag to create clickable images.

By understanding and utilizing these features, you can effectively incorporate and manage images within your web pages, enhancing both the visual appeal and functionality of your content.

#### image

- For adding image on webpage we use `<img />` tag as shown in the following example.
- some common attribute for `<img />` tag: `src, alt, height, width, title`
- syntax for adding image: `<img src="imagename" alt="alternative" title="profile image">`
- `src` attribute needs the image address
- `alt` attribute shows some text about image if image is not found
- `title` attribute shows some tooltip text when we hover over the image
- `height` and `width` attribute helps us to set the height and width of image
- `loading="lazy"` if you have too many images and you want to load them lazily (after loading the other things first then you want to load images)
- we can use `<img>` tag inside of `<a>` tag so that when we click an image it will take us to a link. `<a href="" target="_blank"> <img src="" alt="" /> </a>`

#### iframe

- iframe helps us to display any website, youtube video or map inside our own webpage  
  iframe Example

  ```html
  <iframe
    width="560"
    height="315"
    src="https://www.youtube.com/embed/oN8aS_HW4k8"
    title="YouTube video player"
    allowfullscreen
  >
  </iframe>
  ```

### 7. Table

- Understanding table structure, headers, rows, colspan, rowspan and data cells.

#### HTML Basic Table

- `<table>` tag is used to create table.
- `<thead>` tag is used to create table head.
- `<tbody>` tag is used to create table body.
- `<tfoot>` tag is used to create table footer.
- `<tr>` tag is used to create table row.
- `<td>` tag is used to create table data cell.
- `<th>` tag is used to create table header cell.
- `<caption>` tag is used to create table caption.

- Table Attributes:
  border: Specifies the width of the table's border.
  cellpadding: Specifies the space between the cell content and its borders.
  cellspacing: Specifies the space between cells.

- Follow the image to understand td, tr,
  ![table](images/table.png)

  ```html
  <body>
    <table>
      <caption>
        Student Table
      </caption>
      <thead>
        <tr>
          <th>ID</th>
          <th>Name</th>
          <th>GPA</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>101</td>
          <td>Anis</td>
          <td>3.92</td>
        </tr>
        <tr>
          <td>102</td>
          <td>Rabeya</td>
          <td>3.45</td>
        </tr>
        <tr>
          <td>103</td>
          <td>Rasel</td>
          <td>3.45</td>
        </tr>
      </tbody>
    </table>
  </body>
  ```

  output of the above html code
  ![table2](images/table2.png)

#### HTML Table rowspan, colspan

- `rowspan="N"` attribute is used to tell that a cell will expand N number of rows.
- `colspan="N"` attribute is used to tell that a cell will expand N number of columns.
- An example of rowspan is given below:

  ```html
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <title>Document</title>

      <style>
        table,
        th,
        td {
          border: 1px solid;
          border-collapse: collapse;
        }
      </style>
    </head>
    <body>
      <table>
        <caption>
          Student Table
        </caption>
        <thead>
          <tr>
            <th>ID</th>
            <th>Name</th>
            <th>GPA</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>101</td>
            <td>Anis</td>
            <td>3.92</td>
          </tr>
          <tr>
            <td>102</td>
            <td>Rabeya</td>
            <td rowspan="2">3.45</td>
          </tr>
          <tr>
            <td>103</td>
            <td>Rasel</td>
          </tr>
        </tbody>
      </table>
    </body>
  </html>
  ```

  output of the above html code
  ![table3](images/table3.png)

- An example of rowspan is given below:

  ```html
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <title>Document</title>

      <style>
        table,
        th,
        td {
          border: 1px solid;
          border-collapse: collapse;
        }
      </style>
    </head>
    <body>
      <table>
        <caption>
          Student Table
        </caption>
        <thead>
          <tr>
            <th>ID</th>
            <th>Name</th>
            <th colspan="2">Phone</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>101</td>
            <td>Anis</td>
            <td>017</td>
            <td>018</td>
          </tr>
          <tr>
            <td>102</td>
            <td>Rabeya</td>
            <td>019</td>
            <td>015</td>
          </tr>
        </tbody>
      </table>
    </body>
  </html>
  ```

  output of the above html code
  ![table4](images/table4.png)

- An example of colspan and rowspan is given below:

  ```html
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <title>Document</title>

      <style>
        table,
        th,
        td {
          border: 1px solid;
          border-collapse: collapse;
        }
      </style>
    </head>
    <body>
      <table>
        <caption>
          Student Table
        </caption>
        <thead>
          <tr>
            <th>ID</th>
            <th>Name</th>
            <th>GPA</th>
            <th colspan="2">Phone</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>101</td>
            <td>Anis</td>
            <td rowspan="2">3.45</td>
            <td>017</td>
            <td>018</td>
          </tr>
          <tr>
            <td>102</td>
            <td>Rabeya</td>
            <td>019</td>
            <td>015</td>
          </tr>
          <tr>
            <td>102</td>
            <td>Rabeya</td>
            <td>3.95</td>
            <td>019</td>
            <td>015</td>
          </tr>
        </tbody>
      </table>
    </body>
  </html>
  ```

  output of the above html code
  ![table5](images/table5.png)

#### Accessible table

- `<th scope="col/row">`
- An example of accessible table using scope is given below:

  ```html
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <title>Document</title>

      <style>
        table,
        th,
        td {
          border: 1px solid;
          border-collapse: collapse;
        }
      </style>
    </head>
    <body>
      <table>
        <caption>
          Student Table
        </caption>
        <thead>
          <tr>
            <th scope="col">Student ID</th>
            <th scope="col">Name</th>
            <th scope="col">Age</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">101</th>
            <td>Anis</td>
            <td>31</td>
          </tr>
          <tr>
            <th scope="row">102</th>
            <td>Rabeya</td>
            <td>30</td>
          </tr>
        </tbody>
      </table>
    </body>
  </html>
  ```

  output of the above html code
  ![table6](images/table6.png)

  An example of table using `<colgroup> & <col>` tags is given below:

  ```html
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <title>Document</title>

      <style>
        table,
        th,
        td {
          border: 1px solid;
          border-collapse: collapse;
        }
      </style>
    </head>
    <body>
      <table>
        <caption>
          Student Table
        </caption>
        <colgroup>
          <col span="2" style="background-color: tomato" />
        </colgroup>
        <thead>
          <tr>
            <th scope="col">Student ID</th>
            <th scope="col">Name</th>
            <th scope="col">Age</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">101</th>
            <td>Anis</td>
            <td>31</td>
          </tr>
          <tr>
            <th scope="row">102</th>
            <td>Rabeya</td>
            <td>30</td>
          </tr>
        </tbody>
      </table>
    </body>
  </html>
  ```

  output of the above html code
  ![table7](images/table7.png)

### 8. Form Basics

Forms are essential for collecting user input on web pages. HTML provides a variety of elements to create forms and handle user input effectively. Here’s a detailed explanation of the form elements, input types, and form attributes:

#### Form Elements

Forms are created using the `<form>` element, and various input controls can be placed inside it to collect data from the user.

**1. `<form>` Element**:

The `<form>` element defines a form that collects user input. It can contain various input elements like text fields, checkboxes, radio buttons, and more.

**Syntax**:

```html
<form action="submit_url" method="post">
  <!-- Form elements go here -->
</form>
```

**Example**:

```html
<form action="/submit-form" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <button type="submit">Submit</button>
</form>
```

**2. `<input>` Element**:

The `<input>` element is used to create various types of input fields, such as text, password, email, etc.

**Syntax**:

```html
<input type="input_type" name="name">
```

**Example**:

```html
<input type="text" name="username" placeholder="Enter your username">
```

**3. `<textarea>` Element**:

The `<textarea>` element is used for multi-line text input.

**Syntax**:

```html
<textarea name="name" rows="number" cols="number"></textarea>
```

**Example**:

```html
<textarea name="comments" rows="4" cols="50" placeholder="Enter your comments"></textarea>
```

**4. `<button>` Element**:

The `<button>` element represents a clickable button. It can be used to submit a form.

**Syntax**:

```html
<button type="button_type">Button Text</button>
```

**Example**:

```html
<button type="submit">Submit</button>
<button type="reset">Reset</button>
```

**5. `<select>` and `<option>` Elements**:

The `<select>` element creates a dropdown list, and the `<option>` elements define the options within the dropdown list.

**Syntax**:

```html
<select name="name">
  <option value="value1">Option 1</option>
  <option value="value2">Option 2</option>
</select>
```

**Example**:

```html
<select name="country">
  <option value="us">United States</option>
  <option value="ca">Canada</option>
  <option value="uk">United Kingdom</option>
</select>
```

#### Input Types

The `<input>` element supports various types, each suitable for different kinds of data.

**Common Input Types**:

- `text`: Single-line text input.
- `password`: Password input (masked characters).
- `email`: Email address input.
- `number`: Numeric input.
- `date`: Date input.
- `checkbox`: Checkbox input.
- `radio`: Radio button input.
- `submit`: Submit button.
- `reset`: Reset button.

**Example**:

```html
<form action="/submit-form" method="post">
  <label for="username">Username:</label>
  <input type="text" id="username" name="username">
  
  <label for="password">Password:</label>
  <input type="password" id="password" name="password">
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email">
  
  <label for="age">Age:</label>
  <input type="number" id="age" name="age" min="1" max="100">
  
  <label for="dob">Date of Birth:</label>
  <input type="date" id="dob" name="dob">
  
  <label for="newsletter">Subscribe to newsletter:</label>
  <input type="checkbox" id="newsletter" name="newsletter">
  
  <p>Gender:</p>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male</label>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label>
  
  <button type="submit">Submit</button>
  <button type="reset">Reset</button>
</form>
```

#### Form Attributes

Forms have several attributes that define how the data is sent and handled.

**1. `action` Attribute**:

The `action` attribute specifies the URL to which the form data will be sent when the form is submitted.

**Syntax**:

```html
<form action="submit_url">
  <!-- Form elements go here -->
</form>
```

**Example**:

```html
<form action="/submit-form" method="post">
  <!-- Form elements go here -->
</form>
```

**2. `method` Attribute**:

The `method` attribute specifies the HTTP method to be used when submitting the form. Common values are `GET` and `POST`.

**Syntax**:

```html
<form method="method_type">
  <!-- Form elements go here -->
</form>
```

**Example**:

```html
<form action="/submit-form" method="post">
  <!-- Form elements go here -->
</form>
```

- **GET**: Appends the form data to the URL, suitable for form submissions where data is not sensitive.
- **POST**: Sends the form data in the request body, suitable for form submissions where data is sensitive.

**3. `name` Attribute**:

The `name` attribute specifies the name of the form element. It is used to identify form data after submission.

**Syntax**:

```html
<input type="text" name="name">
```

**Example**:

```html
<form action="/submit-form" method="post">
  <label for="username">Username:</label>
  <input type="text" id="username" name="username">
  <button type="submit">Submit</button>
</form>
```

#### Putting It All Together for form

Here’s an example form that includes various input types, form elements, and attributes:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Example</title>
</head>
<body>
    <h1>Registration Form</h1>
    <form action="/submit-form" method="post">
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" required>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="age">Age:</label>
        <input type="number" id="age" name="age" min="1" max="100">
        
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob">
        
        <label for="comments">Comments:</label>
        <textarea id="comments" name="comments" rows="4" cols="50"></textarea>
        
        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="us">United States</option>
            <option value="ca">Canada</option>
            <option value="uk">United Kingdom</option>
        </select>
        
        <label for="newsletter">Subscribe to newsletter:</label>
        <input type="checkbox" id="newsletter" name="newsletter">
        
        <p>Gender:</p>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>
        
        <button type="submit">Submit</button>
        <button type="reset">Reset</button>
    </form>
</body>
</html>
```

#### Summary for form

- **Form Elements**: Use `<form>` to define a form, and `<input>`, `<textarea>`, `<button>`, `<select>`, and `<option>` for various input controls.
- **Input Types**: Common types include `text`, `password`, `email`, `number`, `date`, `checkbox`, `radio`, `submit`, and `reset`.
- **Form Attributes**: Use `action` to specify the form submission URL, `method` to specify the HTTP method, and `name` to identify form elements.

By understanding and utilizing these form elements, input types, and attributes, you can create effective and user-friendly forms for collecting and processing user input on your web pages.

### 9. Semantic HTML

Semantic HTML

Semantic Tags:
- `<header>`: Represents the introductory content or a group of navigational links.
- `<nav>`: Represents a section of navigation links.
- `<main>`: Represents the dominant content of the `<body>`.
- `<article>`: Represents a self-contained composition in a document (e.g., a blog post).
- `<section>`: Represents a standalone section of content.
- `<footer>`: Represents the footer for a section or document.
- Importance of Semantic HTML:
  - Enhances the accessibility of web content.
  - Improves SEO (Search Engine Optimization) by providing meaningful context to search engines.
  - Helps developers understand the structure and purpose of different sections of a web page.

- div can help to divide screen but it is not semantic
- purpose of HTML5

  - adding more semantic tags
  - more form types
  - improve accessibility
  - improved storage facilities
  - improved graphics & media
  - remove few things

- HTML5 Semantic elements: `<header> <nav> <main> <article> <aside> <section> <footer> <figure> <figcaption> <details> <summary> <mark> <time>`

- sematic tags vs non semantic tags

  - semantic tags are meaningful tags for human, search engine. example: `<form> <table> <p> <h1> etc.`
  - non-semantic tags are not meaningful tags for human, search engine. example: `<span> <div> etc.`
  - sematic tags vs non semantic tags example is given below:
    ![semantic](images/semantic.png)

### 10. Demo for basic HTML

```html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>
  </head>
  <body>
    <!--Section: navbar -->
    <nav>
      <ul>
        <li>
          <a href="#about">About Me</a>
        </li>
        <li>
          <a href="#skills">My Skills</a>
        </li>
        <li>
          <a href="#projects">My Projects</a>
        </li>
        <li>
          <a href="#contact">Contact Me</a>
        </li>
      </ul>
    </nav>

    <!--Section: intro -->
    <header id="intro">
      <h1>Anisul Islam</h1>
      <p><em>Web developer and Lecturer of Computer Sceience</em></p>
      <a href="https://www.youtube.com/channel/UCEXwc6mNh7Lakj6lX-7a2Mg">
        <img src="./images/anis.jpeg" alt="Anisul Islam" height="150" />
      </a>

      <hr />
    </header>

    <!--Section: about me -->
    <section id="about">
      <h2>About Me</h2>
      <p><strong>Experience:</strong> 5 years expercince in web development</p>
      <p>
        <strong>Education:</strong> Master's in Software, Web and cloud
        computing
      </p>
    </section>

    <!--Section: Skills -->
    <section id="skills">
      <h2>Skills</h2>

      <table border="1" cellpadding="5" cellspacing="0">
        <thead>
          <tr>
            <th>Technology</th>
            <th>Proficiency</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>HTML</td>
            <td>Expert</td>
          </tr>
          <tr>
            <td>CSS</td>
            <td>Expert</td>
          </tr>
          <tr>
            <td>JavaScript</td>
            <td>Intermediate</td>
          </tr>
        </tbody>
      </table>
    </section>

    <!--Section: Projects -->
    <section id="projects">
      <h2>Projects</h2>
      <ol>
        <li>
          <a
            target="_blank"
            href="https://github.com/anisul-Islam/portfolio-html"
            >portfolio website</a
          >
        </li>
        <li>Blog website</li>
        <li>E-commerce website</li>
      </ol>
    </section>

    <!--Section: Contacts -->
    <section id="contact">
      <h2>Contact Me</h2>
      <form>
        <div>
          <label for="name">Name : </label>
          <input type="text" id="name" name="name" required />
        </div>

        <div>
          <label for="email">Email : </label>
          <input type="email" id="email" name="email" required />
        </div>

        <div>
          <label for="message">Meassage : </label>
          <textarea name="message" id="message" cols="20" rows="10"></textarea>
        </div>

        <button type="submit">Submit</button>
        <button type="reset">Clear</button>
      </form>
    </section>

    <!--Section: footer -->
    <footer>
      <p>Copyright reserved by &copy; Anisul2024</p>
      <p>Developed with &hearts;</p>
      <a href="tel:01710444700"> Call me</a>
      <a href="mailto:anisul@yahoo.co.uk">Email me</a>
    </footer>
  </body>
</html>

```

### 11. [Assignment for basic HTML](https://github.com/anisul-Islam/full-stack-assignment-3-html)

## Intermdiate Level

### 3.1 Meta tags & SEO

- Using meta tags (`<meta>`) to define page metadata, such as title, description, and keywords.
  Understanding the impact of meta tags on search engine optimization (SEO).

```html
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Free complete html tutorials 2021" />
  <meta name="keywords" content="HTML, html, html5" />
  <meta name="author" content="Anisul Islam" />
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
      background-color: aquamarine;
    }
  </style>
  <script src="index.js"></script>
  <title>Document</title>
</head>
```

- Inside `<head>` tag we can define metadata(document title, character set, links, scripts, styles), other information that will not be visible to the users
- meta tag provides information to the browsers and search engines about the webpage
- `<meta charset="UTF-8" />` defines the character encoding for the HTML document.
- `<meta http-equiv="X-UA-Compatible" content="IE=edge" />` for supporting older version of IE.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0" />` defines that webpage width is related to devices width and initial zoom level is 1.
- `<link rel="stylesheet" href="style.css">` generally connects css file to html. Inside of href attribute we give the css file name.
- `<style> ... </style>` we can use `<style> ... </style>` tag directly inside the head tag for designing html elements.
- `<script src="index.js"></script>` generally connects js file to html. we can also use `<script> ... </script>` tag directly inside the body tag.

### 3.2 Adding font-awesome icon & google font

Adding Font Awesome icons and Google Fonts to your HTML project enhances the visual appeal and usability of your website. Here's an explanation of how to include both in your project:

#### Adding Font Awesome Icons

**Font Awesome** is a popular library for scalable vector icons that can be customized with CSS. To add Font Awesome icons to your HTML project, follow these steps:

1. **Include the Font Awesome CDN:**
   Add the Font Awesome CSS file to your HTML document's `<head>` section using the Content Delivery Network (CDN). This allows you to use Font Awesome icons without downloading any files.

   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Font Awesome and Google Fonts</title>
       <!-- Font Awesome CDN -->
       <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
   </head>
   <body>
       <!-- Add an icon -->
       <i class="fas fa-home"></i>
   </body>
   </html>
   ```

   The `<link>` tag above includes the Font Awesome CSS file, allowing you to use icons in your HTML document. The `i` tag with the classes `fas fa-home` adds a home icon to your page.

2. **Use Icons:**
   To use an icon, insert an `<i>` or `<span>` element and apply the relevant classes for the icon you want to use. Font Awesome uses class names to identify icons.

   ```html
   <!-- Example of using Font Awesome icons -->
   <i class="fas fa-home"></i> <!-- Home icon -->
   <i class="fas fa-envelope"></i> <!-- Envelope icon -->
   <i class="fas fa-phone"></i> <!-- Phone icon -->
   ```

#### Adding Google Fonts

**Google Fonts** provides a library of free and open-source fonts that you can use in your web projects. To add Google Fonts to your HTML project, follow these steps:

1. **Select a Font:**
   Visit [Google Fonts](https://fonts.google.com/), browse the available fonts, and select the ones you want to use. For example, let's select "Roboto."

2. **Include the Google Fonts Link:**
   Copy the `<link>` tag provided by Google Fonts and add it to the `<head>` section of your HTML document.

   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Font Awesome and Google Fonts</title>
       <!-- Font Awesome CDN -->
       <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
       <!-- Google Fonts -->
       <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
       <style>
           body {
               font-family: 'Roboto', sans-serif;
           }
       </style>
   </head>
   <body>
       <h1>Using Google Fonts and Font Awesome Icons</h1>
       <p>This is an example of using Google Fonts (Roboto) and Font Awesome icons.</p>
       <i class="fas fa-home"></i> <!-- Home icon -->
   </body>
   </html>
   ```

   The `<link>` tag above includes the Google Fonts stylesheet, which allows you to use the "Roboto" font in your HTML document.

3. **Apply the Font:**
   Use CSS to apply the selected font to your HTML elements. In this example, we've set the body to use the "Roboto" font.

   ```css
   body {
       font-family: 'Roboto', sans-serif;
   }
   ```

#### use this in the portfolio project's footer

```html
<!--Section: footer -->
<footer>
  <p>Copyright reserved by &copy; Anisul2024</p>
  <p>Developed with &hearts;</p>
  <a href="tel:01710444700">Call me</a>
  <a href="mailto:anisul@yahoo.co.uk">Email me</a>

  <!-- Social Media Section -->
  <h3>Follow Me</h3>
  <ul class="social-media">
    <li>
      <a href="https://www.facebook.com/yourprofile" target="_blank">
        <i class="fab fa-facebook-f"></i>
      </a>
    </li>
    <li>
      <a href="https://www.twitter.com/yourprofile" target="_blank">
        <i class="fab fa-twitter"></i>
      </a>
    </li>
    <li>
      <a href="https://www.linkedin.com/in/yourprofile" target="_blank">
        <i class="fab fa-linkedin-in"></i>
      </a>
    </li>
    <li>
      <a href="https://www.instagram.com/yourprofile" target="_blank">
        <i class="fab fa-instagram"></i>
      </a>
    </li>
  </ul>
</footer>
```

### 3.3 Advanced Table

- `<caption class="table-caption">My Skills and Proficiency</caption>`

#### rowspan, colspan

### 3.4 Advanced Form

- Advanced form elements (`<select>, <option>, <textarea>`)
- Form validation attributes (required, pattern, min, max)
- Form submission (method, action)

- Using form controls like text inputs, checkboxes, radio buttons, dropdowns, and submit buttons.
- HTML `<form>` Elements:

  - `<form>` element is used to create a html form. form help us to collect user data.
  - `<input />` element is the most used form element.
  - `<label>` element is used for labelling form elements. It helps the form elements accessible byguiding the screen reader. `<label for="name">` element has `for=""` attribute which value should be equal to `<input id="name"/>` element's id value.
  - `<select>` - helps to create dropdown menu.
  - `<optgroup label="programming">` - helps to create options for dropdown menu.
  - `<option>` - helps to create options for dropdown menu.
  - `<textarea>` - helps to create multiple lines text input field.
  - `<button>` - helps to create button.
  - `<fieldset>`
  - `<legend>`
  - `<output>`
  - `<datalist>` & `list=""` attributes

- form tag attributes:

  - `<form action="/home" method="post" autocomplete="on">`-> enable the autocomplete option.
  - `<form action="/home" method="post" autocomplete="on" enctype="text/plain">`-> sends data without encoding.
  - `name=""` attribute is used to set the name of any element which is essential for getting data in server side especially.

- input tag type attribute

  - `type=""` attribute can change the visualization of `<input />` element.
  - `<input type="text"/>` creates a single line text input field.
  - `<input type="email"/>` creates a single line email input field.
  - `<input type="password"/>` creates a single line password input field.
  - `<input type="number"/>` creates a single line number input field.
  - `<input type="checkbox"/>` creates a checkbox input field.
  - `<input type="radio"/>` creates a radio button input field.
  - `<input type="button"/>` creates a clikable button.
  - `<input type="submit"/>` creates a submit button for form.
  - `<input type="color"/>` creates a color picker input field.
  - `<input type="date"/>` creates a date picker.
  - `<input type="month"/>` creates a month picker.
  - `<input type="time"/>` creates a time picker.
  - `<input type="week"/>` creates a week picker.
  - `<input type="image"/>` creates a image selector.
  - `<input type="file"/>` creates a file selector.
  - `<input type="url"/>` creates a url selector.
  - `<input type="tel"/>` creates a input field for telephone number.
  - `<input type="search"/>` is used for searching.
  - `<input type="hidden"/>` creates a input field which is not visible to user.
  - `<input type="range" min="" max=""/>` creates a range by setting min and max value, default range is 0 to 100.

  ```html
  <fieldset>
    <legend>Contact Me</legend>
    <label for="email"> Email: </label>
    <input type="email" id="email" />
  </fieldset>
  ```

- HTML Forms Validation:

  - `required` attribute specifies that an input element must be filled before submitting the form.
  - `max=""` attribute is used to set the maximum input value for an input field.
  - `min=""` attribute is used to set the minimum input value for an input field.
  - `pattern=""` attribute is used to set a regular expression for validating an input field.

- others

  - `value=""` attribute is used to set initial value for input field.
  - `readonly` attribute is used to set an input field as readonly.
  - `checked` attribute is used to set an input field already checked.
  - `disabled` attribute is used to make a input field disable.
  - `size=""` attribute is used to set the number of characters for an input field.
  - `maxlength=""` attribute is used to set the maximum number of characters for an input field.

  - `placeholder=""` attribute is used to give a hint to the users.

  - `step=""` attribute specifies steps for input field.
  - `autofocus` attribute makes an input field automatically focus when the page is loaded.
  - `height="" width=""` attribute is used to set input elements height and width.
  - `list="id_of_datalist"` attribute is used to set input elements height and width.

- update the portfolio project

```html
 <!--Section: Contacts -->
    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <div>
                <label for="name">Name : </label>
                <input type="text" id="name" name="name" required />
            </div>

            <div>
                <label for="email">Email : </label>
                <input type="email" id="email" name="email" required />
            </div>

            <div>
                <label for="subject">Subject : </label>
                <select id="subject" name="subject" required>
                    <option value="">Select a subject</option>
                    <option value="inquiry">Inquiry</option>
                    <option value="feedback">Feedback</option>
                    <option value="job">Job Opportunity</option>
                </select>
            </div>

            <div>
                <label for="message">Message : </label>
                <textarea name="message" id="message" cols="30" rows="5" required></textarea>
            </div>

            <div>
                <label for="age">Age : </label>
                <input type="number" id="age" name="age" min="1" max="100" />
            </div>

            <div>
                <label for="website">Website : </label>
                <input type="url" id="website" name="website" pattern="https?://.+" />
            </div>

            <div>
                <label for="image">Upload Image : </label>
                <input type="file" id="image" name="image" accept="image/*" />
            </div>

            <button type="submit">Submit</button>
            <button type="reset">Clear</button>
        </form>
    </section>

```

- A form example is given below:

  ```html
  <form action="/" method="post">
    <div>
      <datalist id="usernames">
        <option value="anis"></option>
        <option value="linkon"></option>
        <option value="ridoy"></option>
      </datalist>

      <label for="username">Username: </label>
      <input
        type="text"
        id="username"
        name="username"
        size="30"
        autofocus
        required
        list="usernames"
      />
    </div>
    <br />
    <div>
      <label for="password">Password: </label>
      <input type="password" id="password" name="password" required />
    </div>
    <br />
    <div>
      <label for="email">Email: </label>
      <input type="email" id="email" name="email" autocomplete />
    </div>
    <br />
    <div>
      <label for="phone">phone: </label>
      <input type="tel" id="phone" name="phone" />
    </div>
    <br />
    <div>
      <label for="dob">Date of birth: </label>
      <input type="date" id="dob" name="dob" />
    </div>
    <br />
    <div>
      <label for="month">favourite Month: </label>
      <input type="month" id="month" name="month" />
    </div>
    <br />
    <div>
      <label for="random">Select a random number from 1 to 5: </label>
      <input
        type="number"
        id="random"
        name="random"
        min="1"
        max="5"
        value="3"
      />
    </div>
    <br />
    <div>
      <label for="profile">Select your image: </label>
      <input type="image" id="profile" name="profile" />
    </div>
    <br />
    <div>
      <label for="file">Select a file: </label>
      <input type="file" id="file" name="file" />
    </div>
    <br />
    <div>
      <label for="color">Select favourite color: </label>
      <input type="color" id="color" name="color" />
    </div>
    <br />
    <div>
      <label for="website">Paste your website's url: </label>
      <input type="url" id="website" name="website" />
    </div>

    <!-- checkbox disable-->
    <br />
    <div>
      <p>Religion:</p>
      <div>
        <input type="checkbox" id="muslim" checked />
        <label for="muslim">muslim</label>
      </div>
      <div>
        <input type="checkbox" id="hindu" />
        <label for="hindu">hindu</label>
      </div>
      <div>
        <input type="checkbox" id="other" disabled />
        <label for="other">other</label>
      </div>
    </div>
    <!-- radiobutton -->
    <br />
    <div>
      <p>Gender:</p>
      <div>
        <input type="radio" id="male" name="gender" />
        <label for="male">male</label>
      </div>
      <div>
        <input type="radio" id="female" name="gender" />
        <label for="female">female</label>
      </div>
      <div>
        <input type="radio" id="other" name="gender" />
        <label for="other">other</label>
      </div>
    </div>
    <!-- dropdown menu -->
    <br />
    <div>
      <label for="department">Department: </label>
      <select name="department" id="department">
        <option value="cse">CSE</option>
        <option value="eee">EEE</option>
        <option value="llb">LLB</option>
      </select>
    </div>
    <!-- textarea -->
    <br />
    <div>
      <label for="message">Message: </label> <br />
      <textarea name="" id="message" cols="30" rows="10"></textarea>
    </div>
    <!-- button -->
    <br />
    <div>
      <button type="submit">Save Data</button>
      <button type="reset">Clear</button>
    </div>
  </form>
  ```

  output of the above html code
  ![form](images/form.png)

### 3.5 Send form data to your email using third-party API

- https://formspree.io/
- add the endpoint

### 3.6 Multimedia Elements in HTML

Multimedia elements in HTML allow you to embed and manage various media types such as videos, audio, and other media objects. Here's an overview of the main multimedia elements and how to use them:

#### Embedding Videos: `<video>`

The `<video>` element is used to embed video content in an HTML document. It supports various attributes to control playback, including `controls`, `autoplay`, `loop`, and more.

**Example:**

```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
```

- **`src`**: Specifies the path to the video file.
- **`type`**: Specifies the MIME type of the video file.
- **`controls`**: Adds play, pause, and volume controls.
- **`autoplay`**: Starts playing the video automatically (not recommended for user experience).
- **`loop`**: Loops the video playback.

#### Embedding Audio: `<audio>`

The `<audio>` element is used to embed sound content in an HTML document. It can also be controlled with various attributes similar to the `<video>` element.

**Example:**

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  <source src="audio.ogg" type="audio/ogg">
  Your browser does not support the audio element.
</audio>
```

- **`src`**: Specifies the path to the audio file.
- **`type`**: Specifies the MIME type of the audio file.
- **`controls`**: Adds play, pause, and volume controls.
- **`autoplay`**: Starts playing the audio automatically.
- **`loop`**: Loops the audio playback.

#### Embedding Other Media Objects: `<embed>`, `<object>`, and `<iframe>`

These tags allow you to embed different types of media and interactive content, such as Flash, PDF files, other web pages, and more.

**Example of `<embed>`:**

```html
<embed src="example.pdf" width="600" height="500" type="application/pdf">
```

- **`src`**: Specifies the path to the media file.
- **`type`**: Specifies the MIME type of the embedded content.
- **`width`** and **`height`**: Specify the dimensions of the embedded content.

**Example of `<object>`:**

```html
<object data="example.pdf" type="application/pdf" width="600" height="500">
  <p>Alternative text for browsers that do not support embedded objects.</p>
</object>
```

- **`data`**: Specifies the path to the media file.
- **`type`**: Specifies the MIME type of the embedded content.
- **`width`** and **`height`**: Specify the dimensions of the embedded content.

**Example of `<iframe>`:**

```html
<iframe src="https://www.example.com" width="600" height="400"></iframe>
```

- **`src`**: Specifies the URL of the page to embed.
- **`width`** and **`height`**: Specify the dimensions of the embedded iframe.
- **`frameborder`**: Specifies whether the iframe should have a border (1 or 0).
- **`allowfullscreen`**: Allows the iframe content to be displayed in fullscreen mode.

#### Summary of multimedia

- **`<video>`**: Embed video files with various playback controls.
- **`<audio>`**: Embed audio files with playback controls.
- **`<embed>`**: Embed other media types like PDFs and Flash.
- **`<object>`**: Embed various media types, providing fallback content.
- **`<iframe>`**: Embed another HTML page or content into the current document.

These elements and tags enhance the multimedia experience on web pages, allowing you to present a rich variety of content seamlessly.

### 3.7 Download PDF button

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Download PDF Example</title>
    <style>
        .download-btn {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            color: white;
            background-color: blue;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>Download PDF Example</h1>
    <a href="path/to/yourfile.pdf" download="YourFileName.pdf" class="download-btn">
        Download PDF
    </a>
</body>
</html>

```

### 3.8 HTML5 Elements

1. **`<canvas>`**:
   - The `<canvas>` element is used to draw graphics on the web using JavaScript. It provides a resolution-dependent bitmap canvas which can be used for rendering graphs, game graphics, or other visual images.

2. **`<svg>`**:
   - The `<svg>` element is used to define vector-based graphics. Unlike bitmaps, SVG images can be scaled indefinitely without losing quality. This makes SVG ideal for logos, icons, and complex graphics that require high resolution.

3. **`<progress>`**:
   - The `<progress>` element represents the completion progress of a task, such as a download or file upload. It is typically used to show how much of the task has been completed.

4. **`<meter>`**:
   - The `<meter>` element represents a scalar measurement within a known range, such as disk usage, temperature, or battery level. It is useful for displaying values that have a known maximum and minimum.

### Adding these Elements to the Portfolio Project

Here's how you can integrate these HTML5 elements into your existing portfolio project:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>
<body>
    <!--Section: Header -->
    <header>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#skills">My Skills</a></li>
                <li><a href="#projects">My Projects</a></li>
                <li><a href="#contact">Contact Me</a></li>
            </ul>
        </nav>
    </header>

    <!--Section: Main content -->
    <main>
        <!--Section: Intro -->
        <section id="intro">
            <h1>Anisul Islam</h1>
            <p><em>Web developer and Lecturer of Computer Science</em></p>
            <a href="https://www.youtube.com/channel/UCEXwc6mNh7Lakj6lX-7a2Mg">
                <img src="./images/anis.jpeg" alt="Anisul Islam" height="150">
            </a>
            <hr>
        </section>

        <!--Section: About me -->
        <section id="about">
            <h2>About Me</h2>
            <p><strong>Experience:</strong> 5 years experience in web development</p>
            <p><strong>Education:</strong> Master's in Software, Web and Cloud Computing</p>
        </section>

        <!--Section: Skills -->
        <section id="skills">
            <h2>Skills</h2>
            <table border="1" cellpadding="5" cellspacing="0">
                <thead>
                    <tr>
                        <th>Technology</th>
                        <th>Proficiency</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>HTML</td>
                        <td>Expert</td>
                    </tr>
                    <tr>
                        <td>CSS</td>
                        <td>Expert</td>
                    </tr>
                    <tr>
                        <td>JavaScript</td>
                        <td>Intermediate</td>
                    </tr>
                </tbody>
            </table>

            <!-- Using <progress> to show skill level completion -->
            <h3>Skill Progress</h3>
            <label for="htmlProgress">HTML:</label>
            <progress id="htmlProgress" value="90" max="100">90%</progress><br>
            <label for="cssProgress">CSS:</label>
            <progress id="cssProgress" value="80" max="100">80%</progress><br>
            <label for="jsProgress">JavaScript:</label>
            <progress id="jsProgress" value="70" max="100">70%</progress>

            <!-- Using <meter> to show experience level -->
            <h3>Experience Level</h3>
            <label for="experienceLevel">Experience:</label>
            <meter id="experienceLevel" min="0" max="10" value="5">5 years</meter>
        </section>

        <!--Section: Projects -->
        <section id="projects">
            <h2>Projects</h2>
            <ol>
                <li>
                    <a target="_blank" href="https://github.com/anisul-Islam/portfolio-html">Portfolio Website</a>
                </li>
                <li>Blog Website</li>
                <li>E-commerce Website</li>
            </ol>
        </section>

        <!--Section: Drawing and Graphics -->
        <section id="graphics">
            <h2>Graphics</h2>
            <!-- Using <canvas> for drawing -->
            <h3>Canvas Example</h3>
            <canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;"></canvas>
            <script>
                const canvas = document.getElementById('myCanvas');
                const ctx = canvas.getContext('2d');
                ctx.fillStyle = '#FF0000';
                ctx.fillRect(10, 10, 150, 75);
            </script>

            <!-- Using <svg> for vector graphics -->
            <h3>SVG Example</h3>
            <svg width="100" height="100">
                <circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red" />
                <text x="50" y="55" font-size="20" text-anchor="middle" fill="white">SVG</text>
            </svg>
        </section>

        <!--Section: Contacts -->
        <section id="contact">
            <h2>Contact Me</h2>
            <form>
                <div>
                    <label for="name">Name: </label>
                    <input type="text" id="name" name="name" required>
                </div>

                <div>
                    <label for="email">Email: </label>
                    <input type="email" id="email" name="email" required>
                </div>

                <div>
                    <label for="subject">Subject: </label>
                    <select id="subject" name="subject" required>
                        <option value="">Select a subject</option>
                        <option value="inquiry">Inquiry</option>
                        <option value="feedback">Feedback</option>
                        <option value="job">Job Opportunity</option>
                    </select>
                </div>

                <div>
                    <label for="message">Message: </label>
                    <textarea name="message" id="message" cols="30" rows="5" required></textarea>
                </div>

                <div>
                    <label for="age">Age: </label>
                    <input type="number" id="age" name="age" min="1" max="100">
                </div>

                <div>
                    <label for="website">Website: </label>
                    <input type="url" id="website" name="website" pattern="https?://.+">
                </div>

                <div>
                    <label for="file">Upload CV: </label>
                    <input type="file" id="file" name="file" accept=".pdf">
                </div>

                <button type="submit">Submit</button>
                <button type="reset">Clear</button>
            </form>
        </section>
    </main>

    <!--Section: Footer -->
    <footer>
        <p>Copyright reserved by &copy; Anisul2024</p>
        <p>Developed with &hearts;</p>
        <a href="tel:01710444700"> Call me</a>
        <a href="mailto:anisul@yahoo.co.uk">Email me</a>
        <div class="social-media">
            <a href="https://facebook.com/yourprofile" target="_blank"><i class="fab fa-facebook"></i></a>
            <a href="https://twitter.com/yourprofile" target="_blank"><i class="fab fa-twitter"></i></a>
            <a href="https://linkedin.com/in/yourprofile" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="https://github.com/yourprofile" target="_blank"><i class="fab fa-github"></i></a>
        </div>
    </footer>
</body>
</html>
```

#### Explanation

1. **`<canvas>`**: Added to the "Graphics" section to draw a simple red rectangle using JavaScript.
2. **`<svg>`**: Added to the "Graphics" section to create a scalable vector graphic (SVG) with a red circle and white text.
3. **`<progress>`**: Added to the "Skills" section to display the progress of proficiency levels for different skills.
4. **`<meter>`**: Added to the "Skills" section to show the experience level as a scalar measurement.

By incorporating these elements, you can showcase the capabilities of HTML5 in handling graphics, progress indicators, and scalar measurements, enhancing the interactivity and visual appeal of your portfolio.

### details and figure elements

- `<details>` elements have tewo states: closed, open
- `<summary>` a short summary of details is provided by summary element
- `<figure>` can have diagram, photos inside of it.
- `<figcaption>` can set the figure caption.

  An example of details, summary elements are given below:

  ```html
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <title>Document</title>
      <style>
        details[open] > summary {
          background-color: aqua;
        }
      </style>
    </head>
    <body>
      <details>
        <summary>Anisul Islam</summary>
        My Name is Anisul Islam. I am 31 years old. I have done my masters in
        Software, Web & cloud at Tampere University, Finland.
      </details>

      <!-- no need to understand this part cause I just tested using javascript here -->
      <!-- <script>
        const details = document.querySelector("details");
        details.addEventListener("toggle", () => {
          if (details.open) {
            console.log("open");
          } else {
            console.log("close");
          }
        });
      </script> -->
      <figure>
        <img src="./images/list.png" alt="list" />
        <figcaption>fig1: list image</figcaption>
      </figure>
    </body>
  </html>
  ```

  output of the heading style code  
   ![details1](images/details1.png)
  ![details2](images/details2.png)

## Advanced Level

### 3.4 Web accessibility

- what is web accessibility?
  - making website supportive for disable people and search engine
- how to check web accessibility?
  - inspect -> lighthouse -> accessibility
  - axe Devtools for accessibility testing
  - chromeVox for screen reading

1. Use Semantic elements over non semantic elements.

- semantic tags are meaningful tags for human, search engine. example: `<form> <table> <p> <h1> etc.`
- non-semantic tags are not meaningful tags for human, search engine. example: `<span> <div> etc.`
- In the following example button is more accessible than div for making a button. Semantic elements help the screen readers.

```html
<div>Click me</div>
<button>Click me</button>
```

- Example of explicit semantic vs implicit sematic element

```html
<div role="button">Click me</div>
<button>Click me</button>
```

- landmarks helps to naviagte from one place to another: header, h1...h6, main, nav, footer

2. Use Heading tags in order

- use one h1 element in a webpage
- keep sequence when using: h1 -> h2 -> h3 ... (follow top-down order)

3. Use alt attribute

- use alt attribute for `<img />` element
- alt attribute provides more info to the blind people
- low bandwidth might not render the image so the alt will help here
- alt attributes helps technologies like search engines
- title attribute can be used when we hover over image to get extra information

4. Contrast ratio checker

- use contrast ratio checker for foreground and background color: https://webaim.org/resources/contrastchecker/

5. Declare the languages

- `<html lang="en">`

6. Meaningful Link txt

- make link text descriptive, understandable and clear `<a href="http://studywithanis.com" target="_blank"> Visit Anisul Islam's website </a>`

7. Form related matters

- use label and bind input elements with label by using id and for value same. example is given below:

  ```html
  <label for="email">Email: </label> <input type="email" id="email" />

  <div class="form-control">
    <fieldset>
      <legend>Choose Gender:</legend>
      <div class="form-control">
        <input type="radio" id="male" name="gender" value="male" />
        <label for="male">Male</label>
      </div>
      <div class="form-control">
        <input type="radio" id="female" name="gender" value="female" />
        <label for="female">Female</label>
      </div>
    </fieldset>
  </div>
  ```

8.  use aria-label vs aria-labelby vs aria-descriptionby

- these attribute has no visual impact but they are for assistive purpose. use them only when you can not use semantic elements
- The aria-label and aria-labelledby attributes are both used to give an element it's accessible name.
- using forms with standards labels - you shouldn't need it at all: -> label, for is more than enough
- **_aria-label_** add accessible name directly to an element and it has higher priority than the element value. In the following example screen reader will say learn more about me instead of learn more

  ```html
  <button aria-label="Learn more about me">Learn more</button>
  ```

- **_aria-labelby_** create a relationship between elements

  ```html
  <h3 id="hobbies">Hobbies</h3>
  <ul aria-labelledby="hobbies">
    <li>Playing Football</li>
    <li>Playing Badminton</li>
    <li>Swimming</li>
  </ul>
  ```

- **_aria-descriptionby_**

  ```html
  <div>
    <label for="password"> Password </label>
    <input
      type="password"
      name="password"
      id="password"
      aria-describedby="help"
      required
    />
    <div id="help">Pasword must be at least 8 character long</div>
  </div>
  ```

9. role and tabindex -> tabindex can start from 0 then -1, -2 for lesser priority so that you can navigate by keyboard one after one in an order

```HTML
  <!-- use nav, role, tabindex, aria-label for an accessible navbar  -->

  <!-- NOT ACCESSIBLE -->
  <div id="nav">
    <a href="#">Home</a>
    <a href="#about">About Me</a>
    <a href="#tutorial">Tutorials</a>
    <a href="#contact">Contact Me</a>
  </div>

  <!-- ACCESSIBLE  -->
  <nav aria-label="navigation menu">
    <ul id="menubar" role="menubar" aria-label="navigation menu">
      <li role="none">
        <a href="#" role="menuitem" tabindex="-1">Home</a>
      </li>
      <li role="none">
        <a href="#about" role="menuitem" tabindex="-1">About Me</a>
      </li>
      <ul role="menu" aria-label="tutorials">
        <li role="none">
          <a href="#tutorials" role="menuitem" tabindex="0">Tutorials</a>
          <ul>
            <li role="none">
              <a href="#html" role="menuitem" tabindex="-1">HTML</a>
            </li>
            <li role="none">
              <a href="#css" role="menuitem" tabindex="-1">CSS</a>
            </li>
          </ul>
        </li>
      </ul>
      <li role="none">
        <a href="#contact" role="menuitem" tabindex="-1">Contact Me</a>
      </li>
    </ul>
  </nav>
```

- References:
- https://www.w3.org/WAI/fundamentals/accessibility-intro/
- https://www.w3schools.com/html/html_accessibility.asp

### 3.5 Graphics

#### progress bar and svg

- `<img src="imageName.svg">`
- `<progress min="0" max="100" value="70"> </progress>`
  <progress min="0" max="100" value="70"> </progress>
- you will learn more about svg and canvas in CSS and Javascript playlist

### 3.6 HTML5 API

- Exploring HTML5 APIs like Geolocation, Drag and Drop, Web Storage, and Web Workers. Understanding their usage and practical applications.

1. **Geolocation API**:

   - The Geolocation API allows you to retrieve the user's geographic location information.
   - Example:

     ```js
     if (navigator.geolocation) {
       navigator.geolocation.getCurrentPosition(function (position) {
         var latitude = position.coords.latitude;
         var longitude = position.coords.longitude;
         console.log('Latitude: ' + latitude + ', Longitude: ' + longitude);
       });
     } else {
       console.log('Geolocation is not supported by this browser.');
     }
     ```

2. **Drag and Drop API**:

   - The Drag and Drop API enables you to create drag-and-drop interactions between elements on a web page.
   - Example:

     ```javascript
     var draggableElement = document.getElementById('draggable');
     var dropZone = document.getElementById('drop-zone');

     draggableElement.addEventListener('dragstart', function (event) {
       event.dataTransfer.setData('text/plain', event.target.id);
     });

     dropZone.addEventListener('dragover', function (event) {
       event.preventDefault();
     });

     dropZone.addEventListener('drop', function (event) {
       event.preventDefault();
       var data = event.dataTransfer.getData('text/plain');
       var element = document.getElementById(data);
       dropZone.appendChild(element);
     });
     ```

3. **Web Storage API**:

   - The Web Storage API provides a way to store key-value pairs locally in the user's browser.
   - Example:

     ```javascript
     // Store data
     localStorage.setItem('username', 'John');

     // Retrieve data
     var username = localStorage.getItem('username');
     console.log(username);

     // Remove data
     localStorage.removeItem('username');
     ```

4. **Canvas API**:

   - The Canvas API allows you to draw graphics and animations on a web page using JavaScript.
   - Example:

     ```javascript
     var canvas = document.getElementById('my-canvas');
     var context = canvas.getContext('2d');

     context.fillStyle = 'red';
     context.fillRect(50, 50, 100, 100);

     context.strokeStyle = 'blue';
     context.lineWidth = 2;
     context.strokeRect(75, 75, 50, 50);

     context.beginPath();
     context.arc(150, 150, 50, 0, 2 * Math.PI);
     context.fillStyle = 'green';
     context.fill();
     context.closePath();
     ```

### 3.7 HTML Templates and Web Components

- Building reusable HTML templates and components using `<template>` and custom elements.

  ```html
  <template id="user-template">
    <div class="user-card">
      <h2 class="user-name"></h2>
      <p class="user-email"></p>
    </div>
  </template>

  <script>
    // Clone the template and populate the data
    var template = document.getElementById('user-template');
    var clone = template.content.cloneNode(true);
    clone.querySelector('.user-name').textContent = 'John Doe';
    clone.querySelector('.user-email').textContent = 'john.doe@example.com';

    // Insert the cloned template into the document
    document.body.appendChild(clone);
  </script>
  ```

- Leveraging frameworks like Angular, React, or Vue.js for more advanced component-based development.
