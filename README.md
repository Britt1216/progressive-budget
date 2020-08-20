# progressive-budget

# Description:

* Budget Tracker is a progressive web application that allows users to track their budgets by adding expenses and deposits to their budget through the "Add/Subtract Funds" buttons. They are able to add a transaction with or without a connection. When a user enters a transaction while offline, these transactions are stored in the indexedDB, and transferred to the database when the user comes back online.

# Offline Functionality:

* Enter deposits offline

* Enter expenses offline

# When brought back online:

* Offline entries should be added to tracker.


# User Story:

AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

# Business Context:

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

# Installation:

To install the required dependencies, run npm install

This package assumes there is a MongoDB server running on localhost:27017. If your server is running somewhere else, you can edit server.js to reflect that.
