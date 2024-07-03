# rn-assignment6-11246331
# React Native Shopping App
This project is a React Native shopping app that allows users to browse products, add them to their cart, and view the cart's total cost. The app uses React Navigation for navigation between screens and AsyncStorage for persistent data storage.

# Design Choices
## User Interface
Header: The header includes a menu icon, the logo, and icons for search and the shopping cart. These elements are aligned to provide a clean and intuitive user interface.
Our Story Section: The "OUR STORY" text is aligned with two icons (Filter and Listview) to enhance usability, allowing users to quickly access filtering and view options.
Product Listing: Products are displayed in a grid layout using FlatList with two columns, making the browsing experience more efficient and visually appealing.
Add to Cart: Each product has an add-to-cart button that uses an icon, making it easy for users to add items to their cart.
## Data Storage
AsyncStorage: Used to persist the shopping cart data. When a user adds a product to the cart, the cart is updated in AsyncStorage, ensuring that the cart state is maintained even if the app is closed or restarted.

# Implementation
## Data Storage
Saving Data: When a product is added to the cart, the new cart state is saved to AsyncStorage.
Loading Data: On app start and when the cart screen is focused, the cart data is loaded from AsyncStorage to ensure the latest cart state is displayed.

# Screens
HomeScreen: Displays the list of products and allows users to add items to their cart.
CartScreen: Displays the items in the cart and the total cost, allowing users to remove items.

# Screenshots
Home Screen: 
![HomeScreen](https://github.com/Believe-wr/rn-assignment6-11246331/assets/151064445/06750b43-b45b-42b4-aa0f-4ae8c8873597)

Cart Screen: 
![CartScreen](https://github.com/Believe-wr/rn-assignment6-11246331/assets/151064445/8d8852a1-01f9-4135-a044-a435643d06f8)
