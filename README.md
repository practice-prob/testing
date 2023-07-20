testing
Unit tests:

Multiplication
Expect multiplication(x, y) to be a number
Expect x input to be a number
Expect y input to be a number
Expect a non-number x or y input to be a thrown error
Expect if the user only puts one argument to be a product that multiplies that argument by 1
Expect if the user puts more than 2 arguments to be a product that multiplies only the first two arguments

concatOdds

Expect concatOdds(x, y) to be an array of integers
Expect x input to be an array of integers
Expect y input to be an array of integers
Expect output to be one combined array with only odd integers and no duplicates
Expect output to be a sorted array
When an array contains strings, throw an error
When an array contains non-integer numbers, throw an error
If either/both of the inputs are not arrays, throw an error
If one of the arrays is empty, sort the remaining array

Functional tests:

When a user clicks checkout, display a panel to ask the user to log in or check out as guest
When a user checks out as a guest, allow the user to sign up for an account during purchase
When the cart is empty, show a pop-up asking user to add something to the cart
When a user signs in to their account, redirect to the checkout dialogue with a message
When a user is signed into their account, prompt if they want to use saved card
If the user tries to sign in and puts in the wrong username or password, display username/password message with a reset link
If the user tries to sign in without a password, display a message asking for password
If the user tries to sign in without a username, display a message asking for username
If the payment information (zip code/address) is incorrect or cannot be verified, display error message asking to re-enter
If the user enters a coupon code, verify  -->
