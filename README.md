# Automation Tasks for https://weathershopper.pythonanywhere.com 

Manual end-to-end test case :
a) visit https://weathershopper.pythonanywhere.com/
b) Get the temperature
c) Based on temperature choose to buy sunscreen or moisturizer
d) If you choose sunscreen, then read Instructions (from i mark on top nex
header) and then add product according y
e) If vou choose moisturizer, then read Instructions and then add product
accordingly
f) Verify the cart
g) Make a payment (For card details refer ->
https://stripe.com/docs/testing#cards) The website
has dummy card numbers.

------------------------------------------------------------------
Solution Expectations:
Code should be designed within Page Object Model with TestNg
(Include Listeners, Parallel Execution)
Add Logging and reporting
Take screenshots on every Successful page. Failure screenshot is
mandatory
Use exception handling wherever required
Add excel file or Properties File to pass data during run time
Code should work without any error
Use valid required assertions
