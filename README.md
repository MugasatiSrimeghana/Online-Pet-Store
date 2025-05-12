# Online-Pet-Store 
## Introduction
This project is a Java-based graphical user interface (GUI) that simulates an online pet store. Users can log in, browse different pet categories (Dogs, Cats, Fish, Rabbits, Pet Food, Accessories), add selected items to their cart, and proceed with the checkout. The application provides an interactive interface where the user can explore various pet items, add them to the cart, and view the total price of the selected products.

## Synopsis
#### The Java Pet Store GUI application allows the user to:

* Log in with a username.

* Browse and view various pet categories such as Dogs, Cats, Fish, and Accessories.

* Add pets or accessories to the shopping cart.

* View the contents of the cart.

* Place an order and get the total amount.

#### This system uses JList for displaying available pets, JButton for navigation, and JLabel for displaying information such as pet names and prices. The entire interface is built using the Swing framework, with layout management handled through CardLayout and BorderLayout.

## Tools Used

* *Java:* Programming language used for developing the application.

* *BlueJ:* Java coding environment.
  
* *Swing:* Java GUI toolkit for building the graphical user interface.

* *CardLayout:* Used for managing different panels, allowing easy navigation between the login page and store sections.

* *JList:* To display pet items and their details (e.g., names, prices, and images).

* *JButton, JLabel:* UI components for user interaction and information display.

* *Labelled Images*

#### This project makes use of several images representing different types of pets. These images are stored locally and displayed alongside pet names and prices.
#### Note: You will need to provide your own images and update the file paths in the code to match your local directory.

## Output
The program provides the following outputs:

* *Login Screen:* A simple login prompt for users to enter their username.

* *Store Screen:* Displays various pet categories. Clicking on any category displays available pets for that category.

* *Add to Cart:* Pets or accessories can be added to the cart. A confirmation dialog appears after adding an item to the cart.

* *Cart Screen:* Displays the list of pets added to the cart, their prices, and the total amount.

* *Order Confirmation:* After placing the order, the total amount is displayed, and the user is informed that the order was placed successfully.

Here is an example of the output flow:

Login Screen:
![image](https://github.com/user-attachments/assets/202d3625-875a-4fdf-8ea9-334a7b9a03f4)

Enter a username and click login.
![image](https://github.com/user-attachments/assets/34bbe0b5-f5b8-442b-8177-74b13614aa9d)


Upon successful login, navigate to the store.

Store Screen:
![image](https://github.com/user-attachments/assets/c673b238-62d7-4b86-95f5-481b908ca6ce)

Browse pet categories and view items.
Select a pet or accessory and click "Add to Cart."

![image](https://github.com/user-attachments/assets/0a81ac87-0ddf-4d52-b7e8-9523f5642f30)
![image](https://github.com/user-attachments/assets/40b45f39-a355-4fbe-b0ac-4c9d4e44c840)
![image](https://github.com/user-attachments/assets/32975ac6-b441-4968-89ec-7e11d9919eb8)

Cart Screen:
View items in the cart with the total amount.

Option to either place the order or go back to the store.

![image](https://github.com/user-attachments/assets/20025b87-635e-4f34-8b5f-4c75da39b54d)


Order Confirmation:
After placing the order, the application displays a confirmation message along with the total amount.
![image](https://github.com/user-attachments/assets/06c3162e-5794-4d72-9d19-9fcd94977833)



## Conclusion
The Java Pet Store GUI is an interactive and user-friendly application that simulates an online pet store environment. This project demonstrates how to use Java Swing for creating graphical user interfaces and implementing interactive features like login, browsing, cart management, and checkout. The use of JList and CardLayout enhances the user experience by providing an organized and structured navigation system.

## Key Takeaways
* Swing Framework: Learned how to use Swing components like JList, JButton, and JLabel to create an interactive application.

* CardLayout: Utilized CardLayout to manage different screens for a smooth user experience.

* File Handling: Implemented local image loading to display pet images with the corresponding names and prices.

* Event Handling: Used action listeners to handle events like logging in, adding items to the cart, and placing orders.
