# Day 13/14 | Break Time

There are no new lessons or content this weekend. We've covered a lot over the last 2-weeks, and while I might be sounding like a broken record at this point, it's important to have some down-time. It also gives people who are a little behind a chance to catch-up a little 😊.

So if you're in catch-up mode, take your time over this weekend to do so, and if you're all caught up, or maybe just working on the challenge, that's great!

We'll be back at it on Monday when we start looking at media queries.

If you're insistent on finding something new to learn about, over on YouTube I have a [video that takes a look at some relatively new CSS functions](https://youtu.be/U9VF-4euyRo):
- [min()](#min)
- [max()](#max)
- [clamp()](#clamp)
- [Problem with viewport units for font-size](#problem-with-viewport-units-for-font-size)

They are some exciting functions that we can use as for the values of elements, so we could set something like `width: min(95%, 1200px);`, which would be the same as setting both a width and a max-width.

And while setting a width and max-width is something we could already do, we can also use this for things like margin and padding (and font sizes!), where something like that wasn't even possible before.

`Clamp()` is even more exciting in how we could use it for responsive typography.

I'm still scratching the surface with these, and browser support for them (especially `clamp()`) isn't perfect yet, but they open up some exciting possibilities for creating responsive websites!


## `min()` :

**`min()` is a cool CSS function which selects the smallest value from the given values.**

You might have used the below property on a div or any other type of element. 

```css
div {
    width: 70%; 
    max-width: 500px;
}
```

When we use this property whichever is the smaller unit is, it is applied to the element like when the `width:70%` is smaller than `500px` it is applied to the div but when the `div` reaches to `500px` it stops increasing as it has the `max-width: 500px;`.

We can get rid of these two lines by using just a single line of code i.e. using `min()` function. 
```css
div {
    width: min(70%, 500px)
}
```
This is equivalent to the two lines of code we wrote above using `width & max-width`.
*For smaller screen sizes it chooses width as 70% it's smaller than 500px*
But if we grow our screen big enough the 70% will become bigger so it will choose 500px as width.

## `max()` : 

**max() is just opposite to min() function & it chooses the maximum value from the given values.**

Note : we can also give multiple values instead of just two values as shown above. for e.g.

```css
div {
    width: max(400px, 50%, 50vh);
}
```
Some more examples on how we can use `min()` and `max()`

```css
width: min(max(), 500px);
```

```css
width: min(500px + 20%, 600px);
```
Note : Do include space when using the math operation.

**Wrong Syntax**
```css
width: min(500px +20%, 600px)
```
Here the +20% will be assumed as a single unit.

## `clamp()` :

`clamp()` function clamps a middle value within a range of values between a defined minimum bound and a maximum bound. The function takes three parameters which are must: 
1. a minimum value, 
2. a preferred value, 
3. and a maximum allowed value.

### Problem with viewport units for `font-size` :

```css
font-size: 2vw;
```

1. For smaller screen sizes it becomes unreadable and

2. Suppose someone wants to zoom your site and see the text but due to the use of viewport units the `font-size` isn't gonna change because viewport size remais the same while the user zooms in or out.

### However there is an alternative you can use i.e. `calc()` :

```css
font-size: calc(1vw + .5rem);
```
Now when the user zooms the text will be zoom alongwith it make it readable.

**But there's still a bit of an issue with this where you can see it's getting really small at a small screen size & you don't want users to pinch and zoom in when they're on a mobile experience because your bodies font-size is too smell.