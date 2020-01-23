# City Tech UXC6

## Course Introduction

The basic web development course is an introduction to front end web site development. In this 6-week course, the students will be exposed to HTML5 and CSS3. By the end of this course, the student will have developed a working set of web pages with various forms of functionality based upon CSS design standards and a working understanding of JavaScript programming.

## Course Dates

- Days: Monday and Wednesday
- Time: 2PM - 5PM
- Class: Jan 22nd, 27th, 29th, Feb 3rd, 5th, 10th, 19th and 24th
- Presentation: Monday, February 24th

## What is the Internet?

The Internet is a network, or system, that connects millions of computers worldwide.

- (The Internet: HTTP & HTML) [https://www.youtube.com/watch?v=kBXQZMmiA4s]
- [What is the world wide web? - Twila Camp] (https://www.youtube.com/watch?v=J8hzJxb0rpc)

## What is a web___?

- A webpage is a single page shown in a web browser. A single video page on YouTube.com is a webpage.
- A website is a collection of webpages under a single URL (Uniform Resource Locator). Youtube (youtube.com) is a website.
- A web application is a website which offers advanced functionality like a computer program would. An example of a web application would be a web based calendar, or web based email. Youtube.com is also a web application

### Website

A website or web site is a page or collection of pages on the World Wide Web that contains specific information which was all provided by one person or entity and traces back to a common Uniform Resource Locator (URL)

URL is an acronym for Uniform Resource Locator and is a reference (an
address) to a resource on the Internet.

- For the URL http://example.com , the protocol identifier is http or https.
- For the URL http://example.com , the resource name is example.com
- [Real Talk about HTTPS] (https://www.youtube.com/watch?v=iP75a1Y9saY)

### What tool is used to access a website?

#### What is browser?

A web browser (commonly referred to as a browser) is a software application for accessing information on the World Wide Web.

Most used web browser by country, as of June 2015. Google
Chrome, Firefox, Safari, UC. Iron, Microsoft Edge, Opera and Android.

## HTML

HTML stands for HyperText Markup Language. Developed by scientist Tim
Berners-Lee in 1990, HTML is the "hidden" code that helps us communicate with others on the World Wide Web (WWW).

HTML tags​: HTML documents are described by HTML tags. Each HTML tag describes different content element in a document. Here are some examples:
- The text between <html> and </html> describes an HTML document
- The text between <head> and </head> provides information about the document The text between <title> and </title> provides a title for the document
- The text between <body> and </body> describes the visible page content
- The text between <h1> and </h1> describes a heading
- The text between <p> and </p> describes a paragraph

### Resources
- [html cheat sheet](https://lifeyourway.net/printables/blogging-html-cheat-sheet.pdf)
- https://www.w3schools.com/tags/
- https://www.htmlgoodies.com/
- https://developer.mozilla.org/en-US/docs/Learn/HTML

### Simple HTML and Inline CSS
- [Lorem Ipsum](https://www.lipsum.com/)
- [Lorem Picsum](https://picsum.photos/)
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Simple HTML and Inline CSS</title>
</head>
<body>
  <h1 style="background-color: yellow; color: black; text-align:center;">My First HTML with Inline CSS</h1>
  <img src="https://picsum.photos/300" alt="Lorem Picsum" style="display: block; margin: 5% auto;">
  <div class="container" style="border: 3px solid red;">
    <p style="background-color: green; color: yellow; padding: 10px 5px 20px 5px; margin: 20px 20px 20px 20px;">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    </p>
  </div>
</body>
</html>
```

### Sample Code using HTML5 tags

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Web Development 101</title>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
  </head>
  <body>
    <header>
      <nav>
        <menu>
          <ul>
            <li>About</li>
            <li>Portfolio</li>
            <li>Resume</li>
            <li>Contact</li>
          </ul>
        </menu>
      </nav>
    </header>
    <main>
      <div class="site-content">
        <h1>Week One: HTML Sample Code</h1>
        <p>This class is awesome!</p>
      </div>
    </main>
    <footer>
      <p>&copy 2020 <br/> Author: First and Last Name</p>
    </footer>
  </body>
</html>
```
