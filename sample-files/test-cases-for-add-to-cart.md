# Test Scenario: Add to Cart

Test cases for the process to add an item to the cart

## TC-001: clicking Add to Cart adds the item to the cart

### Preconditions

* the user has navigated to the Product Details Page (PDP) for the item in question on the e-commerce website

### Testing Steps

1. click the 'Add to Cart' button
2. navigate to the cart
3. confirm that the correct quantity of the correct item was added to the cart

### Expected Result(s)

* the correct quantity of the correct item was added to the cart

## TC-002: adding an item to the cart, quantity = 1

### Preconditions

* the user has navigated to the Product Details Page (PDP) for the item in question on the e-commerce website
* the quantity = 1

### Testing Steps

1. click the 'Add to Cart' button
2. navigate to the cart
3. confirm that the correct quantity of the correct item was added to the cart

### Expected Result(s)

* the quantity of the item added to the cart = 1

## TC-003: adding an item to the cart, quantity > 1

### Preconditions

* the user has navigated to the Product Details Page (PDP) for the item in question on the e-commerce website
* the quantity > 1

### Testing Steps

1. click the 'Add to Cart' button
2. navigate to the cart
3. confirm that the correct quantity of the correct item was added to the cart

### Expected Result(s)

* the correct quantity of the correct item was added to the cart

## TC-004 adding an item to the cart, quantity = 0

### Preconditions

* the user has navigated to the Product Details Page (PDP) for the item in question on the e-commerce website
* the quantity = 0

### Testing Steps

1. click the 'Add to Cart' button
2. navigate to the cart
3. confirm that the item was not added to the cart

### Expected Result(s)

* the item was not added to the cart because you cannot purchase 0 of something

## TC-005 adding an additional item to the cart

### Preconditions

* the user has navigated to the Product Details Page (PDP) for the item in question on the e-commerce website
* there is already another item in the user's cart

### Testing Steps

1. click the 'Add to Cart' button
2. navigate to the cart
3. confirm that the correct quantity of the correct item was added to the cart

### Expected Result(s)

* the correct quantity of the correct item was added to the cart
* the existing item in the cart is unaffected
