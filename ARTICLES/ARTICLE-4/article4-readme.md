## A complete blog on CSS Selectors

**In this blog, I will be talking about various kinds of selectors in the CSS**

---

As a developer, you might be learning about many things in CSS. But if you lag in selecting or targeting the element in your development journey then you might miss the honey from the bee.

I'm saying that mastering the selectors will make you 80% pro in CSS. You should be able to understand which tag or element is tagged or targeted here for the specific output.

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

It will select only the targetted tag from the code file. For example;

```css
p {
  background-color: #4d4d4d;
}
```

This background color will be applied to all paragraphs that are in tag named 'p'.

### Class-Id Selectors

We can select any element by using the class ID selector. But the problem with that is, it selects all paragraphs. If we only want to select a particular paragraph in one color and another one in the second color, then we can't do it with these individual selectors.

So, for that, we have to select these paragraphs' particular class and id. So that we can achieve our results.

For example, I have targetted the class warning and selected One:

%[https://codepen.io/sourabh-bhatt/pen/dyjxdWO]

In the same way, Id can also be selected:

%[https://codepen.io/sourabh-bhatt/pen/RwBXQZZ]

In this, I have selected an individual element by its unique Id.

**_<mark>Note:</mark>_**

1. **_The id should be unique._**
2. **_Classes can be the same._**

### and Selector(Chained)

In CSS there might be some chances where we have a class in 2 different elements. But we only want to select one particular tag and format that. So, boys how would you do that???

Well, here a chained property of CSS comes in; which is the selector. Basically what it does is, select the chained property applied by a class on a particular element.

For example

%[https://codepen.io/sourabh-bhatt/pen/dyjxdWO]

Here, the selector is applying its chained property. Which is basically selecting all the classes mentioned in the list element. It will apply the property on all of the elements.

### Combined Selector

It is one of the best and short ways to write complex CSS in an easy way. In this, we apply the same property to two different elements.

For example;

%[https://codepen.io/sourabh-bhatt/pen/QWBeQJo]

**<mark>Note:</mark> In this example, I just took only 2 elements, but there is no limit:)**

### Inside an element Selector
