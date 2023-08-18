# Day-15 | Intro to media queries

## Media Query Basics :

The code below is the *basic syntax of a Media Query.*
```css
/* Targets all media types */
@media () {

}
```
Now we can write ***media type and media features***

Below syntax illustrates how we can add media-type into the Media Query :
```css
@media media-type () {

}
```
If we *leave it blank* it means it's *targeting all media types* and you might be wondering what they are, they are there's print there's screen. 

There is also speech media queries tht do exist out there.
You won't see this too often though.

We don't include a media type & we just focus inside the parenthesis which is our **media features**. 

So you can look for many things like widths, heights so that's based on like the actual width or height of the viewport. You can look at the orientations, is it landscape? or portrait? You can even look at to see if a feature has the ability to have a hover or not and difference stuff like that. 

The one that we're gonna looking at the most is focusing on width. 

You'll *don't actually focusing on width* because that would be vvery limiting.

So Instead You'll be lookin at `min-width` or `max-width` Now it's a little bit of used to that when you see max you think big, or when you see the word min you think small but it's pretty opposite. Because `min-width:600px;` ***means minimum width of 600px or higher.*** 

```css
/* 600px or bigger */
@media (min-width: 600px) {

}
```

**Note : The order in which you put the CSS is really really important.**

Let's see :
```css
.example {
width: 90%;
margin: 5em auto;
padding: 10em 0;
background-color: steelblue;
}

/* 600px or bigger */
@media (min-width: 600px) {
    .example {
        background-color: olivedrab;
    }
}
/* 800px or bigger */
@media (min-width: 800px) {
    .example {
        background-color: orangered;
    }
}
```
Output : 

![media query illustration](Media%20Query%20Basics/img/media%20query%20illustration.gif)

But when we change the order of the CSS as given below see what will happen : 
```css
/* 800px or bigger */
@media (min-width: 800px) {
    .example {
        background-color: orangered;
    }
}

/* 600px or bigger */
@media (min-width: 600px) {
    .example {
        background-color: olivedrab;
    }
}
```
The Last Media Query will be applied and win over the `@media(min-width: 600px)` & First Media Query will never be applied as you can see below.

![media query illustration](Media%20Query%20Basics/img/media-query-override.gif)

And if you put all the Media Queries above none of them is gonna win over and applied to the webpage.

```css
/* 600px or bigger */
@media (min-width: 600px) {
    .example {
        background-color: olivedrab;
    }
}
/* 800px or bigger */
@media (min-width: 800px) {
    .example {
        background-color: orangered;
    }
}

.example {
width: 90%;
margin: 5em auto;
padding: 10em 0;
background-color: steelblue;
}
```
In this case `background-color:steelblue;` will win over the other two which are put inside the media queries as it comes after those two.

Let's see through the illustration : 

![no media query apply illustration](Media%20Query%20Basics/img/media-query-failure.gif)

No matter what the condition is that is always applying.

**So, the order that you put things in is very, very important!**

So, if you're dealing with the minimum-widths, it's always going to be from smallest to biggest inside your media queries.So they can override each other As we grow to bigger screen sizes.
