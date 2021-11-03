# My HTML Documentation

### Total Chapters are following

1. Introduction
2. Typography
3. List, Image, Link
4. Div, Display
5. Table
6. Form
7. Media (audio, video)
8. Graphics
9. HTML5 & Web Accessibility
10. Projects

<br />

## Chapter 1: Introduction

### [1.1 Introduction to HTML](https://youtu.be/d35dfSwBTNY)

#### What is HTML & Why HTML?

- HTML stands for Hyper Text Markup Language
- It is not a **programming language**
- HTML helps us to create the main structure of a webpage
- With the help of markup tag we can display text, image, video etc. on the webpage

#### History of HTML

- Tim Berners-Lee created HTML in 1991

<br />

### [1.2 Tag, content, attribute, element](https://youtu.be/SEZ7YCF141I)

#### What is Tag & its syntax?

- Tag is the heart of html; HTML document is mainly built with tag.
- Tag Syntax: `<keyword>` ; Inside the angular brackets we need to write predefined keywords to use html tag.
- Small / capital letters both can be used when writing html tag; however small letter is prefered.
- Example: `<p> This is a paragraph </p>`
- In the example, `<p>` is an opening tag, `</p>` is a closing tag and `This is a paragraph` is called content
- In between the starting tag to end tag we have content
- Everything from starting tag to end tag is called Element

#### What are the types of Tag?

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
  ....

  <!-- Some examples of Empty Tag -->
  <br />
  <hr />
  <img />
  <input />
  ...
  ```

#### What is attribute & how to use attribute?

- Attribute helps tag to extend its capabilities
- In the following example, `<img/>` is tag; src, height, width are the attributes
  ```html
  <img src="anis.jpg" height="200" width="200" />
  ```
- Attribute Syntax: `attributeName="attributeValue"`

<br />

### [1.3 Structure of an HTML document](https://youtu.be/t9FkGMxsz_g)

#### HTML basic structure

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

#### Environment setup

- Editor: VScode / Notepad++ / Sublime
- Browser: Google Chrome / Firefox
- Version Control: GitHub

<br/>

### [1.4 First HTML Program](https://youtu.be/j4jh3iZ6t-M)

#### Example of a basic webpage

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
  </head>
  <body>
    This is my first webpage <br />
    I am Anisul Islam <br />
    A full stack web developer & passionate computer science teacher<br />
  </body>
</html>
```

- Here, lang attribute refers to the language; attribute value en refers to english
- Inside `<head>` tag we have set title of the webpage using `<title>` tag
- Inside `<body>` tag we are displaying some text. here `<br/>` tag creates a line break

<br/>

### [1.5 Inside Head Tag]()

#### Example

```html
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
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

<br/>

### [1.6 Debugging](https://youtu.be/ApmhBx908Ik)

- After writing your html code you can check the validity on this website https://validator.w3.org/

<br/>
<br/>

## Chapter 2: Typography

### [2.1 Headings, Paragraph, Horizontal rule](https://youtu.be/NX7YoHFll6s)

#### Example

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

- There are 6 HTML heading levels. `<h1>` is the largest level and `<h6>` is the smallest level.
- by default, heading tags and paragraph tag create new line (block level element)
- `<hr size="2"/>` here `<hr/>` is an empty tag responsible for creating horizontal rule and size attribute set the heights of the horizontal rule in pixel

<br/>

### [2.2 Styling html elemnts](https://youtu.be/yOxgDRpr6kE)

#### Example

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
- some tools for selecting color
  - [htmlcolorcodes][htmlcolorcodes]
  - [imagecolorpicker][imagecolorpicker]
  - [colorhunt][colorhunt]
  - [colorzilla][colorzilla]

<br/>

### [2.3 Text Formatting tags](https://youtu.be/3LYkVHPA7V8)

#### Example

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
</body>
```

<br/>

### [2.4 How to write bangla in html documentation](https://youtu.be/cTdMbPHvH68)

<br/>

### [2.5 Entity, pre tag, comment](https://youtu.be/7YOZEFX1hTQ)

<!-- various links -->

[colorzilla]: https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?hl=en
[colorhunt]: https://colorhunt.co/
[imagecolorpicker]: https://imagecolorpicker.com/
[htmlcolorcodes]: https://htmlcolorcodes.com/
