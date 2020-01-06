# Flex panels image gallery
 
A simple image gallery with 5 column panels, each containing a 3-word sentence.

On page load, we first see the middle word of each panel creating a sentence for itself: Let's take it all in.

By clicking on an image panel, the image expands 5 times and we see the full panel sentence (ex. Hey lets dance).

This was accomplished by using flexbox (flex-grow property), and a smooth transition of transfom property that hides the element off screen until panel is clicked.

Vanilla JS was used to query all selectors and then loop through them with forEach method, and adding an event listener.

The event listener calls toggleOpen and toggleActive functions that toggle the classes 'open' on click, and 'open-active'on transitionend.