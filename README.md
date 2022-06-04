# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./images/Screenshot%202022-06-04%20170422.png)

### Links

- Live Site URL: [https://selt0.github.io/orderSummary-component/](https://selt0.github.io/orderSummary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [Bulma](https://bulma.io/) - For styles
- Mobile-first workflow

### What I learned

So many tools! I used a box shadow generator to add the shadow box underneath the button. As mentioned before, now that I am getting comfortable with bulma, the amount of time it took to create the project was cut in half!

I noticed the files came with two different set of images for the background. A background for mobile and a background for desktops. A quick google search showed me that CSS has it's very own <code>image-set()</code>.
I noticed the image only had the upper half of the design whereas in the mock up, there were two different colors. Took me a couple searches to realize I had to set my own background color, whoops!

```css
body {
  background-image: image-set(
    url("./images/pattern-background-desktop.svg") 2x,
    url("./images/pattern-background-mobile.svg") 1x
    );
    background-position: center top;
    background-repeat: no-repeat;
    background-size: contain;
    background-color: #e0e8ff;
}
```

### Useful resources

- [Box shadow generator](https://html-css-js.com/css/generator/box-shadow/) - This helped me generate the box shadow

## Author

- Website - [Michael Martinez](https://michael-martinez.netlify.app/)
- Twitter - [@MMocomochi](https://www.twitter.com/MMocomochi)
