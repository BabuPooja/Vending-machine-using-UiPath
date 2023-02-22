# Vending-machine-using-UiPath
-A simple vending machine that displays the snacks and beverages, from which you select your item and upload the amount you have.
-the vendor machine calculates the order amount and the remaining amount of your main balance
-displays the options if you want to order something else or finish the order with current selection
-if new items selected, bot calculates the item amount and displays if you have enough balance to place order
-else asks user if they want anything else as their balance is low to place order for the current selection.
-finally if the customer proceeds, the order is placed else the order for the previous selection is placed and remaining balance is displayed.

This is also solution to State Machine topic in UiPath Academy. 
The practice question is

-Creating a Vending Machine

1. Create a workflow that simulates a vending machine. The functionality should be the following:

The user is asked to choose the initial credit ($5, $10, $20).
If they've selected an initial amount, they are asked what drink they want: Coffee ($3) or Tea ($2).

2. Next, the vending machine should check if the user has enough credit for the selected drink. 

If Yes, display a success message and subtract the price of the drink from the total amount to show the remaining credit. The user is then asked if he/she wants to buy another drink or go get their change.
If No, the user is transitioned to the Final State where a message box is displayed with the available amount to be returned and a goodbye message.

3. If they opted to get their change, the user is transitioned to the Final State where a message box is displayed with the available amount to be returned and a goodbye message.

Happy automating!!!!
