1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

getElementById("id")
Selects one element , Uses the id , Returns a single element

getElementsByClassName("class")
Selects elements by class name , Returns many elements , Looks like an array but not exactly an array

querySelector("selector")
Selects first matching element , Uses CSS selector , Very flexible

querySelectorAll("selector")
Selects all matching elements , Returns a NodeList , Uses CSS selector




2. How to create and insert a new element into DOM?

let newDiv = document.createElement("div");
newDiv.textContent = "Hello hablu";
document.body.appendChild(newDiv);




3️. What is Event Bubbling?
When you click something inside another element , the event goes upward to parent elements.




4. What is Event Delegation? Why useful?
Instead of adding event to many children , add event to the parent.
useful :
Less memory needed , Works for new elements added later , Clean code




5. Difference between preventDefault() and stopPropagation()

preventDefault()
Stops the default behavior.

stopPropagation()
Stops the event from moving up .
