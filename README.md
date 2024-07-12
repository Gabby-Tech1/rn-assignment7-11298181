### STUDENT ID: 11298181

# E-Commerce React Native App

## Description

This is a React Native e-commerce application that allows users to browse through a list of products, view detailed information about each product, add products to their cart, and remove products from their cart. The application also includes a drawer navigation menu for easy navigation between screens.

## Features

- **HomeScreen**: Displays a list of available products fetched from an external API.
- **ProductDetailScreen**: Shows detailed information about a selected product.
- **CartScreen**: Displays products added to the cart.
- **Drawer Navigation**: Accessible through a swipe gesture or button to navigate between different screens.
- **Add to Cart**: Allows users to add products to their cart from the HomeScreen or ProductDetailScreen.
- **Remove from Cart**: Allows users to remove products from their cart on the CartScreen.
- **Local Storage**: Uses AsyncStorage to store selected items locally on the device.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Gabby-Tech1/rn-assignment7-11298181.git
    cd 'rn-assignment7-11298181'
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Run the application:
    ```bash
    npm start
    ```

## Dependencies

- React Native
- React Navigation
- AsyncStorage
- Axios

## Usage

1. **HomeScreen**:
    - View a list of products.
    - Click on a product to view more details.

2. **ProductDetailScreen**:
    - View detailed information about a product.
    - Add the product to the cart.

3. **CartScreen**:
    - View products added to the cart.
    - Remove products from the cart.

4. **Drawer Navigation**:
    - Swipe or use the button to open the navigation menu.
    - Navigate between Home, Product Details, and Cart screens.

## API

- The app fetches product data from an external API which is <a>https://fakestoreapi.com/products</a>

## Asynchronous Operations

- The app uses async/await and promises to handle asynchronous operations such as fetching data from the API and interacting with AsyncStorage.

## Local Storage

- The app uses AsyncStorage to store selected items locally on the device, ensuring that the cart data persists between sessions.

## Screenshots of the various screens
