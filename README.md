1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

getElementById("id") -Finds only one element with that id.

getElementsByClassName("class") - Finds all elements with that class (gives a list).

querySelector("selector") -Finds the first element that matches the CSS selector.

querySelectorAll("selector") - Finds all elements that match the CSS selector (gives a list).

2. How do you create and insert a new element into the DOM?

Create element - document.createElement("p")

Add content - element.innerText = "Hello"

Add it to page -parent.appendChild(element)

3. What is Event Bubbling and how does it work?

Event bubbling means - if an event happens on a child element, it goes up to its parent, then to parent’s parent, until it reaches the document.

Example: Button - Div → Body.

4. What is Event Delegation in JavaScript? Why is it useful?

Event delegation means -instead of adding event to many child elements, we put one event listener on the parent and catch events from children.

Useful because:

Less code. and Faster performance.



5. What is the difference between preventDefault() and stopPropagation()?

preventDefault() → Stops the browser’s default action (example: stop a link from opening).

stopPropagation() → Stops the event from going up to parent elements.
