# Coffee-Machine-Simulator
This Python program simulates a coffee machine that takes orders, processes payments, and dispenses coffee. It uses a dictionary to store menu items, their ingredients, and costs. The program also tracks resources (water, milk, coffee) and profit.

Features:
- Menu: latte, espresso, cappuccino
- Resource tracking: water, milk, coffee
- Payment processing: accepts 5, 10, and 20 rupee coins
- Order fulfillment: dispenses coffee and updates resources
- Reporting: displays current resources and profit

How it works:

1. User inputs their order (latte, espresso, cappuccino)
2. Program checks if resources are sufficient for the order
3. If resources are available, user is prompted to insert coins
4. Program processes payment and checks if it's sufficient
5. If payment is successful, coffee is dispensed and resources are updated
6. User can view resources and profit by typing "report"
7. Program can be turned off by typing "off"

This code demonstrates basic Python concepts such as dictionaries, functions, conditional statements, and loops.
