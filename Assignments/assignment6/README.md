#Explain event bubbling

Event bubbling is a behavior in JavaScript where an event that is triggered on a child element will also be propagated or "bubbled up" to its parent elements. This means that if you have a nested structure of elements, such as a div element inside another div element, and you attach an event listener to the inner div, the event will also be triggered on the outer div.

It is called bubbling because the event is said to "bubble up" the chain of parent elements. In contrast, event capturing is the opposite behavior, where an event is propagated from the top of the chain of parent elements down to the target element.

An example of event bubbling is when you have a button inside a div element, and both the button and the div have an event listener for a "click" event. When you click on the button, the event will be triggered on the button and then propagated up to the div element, and both event listeners will be called.

You can stop the event from bubbling further up the chain by calling the stopPropagation() method on the event object.

#code:
document.getElementById("innerDiv").addEventListener("click", function(event) {
  event.stopPropagation();
  // your code here
});
