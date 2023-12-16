# Structure web pages with HTML

### What is HTML and why do we use it?

A: (HyperText Markup Language) is the code used to structure what we see visually on a web page. 

### What are the 3 main parts of an HTML element?

A: The entirety of the HTML element is composed of the opening tag "<p>" , The closing tag "</p>", and the content imbetween the opening and closing tag. EX:"<p>content</p>"

### What is it called when you give an element extra information?

A:  It is called an attribute which is extra information about the element that you don't want in the actual content. 

### What is a Semantic Element?

A: A Semantic Element is an element that gives a line of code meaning.  Semantics = meaning. We want to think about the purpose of the code and the role it plays, not the way we want it to appear. There are a lot of ways to make something appear a specific way, but using the semantic element is important for a variety of reasons. In the following example "h1 is the semantic element:

<h1>This is a top level heading</h1>

------------------------------------------------------------------------

Great example for html from one of the study resources for future reference:

HTML
<!doctype html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>My test page</title>
  </head>
  <body>
    <img src="images/firefox-icon.png" alt="My test image" />
  </body>
</html>
Here, we have the following:

<!DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However, these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.
<html></html> — the <html> element. This element wraps all the content on the entire page and is sometimes known as the root element. It also includes the lang attribute, setting the primary language of the document.
<head></head> — the <head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.
<meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this, and it can help avoid some problems later on.
<meta name="viewport" content="width=device-width"> — This viewport element ensures the page renders at the width of viewport, preventing mobile browsers from rendering pages wider than the viewport and then shrinking them down.
<title></title> — the <title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.
<body></body> — the <body> element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.