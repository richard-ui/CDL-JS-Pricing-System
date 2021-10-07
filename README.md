# CDL Kata Project

[View Project](https://richard-ui.github.io/CDL-JS-Pricing-System/)

- Here i have implemented a shop cart that allows fruit to be added to a basket when the user interacts with it. There should be a discount for some products and this will be taken into account when the quantity is changed by the user. Ive made use of plenty of functions, methods and reusable code in this project. These functions can handle the calculation of the products and the discount along with it.

- I used functions to group blocks of code inside. Doing it this way ensured that the function can be reused over and over again. For example the updateCartTotal() function had to be used many times in multiple other functions and methods.

- Within the function ready() i Declare a for loop that ensures we loop through all the shop buttons for each item.

- We also use another for loop to iterate through the quantity inputs of each item that has added to the cart table.

- For quantity and the add to cart buttons whcih we discussed above, they have event listeners attached to them which triggers a function whenever the user interacts with them.

## Improvements?

- If i had more time, I would of probably implemented a transaction system that is processed when ever the user presses the Purchase button. This would include a confirmation that would be sent to the user by email and an alert box total displays on the webpage with item names with total price of all the items.

