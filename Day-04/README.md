# Day-04 | Catch-up Day

Today is a catch-up day so no official Lessons.
### Extra-curricular

If you are eager to dive keep learning though, there has been some talk about viewport units in the [Discord server](https://discord.gg/9w5M4uAK).

Up next is a video where I take a look at them. A word of warning though, I do look at using them for font-size, and while cool, there are some accessibility issues with doing so, so I wouldn't suggest it unless it's just for a personal project of yours.

This is totally optional, and while they can be useful, they will not be something I'll be diving into in this course.

If you do like them and want to practice with them, there is no reason you can't incorporate them into future challenges though!

# CSS viewport units :

Viewport units are a set of CSS units that are based on the dimensions of the viewport. The viewport is the visible area of the browser window in which your web page displays. Viewport units are useful for creating responsive layouts that adapt to different screen sizes.

The four viewport units are:

- `vh`: The viewport height unit. A value of 1vh is equal to 1% of the viewport height.

- `vw`: The viewport width unit. A value of 1vw is equal to 1% of the viewport width.

- `vmin`: The viewport minimum unit. This unit is based on the smaller dimension of the viewport. If the viewport height is smaller than the width, the value of 1vmin will be equal to 1% of the viewport height.

- `vmax`: The viewport maximum unit. This unit is based on the larger dimension of the viewport. If the viewport height is larger than the width, the value of 1vmax will be equal to 1% of the viewport width.Viewport units are useful for creating responsive layouts that adapt to the size of the viewport. For example, you could use vh to set the height of a header bar so that it always takes up 10% of the viewport height, regardless of the size of the browser window.

Here is an example of how to use viewport units in CSS:
```css
header {
  height: 100vh;
}
```

This code will set the height of the header element to 100% of the viewport height. So, if the viewport is 1000 pixels tall, the header element will be 1000 pixels tall.

Click Below 👇 Video will help you to get a better understanding of `vh`, `vw`, `vmin` & `vmax` units.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=IWFqGsXxJ1E" target="_blank">
 <img src="https://img.youtube.com/vi/IWFqGsXxJ1E/default.jpg" alt="Watch the video" width="320"/>
</a>
