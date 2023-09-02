Overview of the Selenium Automation Test Script for Cart Items Validation
A Selenium automation test script for validating cart items on the website https://www.saucedemo.com/cart.html may be found in this repository. The script automates the process of adding products to the cart, and it then checks to see if every item there matches what was anticipated.

**Prerequisites**
Before running the script, make sure we have the following prerequisites:

Java: Ensure that we have Java installed on our system.

Chrome WebDriver: Download the Chrome WebDriver executable and specify its path in the script.

Selenium WebDriver: we will need Selenium WebDriver for Java, which we can add as a dependency using a build tool like Maven.

Chrome Browser: Make sure Google Chrome is installed on our system.

Running the Script


Clone this repository to your local machine.

Open the CartItemsValidationTest.java file and set the path to your Chrome WebDriver executable.

Build and run the Java file using your preferred IDE or build tool.

**Script Explanation**
The script navigates to the cart page on the website.

It iterates through the available "Add to cart" buttons, adding each item to the cart.

The script opens the cart by clicking on the cart icon.

It validates if all items added to the cart match the expected items by comparing their names.

If all items are successfully added, it prints "All items added in the cart are the same." Otherwise, it prints "Items added to the cart are not the same as added or are missing."

Finally, it closes the browser.

