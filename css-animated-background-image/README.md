---
Tags: 
 - CSS
 - CSS animation
---

# CSS animated background image
Preview the code [here!](https://htmlpreview.github.io/?https://github.com/davidvandenbor/snippets/blob/master/css-animated-background-image/index.html)

For some weird reason, CSS animations don't work when you try to animate CSS background images declared on the ``BODY`` element. So, in order for the animation to work, we have to move the CSS background image to a **separate HTML element**, like a ``SECTION`` or a ``DIV``. The reason for the ``.background-wrapper`` container is to prevent **scrollbars** from appearing when the background animates (overflow:hidden)

<a href="https://htmlpreview.github.io/?https://github.com/davidvandenbor/snippets/blob/master/css-animated-background-image/index.html" target="_blank"><img src="background.jpg" /></a>
