[link to lesson](https://www.codecademy.com/courses/make-a-website/lessons/closer-look-css/exercises/id-selectors)

### A Closer Look at CSS

**CSS id Selectors**

The background image makes a big difference. Nice work!

A previous exercise introduced CSS class selectors to style HTML elements of specific classes. What if a webpage design calls for an individual page element to be styled uniquely, but all other elements of that kind to be styled a different way?

For example, to style one anchor element differently than all the others on a webpage, you could use the HTML id attribute:
```
<a id="learn-code" href="https://www.codecademy.com">Click here to learn to code!</a> 
```
Then in the CSS file, you would create a rule for the id selector, using a # symbol:
```
#learn-code {
  color: #2e69a3;  
}
```
About using id:

1. An id attribute can only be used once because the id is unique to the element it is assigned to.


2. Ids have greater specificity than classes. If an HTML element is using both id and class attributes, the CSS rule for the id will take precedence over that of the class.

Below we will use an id selector to style a single HTML element differently than others of that kind on the webpage.
