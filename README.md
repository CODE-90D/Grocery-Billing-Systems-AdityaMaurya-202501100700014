Grocery Store Billing Program Problem Statement A grocery store wants to calculate the total cost of items purchased by a customer.

The program should accept the price of 3 different items.
It should calculate the total cost.
If the total exceeds $50, a 10% discount must be applied.
Finally, the program should display the Original Total, Discount (if applicable), and Final Payable Amount.
Approach

Input Collection
Prompt the user to enter the price of three items.
Store them as floating-point numbers for accurate currency calculations.
Total Calculation
Add the three item prices to get the original total.
Discount Logic
If the total is greater than $50, calculate a 10% discount.
Otherwise, set discount to zero.
Final Amount
Subtract the discount from the original total to get the final payable amount.
Output
Display the billing summary with:
Original Total
Discount applied
Final Payable Amount
Round values to 2 decimal places for currency formatting.
Sample Output Case 1: Total exceeds $50

Enter price of item 1: 20 Enter price of item 2: 25 Enter price of item 3: 15

--- Billing Summary --- Original Total: $ 60.0 Discount: $ 6.0 Final Payable Amount: $ 54.0

Case 2: Total less than or equal to $50

Enter price of item 1: 10 Enter price of item 2: 15 Enter price of item 3: 20

--- Billing Summary --- Original Total: $ 45.0 Discount: $ 0.0 Final Payable Amount: $ 45.0
