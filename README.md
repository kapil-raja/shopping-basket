# shopping-basket
## Prerequisites:
 Install Scala using this link: https://www.scala-lang.org/download/
## How To Run:
 1. Dowlond the Jar file Using this link: https://github.com/kapil-raja/shopping-basket/releases/download/v0.1.0-SNAPSHOT/shopping-basket-assembly-0.1.0-SNAPSHOT.jar
 2. Open Terminal and navigate to the Jar Downloaded Folder
 3. Execute the below command
     ```scala -cp shopping-basket-assembly-0.1.0-SNAPSHOT.jar com.learning.priceBasket.PriceBasket [your items here]``` <br />
    
  Example:
     ```scala -cp shopping-basket-assembly-0.1.0-SNAPSHOT.jar com.learning.priceBasket.PriceBasket Milk Bread Bread Soup Soup``` <br />
    
     Result will be:
    ```
    Subtotal: £4.20
    Bread 50.0% off: 40p
    Total price: £3.80
    ```
 ## Requirements:
Write a program driven by unit tests that can price a basket of goods taking into account some special offers.
<p>
The goods that can be purchased, together with their normal prices are:
<p>

- Soup – 65p per tin
- Bread – 80p per loaf
- Milk – £1.30 per bottle
- Apples – £1.00 per bag
<p>
Current special offers

- Apples have a 10% discount off their normal price this week
- Buy 2 tins of Soup and get a loaf of Bread for half price
<p>
The program should accept a list of items in the basket and output the subtotal, the special offer discounts and the final price.
Input should be via the command line in the form PriceBasket item1 item2 item3 ...
For example

`PriceBasket Apples Milk Bread`

Output should be to the console, for example:
```
Subtotal: £3.10
Apples 10% off: 10p
Total price: £3.00
```
If no special offers are applicable the code should output:

```
Subtotal: £1.30
(No offers available)
Total price: £1.30
```



    
  
