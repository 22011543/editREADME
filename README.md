The code above is an implementation of a simple motorcycle accessory shop program using the Python programming language with the Object-Oriented Programming (OOP) concept. The program consists of two main classes: ProdukMotor and FinShop. Let's explain each part of the program:

Class ProdukMotor:
Purpose: Represents motorcycle accessory products by storing information about the name and price of each product.
Attributes:
nama: Stores the name of the product.
harga: Stores the price of the product.
Class FinShop:
Purpose: Represents a motorcycle accessory shop by providing a menu of motorcycle products and gasoline prices. It can also calculate the total cost of purchases based on motorcycle products or gasoline selected by customers.
Attributes:
daftar_produk_motor: Stores a list of motorcycle products along with their prices.
harga_bensin: Stores the price of gasoline per liter.
Methods:
sapa_pelanggan: Displays a greeting message to the customer.
tampilkan_menu_produk_motor: Displays the menu of motorcycle products along with their prices.
tampilkan_menu_bensin: Displays the menu of gasoline types along with their prices per liter.
hitung_biaya_produk_motor: Calculates the total cost of purchasing motorcycle products based on the product name and quantity.
hitung_biaya_bensin: Calculates the total cost of purchasing gasoline based on the type of gasoline and the quantity in liters.
main Function:
Purpose: The main function that runs the program and interacts with the user.
Steps:
Creates a FinShop object.
Asks for the customer's name.
Displays the menu of motorcycle products and gasoline.
Asks the user to choose between motorcycle products and gasoline.
If motorcycle products are chosen, asks for the type of product and the quantity to be purchased. Calculates the total cost and displays the purchase receipt.
If gasoline is chosen, asks for the type of gasoline and the quantity in liters. Calculates the total cost and displays the purchase receipt.
Class TestFinShop:
Purpose: Conducts testing on the methods of the FinShop class using the unittest module.
Testing Methods:
test_hitung_biaya_produk_motor: Tests the functionality of calculating the cost of motorcycle products.
test_hitung_biaya_bensin: Tests the functionality of calculating the cost of gasoline.

i made this program to implement "self-service shop"
