# sabrittany-angelle-p0

# MovieTheatreApp

# Customer
  Have an option of login / register account
  Register account -> full name-> custom exception (if under 18 parental advisory) age -> debit card number -> phone number -> deposit money
  Welcome customer 
  Movie List -> movie -> how many tickets($10/person) -> total so far(add to cart) -> give option if customer wants to order food ahead of time -> y/n
  y- List of food items -> food-> quantity-> total -> complete order->  
  n- List the total and movie and quantity 
 // if total(whatever is in add to cart) <= deposit money 1/2/3 else insuffient funds a. deposit more money b. cancel order
  Final Page -> 1.Are you ready to complete your order y / 2.Edit Food items / 3.Edit Movie / 4. Cancel Order
  1. y/ Awesome your order is complete  here is your confirmation number 
  2. Edit Food Items -> list what customer selected -> change/delete item quantity -> Final Page
  3. Edit Movie -> list what customer selected -> change/delete item
  Complete -> (have the system generate some kind of confirmation number this will be your primary key) Make sure to present your confirmation number 
  
# Employee
  Can approve/reject if confirmation number is not valid (like if it was used twice)
  verify the customer themselves 1.name&phone number 2.confirmation code 3. Hit Complete to close out this order
  if you try to enter in that same code twice you will be an 'error'
