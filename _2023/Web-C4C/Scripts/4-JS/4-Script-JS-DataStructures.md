## Data Structures

- Variables
- Arrays
- JSON

notes:
We'll take a trip and visit 3 broad types of data structures. Variables, arrays, and JSON.

---

Understanding the design of programming languages

![be specific](https://media.giphy.com/media/t7NqkPey14axG/giphy.gif)

notes:
When we use JavaScript, we have to keep in mind that what we're doing is describing in another language exactly what we want to accomplish. 

Part of describing what we want to accomplish is describing how we should store information. 

---

### Humans store information

By writing it!

![writing](https://media.giphy.com/media/XIqCQx02E1U9W/giphy.gif)

notes:
The way that we humans store information is by writing it down somewhere. Either in a note taking app or on paper.

---
### Machines store information

By writing it!

![robot writing](https://media.giphy.com/media/cENTTQmqUOfN1OUzCI/giphy.gif)

notes:
Machines do the same thing, except instead of paper or an app, they write their notes in memory. It's different from human memory because their memory is fixed and doesn't change as easily as ours does. 

---

We'll build a mental model of data structures by using an analogy of storing cookies.

---

Let's paint a picture. Let's say that I just bought a bunch of thin mints. Thin mints are stored in a box that's meant for a very specific item. Cookies! If I open that box and  I see cookies there, than I'd be pretty happy that I got what I was looking for. So when I'm looking for cookies in the future, I know all I have to do is look for my box. If I want to look for legos, then I would look for my lego box. If I was looking for cookies and saw legos in my cookie box, well it's possible to do but it doesn't make sense. It's not organized.

In the same way, machines have a bunch of boxes that they use to store objects. We can name these boxes whatever we'd like. So I could say that this box's name is now `cookieBox` and then I could put the word "cookie" inside that box.

Boxes can hold a lot of different types of objects. Heck, they could even hold other boxes! Or they could give us directions to a box somewhere else entirely! The big takeaway here is that variables are names for boxes of stuff. The stuff that we put inside these boxes can be anything but they can generally be grouped into a few different categories.

---

For computers, we generally use these 3 categories: primitives, arrays, and objects. Primitives are simple information, it's just numbers and words. In the JavaScript language, we can declare using magic words that a box in memory will be called "`cookieName`" by saying "`let cookieName = "thin mint";`" and then we can put the name of our cookie there. 

Arrays are lists of other things. If we wanted to have a bunch of different cookie names, we could group them together into a list. In JavaScript, we would declare a new box called "`cookieNames`" and then we would write this out as our magic words. If we wanted to figure out what the first name was, well I could look at the very first slot, which is located at the address / index of 0. 

Objects are anything that isn't the other two. Objects can get complicated but in the JavaScript language, we can think of them as dictionaries that has a "word" and a "definition" but I like to think of them as locked boxes. Each box can contain a bunch of different other boxes that we call properties. These boxes don't know they're being summoned unless we have the right key, which is their name. So if we wanted to call them, we'd have to open the big box first, then open the property we want to peek into. Objects also describe boxes of other boxes. So we can have an object inside of another object, just like how we can have boxes inside of other boxes.

---

Objects are cool because they're so flexible we can use them for anything. In fact, they're so cool that we have a dedicated file type for these objects called JSON. This allows us to describe a dictionary without knowing the language, JavaScript.

---

![[4-Drawing-JS-DataStructures]]