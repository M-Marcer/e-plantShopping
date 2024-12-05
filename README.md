# Sample Reactive E-Shopping

**Final Project** for the course [IBM: Developing Front-End Apps with React](https://www.coursera.org/learn/developing-front-end-apps-with-react).

This project is a simple, responsive e-commerce website built with React for plant shopping. Users can browse different categories of plants, add them to their shopping cart, and view the cart. The app also supports adding multiple items, viewing total prices, and more. The project is deployed at [this page](https://m-marcer.github.io/e-plantShopping/)

## Features
- **Product Categories**: View a variety of plant categories.
- **Add to Cart**: Add plants to the shopping cart.
- **Remove from Cart**: Remove plants from the cart.
- **Cart Summary**: View total price and quantity in the cart.
- **Disable Add to Cart Button**: When a plant is added to the cart, the "Add to Cart" button is disabled and visually updated.

## Technologies Used
- **React**: Core JavaScript library for building the user interface.
- **Redux**: State management to manage the shopping cart and products.
- **Vite**: Next-generation, fast, and optimized build tool for React.
- **GitHub Pages**: Hosting for the website.

## Installation

To run this project locally, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/M-Marcer/e-plantShopping.git
   ```

2. Navigate into the project directory:

   ```bash
   cd e-plantShopping
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

   Your app should now be running on [http://localhost:3000](http://localhost:3000).

## Deployment

To deploy the app to GitHub Pages, run:

```bash
npm run deploy
```

The app will be available at:  
`https://your-username.github.io/e-plantShopping/`  
Make sure to replace `your-username` with your actual GitHub username.

## File Structure
```bash
src/
│
├── components/           # React components (Cart, Product, etc.)
├── redux/                # Redux actions and reducers for cart management
├── App.jsx               # Main application component
├── main.jsx              # Entry point for React app
├── assets/               # Images and other static files
├── styles/               # Styles for the application
├── vite.config.js        # Vite configuration for building and deploying
└── index.html            # The HTML template for the app
```

## How It Works

- **Home Page**: Displays different categories of plants. You can add items to the cart by clicking the "Add to Cart" button.
- **Shopping Cart**: Once a plant is added to the cart, you can see it in the cart along with the total number of items and the price. You can remove items from the cart, and the total quantity will be updated accordingly.
- **Disabled Buttons**: If a product is already added to the cart, its "Add to Cart" button will be disabled and its background color will change to grey.

## Future Improvements
- Add user authentication and user-specific cart storage.
- Allow users to filter and sort products based on categories or price.
- Implement order checkout functionality.
- Add a search feature for quicker plant discovery.


## License
This project is licensed under the MIT License.
