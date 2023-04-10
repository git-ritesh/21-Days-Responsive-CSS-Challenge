# Em vs Rem 

## Em (Relative)

- If you're using a font size using EMs it will be in relation to that elements parent 
- 1em generally defaults to 16 pixels if the parent doesn't have a font size.
- In EMs the font sizes are compounding on top of each other. i.e. if there's a div whose font size is 1em i.e 16px if we put a child into the parent div and specify the font size as 2em then it becomes 2 * 16px(parent's) i.e. 32px and so on and so forth.
- font-size is always looking at the parent but the margin, padding, width and any other unit is looking at this font-size. it's looking at the font-size of that element.

## Rem (Consistent)
- According to mozilla developer network _Rems were actually invented with the sole purpose of fixing that whole compounding problem_ we just see in Em.
- Rem stands for **root M**
- Rem looks at the HTML elements font size and not the body. 
- Rem is always consistent it's always looking at what the font size of HTML element is whereas EMs are more variable the font-size looks at the parent and all the other properties we can apply looks at the font-size of that element 

#### For more clarity you can just watch the video [Click Me.](https://youtu.be/_-aDOAMmDHI)