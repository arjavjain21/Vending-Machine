# Vending-Machine
The goal of this project is to design, write, and test a Java program that simulates the operation of a vending machine. We will be using concepts of Object Oriented Programming for this project.

Why a vending machine?
Thanks to technological advancements, vending machines have come a long way since their beginning. With advanced vending solutions, readily available, the benefits of a vending machine can bring a unique addition to a business.

The following steps of the process are essential since they help us define how exactly the program will work.

Let’s start by creating a use case:
1. The vending machine displays a welcome message with all products and prices
2. The vending machine asks the user to select a product
3. The Vending machine asks the user to enter notes and it's denominations. We are also planning to add online payment gateways that accept the exact amount of the product.
4. The Vending machine calculates the total money inserted
5. Calculates the change amount
6. Returns the change Amount 
 
Setup and Test
1. Complete the VendingMachineTester class. We will set up the vending machine with the main method of this class. The function will also allow users to purchase different kinds of items from the vending machine. To do this, we will take inputs from the user according to the item they would like to purchase and then ask them to swipe their card on the machine.

The main method uses the objects of the vending machine pieces explained above.

2. Now we test the class by simulating the following transactions:
• A successful purchase in which the user receives the desired item. The user will then receive the receipt showing the amount they are left with in their card, after the purchase.
• A purchase attempt that is unsuccessful because the stockpile does not contain that particular item.
In this case the vending machine shows an output that shows the error message about unavailability of the product.
• A purchase attempt that is unsuccessful because the user’s card doesn’t have enough balance.
 
The inspiration of this project comes from the vending machines I had in my college campus. They were mostly out of order or used to have some payment issues where the user got charged but didn’t receive his/her order. With this project, my team and I planned to make the system better and more effective 
