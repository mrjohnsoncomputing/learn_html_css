# 2 - Structure
**Skills**: Tags

Let us talk about the structure of a HTML page, just so that you know what is going on inside the *index.html* file. Once we understand it properly, we can start making big changes to it. 

## Browser
First we must understand something. What do all of the following have in common:
- Google Chrome
- Safari
- Firefox
- Internet Explorer
- Microsoft Edge

The answer is that they are all browsers, and their job is to be able to read HTML code and present it to you in a nicely formatted way. 
HTML code is what we write web pages in, such as www.wikipedia.org, and so the browser's job is to be able to read and present web pages.

In order to make sure the browser understands how it should display everything, we have to be quite specific with what is what, so it doesn't make any mistakes.

## Doctype
This tells the browser what kind of document we are using. You will see on line 1 of *index.html* that we are telling it that the Doctype is HTML. Makes sense right? 

It *might* seem a *bit* overkill that the tag on the next line is `<html>` (didn't we just tell the browser that this was an html document?) but this is to tell the browser that from here until the `</html>` it should expect to find only html code. 

## Head
The `<head>` section of a HTML document is there to tell the browser information about the document. You wouldn't put any content here.

The first two tags are `<meta>` tags, the first is just telling the browser what language the page is written in, and the second is telling the browser how to display the page on different devices. 

We then have the `<title>` - this is the text that appears on the tab at the top. A bit useless if we are working in repl.it, as we don't have a tab for this page, unless you click on the little box with an arrow in the top right, to open it in a new tab. 

```
#### Bonus task
Try changing what is written inside the title tag and then refreshing the new tab you opened the page in.
```

Lastly we have a `<link>` to a stylesheet and a `<script>` tag linking to a script file. We will cover those in a later lesson, but in short, the stylesheet tells the browser about how the page should look - think colours, fonts, sizes etc. The script allows us to tell the browser how the webpage should behave - for example, to do a certain thing when a button is clicked.

## Body
That leaves us with the body tags. Almost everything you do in your time with HTML will be done in the body. The body is for **content**. Anything that you want to appear on the actual page goes in the body. And of course it must have the appropriate tags with it. 

## End
Right that's enough of the formalities, lets get creative!
*Sidenote: HTML stands for HyperText Markup Language, and as such is a Markup Language,* **not** *a Programming language*