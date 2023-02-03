# Demo | Flexbox with nth-child (pseudo-class) Selectors

This demo goes over:
- introduction to relative units
- flexible layouts (stages of squishiness)
- `nth-child` selectors.


Couple of things to note about `nth-child` selectors:
- The `nth-child` pseudo-class matches elements based on their position in their grouping. 

For example: 
Let's say you have a list with 4 items, and you wanted to target the 3rd item. How would you do that?

```html
<ul>
  <li>one</li>
  <li>two</li>
  <li>three</li>
  <li>four</li>
</ul>
    

```
You would write: **`li:nth-child(3){ ... }`**

See more here: https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-child
