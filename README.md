To-Do List with JavaScript

In this tutorial, we will be creating a simple to-do list that allows the user to add items to the list, mark them as complete, and remove them from the list. 

First, let’s take a look at the HTML code. We have a container div that contains a form with an input field and a button, and an unordered list to hold our to-do list items.

Next, let’s examine the JavaScript code. We start by selecting the add button and the list element using the querySelector method. Then, we add an event listener to the add button that listens for a click event.

Inside the event listener, we first prevent the default action of the button (which is to submit the form) by calling the preventDefault method on the event object. Then, we select the input field using querySelector and store its value in a variable called listitem.

Next, we check if the listitem variable is not an empty string. If it is not empty, we create a new li element and set its inner HTML to the value of listitem. Then, we create a new button element and set its class to close. We also set the inner HTML of this button to a times symbol (\u00D7).

We then append the button element to the li element and append the li element to the list. Finally, we clear the value of the input field and add two more event listeners to the li and button elements.

The first event listener, added to the li element, listens for a click event and strikes through the text of the li element when it is clicked. The second event listener, added to the button element, listens for a click event and hides the parent li element when it is clicked.

And that’s it! With just a few lines of code, we were able to create a functional to-do list with JavaScript. I hope this tutorial was helpful and that you were able to learn something new.
