# Split-Landing-Page

## About 
This Split Landing page project has the ability to have multiple items on the landing page with hover effects allowing the user to expand one side of the viewport or the other.  This application could be used on an e-commerce site to allowing the user to compare products.

## Technologies Used
- HTML
- CSS
- JavaScript

## Lessons Learned
1.  One of the first things I learned was to use `background-repeat: no-repeat;` to prevent an image from repeating. I was able to use these CSS code on `.split.left` and `.split.right` to keep both images from repeating. 
[MDN Web Docs/background-repeat](https://developer.mozilla.org/en-US/docs/Web/CSS/background-repeat)

2. :root element can be useful global css variables such as the background color that was used.
[MDN Web Docs/:root](https://developer.mozilla.org/en-US/docs/Web/CSS/:root)

3. I had to move the h1 element to the left.  I was able to accomplish this by using `transform: translateX()`. This allowed the h1 elemnets to shift -50% to the left of the viewport.
[MDN Web Docs/transform: translateX()](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translateX())