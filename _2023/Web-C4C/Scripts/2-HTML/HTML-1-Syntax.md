## 📍 HTML - Ingredients
- [🏗️ HTML]()
	- Hierarchy
	- Tags
		- Anatomy of Tags
		- Structure Tags
		- Content Tags
		- Action Tags
	- Hero Banner
	- Images
	- Action Tags
- CSS
- JavaScript
---
## HTML Hierarchy

![Tree](https://media.giphy.com/media/Vi5TUmZz8LZb95j2xb/giphy.gif)

notes:
HTML Hierarchy tree is a way of describing how different parts of an HTML page belong to another part.

We call each of these parts, elements. Elements can be nested inside of each other. The best mental model to use for this is a tree. Notice how each leaf belongs to a branch, each branch belongs to a bigger branch, and every branch belongs to the trunk? The same is true for HTML elements.

This makes it really easy for us to see what content belongs to what branch.

Let's breakdown our website into it's hierarchical parts.
- Notice the collapse arrows? we can click this to collapse every sub-branch that belongs to this element.
- This makes it a lot easier for us to see

---
### Tags

notes:
Formally, elements refer to the idea of a smaller part of our HTML tree. We call the actual code for each element, a tag. That's what we see inside the `<>`. For our purposes, we can consider tags to be the same as elements.

---
### Anatomy of a tag

```HTML
<tag></tag>

<tag>content</tag>

<tag properties="value"></tag>

<tag properties="value">content</tag>
```

notes:
Each tag is made of 3 parts. The tag name, the properties, and the content. Properties describe how the tag should behave and look. 

All tags have default properties that we can override but typically they have those default properties to fulfill a specific task.

---
### Types of tags

There are [142 different HTML tags](https://devdevout.com/html/how-many-html-tags-are-there) but generally there are only about 3 broad categories.

Purpose:
- Structure
- Content
- Action

notes:
It turns out that there are a lot of different types of tasks to fulfill for websites. 142 of them! Thankfully we don't always need to use that many. Something else that's nice is that there's only really 3 categories that we care about. Structure, Content, and Action tags.

---
### Structure

- helps group elements together

> [!Optional]
> Check out this [codepen](https://codepen.io/totally-not-frito-lays/pen/xxMJbgm?editors=1000)!
> - Try moving the content tags around to see how it changes
> - Pay attention to: 
> 	- `<main>`
> 	- `<div>`
> 	- `<section>`
> 	- `<ul>`
> 	- `<body>`

---
### Content

- what fills the website itself

> [!Optional]
> Check out this [codepen](https://codepen.io/totally-not-frito-lays/pen/RwvBNjP)!
> - Try changing the content of each tag
> - Pay attention to:
> 	- `h1`
> 	- `p`
> 	- `span`
> 	- `img`


---
### Action

- triggers some sort of event

> [!Optional]
> Check out this [codepen](https://codepen.io/totally-not-frito-lays/pen/wvNxBPg?editors=1111)!
> - Try clicking on the links
> - Notice how the `a` tag can be nested inside other tags?
> - Look for the script tag!