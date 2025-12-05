# DataURLDecoder
Simple HTML Loader

This page loads HTML from a base64 string in the URL.

How it works

You pass your HTML as a base64 value in the data parameter:

https://username.github.io/repo/?data=BASE64_HERE


The script decodes it and writes the HTML into the page.

Encoding your HTML

Open the browser console and run:

btoa("\<h1\>Hello\</h1\>")

(or different HTML code inside the quotes)


Use the result in the data parameter.

That's it.
