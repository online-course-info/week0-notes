
# Requirements for this course:
>**Have the Visual Studio Code IDE installed aka `vs code`**
>**Have the following Visual Studio Code extensions:**

>_Live server_

>_Prettier_

>_Github_

>**You must _HAVE_ a `GitHub` account***
# HTML INTRODUCTION
***What is the HTML?***
>HTML stands for Hyper Text Markup Language

>HTML is the standard markup language for creating Web pages

>HTML describes the structure of a Web page

>HTML consists of a series of elements

>HTML elements tell the browser how to display the content

>HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

# FIRST HTML CODE LINES

**I know you are eager to write your first `HTML` code, but first let me tell you about some HTML `tags`**

>The `<!DOCTYPE html>` declaration **defines** that this document is an HTML document and content

>The `<html>` element is the **root** element of an HTML page

>The `<head>` element contains meta information about the HTML page

>The <title> element **specifies** a title for the HTML page (which is shown in the browser's title bar or in the page's tab like this)
![image](https://user-images.githubusercontent.com/119107805/204101802-3db6f16c-7d1e-4a63-bec0-fb83cf1088db.png)

>The `<body>` element defines the document's body, and is a **container for all the visible contents**, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.

**This is a simple HTML code:**
```html
<!DOCTYPE html>
<html>
    <head>
      <title>This is my page on this browser</title>
      // your html code
    <head>
    <body>
         // your html code
    </body>
<html>
```
# The `<!DOCTYPE>` Declaration

  >The `<!DOCTYPE>` declaration represents the document type, and helps browsers to display web pages correctly
  
  >It **must** only appear once, at the top of the page (before any HTML tags)
  
  >The `<!DOCTYPE>` declaration is not case sensitive
  
  >The `<!DOCTYPE>` declaration for HTML is:
  
```html
  <!DOCTYPE html>
```

  **Now we will "enter" the body**

# HTML `Headings`
  
  >HTML headings are defined with the ``<h1>`` to ``<h6>`` tags
 
  >``<h1>`` defines the most important heading. ``<h6>`` defines the least important heading
  
  This is the code for HTML Headings:
 ```html
  <!DOCTYPE html>
<html>
    <head>
      <title>My first Headings</title>
    <head>
    <body>
      <h1>My Heading 1</h1>
      <h2>My Heading 2</h2>
      <h3>My Heading 3</h3>
      <h4>My Heading 4</h4>
      <h5>My Heading 5</h5>
      <h6>My Heading 6</h6>
    </body>
<html>
 ```
  _And the output will be like this:_
  
  ![image](https://user-images.githubusercontent.com/119107805/204102386-3fd328f2-c0f4-4952-9574-dbbaffe768de.png)

# HTML Paragraphs
  >HTML paragraphs **are defined** with the  ``<p>`` tag:
  
  The code for HTML Paragraphs:
  
  ```html
    <!DOCTYPE html>
<html>
    <head>
      <title>My first Paragraphs</title>
    <head>
    <body>
      <ph>This is first paragraph.</ph>
      <ph>This is second paragraph.</ph>
    </body>
<html>
  ```
  _And the output will be like this:_
  
  ![image](https://user-images.githubusercontent.com/119107805/204102574-5961d59b-beb4-49d8-9c1e-dd04b10a9141.png)
  
  **How we can separate this paragraphs?**
  
  >We can separate this paragraphs with `<br>` tag like this:
  
  ```html
    <!DOCTYPE html>
<html>
    <head>
      <title>My first Paragraphs</title>
    <head>
    <body>
      <ph>This is first paragraph.</ph>
      <br>
      <ph>This is second paragraph.</ph>
    </body>
<html>
  ```
  
  _And the output will be like this:_
  
  ![image](https://user-images.githubusercontent.com/119107805/204102679-c0a0079a-5daa-423e-8a60-ec00508a83da.png)
  
  **How we can separate this paragraphs with a horizontal line?**
  
  >We can separate this paragraphs with `<hr>` tag like this:
  
  ```html
    <!DOCTYPE html>
<html>
    <head>
      <title>My first Paragraphs</title>
    <head>
    <body>
      <ph>This is first paragraph.</ph>
      <hr>
      <ph>This is second paragraph.</ph>
    </body>
<html>
  ```
  
  _And output will be like this:_
  
  ![image](https://user-images.githubusercontent.com/119107805/204102749-fae844f1-3bd9-43f0-be95-4e929ba249ae.png)
  
  # Your "HomeWork" for next week
  
  >Your "HomeWork" for next week will be problem set 1,I will most likely send on Sunday afternoon!
  
  **Bye!**
