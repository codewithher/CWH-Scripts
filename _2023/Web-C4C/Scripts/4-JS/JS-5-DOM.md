notes:
Just like CSS, JavaScript can grab HTML elements. When we grab HTML through JavaScript, this is known as the document object model, or the DOM. From here on out, when we talk about DOM elements, we mean HTML elements that are in JavaScript. That's because JavaScript speaks a different language than HTML but it has tools to help interpret the language. Tools in JavaScript and programming languages are known as functions. Functions are a set of instructions that run on some input and it can produce some output or change the object it was used on. 

To better understand JavaScript, let's change our mental model to that of an archeologist. We're going to be the Archeologist and we can only speak in JavaScript. We found an ancient sheet of paper that is written in "HTML." We're going to call this sheet of paper, the `document`. Now while we can't read it ourselves, we can use a translator to pick out specific parts of the document to use. This tool is used for both translating and for picking a specific part to use. The tool we use for translating from HTML to JavaScript is the `querySelector()`.  This tool works by attaching it to the document, then telling it what part of the document we want to translate. The nice thing is that it translates in a very similar way to CSS. We can grab tags by specifying the tag name, or we could grab classes by the class name and putting a `.` before it. We can also grab by a specific ID by using a `#` instead.

Now while we could translate the whole document once and not have to worry about translating it, we have to keep in mind that once we translate it, we have to store our translation in boxes. When we translate the entire document at once by using: `document.querySelector("html");`, what we're doing is getting a really big box with tons of tiny boxes. We get one box for each element in the HTML tree. Websites, like most trees, have lots of branches. Most of the time, we only care about specific branches or boxes so we typically grab what we need when we need it.

---

### HTML + CSS + JS

![html,css,js](https://p92.com/binaries/content/gallery/p92website/technologies/htmlcssjs-overview.png)

notes:
Even though they all work together to make websites, we have to remember that each language is different. They can only understand a little of each other's languages at a time.

---
### Translation Tool

> Just a little bit at a time

```html
<script>
// we can put JavaScript in here
</script>

<style>
/** we can put CSS in here */
</style>
```

notes:
HTML can understand JS and CSS perfectly clearly but only when they say it in these tags.

---
### HTML🤏CSS

![point](https://static0.srcdn.com/wordpress/wp-content/uploads/2019/12/Spider-Man-1967-Pointing-Meme.jpg)

notes:
CSS can sorta grab parts of HTML but it doesn't know what to do with it besides point at it and paint it.

---
### HTML🤏JS

![translate](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fnature.2016.20696/MediaObjects/41586_2016_Article_BFnature201620696_Figa_HTML.jpg)

notes:
When JavaScript grabs HTML, it's treated like google translate. It can translate it but we've got to store the translation somewhere when we're done.

---
### HTML🤏JS

> Using the DOM

![DOM](https://media.giphy.com/media/IUxFvKwD3jXisqR5w7/giphy.gif)

notes:
We call this using the DOM.

---
### DOM

- Document
- Object
- Model

notes:
I mean the document object model.

---
### DOM

> Using HTML in JavaScript

notes:

This is basically the way that we control the website and do all the fun stuff!