# Traceability Matrix for Add to Cart

This is the requirements traceability matrix for the process of adding an item to the cart.

### Business Requirements

1. Clicking Add to Cart adds the item to the cart
2. The correct quantity is added to the cart
3. The correct item is added to the cart
4. The user can add more than one item to the cart
5. The user cannot add the item to the cart when the quantity = 0

| Test Case ID |        Test Case Description        | BR-001 | BR-002 | BR-003 | BR-004 | BR-005 |
| :---: |:-----------------------------------:|:------:|:------:|:------:|:------:|:------:|
| TC-001 | clicking add cart adds item to cart |   x    |        |   x    |        |        |
| TC-002 | add to cart, quantity = 1 | |   x    |        |        | | 
| TC-003 | add to cart, quantity > 1 | |   x    |        |        | |
| TC-004 | add to cart, quantity = 0 | |        |        |        | x|
| TC-005 | adding an additional item to the cart | | | | x | |

