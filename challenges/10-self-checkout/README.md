# Self-Checkout
Working with multiple inputs and currency can introduce
some tricky precision issues.

Create a simple self-checkout system. Prompt for the prices and quantities of
three items. Calculate the subtotal of the items. Then calculate the tax using
a tax rate of 5.5%. Print out the line items with the quantity and total, and
then print out the subtotal, tax amount, and total.

### **Example Output**
>`Enter the price of item 1: `

[user inputs the price of item 1]

>`Enter the quantity of item 1: `

[user inputs the quantity of item 1]

>`Enter the price of item 2: `

[user inputs the price of item 2]

>`Enter the quantity of item 2: `

[user inputs the quantity of item 2]

>`Enter the price of item 3: `

[user inputs the price of item 3]

>`Enter the quantity of item 3: `

[user inputs the quantity of item 3]

>`Subtotal: £64.00`

>`Tax: £12.80`

>`Total: £76.80`

### **Constraint**
- Keep the input, processing, and output parts of your program separate.
Collect the input, then do the math operations and string building, and then
print out the output.
- Be sure you explicitly convert input to numerical data before doing any
calculations.