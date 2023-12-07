## 📍 JS - The Science
- ~~HTML~~
- ~~CSS~~
- [🧙‍♂️ JavaScript]()
	- Interactivity
	- Data Structures
	- Loops
	- Conditionals
	- Web Components

notes:
Part of the reason the navigation bar was so complicated is because it uses this dark sorcery thing we call javascript.

If you recall, from our mental model, javascript filled in the role of baking science. It changed the way that our cookie dough baked and looked. 

In the same way, Javascript allows us to move around our navigation bar.

---
## Interactivity

![Types of Websites](1-Types-Websites.png)
notes:
Remember this? JavaScript is the sauce that allows us to move between static and dynamic webpages. Static sites have almost everything written with just HTML and CSS. Dynamic sites have a lot more that is controlled by JavaScript. Usually it's generated using a design pattern known as component-based design. We'll cover more of that later.

---
### Interactive JS Example
> [!Activity]
> Check out any one of these projects! Add your own favorite!
> - [Cloth Simulation](https://codepen.io/dissimulate/pen/nYQrNP)
> - [Star Wars Intro Crawl](https://codepen.io/TimPietrusky/pen/AGrxGb)
> - [Animated Snow](https://codepen.io/ste-vg/pen/GqaZbo)
> - [Typing Test](https://codepen.io/Hyperplexed/pen/MOObKy)
> 



notes:
The important thing to know now about JavaScript is that we can do things like this. Go ahead and check out these examples, poke around codepen and see if you can find another one that's really cool.

---
## Data Structures

- Variables
- Arrays
- JSON

notes:
When we use JavaScript, we have to keep in mind that what we're doing is describing in another language exactly what we want to accomplish. 

Part of describing what we want to accomplish is describing how we should store information. 

The way that we humans store information is by writing it down somewhere. Either in a note taking app or on paper.

Machines do the same thing, except instead of paper or an app, they write their notes in memory. It's different from human memory because their memory is fixed and doesn't change as easily as ours does. 

Machines have different ways they can store and organize information just like how we can store and organize information in boxes.

For machines they use variables, arrays, and objects or some combination of all of these options. 

We'll build a mental model of data structures by using an analogy of storing cookies.

Variables can store almost anything. It's like putting things on the table in a taped off area. You can basically put anything on the table. If I said this square here is going to be the home for my cookies, then when I want to find my cookies, I just look for where I taped off the area for my cookies. Sometimes it's possible to put something else that's not supposed to be in that taped off area. Like somebody else's cookies, or even worse, something that's not cookies, like an apple. Now I wouldn't want to put apples where I put my cookies otherwise when I want cookies and I get apples, I'd be very confused. 

Now for arrays. Arrays are a serialized list of variables. That's fancy speak for saying variables that sit next to each other. Let's imagine I wanted to collect a bunch of different cookies. Normally I'd need to make a new space for my new cookies on the table. Eventually we'll end up with cookies all over the place and that's not very tidy. Instead of looking for a bunch of different cookie zones, I could try to organize them in a filing cabinet instead. So now when I want a cookie, I could just look for my cookie filing cabinet instead. If I wanted the second cookie, I'd just look at the second drawer of my filing cabinet. If I wanted to take all of the cookies out, then I would go through my filing cabinet and open each drawer out individually while I'm there.

JSON is very specific to JavaScript. It's so specific that it's literally short for JavaScript Object Notation. Why would we need a new data type specifically for JavaScript? Well it's because it's flexible and easy to understand. JSON generally has a pattern of a "key" and a "value," just like how dictionaries have a "word" and a "definition." For us, we use JSON to store all of our definitions of different cookies. In our model, we could say that JSON objects are like boxes that have names in them. We can put boxes inside of boxes. We can put even smaller series of boxes inside other boxes, just like filing cabinets. If I wanted to reach a box that was inside 4 other boxes, I'd have to open the outer most box first, then get the next outer most box and so on.

Before we can look at how data structures are used in our website, we have to look at how JavaScript grabs HTML or CSS elements. After all, we can't have bakery science without the cookie, can we? 

Just like CSS, JavaScript can grab HTML elements. When we grab HTML through JavaScript, this is known as the document object model, or the DOM. From here on out, when we talk about DOM elements, we mean HTML elements that are in JavaScript. That's because JavaScript speaks a different language than HTML but it has tools to help interpret the language. Tools in JavaScript and programming languages are known as functions. Functions are a set of instructions that run on some input and it can produce some output or change the object it was used on. 

To better understand JavaScript, let's change our mental model to that of an archeologist. We're going to be the Archeologist and we can only speak in JavaScript. We found an ancient sheet of paper that is written in "HTML." We're going to call this sheet of paper, the `document`. Now while we can't read it ourselves, we can use a translator to pick out specific parts of the document to use. This tool is used for both translating and for picking a specific part to use. The tool we use for translating from HTML to JavaScript is the `querySelector()`.  This tool works by attaching it to the document, then telling it what part of the document we want to translate. The nice thing is that it translates in a very similar way to CSS. We can grab tags by specifying the tag name, or we could grab classes by the class name and putting a `.` before it. We can also grab by a specific ID by using a `#` instead.

Now while we could translate the whole document once and not have to worry about translating it, we have to keep in mind that once we translate it, we have to store our translation in boxes. When we translate the entire document at once by using: `document.querySelector("html");`, what we're doing is getting a really big box with tons of tiny boxes. We get one box for each element in the HTML tree. Websites, like most trees, have lots of branches. Most of the time, we only care about specific branches or boxes so we typically grab what we need when we need it.

---
## Loops

Loops are a function, or tool, that we can use to repeat a task over and over again. There's a few ways we can describe repeating. We can repeat an action on a data structure until we run out of boxes or filing cabinets to check. Or we could just repeat this action until we've searched the first, for example, 5 times. 

Most of the time we use loops to work very closely with data structures.

---
## Conditionals

Conditionals are a function / tool that we can use to only work sometimes. Except we can define when that sometimes is true. This allows us to decide if we reject a cookie because it contains something we don't like or are allergic to. Let's say we're allergic to peanut butter. We can use a conditional to say: "hey, if it has peanut butter, then I'm not eating it."

We'll use this as a way to decide if we're using cookies that are from one bakery or another. Check out the next activity for more details.

---
## Events

For events, let's change our model to role play as a environmental scientist stationed in the Antarctic. In this model, the HTML document is the environment and events are the weather events. While we're just hanging out, doing science, we can sometimes see events happening in front of us snow storms or the Aurora Borealis. Well we really want to know when that happens so that we can take a picture of the Aurora Borealis when it comes or shelter away when a snowstorm is coming but we have science work to do most of the time.

So that we can do our normal job and also be ready for snow storms or the Aurora, let's take out some more tools / functions. In this case, we're going to bring out some sensors, called `eventListener`'s. These will listen to any sort of input we tune it to listen to. We can attach our listener to a mountain to listen for snow. When the snow comes, we can tell it to send us an alert! We can attach a separate listener on our base to let us know when the sky is really bright at night to tell us that the Aurora is out!

In the real world with real JavaScript, we attach event listeners to HTML DOM elements. Except the events that we listen to are a lot less cool. The most common ones we use are "click" or "onload". Adding event listeners to different elements allows us to change the website based on interactions from the user.

Now that we've been through all of this, let's try reading some of the JavaScript that we have on our website. Just a heads up, JavaScript is complicated and we've only just reached the tip of the iceberg. If you don't understand everything that's going on, that's okay.

Let's check out the logic for `scripts.js`
- What do you see?
	- constant variable or box that contains the DOM element of something that has the ID of "mobile-men-trigger-open
	- we have a function that is being stored in a constant variable
		- the function toggles or flips the switch on a class to either open or not
	- we add an event listener to one of the DOM elements and we give it a tool
		- that tool is the function which flips the switch

---
## Web Components

Up until now, most of the content on our HTML page has been statically written. That means it was written in pure HTML or CSS. When we were categorizing our website, we mentioned that we had some dynamic content.  [dynamic](https://www.merriam-webster.com/dictionary/dynamic) means it is "marked by continuous and productive activity or change." To describe content as dynamic, that means that our content is changing. In our website, we change our content based off of the contents of JSON files.

Let's look at `index.html` and look for where the dynamic content is. Notice how the places where we defined dynamic content doesn't have something written there in the HTML? It's generated by JavaScript.

Let's talk about why we would use dynamic content.

Dynamic content is useful for generating content around something that changes. In our website, what's the stuff that's going to change or there's a lot of? Well there's two main things that I can think of. Number one, the cookies page! If we decide to change bakeries, then the types of cookies will change. Rather than changing this manually with HTML, we can change this with JavaScript. This allows us to pull from a local JSON file if we're with one bakery, or to a different JSON file if we're with a different bakery. If we're really fancy, we could add another layer of complexity by asking the bakeries themselves what cookies they have. That would making an API call and we can talk about that in another project. 

We could also use this strategy to dynamically update our promotion banner based on the time of year it is. As a marketing strategy, sometimes it helps to showcase a specific cookie. So we can do that with components as well. This makes it easy for us to drop dynamic content into specific parts of the website.

