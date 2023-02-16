---

**In this blog, I will be talking about various kinds of selectors in the CSS**

---

As a developer, you might be learning about many things in CSS. But if you lag in selecting or targeting the element in your development journey then you might miss the honey from the bee.

I'm saying that mastering the selectors will make you 80% proficient in CSS. You should be able to understand which tag or element is tagged or targeted here for the specific output.

# Various kinds of Selectors in HTML

### Universal Selectors

As the name suggests, the property selected will be applied to all tags. For eg;

```css
* {
  padding: 0;
  margin: 0;
}
```

### Individual Selectors

It will select only the targeted tag from the code file. For example;

```css
p {
  background-color: #4d4d4d;
}
```

This background color will be applied to all paragraphs that are in tags named "p."

### Class-Id Selectors

We can select any element by using the class ID selector. But the problem with that is that it selects all paragraphs. If we only want to select a particular paragraph in one color and another one in the second color, then we can't do it with these individual selectors.

So, for that, we have to select these paragraphs' particular class and ID. so that we can achieve our results.

For example, I have targetted the class warning and selected One:

%[https://codepen.io/sourabh-bhatt/pen/dyjxdWO]

In the same way, ID can also be selected:

%[https://codepen.io/sourabh-bhatt/pen/RwBXQZZ]

In this, I have selected an individual element by its unique Id.

**_<mark>Note:</mark>_**

1. _The id should be unique._
2. _Classes can be the same._

### and Selector(Chained)

In CSS there might be some chances where we have a class in 2 different elements. But we only want to select one particular tag and format it. So, boys, how would you do that?

Well, here a chained property of CSS comes in, which is the selector. Basically, what it does is select the chained property applied by a class on a particular element.

For example

%[https://codepen.io/sourabh-bhatt/pen/dyjxdWO]

Here, the selector is applying its chained property. which is basically selecting all the classes mentioned in the list element.

### Combined Selector

It is one of the best and short ways to write complex CSS in an easy way. In this, we apply the same property to two different elements.

For example;

%[https://codepen.io/sourabh-bhatt/pen/QWBeQJo]

**<mark>Note:</mark> In this example, I just took only 2 elements, but there is no limit:)**

### Inside an element Selector

We often try to hit a particular element with a particular element or tag. But by class and ID, it might not get sh\*t done. So, here we use inside and element selectors. Basically, it hits the particular element inside an element.

For example,

%[https://codepen.io/sourabh-bhatt/pen/NWLKvBp]

# Direct Child

What if you don't want to use the inside element selector but still want to select an element that is inside another element?

Well, in this case, the use of "direct child" comes into play. We will get to use "direct child" so many times when it comes to targeting a specific child.

For example,

%[https://codepen.io/sourabh-bhatt/pen/NWLKvBp]

**_<mark>Note:</mark>_** _The first two letters, "li" and "ul," are direct children. But in "ul," it has one more child, which is the grandchild of "div." So, it will not select "ul"._

# Sibling Selector

> You might have heard this selector in real life but not in CSS:)

PS: This is the power of reading documentation and getting experience:)

As the name sibling depetics; to share the something with next. Same happens in css also. In CSS we might want to apply the code for another element. So, then we will use sibling selector often shown as "~" or "+"

For example;

%[https://codepen.io/sourabh-bhatt/pen/NWLKvBp]

# Pseudo Selectors

Pseudo-selectors are special classes for selecting a particular element.

For example,

### :hover

":hover" element applies to the element when we want to hover over it or change its current state to a new one and then to the previous one. It is one of the best pseudo-selectors used for building buttons.

For example,

%[https://codepen.io/sourabh-bhatt/pen/NWLKvBp]

As in the above example, I have made a hover selector over the class 'sibling' and given it a background color 'red'.

### ::before

The "::before" selector creates a pseudo element on the very first child of the selected element. It requires a 'content' property. It is mandatory to have it, or else it will not work.

%[https://codepen.io/sourabh-bhatt/pen/NWLKvBp]

### ::after

As "::before" applies the property before the element same "::after" applies the property after the element. It does by selecting the last child of the element.

%[https://codepen.io/sourabh-bhatt/pen/NWLKvBp]

**<mark>Note:</mark>** These pseudo selectors must follow display inline property.

# Conclusion

So, developers, this is the end of the blog but not the end of selectors. You can refer to MDN DOCS for more in-depth knowledge about selectors.

Do lemme know if there any mistake I made in explanation.

#iwritecode #webdev #wemakedevs #debuggingfeb
