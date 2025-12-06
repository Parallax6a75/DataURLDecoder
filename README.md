# DataURLDecoder
Simple HTML Loader (LZ-String Version)

This page loads HTML that was compressed with LZ-String and passed in the data parameter.

How it works

You open a link like:

https://parallax6a75.github.io/DataURLDecoder/?data=ENCODED_HTML


The script decompresses the value and writes the HTML into the page.

If no data parameter is present, the page will prompt you to enter HTML and will generate a new link with the compressed version.

Creating a link

Open the page:
https://parallax6a75.github.io/DataURLDecoder/

When the prompt appears, paste your HTML.

The page will show a link that contains the compressed data.

Share or open that link — it will render your HTML.

Manual encoding (optional)

If you want to encode HTML yourself, run this in the browser console:

LZString.compressToEncodedURIComponent("\<h1\>Hello\</h1\>");


Use the result as the data value:

https://parallax6a75.github.io/DataURLDecoder/?data=RESULT_HERE

What this is for

This repository provides a simple way to pack an entire HTML page into a URL using LZ-String and load it on demand.
