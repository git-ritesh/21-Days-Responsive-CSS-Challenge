# Day-16 | What breakpoints to use ? 

In this Lesson we're gonna discuss about _breakpoints_.

Following are the things on which we'll be looking at :

- What is breakpoint ? 
- When do we use it ? 
- How do we decide them ? 

# Breakpoints 

In CSS, ***breakpoints refer to specific points or ranges of screen widths at which the layout and styling of a website or web application is adjusted*** to provide a better user experience on different devices, such as desktops, tablets, and mobile phones. 

Breakpoints are primarily used in responsive web design to create a fluid and adaptable layout that looks and functions well across various screen sizes.

Breakpoints are used in combination with media queries, which are CSS rules that apply styles based on the characteristics of the user's device or viewport. 

Media queries allow you to define different sets of CSS rules for different screen sizes, resolutions, and other attributes.

*Here's a general outline of how breakpoints and media queries work together:*

1. **Define Breakpoints :** Breakpoints are typically set at common device widths or logical points where the layout might need to adapt. Common breakpoints could be set at 320px (small mobile), 768px (tablet), 1024px (desktop), and higher.

2. **Write Media Queries :** Media queries are CSS rules that specify different styles to be applied at specific breakpoints. They typically use the @media rule along with the min-width or max-width properties to target specific ranges of screen widths. For example:

    ```css
    /* Styles for screens with a width of up to 768px (small mobile) */
    @media (max-width: 768px) {
    /* CSS rules for small screens */
    }

    /* Styles for screens with a width between 769px and 1024px (tablets) */
    @media (min-width: 769px) and (max-width: 1024px) {
    /* CSS rules for tablets */
    }

    /* Styles for screens with a width of 1025px and above (desktop) */
    @media (min-width: 1025px) {
    /* CSS rules for desktops */
    }
    ```
3. **Adjust Layout and Styling :** Within each media query block, you can adjust various CSS properties, such as font sizes, spacing, column layouts, visibility of certain elements, and more, to ensure that your website or application looks and functions well on devices of different sizes.

    By utilizing breakpoints and media queries, you can create a responsive design that provides a consistent and user-friendly experience across a wide range of devices, from small smartphones to large desktop monitors.


## Best Practices : 

- Use breakpoints when your layouts starts to fail i.e. when it starts goin' the wrong way. & How to figure that out is by looking at the layout & playing with it.

- Don't use too many breakpoints in your code as it will be tough to maintain when things will change in your design. So, keep them to a minimum as well as maintain the nice looking and functional layout.

- You shouldn't target very specific devices.

If you want further information about how to use breakpoints in the most efficient way. 

### Resources : 

**Article :** [The 100% correct way to do CSS Breakpoint](https://www.freecodecamp.org/news/the-100-correct-way-to-do-css-breakpoints-88d6a5ba1862/)

A dive into how to pick breakpoints for your projects. I still maintain that the design should dictate the ones you're using, but as I said at the end of my video, I end up very often using the same, or very similar ones, almost all the time.

The [tl;dr](https://www.dictionary.com/browse/tldr) of the article: Use 600px, 900px, 1200px, and 1800px if you plan on giving the giant-monitor people something special. 