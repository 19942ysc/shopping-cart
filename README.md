# Shopping-Cart

Clone the repository onto your desktop, and navigate to it from the command-line;

    cd ~/Desktop/shopping-cart

and, create a conda environement;

    conda create -n shopping-env python=3.8

and, run activate the shopping-cart environement;

    conda activate shopping-env

and then, run the python file 'shopping_cart.py' from the command-line;

    python shopping_cart.py

Follow the prompts and enter product identifer between 1 and 20.


Here is a sample input:

    Please input a product identifier, or 'DONE': 5
    Please input a product identifier, or 'DONE': 14
    Please input a product identifier, or 'DONE': 21
    Sorry, the product identifier does not exist. Please try again.
    Please input a product identifier, or 'DONE': 6
    Please input a product identifier, or 'DONE': 3
    Please input a product identifier, or 'DONE': 4
    Please input a product identifier, or 'DONE': 4
    Please input a product identifier, or 'DONE': done


Here is a sample output:

    > --------------------------------
    > GREEN FOODS GROCERY
    > WWW.GREEN-FOODS-GROCERY.COM
    > --------------------------------
    > CHECKOUT AT: 2022-08-04 15:01
    > --------------------------------
    > SELECTED PRODUCTS:
    >    Green Chile Anytime Sauce ( $7.99 )
    >    Fresh Scent Dishwasher Cleaner ( $4.99 )
    >    Dry Nose Oil ( $21.99 )
    >    Robust Golden Unsweetened Oolong Tea ( $2.49 )
    >    Smart Ones Classic Favorites Mini Rigatoni With Vodka Cream Sauce ( $6.99 )
    >    Smart Ones Classic Favorites Mini Rigatoni With Vodka Cream Sauce ( $6.99 )
    > --------------------------------
    > SUBTOTAL: $51.44
    > TAX: $4.50
    > TOTAL: $55.94
    > --------------------------------
    > THANKS, SEE YOU AGAIN SOON!
    > --------------------------------
