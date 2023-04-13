## Note :

The EMs set on anything else other than `font-size`, don't reference the parent they reference the `font-size` of that element.

### When to use EMs then ?

EMs come in when you wanna set `margins` and `padding` and things like that. Because in this case they're referencing the font-size of that element.

## Using REMs

### Benefits :

- `Rem` can be helpful when it comes to change `font-size` across your whole site because we are referencing to the `:root`.

- it can be the first step in just making life a little, bit easier, Like Mobile has the html, has a `font-size` of like `70%`, and then that goes up to `90%`, and then it goes up to `110%`, and just, your whole site's updating the `font-size` for your different screens without having to go through all of the different font properties.

### Limitations :

- if you put in a media query, where you're just changing the font-size of the html element your whole site is just gonna poof! Everything's gonna change along with it. It's not always perfect but it can be the 1st step in making life a little, bit easier.
