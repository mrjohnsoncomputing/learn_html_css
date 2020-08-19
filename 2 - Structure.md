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
The head section of a HTML document is there to tell the browser information about the document. You wouldn't put any content here