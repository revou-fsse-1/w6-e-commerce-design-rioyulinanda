E-Commerce Design Assignment

# a. Product Details (Sequence Diagram)

![banner](./assets/Display%20Product%20Details%20Sequence%20Diagram.png)

using sequence diagram to represent the flow of displaying product details, starting from the user input of the product id, then UI addresses the product id to the backend, continuing with backend checking the availability of the product in the database, then there will be 2 status, is it available or not and will be sent back from database to the backend, then to UI. Then will be done once the UI shows to the user the status of the product, whether is available or not.

# b. Create Order (Activity Diagram)

![banner](./assets/Create%20Order%20Activity%20Diagram.png)

## Algorithm

1. Input the product details
2. The system will check the availability of the product
3. If no, the user will be directing to customer service
4. If yes will continue to calculate the price
5. Then order will be created, while the system also reducing the stock that will be purchase by user

## Pseudocode

```pseudocode

funtion createOrder(products)
1. Input an array of product objects
2. check product availability
3. if product is available  continue to calculate the price
4. initialize totalPrice=0
5. Loop through each product in the array
   a. add the price to the totalPrice from each product
   b. Reduce 1 of the quantity from each products
6. Return consist of totalPrice including updated stock of the product

```

## Complexity Analysis

# c. Architecture Diagram

![banner](./assets/Architecture%20Diagram.png)
