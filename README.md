# Coding Challenge

Based on the API documentation, use PHP (preferably using Laravel 5.3, but feel free to use any or no framework), to implement working endpoints for Create Purchase and Retrieve List of Purchases.

    https://github.com/Sarmizegetusa/Coding-Challenge/wiki

This will include creating database tables and models for the Purchase and Offering objects.

Write tests for the endpoints using whatever PHP testing framework you like, but given the time constraints you're free to write tests in an add hoc fashion.

Use basic authentication and perform the necessary argument validations and error checking. If you find that anything in the documentation is not clearly specified, then just take your best guess and move on.

Prepopulate a couple Offering objects to use when creating a Purchase.

Create a screen using AngularJS (feel free to use any other framework), to create purchase. It should have the following:

* A way to select the Offering to purchase.
* A field for the customer name.
* A field for quantity.
* It should show the total amount of the purchase.
* It should use the API endpoint to create the purchase.

Create another screen where you'll use the API endpoint to Retrieve the list of purchases, and show a table with:

* Purchase ID
* Offering title
* Quantity
* Unit price
* Total
