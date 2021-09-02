# Coding Challenge (Donations)

## Pre-requisites

Before attempting the challenge, make sure you have a Github account, and create a public repository (ex. PivvitChallenge), where you'll put all the code you create during the challenge.

Setup an environment with PHP 7.4, Laravel 7, and VueJS 2, and have everything ready to just start coding.

## Instructions

Based on the API documentation, use Laravel to implement working endpoints for Create Donation and Retrieve List of Donations.

https://github.com/Sarmizegetusa/Coding-Challenge/wiki/Donations

This will include creating database tables and models for the Donation and Campaign objects.

Write tests for the endpoints using PHPUnit.

Use basic authentication and perform the necessary argument validations and error checking. If you find that anything in the documentation is not clearly specified, then just take your best guess and move on.

Prepopulate a couple of Campaign objects to use when creating a Donation.

Create a screen using VueJS, to create donation. It should have the following:

* A way to select the Campaign to donate to.
* A field for the donor name.
* A field for amount.
* It should use the API endpoint to create the donation.

Create another screen where you'll use the API endpoint to Retrieve the list of donations, and show a table with:

* Donation ID
* Campaign title
* Amount
* Donor name

### If you have more time

Create a screen to manage campaigns (create/update/list/delete).