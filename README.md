# Vending-Machine_FPGA-Implementation+

Here we have made a Paramterized Vending machine for zedboard implementation which works in the following way:
1. It takes 3 inputs from the user : Choice of item, Quantity of Item, Cost Price(payment).
2. It shows the remaining items when user choses any item, shows cost when user enters the quantity of the item and finally user has to pay this same amount as cost .
3. We have used zedboard(with 8 input DIP switches), 2 of them were used to select inputds and rest 6 switches to represent the input value.
4. We used Vivado’s IP Integrator (Block Design) to connect different modules for FPGA implementation.
