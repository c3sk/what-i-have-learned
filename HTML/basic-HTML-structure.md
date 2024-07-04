# Basic HTML Structure

The basic structure of an HTML file is as follows:

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

- `<!DOCTYPE html>`: This tag is also known as the doctype declaration and is used to specify the HTML version being used in the document. This version of the doctype declaration tells the browser to use HTML5, the latest version of HTML available.

- `<html></html>`: This tag is the root element that encompasses all other elements of the document, marking the beginning and end of an HTML document. The `<html>` tag can include several attributes, the most common being lang to specify the language of the document, aiding in accessibility and search engine optimization.

- `<head></head>`: This tag is a container for metadata and links to resources related to the HTML document. It contains information that is not displayed on the web page, such as character encoding, links to external CSS/Javascript or viewport settings.

- `<body></body>`: This is the tag that acts as a container for all the visible content of an HTML document, such as text, images, videos, links, forms, and other multimedia and interactive elements.
