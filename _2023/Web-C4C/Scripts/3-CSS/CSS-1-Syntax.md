## 📍 CSS - The Style
- ~~HTML~~
- [🎨 CSS]()
	- Selectors
	- UX
	- Identity
	- Readability
	- Discoverability
- JavaScript

notes:
Now, we're onto the style. We're looking to make our cookie website look nice.

---

## Selectors

![the claw | 700px](https://media.giphy.com/media/YMXpTBoVQbL9N8MKZa/giphy.gif)

notes:
The core part of CSS is not about writing content. In the same way we can't make a cookie look cool if we don't have the ingredients to make the cookie, we can't make a website look cool if we don't have HTML.

Because of this, the core part of CSS is selectors. This is how we describe what part of the cookie / website, we want to style. 

---

### CSS Syntax

```css
noun {
	part: adjective;
}
```

notes:
So this is how we might write CSS. Our noun would be out here, next the part, then the adjective.

---

### CSS Syntax Example

```css
water-bottle {
	lid: blue;
}
```

---

### Selector types

1. ✅ Element 
2. ✅ Class
3. ⛔ ID 
4. ⛔ Inline 

notes:
Elements or tags, will grab all the tags of that type and apply the styles we have defined.

Meanwhile classes are a property we can apply to different types of tags to style them in the same way. This gives us the chance to have more control over "categories" of elements to style.

We only use these top two in the website we're building.

The following two are for grabbing a single element. The `ID` option allows us to grab it from a CSS file like the rest of the selectors by defining a property. The `inline` allows us to set CSS styles directly as a property itself.

---

### Optional Selector Activity

> [!Optional]
> If you're curious, you can check out this [CSS selector example](https://codepen.io/totally-not-frito-lays/pen/KKJBRmq?editors=1100).

notes:

After looking at the example, try looking through our website to see how we use selectors to theme everything!

---
### Optional CSS Variables Activity

> [!Optional] 
> If you're curious, you can also check out this [CSS variables example](https://codepen.io/totally-not-frito-lays/pen/xxMJjzM).
