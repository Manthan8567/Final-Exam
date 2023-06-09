# Readme file
Question 1: 
A)	A class diagram shows the static structure of a system, including classes their attributes, methods, and the relationships between them. It is important for object-oriented modeling, as it provides an overview of a system’s architecture and helps developers to understand class relationships. 

For example: An online bookstore system. Its class diagram can have different classes like Customer class, Book class, Order class, ShoppingCart class and these classes can have attributes and methods like Customer class can have attributes: Customer name, id, email. And methods like register(), login(), vieworders(), etc. And about its relationships, A customer can have multiple orders(one-to-many), An order can have multiple books(many-to-many), A customer has one shopping cart(one-to-one).

B)	An activity diagram shows the flow of activities, actions, and decisions between the activities. It describes the behaviour of the system and helps to understand the logic of the system. 

For example: the online bookstore system. The activity diagram for this could include, Browse Books, Add Books to ShoppingCart, Proceed to Checkout, Entre Shipping and Payment Information, Confirm Order, Receive Order Confirmation. And the control flow for this diagram could be start with “Browse Books”, After selecting a book, ad it to the ShoppingCart, then proceed to checkout and confirm the order. Finally, receive an order confirmation.

C)	A sequence diagram shows interactions between objects in a system, focussing on the order of messages exchanges. It is helpful for understanding how object collaborate to complete a specific task or user case.

For example: in the same online bookstore system, the sequence diagram for ordering a book could have User, BookList, ShoppingCart, Order, PaymentProcessor. And the interaction would be First, the User requests a list of books from the BookList. Then User selects a book and sends an “add to cart” message to the ShoppingCart. Then when User is ready to checkout, it sends a message “proceed to checkout” to the ShoppingCart. Then ShoppingCart creates an Order and sends the User’s shipping and payment information to the PaymentProcessor. Then the PaymentProcessor processes the payment and sends a confirmation to the Order. Finally, the Order sends and order confirmation message to the User.

[Click here to view the documentation](documentation.md)
