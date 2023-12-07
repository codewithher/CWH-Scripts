
Before we can look at how data structures are used in our website, we have to look at how JavaScript grabs HTML or CSS elements. After all, we can't have bakery science without the cookie, can we? 

---

Just like CSS, JavaScript can grab HTML elements. When we grab HTML through JavaScript, this is known as the document object model, or the DOM. From here on out, when we talk about DOM elements, we mean HTML elements that are in JavaScript. That's because JavaScript speaks a different language than HTML but it has tools to help interpret the language. Tools in JavaScript and programming languages are known as functions. Functions are a set of instructions that run on some input and it can produce some output or change the object it was used on. 

---

To better understand JavaScript, let's change our mental model to that of an archeologist. We're going to be the Archeologist and we can only speak in JavaScript. We found an ancient sheet of paper that is written in "HTML." We're going to call this sheet of paper, the `document`. Now while we can't read it ourselves, we can use a translator to pick out specific parts of the document to use. This tool is used for both translating and for picking a specific part to use. The tool we use for translating from HTML to JavaScript is the `querySelector()`.  This tool works by attaching it to the document, then telling it what part of the document we want to translate. The nice thing is that it translates in a very similar way to CSS. We can grab tags by specifying the tag name, or we could grab classes by the class name and putting a `.` before it. We can also grab by a specific ID by using a `#` instead.

---

Now while we could translate the whole document once and not have to worry about translating it, we have to keep in mind that once we translate it, we have to store our translation in boxes. When we translate the entire document at once by using: `document.querySelector("html");`, what we're doing is getting a really big box with tons of tiny boxes. We get one box for each element in the HTML tree. Websites, like most trees, have lots of branches. Most of the time, we only care about specific branches or boxes so we typically grab what we need when we need it.