# VH Mentorship Workshop 3 Take-Home: To-Do-List Upgrade

## Instructions

Make your to-do-list even more awesome by adding a couple of features!

## Challenge 1: Listening for key events

Clicking the "Add" button every time we submit is annoying when we have to write a ton of tasks down. Create a useEffect function that will submit the form every time the user presses the "Enter" key. There are many ways to do this, the easiest can be found using a simple Google search, and I like these articles: 
* [Event Listeners in React Components](https://www.pluralsight.com/guides/event-listeners-in-react-components)
* [How To Trigger Button Click on Enter](https://www.w3schools.com/howto/howto_js_trigger_button_enter.asp)

## Challenge 2: Overdue events

Overdue assignments should have more emphasis than normal assignments. Turn the background of the item from blue to red if the assignment is overdue.
* Create a new CSS class that sets the background color to red
* Replace the className="item" in the Item.js file with some logic. If the current time (new Date()) is greater than the Item's date (itemData.date), the className should be "item red". Otherwise, it should just be "item". (HINT: Use the [ternary operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator))

## Challenge 3: "Feel Good" Features!

Some todolist applications, such as [Todoist](https://todoist.com) provide "feel good" features such as measuring the number of assignments you've completed. Create a new firebase collection of "users". Within this collection, store the user's email, as well as the number of assignments they have completed. In other words, you will need to update a new collection "users" every time the removeItem() function is called in List.js. Retrieve the current user's "completed count" every time they log in, and display this information somewhere above the to-do-list.

## Have fun!

We're excited to see what you all come up with! Note that these challenges are just suggestions, so feel free to run with your own ideas on how to further increase the app's functionality in an elegant way. This is your project at the end of the day, so take it in any direction you wish. Don't hesitate to reach out to VH Content members and pod leaders for assistance, or share your progress in the discord channel mentee-works!
