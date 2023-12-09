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

---
