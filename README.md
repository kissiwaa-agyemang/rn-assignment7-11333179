# rn-assignment7-11333179

  # Shopping Cart Application
 This is shopping cart application built with react that uses javaScript . It allows users to view available items,
 select items to cart , remove tems from cart and view details about the items.

  # Features
 Home Screen: View a list of products.
 Product Details: View product details in a modal.
 Add to Cart: Add products to the cart.
 Cart Screen: View and manage cart items, see the total price.
 Drawer Navigation: Navigate between different sections of the app.

# How It Works

 # State Management
useState: Manages local state (cart items, products, loading status).
useEffect: Fetches data and performs side effects.
  
# Data Storage
AsyncStorage: Saves cart items across sessions.


 # Navigation
React Navigation: Implements stack and drawer navigation.

# Components
Home Screen (HomeScreen.js)
Fetches products from https://fakestoreapi.com/products using axios.
Displays products in a grid with FlatList.
Shows product details in a modal.
Adds products to the cart.
Cart Screen (CartScreen.js)
Retrieves cart items from AsyncStorage.
Displays cart items and total price.
Allows removing items from the cart.
Product Item Component (ProductItem.js)
Displays product image, title, description, and price.
Adds products to the cart.
App Component (App.js)
Sets up navigation using DrawerNavigator and StackNavigator.


# Images
![WhatsApp Image 2024-07-12 at 21 27 21_b22526e6](https://github.com/user-attachments/assets/eb1c1cfb-46de-466f-b96b-385c34c7bedb)
![WhatsApp Image 2024-07-12 at 21 27 21_e0e4b074](https://github.com/user-attachments/assets/a01a503c-7883-4157-8fd0-21bd7c5e8ac6)
![WhatsApp Image 2024-07-12 at 21 27 22_c2f80916](https://github.com/user-attachments/assets/33c3c7e9-14f7-4948-b652-f4560db145b2)
![WhatsApp Image 2024-07-12 at 21 27 22_1fad4c52](https://github.com/user-attachments/assets/311ab32c-2337-4238-99a6-d5625f219de0)


