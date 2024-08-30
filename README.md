# Psuedo for function multiplication(){}

- multiply two numbers together
- Accept two numbers together as arguments
- Return a single number
- Return the prodcut of the two input numbers

# Psuedo for function concatOdds(){}

- takes two arrays of integers as arguments.
- return a single array that only contains the odd numbers
- result should be in ascending order, from both of the arrays

- expect.multiplication(2,3).toBe(6)
- expect.multiplication(10,5).toBe(50)
- expect.multiplication(1,1).toBe(1)
 
- expect.concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]).toBe([-1, 1, 3, 9, 15])
- expect.concatOdds([2, 1], [1, 1, 1, 4, 15, -1]).toBe([-1, 1, 15])
- expect.concatOdds([5,8,9,3], [3,7,42,51]).toBe([3, 5, 7, 9, 51])

# Function Test (Plain Language)

A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.
Think about the following; you may need to make assumptions or decisions about the prompt and how the feature should behave:

What should happen if the cart is empty?
- If the carty is empty, page should display "Cart Empty"
- Redirect link back shopping items 

What needs to be shown to the user at each step of check out?
- check out button
- a payment method form
- name/shipping/billing address form(s)
- create account prompt to save information for future login and purchases
- Confirm order & submit button
- landing page displaying "Thank you, your order has been placed"
