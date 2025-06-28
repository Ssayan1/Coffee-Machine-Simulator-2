# Coffee-Machine-Simulator-2
A Python-based coffee machine simulator that manages resources, processes payments, and serves different coffee drinks with a realistic vending machine experience.
Features

Menu Management: Dynamic coffee menu with multiple drink options
Resource Tracking: Monitors water, milk, coffee beans, and other ingredients
Payment Processing: Handles coin transactions and change calculation
Inventory Reports: Check current resource levels and profit
Interactive Interface: Command-line based user interaction

How it Works

Order Process: Users select from available coffee options
Resource Check: Verifies sufficient ingredients are available
Payment: Processes payment and calculates change
Coffee Making: Deducts resources and serves the drink
Reports: View current inventory and earnings with "report" command

Commands

Enter drink name (e.g., "latte", "cappuccino", "espresso")
report - View current resources and money
off - Turn off the machine

Requirements

Python 3.x
Custom modules: menu.py, coffee_maker.py, money_machine.py

Usage
bashpython main.py
Architecture

Menu Class: Manages available drinks and finds user selections
CoffeeMaker Class: Handles resource management and coffee preparation
MoneyMachine Class: Processes payments and tracks profits

Perfect for learning object-oriented programming concepts, modular design, and simulating real-world systems in Python.
