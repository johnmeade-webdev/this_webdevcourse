# HTML

## 2. HTML Documents

At its most basic, an HTML page consists of the following:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>This Webdev Course</title>
  </head>
  <body></body>
</html>
```

Every document starts with the `<!DOCTYPE html>` tag. Notice two things. First, there's no closing tag. There are a handful of elements that only require a single opening tag. These elements typically do not show rendered text. Common example are the `<audio>`, `<video>`, and `<img>`. Secondly, the name of the tag starts with an exclamation point (bang). The bang is an artifact of previous markup declaration standards and isn't really used anywhere else in modern HTML. Yet, the `<!DOCTYPE html>` tag is still required and prompts the browser to parse the page appropriately.

Next, wrapping everything else in the document, is the `<html></html>` element. This is the top-level element and gives the browser a clear beginning and end to the document. There are two elements nested inside of the `<html>` element. 

`<head></head>` contains all of the information the browser needs about who owns the pages, the encoding it uses, resources the browser will need to download to make the page appear and function as intended, and even information for search engines and social media. We will talk more about the `<meta>` and `<title>` when we take our deep-dive into the `<head>` element.

`<body></body>` contains all of the actual content that will be accessible on the page to the user. If the `<head>` element is the requirement sheet explaining the binding, paper, and dustcover of the book, the `<body>` contains the actual text of the story. We will talk more about the content and organization of elements within the `<body>` when we do your deep-dive on the topic.