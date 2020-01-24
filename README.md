# GOG.com Frontend Recruitment Task

## Description

Implement the design from provided PSD file accurately. Feel free to use any tools you like. Please send us a link to the repository of your solution after you're finished - we're as much interested in the source code as in the working application.

Don't worry about cross-browser compatibility, or mobile views support. Focus on code quality and maintainability.

## Requirements

1. Top bar with Cart icon:
    * Number reflects amount of Products in Cart
2. Cart dropdown
    * It should be closed by default
    * "CLEAR CART" button removes all Products from Cart
    * Hovering over Product reveals "Remove" option
3. Content with Products that you can add to Cart
    * Clicking on price button adds Product to Cart
    * Products in Cart should be marked as "IN CART"
    * You can’t add the same product to cart twice

If there is something missing or unclear in the description above, we ask you to be creative and implement your own solution to the problem.

## My approach

### Store

Usually cart state we keep at backend. I can kind simulate backend or save 
state at local storage. But both of this method are long(own backend) or
I'll not advise(keeping cart store in local storage).

### Image handling 

I have plan to import game pictures from public gog.com source, to keep the app
light.

### Extra 

If I'll have time, I'll include few things.
- [x] simple [hosting].
- [ ] translation
- [ ] RWD


[hosting]: https://jovial-booth-54c65f.netlify.com/
